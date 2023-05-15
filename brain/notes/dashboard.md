```dataview
table without id file.link as "Next 2 Weeks",choice((date < date(today)),"<span style='color:red;'>" + (date - date(today)) + "</span>",choice((date > date(today)), (date - date(today)),"Today")) as "Due Date"
from #projects
where date > date(today)-dur(2 w) and date < date(today)+dur(2 w)
where !done
sort date asc
```

```dataview
table without id file.link as "Long Term",choice((date < date(today)),"<span style='color:red;'>" + (date - date(today)) + "</span>",choice((date > date(today)), (date - date(today)),"Today")) as "Due Date"
from #projects
where !done
where date
where !contains(file.name, "template")
sort date asc
```
