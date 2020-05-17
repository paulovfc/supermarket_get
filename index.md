---
layout: default
title: Main layout
---
<meta name="viewport" content="width=device-width, initial-scale=1.0"> 
<div class="grid-container">
	<div class="header_top"
		style="background-image: url('/assets/images/large_1.png');
		background-repeat: no-repeat;
		text-align:center;
		height:550px;
		max-width:100%">
		
		<!--<img src="/assets/images/large_1.png" alt="" style="border:1px solid red; max-width:100%;height:auto;"> -->
		<div class="mailing_list" style="padding-top: 50px;">
			<form method="post" name="MyForm">
			<input type="text" name="name" id="name" />
			<input type="submit" name="send" id="send" value="send" />
			</form>
		</div>
	
	</div>

	<div class="content_middle">
		<div class="how_it_works">
			<div class="sparmaus" ></div> 
			<div class="sparhase" ></div>
			<div class="sparfuchs" ></div>
			<div class="sparvana" ></div>
		</div>
	</div>

	<div class="footer_bottom">
		<div class="pricing_plan"></div>
		<div class="social_media"></div>
		<div class="footer"></div>
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
  

