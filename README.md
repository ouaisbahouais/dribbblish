# Dribbblish

## Screenshots
#### Base
![junoTweak](https://raw.githubusercontent.com/ouaisbahouais/dribbblish/main/Capture%20d%E2%80%99%C3%A9cran%20du%202021-03-20%2020-37-51.png)

## More
Requires spicetify-cli **v0.9.9 or newer**.

### How to install

Run these commands:

#### Linux:
In **Bash**:
```bash
cd "$(dirname "$(spicetify -c)")/Themes/Dribbblish"
mkdir -p ../../Extensions
cp dribbblish.js ../../Extensions/.
spicetify config extensions dribbblish.js
spicetify config current_theme Dribbblish color_scheme base
spicetify config inject_css 1 replace_colors 1 overwrite_assets 1
spicetify apply
```

### Color Schemes
There are 9 color schemes you can choose: `base`, `white`, `dark`, `dracula`, `gruvbox`, `nord-dark`, `nord-light`, `horizon`, `samourai`, `purple`. Change scheme with commands:
```
spicetify config color_scheme <scheme name>
spicetify apply
```

## `color.ini` reference

These keys are used in the `colors.ini` file.

| Key | Target |
|-|-|
|`main_fg`| The main Accent, used for sidebar and some interface elements|
|`main_bg`| The real star of the show, the main Backgroud of app (on the right side)|
|`secondary_fg`| Main text and some other small stuff|
|`secondary_bg`| The background for the left side navbar|
|`selected_button`| Button currenly being hovered|
|`pressing_fg`| The color that momentarialy appears when you press anything|
|`pressing_button_fg`| The textcolor for a pressed button|
|`pressing_button_bg`| BG color for the pressed button|
|`sidebar_and_player_bg`| Background for the player|
|`sidebar_indicator_and_hover_button_bg`| For the slider & selected items when you hover over it|
|`cover_overlay_and_shadow`| Overlay for when you hover over the album covers|
|`slider_bg`| The background for the slider|
|`scrollbar_fg_and_selected_row_bg`| Color for the current selected row|
|`active_control_fg`| Foreground for active control items|
|`indicator_fg_and_button_bg`| Button text color|
|`miscellaneous_bg`| The background color of toolips ("You're offline" etc)|
|`miscellaneous_hover_bg`| Hover Color for the Tooltips|
|`preserve_1`| Misc text colors|
