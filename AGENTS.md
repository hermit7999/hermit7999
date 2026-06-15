# AGENTS.md

## Cursor Cloud specific instructions

This repository is a **GitHub profile README** repo (the special `hermit7999/hermit7999` repo). Its sole content is `README.md`, which GitHub renders on the owner's profile page.

There is intentionally **no application, dependency manifest, build system, test suite, or lint config** here. Do not look for `package.json`, `requirements.txt`, services, CI, or git hooks — none exist. The update script is a no-op for this reason.

- "Running" the project means rendering `README.md` the way GitHub does. To preview locally, use any GitHub-flavored markdown previewer, e.g. `grip` (`pip install grip` then `grip README.md 0.0.0.0:6419`) and open `http://localhost:6419/`.
- Note: unauthenticated/offline `grip` renders GitHub emoji shortcodes (e.g. `:wave:`) as raw text; GitHub itself renders them as emoji. This is a previewer limitation, not a content issue.
