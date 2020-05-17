---
layout: default
title: Main layout
---
<!--<img src="/assets/images/large_1.png" alt="" style="border:1px solid red; max-width:100%;height:auto;"> 
https://www.w3schools.com/code/tryit.asp?filename=GEVNXTYDI0Q9 

<img src="/assets/images/sparvana_logo_36.png" alt="">
-->


<div class="grid-container" style="width:auto;">

	<div class="header_top" style="background-color: rgba(177, 177,177, 0.7);background-image: url('/assets/images/large_1.png');background-repeat: no-repeat;text-align:center;height:550px;max-width:100%;">
		<div class="title" style="background-color: rgba(177, 177,177, 0.9);font-weight:bold;color:white;width:auto;height:auto; text-align:center;font-family:Helvetica, sans-serif;font-size:16px;">Sparvana</div>		
		
		<div class="title" style="padding-top:150px;font-weight: bold;color:white;width:auto;height:auto; text-align:center;font-family: Helvetica, sans-serif;font-size:6vw;">
	Entlasten Sie den Einkauf von Lebensmitteln2! 
		</div>
		
		
		
		<div class="mailing_list" style="padding-top: 50px;">
			<form method="post" name="MyForm">
			<input type="text" name="name" id="name" />
			<input type="submit" name="send" id="send" value="send" />
			</form>
		</div>
	
	</div>

	<div class="content_middle" >
		<div class="how_it_works">
			<div class="sparmaus" ></div> 
			<div class="sparhase" ></div>
			<div class="sparfuchs" ></div>
			<div class="sparvana" ></div>
		</div>
	</div>

	<div class="footer_bottom" >
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
  

