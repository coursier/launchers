# coursier CLI launchers

The latest coursier CLI launchers are pushed in this repository by the coursier CI release workflow.

Beware that some of those launchers are deprecated, but kept here so as not to break workflows of users relying on them:
- `cs-amd64-*` launchers: use the `cs-x86_64-*` launchers instead
- non compressed `cs-*` launchers: use the `.gz` (Linux, macOS) or `.zip` (Windows) launchers instead, and uncompress them before use
