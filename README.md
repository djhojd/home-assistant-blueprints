# 🏠 Home Assistant Blueprints

Welcome to my custom repository of smart Home Assistant blueprints! This collection is focused on efficiency, comfort, and sustainability.

## 🚀 Installation

To use a blueprint from this repository:
1. Copy the **Raw** URL of the blueprint YAML file.
2. Go to **Settings** > **Automations & Scenes** > **Blueprints** in Home Assistant.
3. Click **Import Blueprint** and paste the URL.

## 📖 Content

### 🌡️ Dynamic Door/Window Notification
*Path: `blueprints/automation/dynamic_window_notification.yaml`*

**Description**:
Smartly monitors doors or windows and reminds you to close them if the outdoor temperature is cold.

**Key Features**:
- **Temperature Awareness**: Increases frequency of alerts as it gets colder outside.
- **Presence Filtering**: Only notifies residents who are currently marked as "Home", avoiding unnecessary pings while away.
- **Customizable Thresholds**: Easily tune what you define as "Cold", "Mild", and "Warm" directly in the HA UI.

---
*Created with ❤️ for better smart home automation.*
