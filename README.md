# Flutter Presence Management
# Flutter Presence Management

## Introduction

Open Source Flutter Presence App integrated with geolocation (GPS) to help companies manage employee attendance and work shifts. Features a multi-user system (admin and employee), a beautiful user interface, and is built using **Flutter**, **GetX**, and **Firebase**. Easy to customize or extend with new features.

## App Screenshots

<img src="https://github.com/mrezkys/flutter_presence/blob/main/demo/banner.jpg" width="auto" height="auto" >
<img src="https://github.com/mrezkys/flutter_presence/blob/main/demo/shot.jpg" width="auto" height="auto" >
<img src="https://github.com/mrezkys/flutter_presence/blob/main/demo/details.jpg" width="auto" height="auto" >

## Demo

You can try the demo (Android only):

[Download Demo APK](https://github.com/mrezkys/flutter_presence/tree/main/demo/application)

**Admin Login**  
Email: mrezkysulihin@gmail.com  
Password: 123456789

**Employee Login**  
Email: mrezkysulihin12@gmail.com  
Password: 123456789

## Installation

**Step 1:** Clone the repository and get dependencies:

```bash
git clone https://github.com/Wissemtriki/Flutter-Presence-Management.git
cd flutter_presence
flutter pub get
Step 2: Rename the app package name (to avoid Firebase issues) manually or using the rename package
.

Step 3: Reinitialize Firebase CLI (See Documentation
).

Step 4: Enable Firebase email/password authentication.

Step 5: Create Firestore Database.

Step 6: Set up the database and admin account:

Add user in Firebase Authentication.

Copy the User UID.

Create a Firestore collection using the UID as the document ID.

Set the role field (admin or employee) and created_at using ISO8601 string format, e.g.:

2022-05-10T12:34:58.274129
Step 7: Run the Flutter app.

Step 8: Update company data at lib/company_data.dart.

About the Author

Developed by mrezkys
.
UI designed by mrezkys
.

Thanks To

Icons created by Piqo Design
 used in this project.

License

Flutter Presence is licensed under the MIT License.

Donate

Support the project at trakteer

<a href="https://trakteer.id/mrezkys" target="_blank"><img src="https://cdn.trakteer.id/images/embed/trbtn-red-5.png" height="45" style="border: 0px;" alt="Trakteer Saya"></a>

Announcement

Flutter Presence is currently at v1.0.0.
