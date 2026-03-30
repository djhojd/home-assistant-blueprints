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
- **🕒 Open Duration Tracking**: Notifications now include exactly how many minutes the door or window has been left open.
- **🌡️ Temperature Awareness**: Automatically adjusts the alert frequency based on the outside temperature (e.g., more frequent alerts when it's freezing).
- **🏠 Presence Filtering**: Intelligently only sends notifications if at least one tracked resident is currently marked as "Home".
- **⚙️ Customizable Thresholds**: Easily define your own "Cold", "Mild", and "Warm" temperature setpoints and notification intervals directly in the Home Assistant UI.
- **⏳ Grace Period**: Includes a built-in 1-minute grace period to avoid notifications for brief openings (like letting a pet out).

---
*Created with ❤️ for better smart home automation.*
