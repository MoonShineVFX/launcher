# Avalon Launcher

The Launcher provides an interface towards the file-system and environment.

![Avalon Launcher](https://user-images.githubusercontent.com/1860085/42269207-d595694e-7f7d-11e8-922d-c0ab7543c148.gif)

### Branch: Nolava
This branch contains some MoonShine customized features, like:
* [`08a69a6`](https://github.com/MoonShineVFX/launcher/commit/08a69a6cf2c870223a25a5bd152ffff45df95c65) multi-roots: Different root between projects
* [`b8dc31f`](https://github.com/MoonShineVFX/launcher/commit/b8dc31f031ca66109e8f6dc9e15cc79607d0fd07) slash-fix: Fix root path slash
* [`52b5776`](https://github.com/MoonShineVFX/launcher/commit/52b5776f95fb067b7edb0fbfa2eab1d23714d082) project-membership: Project visible on user membership for shorter project list in Launcher home page

## Customization

Environment Variable | Description
--- | ---
```AVALON_ACTIONS``` | Paths to action plugins. Will run "register" method in python scripts, if found.
