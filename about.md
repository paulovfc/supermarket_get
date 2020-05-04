---
layout: default_about
---

# About page

This page tells you a little bit about me v24.

<p>Getting started with Firebase</p>
<h1 id="bigOne"></h1>

<form method="post">
<input type="text" name="name" id="name" />
<input type="submit" name="send" id="send" value="send" />
</form>

<!-- The core Firebase JS SDK is always required and must be listed first -->
<script src="https://www.gstatic.com/firebasejs/7.14.2/firebase-app.js"></script>

<!-- TODO: Add SDKs for Firebase products that you want to use
     https://firebase.google.com/docs/web/setup#available-libraries -->
<script src="https://www.gstatic.com/firebasejs/7.14.2/firebase-analytics.js"></script>
<script src="https://www.gstatic.com/firebasejs/7.14.2/firebase-firestore.js"></script>

<script>
  // Your web app's Firebase configuration
  var firebaseConfig = {
    apiKey: "AIzaSyDLKgD71AO7O9s7xGLQLYjJYlqJWiRf4yU",
    authDomain: "sparvana-firebase.firebaseapp.com",
    databaseURL: "https://sparvana-firebase.firebaseio.com",
    projectId: "sparvana-firebase",
    storageBucket: "sparvana-firebase.appspot.com",
    messagingSenderId: "1049047251963",
    appId: "1:1049047251963:web:982fcbb0c34bb3b6dde95e",
    measurementId: "G-FQDXJT12JN"
  };
  // Initialize Firebase
  var app = firebase.initializeApp(firebaseConfig);
  firebase.analytics();

var db = firebase.firestore(app);

var d = Date()

db.collection("email_subs").add({
    email: document.getElementById("name").value,
    date: document.getElementById("name").value
})


</script>



