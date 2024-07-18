# TalkEase

This Android chat application leverages Google Firebase for authentication, database, and storage functionalities. Users can log in, search, and chat with others on the server. Additionally, users can upload a profile picture and update their name. This README file provides an overview of the app's features, setup instructions, and dependencies.
## Interface
![1](https://github.com/user-attachments/assets/69e98a53-813d-401f-8ecf-e93bb2f6f02c)
![2](https://github.com/user-attachments/assets/7545c81a-ea06-406b-b06e-e8af47c7fdac)
![3](https://github.com/user-attachments/assets/e1048055-5040-490b-abe1-2a741711d449)
![4](https://github.com/user-attachments/assets/69419d94-f634-4e8a-a67d-3be0e297b446)
![5](https://github.com/user-attachments/assets/25edb4c2-8c5a-4140-b053-425c5b898ed1)
![6](https://github.com/user-attachments/assets/f420e844-08a8-4415-bc5a-d699dce465b2)


## Features
- **User Authentication**: Login page with Firebase Authentication.
- **Chat Functionality**: Search and chat with any person on the server.
- **User Profile**: Upload profile pictures and update user names.
- **Data Storage**: Store user details and chatrooms using Firebase Firestore.
- **Messaging**: Firebase Cloud Messaging integration for real-time chat updates.

## Dependencies

The project uses the following dependencies:

```bash
dependencies {
    implementation("androidx.appcompat:appcompat:1.6.1")
    implementation("com.google.android.material:material:1.11.0")
    implementation("androidx.constraintlayout:constraintlayout:2.1.4")
    implementation("com.google.firebase:firebase-firestore:25.0.0")
    implementation("com.google.firebase:firebase-storage:21.0.0")
    implementation("com.google.firebase:firebase-messaging:24.0.0")
    testImplementation("junit:junit:4.13.2")
    androidTestImplementation("androidx.test.ext:junit:1.1.5")
    androidTestImplementation("androidx.test.espresso:espresso-core:3.5.1")
    implementation ("com.hbb20:ccp:2.5.0")
    implementation("com.google.firebase:firebase-auth")
    implementation(platform("com.google.firebase:firebase-bom:32.8.1"))
    implementation ("com.firebaseui:firebase-ui-firestore:8.0.2")
    implementation ("com.github.dhaval2404:imagepicker:2.1")
    implementation ("com.github.bumptech.glide:glide:4.16.0")
    implementation("com.squareup.okhttp3:okhttp:4.12.0")
}
```
## Installation and Setup

### Clone the repository:
```bash
git clone https://github.com/yourusername/chat-application.git
cd chat-application
```
### Open the project in Android Studio:

- Open Android Studio.
- Click on "Open an existing Android Studio project".
- Navigate to the cloned repository and select it.

### Configure Firebase:

- Go to the Firebase Console and create a new project.
- Register your app with Firebase by adding the Android package name.
- Download the google-services.json file and place it in the app directory of your project.
- Follow the Firebase setup instructions to configure your Firebase project.

### Build and run the project:

- Sync the project with Gradle files.
- Build and run the project on an emulator or a physical device.

## Usage

#### Login:

- Open the app and log in using your email and password.
- If you don't have an account, sign up using the provided sign-up option.

#### Chat:

- Search for other users by their username.
- Start a chat by selecting a user from the search results.
- Send and receive messages in real-time.

#### Profile:

- Upload a profile picture by selecting the profile picture option.
- Update your username in the profile settings.

## Contact
For any questions or suggestions, feel free to contact adityapratapsingh273@gmail.com.

