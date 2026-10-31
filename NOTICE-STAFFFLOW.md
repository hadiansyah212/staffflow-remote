# StaffFlow Remote

Modified version of [RustDesk](https://github.com/rustdesk/rustdesk) 1.5.0, distributed under the
GNU AGPL-3.0 (see `LICENCE`). Original work: Copyright Purslane Tech Pte. Ltd. and contributors.
"RustDesk" is the upstream project's name; this build is not affiliated with or endorsed by it.

Changes, first made 2026-10-31 (see the `staffflow` branch history):

- App name, icons and rendezvous server/key.
- Unused features locked off (file transfer, tunnel, terminal, audio, camera, printer, remote restart).
- Added the `--staffflow-session` command, used by the StaffFlow app to switch approval mode.
- The "being controlled" connection window can't be hidden.

Source of this build: https://github.com/hadiansyah212/staffflow-remote (branch `staffflow`) and
https://github.com/hadiansyah212/staffflow-remote-common (branch `staffflow`).
