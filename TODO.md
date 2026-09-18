## FIXME
- icon disappears sometimes (after reload? when moving window across monitors?)
- intermittent Windows crash on link click: added structured logging + fixed missing try/except in `_open_parent_folder`; look at `~/.link4000/link4000.log` after next occurrence

## TODO
- resolve links on OneDrive to sharepoint URLs
- add dialog for managing exclusions (separate dialog or main list with hidden items shown?)
- UX: what buttons do we need in the main list?

## NOT PLANNED
- add auto-update mechanism ← this needs public distribution of a binary which introduces licensing issues
- add indexing of items to enable full text search ← out of scope, link4000 is a link manager, not a document management system
