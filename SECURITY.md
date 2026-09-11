# Security

This policy covers the Campfire-Red repositories that have no `SECURITY.md`
of their own: the website, this `.github` repository and the org's files.
Campfire itself — the app, the connector, the crates, the ui package and the
cloud backend — carries its own policy in its repository, and a report about
any of those belongs there.

## Reporting a vulnerability

Use GitHub's private vulnerability reporting on the repository concerned —
Security tab, "Report a vulnerability" — or write to
[we@campfire.red](mailto:we@campfire.red). Please do not open a public issue:
a public issue is a disclosure, and it reaches attackers before it reaches
users.

What helps: what an attacker gains, the smallest reproduction you have, and
where you found it. Expect a first reply within a week and an honest answer
about timing rather than an optimistic one. Credit if you want it.

## Scope

The website is static — one page, no script, no form, no data — so a report
about it is about what it says or serves: a wrong claim, a bad link, a stale
picture. That is welcome too, as an issue rather than an advisory.
