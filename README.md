# Task (template)
Template repository used for creating FDND tasks.

## Folder structure
Task uses a standard folder structure following convention described in [conventions/folder-structure.md](https://github.com/fdnd/conventions/blob/master/folder-structure.md). Feel free to remove folders if you're creating a task without scaffolding.

## .description
This task is hooked up to the FDND curriculum using (yaml front matter)[https://assemble.io/docs/YAML-front-matter.html].

```
---
title: "een titel"
# max 280 characters in description
description: "korte beschrijving van de taak"
semester: 1-4
# taskclass will be used to group tasks together in a semester
# make sure you use a unique name
taskclass: "naam van taakklasse voor bundeling van taken"
# level determines the order of tasks in a taskclass
level: 0-5
# these criteria determine the skill level of a task compared
# to the whole curriculum on a 6 point scale. Read the Rubric!
behavior-criteria:
  collaboration: 0-5
  learning-capacity: 0-5
  problem-solving: 0-5
  act-methodically: 0-5
  communicating: 0-5
# how many students will work on this task, 0 for individual
collaborators: 0-8
# tags are used to categorize tasks
tags:
  - opsomming
  - van
  - tags
# burn-points determine the weight of a task, 0 is easy and
# probably fast, 144 takes a whole sprint
burn-points: 0-144
---
```

# Een titel
Hier een heldere beschrijving van de taak. Je kunt volledige markdown syntax en links gebruiken maar geen afbeeldingen!


