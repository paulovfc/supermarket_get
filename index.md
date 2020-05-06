---
layout: default
title: Main layout
---
<div class="grid-container">
  <div class="header_top1">
	<img src="/assets/images/large_1.png" alt="Main">
  </div>
  <div class="content_middle">
    <div class="mailing_list">mailing_list</div>
    <div class="how_it_works">how_it_works</div>
  </div>
  <div class="footer_bottom">
    <div class="pricing_plan">pricing_plan</div>
    <div class="social_media">social_media</div>
    <div class="footer">footer</div>
  </div>
</div>

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
  firebase.initializeApp(firebaseConfig);
  firebase.analytics();
</script>
  

