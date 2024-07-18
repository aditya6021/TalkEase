# Chat Application

This Android chat application leverages Google Firebase for authentication, database, and storage functionalities. Users can log in, search, and chat with others on the server. Additionally, users can upload a profile picture and update their name. This README file provides an overview of the app's features, setup instructions, and dependencies.

## Features

- **User Authentication**: Login page with Firebase Authentication.
- **Chat Functionality**: Search and chat with any person on the server.
- **User Profile**: Upload profile pictures and update user names.
- **Data Storage**: Store user details and chatrooms using Firebase Firestore.
- **Messaging**: Firebase Cloud Messaging integration for real-time chat updates.

## Dependencies

The project uses the following dependencies:

```gradle
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
