# Notes app using Swift with Built-in caching

# Reminder App

Welcome to the Reminder App! This app is built using Swift and UIKit, designed to help you manage your tasks with ease. It features push notifications to remind you of your tasks and supports data persistence to ensure your tasks are saved even when you close and reopen the app.

## Features

- **Push Notifications**: Get notified about your reminders.
- **Data Persistence**: Your reminders are saved locally so that they are available even after closing and reopening the app.

## Requirements

- Xcode 12.0 or later
- iOS 14.0 or later
- Swift 5.3 or later

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed Xcode on your Mac.
- You have an Apple Developer account to configure push notifications.

### Installation

### Step 1: Open the Project in Xcode

   ```bash
   git clone https://github.com/j0shiJ/NoiseAssignment.git
     ```

### Step 2: Open the Project in Xcode

Open `NexxReminders.xcodeproj` in Xcode by double-clicking the file or using the command line:

```bash
open NexxReminders.xcodeproj
```

### Step 3: Install Dependencies

If you are using any dependencies managed by CocoaPods or Swift Package Manager, install them:

```bash
pod install
```

### Step 4: Configure Push Notifications

1. Go to your project settings in Xcode.
2. Under the "Signing & Capabilities" tab, add the "Push Notifications" and "Background Modes" capabilities.
3. Make sure your App ID is registered for push notifications in the Apple Developer portal.
4. Configure your push notification certificates in the Apple Developer portal and upload them to your server.

### Step 5: Build and Run

Select your target device or simulator and click the run button in Xcode or use the shortcut `Cmd + R`.

### Usage

Once the app is running on your device or simulator:

1. **Add a Reminder**: Tap the add button (+) to create a new reminder.
2. **Set Notification**: Set the time for your reminder to receive a push notification.
3. **Data Persistence**: Close and reopen the app to see your saved reminders.
