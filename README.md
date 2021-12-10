# Remote Workspace

**Sometimes it's the work that's remote, sometimes it's the workspace**

A quick way to spin up a Debian cloud machine with Chrome and web-based VNC, all securely tunneled for your user only via the magic of GitHub Codespaces.

## Setup

1. Fork this repo into an organization that has [GitHub Codespaces](https://github.com/features/codespaces) enabled
1. Launch a Codespace
1. Once it loads, click the "ports" tab (next to "terminal") in VS Code, and open the url shown in the Local Address column
1. Type in "vnc" as the password for the NoVNC web client
1. Open Chrome by clicking the menu icon on the bottom left and selecting "Web Browser".

You now have a Linux machine running in the cloud for (relatively) [cheap](https://docs.github.com/en/billing/managing-billing-for-github-codespaces/about-billing-for-codespaces#codespaces-pricing)!