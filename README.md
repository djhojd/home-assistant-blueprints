# 🏠 Home Assistant Blueprints

Welcome to my custom repository of smart Home Assistant blueprints! This collection is focused on efficiency, comfort, and sustainability.

## 🚀 Installation

To use a blueprint from this repository:
1. Copy the **Raw** URL of the blueprint YAML file.
2. Go to **Settings** > **Automations & Scenes** > **Blueprints** in Home Assistant.
3. Click **Import Blueprint** and paste the URL.

## 📖 Content

**Quick Links**:
- [🌡️ Dynamic Door/Window Notification](#-dynamic-doorwindow-notification)
- [🕹️ IKEA BILRESA Dual Button Generic Remote](#-ikea-bilresa-dual-button-generic-remote)
- [💡 IKEA BILRESA Dual Button Light Remote](#-ikea-bilresa-dual-button-light-remote)

---

### 🌡️ Dynamic Door/Window Notification
*Path: `blueprints/automation/dynamic_window_notification.yaml`*

**Description**:
Smartly monitors doors or windows and reminds you to close them if the outdoor temperature is cold.

**Key Features**:
- **🕒 Open Duration Tracking**: Notifications now include exactly how many minutes the door or window has been left open.
- **🌡️ Temperature Awareness**: Automatically adjusts the alert frequency based on the outside temperature (e.g., more frequent alerts when it's freezing).
- **🏠 Presence Filtering**: Intelligently only sends notifications if at least one tracked resident is currently marked as "Home".
- **⚙️ Customizable Thresholds**: Easily define your own "Cold", "Mild", and "Warm" temperature setpoints and notification intervals directly in the Home Assistant UI.
- **⏳ Grace Period**: Includes a built-in 1-minute grace period to avoid notifications for brief openings (like letting a pet out).

---

### 🕹️ IKEA BILRESA Dual Button Generic Remote
*Path: `blueprints/automation/ikea_bilresa_dual_button_remote.yaml`*

**Description**:
A universal blueprint that transforms your IKEA BILRESA Dual Button remote into a powerful, generic controller for any Home Assistant action.

**Key Features**:
- **🌟 6 Custom Action Slots**: Support for Single Click, Double Click, and Long Press on both the Upper and Lower buttons.
- **📱 Universal Compatibility**: Can control Climate, Media Players, Covers, Scripts, or Scenes.
- **🚀 Responsive Interaction**: Built with `mode: restart` for a snappy remote feel.

---

### 💡 IKEA BILRESA Dual Button Light Remote
*Path: `blueprints/automation/ikea_bilresa_dual_button_light_remote.yaml`*

**Description**:
A specialized version of the remote blueprint optimized specifically for light entities and light groups.

**Key Features**:
- **🛠️ Smart Brightness Logic**: Pre-configured for increase/decrease steps and brightness cycling.
- **✨ Custom Templates**: Both double-click actions support custom Jinja2 templates for ultimate flexibility directly in the UI.
- **⚙️ Configurable Step Size**: Choose your own brightness increment/decrement percentage.

---
*Created with ❤️ for better smart home automation.*
