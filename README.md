# pradeepdev001.github.io

Public privacy policies for my Android apps, served by GitHub Pages. The apps'
own repositories stay private; only these pages are public.

| App           | Package                        | Privacy policy URL (for Play Console)                  |
| ------------- | ------------------------------ | ------------------------------------------------------ |
| PK Player     | `com.pktech.pkplayer`          | https://pradeepdev001.github.io/pk-player/privacy/     |
| PK Calculator | `com.pktech.pkcalculator`      | https://pradeepdev001.github.io/pk-calculator/privacy/ |
| Naam Karan    | `com.pktech.naamkaran`         | https://pradeepdev001.github.io/naamkaran/privacy/     |
| PK Downloader | `com.pktech.pkdownloadmanager` | https://pradeepdev001.github.io/pk-downloader/privacy/ |
| PK DocScan    | `com.pktech.pkdocscan`         | https://pradeepdev001.github.io/pk-docscan/privacy/    |

The site root, https://pradeepdev001.github.io/, lists all of them and works as
the "Website" field on a Play listing.

## Editing a policy

Each policy is one Markdown file, `<app>/privacy.md`. Change it, update the
**Effective** date at the top, commit and push — GitHub Pages rebuilds in a
minute or two. The layout is `_layouts/default.html` and the styles are
`assets/style.css`, shared by every page.

A policy must describe what the app actually does. Change it in the same week as
any change to an app's permissions, SDKs or network use — a Play reviewer
compares the policy, the Data safety form and the app itself.

## Adding an app

1. Copy an existing `<app>/privacy.md` to a new folder and set its `permalink`.
2. Add it to the list in `index.md` and to the table above.
