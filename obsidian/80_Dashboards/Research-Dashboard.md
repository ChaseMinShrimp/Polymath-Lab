## Active Projects (with due dates)
```dataview
table file.link as Project, due, status
from "30_Projects"
where type = "project" and status != "done" and due
sort due asc
```

## Active Projects (no due date yet)
```dataview
table file.link as Project, status
from "30_Projects"
where type = "project" and status != "done" and !due
sort file.mtime desc
```

## Reading Queue (latest added)
```dataview
table file.link as Paper, authors, year, venue
from "20_Papers"
where type = "paper"
sort file.ctime desc
limit 20
```

## 14-Day Habit Tracker (open tasks)
```dataview
task from "10_Daily"
where !completed and text =~ /Research Habit/
sort file.name desc
```
## Active Projects (with due dates)
```dataview
table file.link as Project, due, status
from "30_Projects"
where type = "project" and status != "done" and due
sort due asc
```

## Active Projects (no due date yet)
```dataview
table file.link as Project, status
from "30_Projects"
where type = "project" and status != "done" and !due
sort file.mtime desc
```

## Reading Queue (latest added)
```dataview
table file.link as Paper, authors, year, venue
from "20_Papers"
where type = "paper"
sort file.ctime desc
limit 20
```

## 14-Day Habit Tracker (open tasks)
```dataview
task from "10_Daily"
where !completed and text =~ /Research Habit/
sort file.name desc
```

## Active Projects
```dataview
table due, status
from "obsidian/30_Projects"
where type = "project" and status != "done"
sort due asc
