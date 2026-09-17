# Screenshot file names

Drop PNGs here (this folder is Docusaurus `static/img/`). Captions and page mapping: docs page **Screenshot inventory** (`/meta/screenshot-inventory`).

Until a PNG exists, the site shows `_todo.svg`.

Raw captures: workspace `Screenshots/`. Publish:

```text
python tools/crop_docs_screenshots.py
```

```
overview/main-window.png
runners/table.png
runners/row-selected.png
runners/presets.png
runners/schedule.png
miners/table.png
miners/presets.png
performance/charts.png
about/tab.png
settings/overview.png
settings/coordination.png
settings/cpu.png
settings/appearance.png
settings/appearance-accent.png
settings/appearance-accent-mono.png
settings/miners-ytdlp.png
settings/app-behavior.png
settings/app-behavior-session.png
settings/app-behavior-startup.png
settings/app-behavior-updates.png
settings/app-behavior-tray.png
settings/app-behavior-disk.png
settings/app-behavior-deferred.png
settings/work-schedule.png
settings/notifications.png
settings/libraries.png
```

Still missing (placeholder on the page):

```
start/getting-started.png
runners/letterbox.png
miners/queue.png
tray/menu.png
tray/icon.png
help/f1-shortcuts.png
settings/path-vitality.png
```
