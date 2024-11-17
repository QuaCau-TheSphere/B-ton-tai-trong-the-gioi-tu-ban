---
share: true
created: 2024-11-12T21:05
updated: 2024-11-12T21:05
---

🏃‍♂️ Goal reached? `= choice(this.steps > 10000, "YES!", "**No**, get moving!")`

You have `= length(filter(link(dateformat(date(today), "yyyy-MM-dd")).file.tasks, (t) => !t.completed))` tasks to do. `= choice(date(today).weekday > 5, "Take it easy!", "Time to get work done!")`
