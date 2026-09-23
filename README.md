# Looneth's Repo

A custom Dalamud repository for Looneth's Final Fantasy XIV plugins. Browse plugin details and release status on the [plugin directory](https://ey4o.github.io/XIV-Plugins/).

> **Current status:** AutoTataru is in testing. There is no public plugin download yet, so the repository feed is empty and no plugin will appear in the installer until a release is ready.

## Add the repository to Dalamud

1. Launch the game with Dalamud enabled and type `/xlsettings` in chat.
2. Open **Experimental → Custom Plugin Repositories**.
3. Add this URL and save:

   ```text
   https://ey4o.github.io/XIV-Plugins/repo.json
   ```

4. Type `/xlplugins` to open the Plugin Installer. Once a plugin has a public release, find and install it there. Dalamud will use this same repository for future updates.

You can add the repository now, but the installer will show no plugins from it until the first public release. There is no need to download a ZIP manually.

## Plugins

| Plugin | Status | Details |
| --- | --- | --- |
| AutoTataru | In testing; public release pending | [Plugin page](https://ey4o.github.io/XIV-Plugins/plugins/autotataru/) |

The [directory site](https://ey4o.github.io/XIV-Plugins/) will list new plugins and release information as they become available.

## About this repository

The site is hosted from `docs/` with GitHub Pages. The file `docs/repo.json` is the [Dalamud custom repository feed](https://dalamud.dev/plugin-publishing/custom-repositories/); it will list plugins only after their public builds are verified.
