# Looneth's Repo

A custom Dalamud repository for Looneth's Final Fantasy XIV plugins. Browse plugin details and release status on the [plugin directory](https://ey4o.github.io/XIV-Plugins/).

> **Current status:** AutoTataru 0.9.0 is available as a testing release. RePlate is a work in progress and not in the feed yet.

## Add the repository to Dalamud

1. Launch the game with Dalamud enabled and type `/xlsettings` in chat.
2. Open **Experimental → Custom Plugin Repositories**.
3. Add this URL and save:

   ```text
   https://ey4o.github.io/XIV-Plugins/repo.json
   ```

4. Type `/xlplugins` to open the Plugin Installer, then find and install the plugin there. Dalamud will use this same repository for future updates.

There is no need to download a ZIP manually.

## Plugins

| Plugin | Status | Details |
| --- | --- | --- |
| AutoTataru | Testing release 0.9.0 | [Plugin page](https://ey4o.github.io/XIV-Plugins/plugins/autotataru/) |
| RePlate | Work in progress; public release pending | [Plugin page](https://ey4o.github.io/XIV-Plugins/plugins/replate/) |

The [directory site](https://ey4o.github.io/XIV-Plugins/) will list new plugins and release information as they become available.

## About this repository

The site is hosted from `docs/` with GitHub Pages. The file `docs/repo.json` is the [Dalamud custom repository feed](https://dalamud.dev/plugin-publishing/custom-repositories/); it will list plugins only after their public builds are verified.
