# hass-hue-icons

Vector based icon pack for Home Assistant, inspired by the Hue icons. For personal use only.

## Installation

- Copy `hass-hue-icons.js` into your config/www folder.
- Go to Configuration -> Lovelace Dashboards -> Resources -> Add Resource
- set url as `/local/hass-hue-icons.js` and Resource Type as `Javascript Module`.
- Save, restart Home Assistant.

## Usage

- In your entity editor, specify an icon as `hue:icon_name`

### Example:

```
title: My Room
state_color: true
type: entities
entities:
  - entity: light.my_wall_light
    name: My Wall Light
    icon: hue:wall_spot
```

### Troubleshooting:
If you cannot see the new icons, flush your network cache. 

# Thanks and Props
@hulkhaugen and @thomasloven for the technique.