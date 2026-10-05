# Lawyer Logger – public assets

Images for the Lawyer Logger add-on that must be reachable at a public
HTTPS address (for example the Gmail add-on icon, `logoUrl` in the
manifest). The add-on's code is in a separate, private repository.

| File | Use |
| --- | --- |
| `icon/lawyer-logger-128.png` | Gmail add-on icon (`logoUrl`) |
| `icon/lawyer-logger-256.png`, `-48.png`, `-24.png` | Other sizes |
| `icon/*.svg` | The same icon as SVG |

The icon is drawn by `scripts/make-icon.mjs` in the add-on repository. To
change it, edit and rerun that script there, then copy the files here.
Keep the file names: the add-on links to them directly.

© Daniel Rourke Consulting. All rights reserved.
