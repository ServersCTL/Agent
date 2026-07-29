# Contributing

Thank you for helping improve ServersCTL.

## Bug reports

**Preferred:** use the ServersCTL panel — **Support hub → Bug reports** at [serversctl.com/app/support/bugs](https://serversctl.com/app/support/bugs) (no GitHub account required).

**Optional:** open a **[GitHub issue](https://github.com/ServersCTL/Agent/issues/new?template=bug_report)** if you already use GitHub. Include:

- Agent version (from the panel **Settings → Agent updates** card or `balctl-agent-version.txt` on the server)
- Pool type (HAProxy, OpenLiteSpeed, Galera, cPanel, etc.)
- Steps to reproduce
- Diagnostic log output from the affected server

## Using the agent

Running the agent requires enrollment through [serversctl.com](https://serversctl.com) (or [balctl.com](https://balctl.com) for HAProxy pools). Community and Pro plans both include documentation and in-app bug reports.

## Code changes

This repository is a **read-only mirror** of the shipped agent source. We do not merge pull requests here. Security-sensitive fixes are handled through our private release process.

## Security

See [SECURITY.md](SECURITY.md) for responsible disclosure.
