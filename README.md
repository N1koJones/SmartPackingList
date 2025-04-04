# SmartPackingList

SmartPackingList is an Android app that helps users create and manage packing lists for their trips. It features offline item suggestions based on trip type, destination, and duration.

## Features

- Create and edit packing lists
- Add, edit, delete, and check off individual items
- Smart item suggestions based on fuzzy-matched trip details
- Room database for persistent offline storage
- Optional dark mode
- Trip reminder notifications sent the day before departure

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/SmartPackingList.git
   ```

2. Open the project in Android Studio

3. Build and run on an emulator or device

## Notes

- Notifications require POST_NOTIFICATIONS permission on Android 13+
- Exact alarms may require system settings access on Android 12+
- If you see an error related to Room.databaseBuilder(...), Android Studio will usually offer to add the missing Room dependency via a popup. Just click "Add dependency" when prompted, and it will handle the installation for you automatically.
