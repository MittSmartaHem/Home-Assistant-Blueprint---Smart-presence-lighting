# 💡 Presence-Based Lighting Blueprint

This Home Assistant blueprint automates lighting based on presence detection and household mode. It’s designed to create smart, mood-aware lighting that adapts to whether someone is home, asleep, or away.

## ✨ Features

- Adjustable brightness for different household modes (`home`, `sleep`)
- Delayed shutoff depending on how long the room has been empty
- Easy configuration via Home Assistant UI

## 🧰 Requirements

To use this blueprint, you need:

- `input_select` helper for household mode (with options like `home`, `sleep`)
- `input_datetime` helper to track last presence (type: Date and Time)
- Presence sensor(s) for the room
- Light entity to control

## ⚙️ Configuration

When creating an automation from this blueprint, you’ll be asked to:

- Select the presence sensor for the room
- Choose the light entity to control
- Set brightness levels for each mode
- Define delay times before turning off the light

## 🔗 Import Blueprint

You can import this blueprint directly into Home Assistant using the link below:
