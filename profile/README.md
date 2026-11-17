# Monkeymaxxing

**Server systems run by your coding agent: bank-vault secure, massively scalable, and a fraction of the cost.**

Reject the galaxy brain. Return to monkey.

Free, open source tools for running your own server systems. You or your
coding agent use them to build, fix, and move every part.

| Tool | What it does |
| --- | --- |
| [Monkeymaxxing Stack](https://github.com/monkeymaxxing/monkeymaxxing-stack) | A full production system for web apps, websites, and APIs, on plain Linux servers in your own accounts. Your coding agent builds it in about a day and then runs it. |
| [MMX](https://github.com/monkeymaxxing/mmx) | Sets up and changes your Linux servers. You list what each server should have in plain YAML files; `mmx dryrun` shows what would change, and `mmx run` makes the changes. |
| [MMWatchdog](https://github.com/monkeymaxxing/mmwatchdog) | Watches your Linux servers and alerts you when something is wrong. You list what to watch, such as a service, a web page, a disk, or a database, in plain YAML files. |
| [MMHotline](https://github.com/monkeymaxxing/mmhotline) | Gets an urgent alert to a person who can act on it. It works out who is on call and contacts them on their phone; if they don't answer, the backup, then everyone else who is available. |
| [doubleshell](https://github.com/monkeymaxxing/doubleshell) | Lets you SSH to your servers over WireGuard, so no SSH port is open to the internet. It runs WireGuard inside itself, so your laptop needs no VPN and no admin rights, and you keep using `ssh`, `scp` and `rsync` as before. |

Every repository is also on [GitLab](https://gitlab.com/monkeymaxxing), for
when GitHub is down. Report issues and send changes here on GitHub.

Guides, courses, and the newsletter: [monkeymaxxing.com](https://monkeymaxxing.com)
