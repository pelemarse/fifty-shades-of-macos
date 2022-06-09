# Fifty Shades of MacOS

Sublime Text 4 Dark and Light Theme. Tested only on the latest versions of MacOS (12.4) and Sublime Text 4 Dev Build (4134). Made for yourself, but maybe someone will be interested too.

Syntax color schemes is on very basic level stage.

<img src="screenshot.png" alt="Alt text" title="Optional title">

[More Screenshots](../main/screenshots/screenshots.md)

### Recommended Sublime Text settings
`Preferences.sublime-settings`
```json
{
	"theme": "auto",
	"file_tab_style": "rounded",
	"show_tab_close_buttons_on_left": true,
	"show_tab_close_buttons": true,
	"hide_tab_scrolling_buttons": true,
	"close_windows_when_empty": false,
	"hide_tabs_dropdown_button": true,
	"hide_new_tab_button": true,
	"caret_style": "blink",
	"font_face": "SF Mono",
	"rulers": [80],
	"highlight_line": false,
	"scroll_past_end": true,
	"mini_diff": false,
	"color_scheme": "auto",
	"dark_theme": "Fifty Shades of MacOS Dark.sublime-theme",
	"light_theme": "Fifty Shades of MacOS.sublime-theme",
	"dark_color_scheme": "Fifty Shades of MacOS Dark.sublime-color-scheme",
	"light_color_scheme": "Fifty Shades of MacOS.sublime-color-scheme",
}
```

### Terminus plugin settings
`Terminus.sublime-settings`
#### Dark Mode
```json
{
	"theme": "user",
	"unix_term": "xterm-256color",
	"256color": true,
	"user_theme_colors":
		{
			"comment": "#282a37",
			"background": "#1e1e1e",
			"black": "#000000",
			"blue": "#bd93f9",
			"brown": "#f1fa8c",
			"cyan": "#8be9fd",
			"foreground": "#f8f8f2",
			"green": "#50fa7b",
			"light_black": "#555555",
			"light_blue": "#bd93f9",
			"light_brown": "#f1fa8c",
			"light_cyan": "#8be9fd",
			"light_green": "#50fa7b",
			"light_magenta": "#ff79c6",
			"light_red": "#ff5555",
			"light_white": "#ffffff",
			"magenta": "#ff79c6",
			"red": "#ff5555",
			"white": "#bbbbbb",
		},
	"view_settings": {
		"font_face": "SF Mono Regular",
		"font_size": 11,
		"rulers": []
	}
}
```

#### Light Mode

```json
{
	"theme": "user",
	"unix_term": "xterm-256color",
	"256color": true,
	"user_theme_colors":
  {
    "comment": "#282a37",
    "background": "#ffffff",
    "foreground": "#1f2023",
    "black": "#000000",
    "red": "#990001",
    "green": "#00a600",
    "blue": "#0000b2",
    "magenta": "#b102b3",
    "cyan": "#00a6b2",
    "white": "#bfbfbf",
    "brown": "#979648",
    "light_black": "#bfbfbf",
    "light_red": "#e50101",
    "light_green": "#008540",
    "light_blue": "#0000ff",
    "light_magenta": "#e501e6",
    "light_cyan": "#00e5e6",
    "light_white": "#e5e6e6",
    "light_brown": "#b0b300"
  },
	"view_settings": {
		"font_face": "SF Mono Regular",
		"font_size": 11,
		"rulers": []
	}
}
```
