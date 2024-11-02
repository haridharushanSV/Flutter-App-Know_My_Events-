
# Know My Events

**Know My Events** is a Flutter application that allows users to easily find and manage their scheduled events from their organization. The app fetches event data from a Django REST Framework (DRF) API, providing a seamless experience for users to stay updated on their upcoming activities.

## Features

- **Event Listing:** View a list of scheduled events organized by your organization.
- **Event Details:** Get detailed information about each event, including date, time, and location.
- **User-Friendly Interface:** Intuitive and responsive UI for easy navigation.

## Prerequisites

- Flutter SDK (version 2.0 or higher)
- Dart SDK
- An emulator or physical device for testing
- Access to the Django REST Framework API

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/haridharushanSV/Flutter-App-Know_My_Events.git
   cd know-my-events
   ```

2. **Install dependencies:**

   ```bash
   flutter pub get
   ```

3. **Configure API Endpoint:**
   - Open `lib/constants.dart` and update the API URL to point to your DRF backend.

   ```dart
   const String apiUrl = "https://your-api-url.com/api/";
   ```

4. **Run the app:**

   Use the following command to run the app on your emulator or connected device:

   ```bash
   flutter run
   ```
     ```bash
   flutter run -d chrome --web-renderer html
   ```

## Usage

1. **View Events:** Once logged in, navigate to the events screen to view your scheduled events.
   
## API Integration

The app interacts with a Django REST Framework API that provides endpoints for:

- **Fetching Events**
- **Fetching Event Details**

Ensure your DRF API is up and running before using the app.

## Contributions

Contributions are welcome! If you would like to contribute to the project, please fork the repository and submit a pull request.
