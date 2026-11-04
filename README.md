# Loadout for Claude Code

Loadout gives your AI real business data and tested methods for running and growing a business. Your AI uses it to find clients, price and pitch an offer, check websites, domains and email setup, read reviews and local search rankings, and hand the work over as files.

## Install

In Claude Code, run these two commands:

```
/plugin marketplace add agentloadout/loadout
/plugin install loadout@loadout
```

The second one opens the plugin: choose to install it. Then type `/mcp`, pick the Loadout server and sign in with your Loadout account. No account yet? You can make one when you sign in.

From a terminal, the same is `claude plugin marketplace add agentloadout/loadout` then `claude plugin install loadout@loadout`.

To get a newer version, run `/plugin marketplace update loadout`, or turn on auto-update for this marketplace in `/plugin`.

## What the plugin contains

- **One skill, `loadout`.** The front door: it picks the right Loadout method for a business task and keeps your Business Brief.
- **A startup hook.** At the start of each session, and after `/clear` or compaction, it tells Claude that Loadout is connected and lists Loadout's methods, so Claude loads the right one before it fetches any data. It prints a text file that ships with the plugin. It runs no other program and sends nothing anywhere.
- **The Loadout server address**, `https://mcp.agentloadout.com`, which you sign in to.

The methods themselves are not in this repository. After you sign in, Claude loads them from Loadout's server, so they are always the current version.

Loadout: https://agentloadout.com. Terms: https://app.agentloadout.com/terms. Privacy: https://app.agentloadout.com/privacy.
