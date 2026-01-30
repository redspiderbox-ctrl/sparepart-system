// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyA3kmXVazglf3uscpb9v3Fxs0lIkKGiyTM",
  authDomain: "redspiderbox-72eaf.firebaseapp.com",
  projectId: "redspiderbox-72eaf",
  storageBucket: "redspiderbox-72eaf.firebasestorage.app",
  messagingSenderId: "761006510932",
  appId: "1:761006510932:web:f6ff0861eae77ea54c6ec1",
  measurementId: "G-JR3NH087DZ"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
