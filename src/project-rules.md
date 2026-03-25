# Project Rules

## Branch Naming

Branch names should follow this structure:

```
<purpose>/#<task-number>-<short-description>
```

### Purpose
- `feature` - New features
- `bugfix` - Fixing bugs
- `hotfix` - Urgent fix

### Examples
- `feature/#67-add-some-controller`
- `bugfix/#52-api-documentation`

### Notes:

Task number should correspond to the issue or ticket in the project management system.
Short description should be lowercase, words separated by hyphens (-).
Keep branch names concise and descriptive.

## Commit format

```
<type>: #<task-number>-<task-short-description>

Commit description
```

Type table:
- `feat` - New feature
- `fix` - Bug fix
- `docs` - Changes to documentation
- `style` - Formatting (does not affect the code)
- `refactor` - Refactoring without changing functionality
- `test` - Adding tests
- `chore` - Updating dependencies, configuring CI
