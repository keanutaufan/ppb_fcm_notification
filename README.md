# PPB Awesome Notifications + FCM

A simple app to demonstrate how to send notifications on mobile device
built using Flutter, Awesome Notification, and Firebase,
developed by yours truly:

- **Name:** Keanu Fortuna Taufan
- **NRP:** 5025221043
- **Class:** Mobile Programming B

Some (laggy) previews:

https://github.com/user-attachments/assets/bc5e8a41-8175-4b47-9ae1-348634cb5cb9

## Features

- **Local Notification** - various locally triggered notification, powered by Awesome Notifications
- **Cloud Notification** - notification campaign sent from FCM console, powered by Firebase
- **Auth** - user login powered by Firebase Auth 

## Installation

### Prerequisites

- Dart and Flutter SDK
- Device emulator or real device in developer mode
- Code editor

### Steps

**1. Clone this repository:**

```bash
git clone https://github.com/keanutaufan/ppb_fcm_notification.git
cd ppb_fcm_notification
```

**2. Install dependencies:**

```bash
flutter pub get
```

**3. Run the application:**

```bash
flutter run
```

**4. Replace Firebase credential with yours (optional)**


## How to Use

1. **Write down the FCM token**
   - When the application first run, flutter will print your FCM token to the console
   - Copy this value as this will be needed later
   - If you can't see this value, make sure you run Flutter in debug mode

2. **Login to the Application**
   - Use the default credentials:
     
     ```
     Email    : testuser@example.com
     Password : testuser
     ```
  
3. **Use the Local Notification**
   - Once authenticated, navigate to the Notification page
   - Test out various local notifications
  
4. **Test out the FCM functionality**
   - To use the Firebase Cloud Messaging functionality, you'd need to use your own Firebase credentials
   - Navigate to Firebase Cloud Messaging in your Firebase console, and create a new campaign
   - Type in your notification details to the console
   - To test out the FCM functionality, use the "Send Test Message" feature
   - Paste your FCM token when prompted

## References

- [Awesome Notification Guide by @agusbudi](https://github.com/agusbudi/mobile-programming/tree/main/10.%20Awesome%20Notifications)
- [Firebase Cloud Messaging Documentation](https://firebase.google.com/docs/cloud-messaging)
- [Awesome Notifications Documentation](https://pub.dev/packages/awesome_notifications)
