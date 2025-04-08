# <project_name>

> <project_quick_description>

## Important informations

**Licence** : <license>
**Creation date** : <creation_date>

## Team

- Bathily Yahaya : Developer

## GitHub Structure

### Branch

- main (complete versions) - PROTECTED BY PULL REQUEST
- dev (developed features) - PROTECTED BY PULL REQUEST
- autotests (developed automatic tests) - PROTECTED BY PULL REQUEST
- design (available design elements) - PROTECTED BY PULL REQUEST
- documentation (developed documentation) - PROTECTED BY PULL REQUEST
- <branch_name>/features/<feature_name>

### Folder structure

- dev (application code)
- autotests (automatic tests)
- design (design elements)
- documentation (documentation elements)
- versions (application versions)
- devtools (custom development tools)
- .github/workflows (github action configs)

## GitHub Flow

- main : the main branch merge elements from (dev, autotests, design, documentation)
- (dev, autotests, design, documentation) : these branches merge elements from feature branches
- <branch_name>/features/<feature_name> : features branches are created from the <branch_name> branch

## Prerequisites

- Git
- Make
- Docker

## Technologies

- GitHub : Code version manager
- Make : Quick commands for utilities
- Docker

## Quick launch process

### For the project

- Launch the makefile command "project-print-init"

## Util links 

- [https://github.com/users/<github_pseudo>/projects/<github_project_id>](GitHub Project)