# Stage Hunter — interactive demo

https://linaismailova-cloud.github.io/stage-hunter-demo/

This repository contains only static build assets. Application source remains private.

The current demo reuses the prepared cabinet components with an isolated local adapter:
work areas, position schedules, scoped professional profiles, event discussion,
draft recovery, delivery reconciliation, readiness and operational admin screens.

All people, qualifications, contacts and events are synthetic. Select a character
in the demo banner to check both sides. Data remains in that browser; there is no
real registration, server authorization or device synchronization. Do not enter
personal data. Test controls (clock, interrupted save, lost reply, reset) are in
the collapsible demo tools. Contact entry and real Auth are disabled.

- `/presentation/`: presentation and profession catalog
- `/demo/`: new interactive cabinets (also at `/`)
- `/demo/?role=worker`: specialist
- `/demo/?role=admin`: synthetic administrative view
- `/mini-app/`: Telegram UI shell with browser fallback, synthetic data and disabled identity
- `/legacy-demo/`: previous prototype; separate browser storage is preserved
- `/release.json`: exact source version and disabled runtime flags

Telegram login, SMTP, real database security and multi-connection transactions
are not demonstrated by this static site. No individual 1:1 chat is claimed.

The Mini App shell has not been connected to a live bot. Telegram UI integration is
validated with a mock SDK; real Android/iOS validation and server login remain pending.
