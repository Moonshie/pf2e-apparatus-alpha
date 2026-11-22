# PF2e Apparatus alpha

Early testing builds for invited GM friends. Downloads are public; please share feedback with Moonshie.

## Install

In Foundry Setup, open **Add-on Modules → Install Module**, paste a manifest URL and click **Install**.

- **Apparatus:** https://raw.githubusercontent.com/Moonshie/pf2e-apparatus-alpha/main/pf2e-apparatus/module.json
- **Apparatus UI (optional):** https://raw.githubusercontent.com/Moonshie/pf2e-apparatus-alpha/main/pf2e-apparatus-ui/module.json

Install Apparatus first, then Apparatus UI if wanted. Enable the modules in your PF2e world.
PF2e HUD remains required in both Classic and Modern presentation. Players joining your server do not install separate copies.

The current development baseline is **Foundry 14.369, PF2e 8.6.1 and PF2e HUD 2.57.0**.
The UI adapter supports PF2e HUD 2.56.2 and 2.57.0. Apparatus also requires Socketlib, PF2e Toolbelt and libWrapper;
Foundry will offer the declared dependencies, including any dependencies of PF2e HUD.

## Updates

Use Foundry Setup's normal module update controls. Keep using these same manifest URLs.
Only published alpha builds appear here; development commits are not automatic releases.
Each player can choose Modern or Classic in Apparatus UI's module settings.

## Feedback

Send Moonshie the two module versions, Foundry/PF2e/PF2e HUD versions and steps to reproduce the issue.
Use a backup or copy of a world for initial alpha testing.

## Distribution

This repository hosts release manifests and built installation ZIPs. The development repositories remain private.
The JavaScript delivered to Foundry clients can still be inspected. Asset attribution is included in the installation ZIPs.
