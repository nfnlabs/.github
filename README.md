# nfnlabs/.github

Org-wide default community health files for `nfnlabs`.

## Issues

The structure of an issue comes from the organization settings:

- **Issue types** (Org settings > Planning > Issue types): Bug, Task, Story,
  Feature and Epic.
- **Issue fields** (Org settings > Planning > Issue fields): Priority, Severity,
  Environment, Platform, Discipline, Bug category, Effort, Start date, Target
  date, Request kind, Requested on and Approved on.

The forms in `.github/ISSUE_TEMPLATE/` only prompt for the description and set
the issue type automatically, using the type defined in the organization
settings. They do not add labels. Fields such as Severity or Approved on are set
in the issue sidebar after the issue is created. Choosing "Open a blank issue"
creates an issue with no type; pick the type from the sidebar.

| Form | Issue type |
|---|---|
| Epic | Epic |
| Bug report | Bug |
| Task | Task |
| Feature request / Improvement / Change request | Feature |
| Story | Story |

Repositories that define their own `.github/ISSUE_TEMPLATE/` override these.
