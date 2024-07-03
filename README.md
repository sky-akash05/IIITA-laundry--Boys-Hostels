

# IIITA Laundry System App

This is a mobile application designed to manage the laundry services for IIITA Boys Hostels. Built using React Native and Firebase, the app provides a seamless experience for students to schedule laundry pickups, track their laundry status, and receive notifications.

## Features

- **User Authentication:** Secure login and registration using Firebase Authentication.
- **Laundry Scheduling:** Users can schedule laundry pickups.
- **Status Tracking:** Real-time tracking of laundry status.
- **Notifications:** Push notifications to keep users updated on their laundry status.
- **Admin Panel:** Admins can manage laundry requests and update statuses.

## Technologies Used

- **Frontend:** React Native
- **Backend:** Firebase (Firestore, Authentication)
- **Notifications:** Firebase Cloud Messaging (FCM)

## Installation

To run this project locally, follow these steps:

### Prerequisites

- Node.js
- npm or yarn
- Firebase project setup

### Clone the Repository

```bash
git clone https://github.com/sky-akash05/IIITA-laundry--Boys-Hostels.git
cd IIITA-laundry--Boys-Hostels
```

### Setup

1. Install the dependencies:

```bash
npm install
```

2. Create a `.env` file in the root directory and add the following environment variables:

```env
FIREBASE_API_KEY=your_firebase_api_key
FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
FIREBASE_PROJECT_ID=your_firebase_project_id
FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
FIREBASE_APP_ID=your_firebase_app_id
```

### Firebase Configuration

Ensure that your Firebase project is properly set up with Firestore, Authentication, and Cloud Messaging. You can follow the Firebase documentation to set these up.

### Running the Application

1. Start the Metro bundler:

```bash
npm start
```

2. Run the application on an emulator or physical device:

```bash
npm run android    # For Android
npm run ios        # For iOS
```

## Usage

1. Register a new user or log in with existing credentials.
2. Schedule a laundry pickup by selecting the date and time.
3. Track the status of your laundry in real-time.
4. Receive notifications about your laundry status.
5. Admins can log in to access the admin panel for managing laundry requests and updating statuses.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.
