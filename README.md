# ServersCTL agent

Public source mirror of the ServersCTL VM agent (heartbeat client, job runner, and self-update helper).

**Using the agent requires a [ServersCTL](https://serversctl.com) account** and enrollment through the control plane. The agent is licensed, not sold — see [LICENSE](LICENSE).

## Bug reports

Report defects from the ServersCTL panel: **Support hub → Bug reports** ([serversctl.com/app/support/bugs](https://serversctl.com/app/support/bugs)). No GitHub account required — include agent version, pool type, steps to reproduce, and diagnostic logs from the affected server.

Optional: if you already use GitHub, you may also open an issue on **[GitHub Issues](https://github.com/ServersCTL/Agent/issues/new?template=bug_report)**.

## Install

1. Create a pool and enroll the server from the ServersCTL panel.
2. Run the install command shown on the member **Agent** tab.

Official production builds are distributed from the ServersCTL CDN (`download.serversctl.com`), not from this repository. Source here is published for transparency and issue tracking; sync may lag slightly behind the CDN during releases.

## Repository policy

- **Issues:** welcome — use the bug report template.
- **Pull requests:** not accepted on this mirror; development happens in the private ServersCTL monorepo.
