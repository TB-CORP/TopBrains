# Statuses
Statuses are unique identifiers of a certain resource in a certain state in a certain environment. When brands/projects reach more than 1, this documentation must be expanded and moved to a shared resource.

## Contents
- [Introduction](#statuses)
- [Status guidelines](#status-guidelines)
- [Available](#available)
    - [Environments](#environments)
    - [Groups](#groups)
    - [List](#list)

## Status guidelines
Each status is name, code and description.
- Title shares general meaning
- Code is a four-digit number (XXXX) divided into segments in a semantic context:
    - `X`XXX: environment (brand/project)
    - X`X`XX: group
    - XX`XX`: value
- Description shares detailed meaning

## Available
### Environments
|  Code  | Brand/Project |
| :----: | :-----------: |
| `1XXX` |    Common     |
| `2XXX` |   TopBrains   |

### Groups
|  Code  |  Group name  |
| :----: | :----------: |
| `21XX` |    Common    |
| `22XX` |     User     |
| `23XX` |    Course    |
| `24XX` | Subscription |
| `25XX` |   Payment    |
| `26XX` |    Lookup    |

### List
|      Name      |  Code  | Description |
| :------------: | :----: | :---------- |
|     Active     | `2101` | -           |
|    Inactive    | `2102` | -           |
|    Deleted     | `2103` | -           |
|     Failed     | `2104` | -           |
|   Validating   | `2105` | -           |
|   Completing   | `2201` | -           |
| Not subscribed | `2202` | -           |
|   Uploading    | `2401` | -           |
|    Uploaded    | `2402` | -           |
|   Proceeding   | `2403` | -           |
