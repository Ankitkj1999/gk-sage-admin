# app_admin

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
# demo_admin
# demo_admin


// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
apiKey: "AIzaSyDb3CnoTeXJzFzA6gEs4ecQySu26y1JCSg",
authDomain: "gk-sage-admin-cb224.firebaseapp.com",
projectId: "gk-sage-admin-cb224",
storageBucket: "gk-sage-admin-cb224.firebasestorage.app",
messagingSenderId: "619698291708",
appId: "1:619698291708:web:677b3b712fb96c8b01a879",
measurementId: "G-S5Z68MG6YQ"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);


flutter build web --web-renderer html --release

flutter build web --release --web-renderer html