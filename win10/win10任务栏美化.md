# win10任务栏美化

- 需要的软件：TranslucentTB

## 懒人版：

```json
// See https://TranslucentTB.github.io/config for more information
{
  "$schema": "https://sylveon.dev/TranslucentTB/schema",
  "desktop_appearance": {
    "accent": "clear",
    "color": "#00000000",
    "show_peek": false,
    "show_line": false
  },
  "visible_window_appearance": {
    "enabled": true,
    "accent": "clear",
    "color": "#00000000",
    "show_peek": true,
    "show_line": false,
    "rules": {
      "window_class": {},
      "window_title": {},
      "process_name": {}
    }
  },
  "maximized_window_appearance": {
    "enabled": true,
    "accent": "acrylic",
    "color": "#00000000",
    "show_peek": true,
    "show_line": true,
    "rules": {
      "window_class": {},
      "window_title": {},
      "process_name": {}
    }
  },
  "start_opened_appearance": {
    "enabled": true,
    "accent": "clear",
    "color": "#F4F4F4C8",
    "show_peek": true,
    "show_line": true
  },
  "search_opened_appearance": {
    "enabled": true,
    "accent": "normal",
    "color": "#00000000",
    "show_peek": true,
    "show_line": true
  },
  "task_view_opened_appearance": {
    "enabled": true,
    "accent": "clear",
    "color": "#00000064",
    "show_peek": true,
    "show_line": true
  },
  "battery_saver_appearance": {
    "enabled": false,
    "accent": "opaque",
    "color": "#00000000",
    "show_peek": true,
    "show_line": false
  },
  "ignored_windows": {
    "window_class": [],
    "window_title": [],
    "process_name": []
  },
  "hide_tray": false,
  "disable_saving": false,
  "verbosity": "off"
}
```

## 注意

win10开始菜单的遮罩层颜色为：R: 244, G: 244, B: 244, A: 200
win10任务视图的遮罩层颜色为：R: 0, G: 0, B: 0, A: 100
