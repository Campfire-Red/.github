# .github

The org's public face: GitHub renders `profile/README.md` as the landing at
github.com/Campfire-Red and hands `SECURITY.md` to every org repository that
lacks one. Both only work while this repository stays **public** and keeps
its name, so nothing internal goes in — no plan, no open item, no comment
that narrates.

## Rules

- **Texts are not written here.** The landing's sentences are definitions
  in the org's private `Organization` repo, `social/README.md`: the tagline,
  the paragraph, the links, the mailbox. A change starts there and lands
  here after. The claims are Campfire's README badges and nothing more —
  never a competitor's name, never "secure" or "private" alone, never a
  price or the license while both are open.
- **No link into a private repository.** The app repo is private, so a
  link to its releases, `DEPLOY.md` or `ARCHITECTURE.md` 404s for every
  visitor. Until it is public the landing links to `campfire.red`, X and
  the mailbox only; the day it opens, Download, Host your own and How it
  works replace them (Organization `TODO.md`, "The org").
- **The picture is a copy.** `profile/icon.svg` mirrors Campfire's
  `app/src-tauri/icons/icon.svg`; a reshape happens there and is copied
  here. The README references it by its raw URL, which renders on the org
  page and on the repo page alike.
- **`SECURITY.md` is the default, not Campfire's.** Campfire's own policy
  covers the product; this one covers the website, this repo and the org's
  files. Keep the two from contradicting each other: the same mailbox, the
  same "no public issue" rule.
- **Only what GitHub reads.** A file here is one GitHub renders somewhere:
  `profile/`, `SECURITY.md`, and if ever needed the other community health
  files (`CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, issue and PR templates,
  `FUNDING.yml`). Add one when a second repo needs it, not before.
- **Commits** take Conventional Commits subjects like Campfire's
  (`docs(profile): …`); no sign-off is needed here.
