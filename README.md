# braindump

A Java command-line tool for getting open loops out of your head and onto a list, which shows up as a clean dashboard.

## Project Goal

I'm constantly facing the problem of having too many open loops in my head, including small tasks, goals, and things I'm stressed about, all requiring a bit of my energy and focus. Trying to remember all of these things makes it incredibly difficult to gain clarity on what I actually have to do and accomplish. BrainDump gives me a fast way to get everything out of my head and into a program, so I can focus on essential things.

## MVP Scope

Version 1.0 does three things and saves everything into a file so no data is lost between sessions.

- add: saves a new task
- list: shows all tasks in one organized dashboard
- done: marks a task as completed

## Future Plans / Schedule

- Category labels (school, gym, business, life) with filtering
- Priority levels and a "Today's top 3" section
- Weekly stats (tasks added, completed, etc.)

## Tech Stack

- Language: Java
- Libraries: Java standard library (java.nio.file, java.time, Scanner)
- Data storage: Plain CSV file with id, text, date added, done
- Tools: Git/Github, terminal
