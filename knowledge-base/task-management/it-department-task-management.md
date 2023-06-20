# IT department task management
This article is a must-read to get you started in organizing your IT department tasks, it will summarize the most basic aspects of task organization and give the best recommendations. Disclamer, before reading this article, familiarize yourself with the user interface of ClickUp application.

---

## Contents
- [Introduction](#it-department-task-management)
- [Tags](#tags)
- [ClickUp](#clickup)
    - [Structure](#structure)
        - [`Main` list](#main-list)
        - [Team-based lists](#team-based-lists)
    - [Task hierarchy](#task-hierarchy)
        - [Segmentation process](#segmentation-process)
- [Parallel development](#parallel-development)

## Tags
There are two types of tags, project-based and general. Project-based tags indicate work in a specific project or part of a project, have the prefix `@` at the beginning and can be used independently. General or general purpose tags are intended to clarify the type of work in progress in a project or part of a project, cannot be used alone, only together with at least one project-based tag and they do not have a prefix.

## ClickUp
The ClickUp application is used to organize tasks. In the ClickUp application, TB-CORP has several departments in the form of spaces, this article is only about the IT department. All further terms about task organization will be used with the ClickUp user interface in mind.

### Structure
The structure of the IT department space is also an integral part of the task organization. The space has several lists representing the structure of the task organization.

#### `Main` list
The `Main` list includes milestones. Milestones are tasks which have been decomposed from the goals of the IT department and distributed based on the teams. Only the CTO and other department managers to whom permission has been given by the CTO have the right to edit the `Main` list. Managers and "C" managers in other departments can only coordinate departmental goals, but not work on milestones.

#### Team-based lists
The other lists besides the `Main` list are team-based lists. Team-based lists are lists of departmental teams that have been logically organized. Each team-based list has its status in the `Main` list, taking a milestone, the team leader segments it into chunks in the same `Main` list as sub-tasks of the milestones and then segments these chunks into tasks already in their list. This creates a hierarchy of tasks.

### Task hierarchy
The task hierarchy is a system of segmenting tasks from large tasks that concern the entire department, like goals, to the most specific tasks. From the above, the following task hierarchy was built in ClickUp.
```
    A goal for the IT department
                 |
                 V
    Milestones on the Main list
                 |
                 V
Chunks at milestones on the Main list
                 |
                 V
 Specific tasks in team-based lists
```
#### Segmentation process
The process of segmenting a goal to a specific task follows the next algorithm.
1. Define the goal;
```
Goal:
+--------------------+
```
2. Decomposition into entities;
```
Entity:                Entity:                Entity:              
+--------------------+ +--------------------+ +--------------------+
```
3. Parallel structuring and sorting;
```
Entity 1:
+--------------------+
Entity 2:
+--------------------+
Entity 3:
+--------------------+
```
4. Breakdown into milestones;
```
Entity 1:
+-----O-----O-----O-----+
Entity 2:
+-----O-----O-----O-----+
Entity 3:
+-----O-----O-----O-----+
```
5. Selecting a milestone in each entity;
```
Entity 1: +----------O
Entity 2: +----------O
Entity 3: +----------O
```
6. Breakdown of milestones into chunks;
```
Entity 1: +--|--|--|--|--O
Entity 2: +--|--|--|--|--O
Entity 3: +--|--|--|--|--O
```
7. Coordinating milestone chunks for parallel development;
```
Entity 1: +--|--|--|--|--O
    Entity 2: +--|--|--|--|--O
            Entity 3: +--|--|--|--|--O
```
8. Getting the job done;
9. Repeat procedures 5-8 for the next milestones;

## Parallel development
Linear development of one entity after another wastes too much time and prevents developers from achieving maximum efficiency at the expense of gaps in their workflow. Parallel development is designed to eliminate this problem.

Parallel development is segmenting a milestone of a certain goal into chunks in several entities of the development process, coordinating them in such a way that when one entity completes 1 or more chunks, another entity can start working without waiting for the completion of the previous entity's milestone. Example, design and web application development, when working on the design project you don't have to wait for it to be complete, you can define the chunks after which the web application developer can get to work.

The correct and necessary segmentation process is already sewn into the IT department's task organization structure, see [task hierarchy](#task-hierarchy).

The organization and control of parallel development is done by the CTO and other managers in the department to whom permission has been given by the CTO.

#knowledge-base