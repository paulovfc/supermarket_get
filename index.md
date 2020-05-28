---
layout: default
title: Einkaufen Nirvana!
---
<!--<img src="/assets/images/large_1.png" alt="" style="border:1px solid red; max-width:100%;height:auto;"> 
https://www.w3schools.com/code/tryit.asp?filename=GEVNXTYDI0Q9 

<img src="/assets/images/sparvana_logo_36.png" alt="">

			<form method="post" name="MyForm">
			<input type="text" name="name" id="name" />
			<input type="submit" name="send" id="send" value="send" />
			</form>
			
	<div class="sparmaus" ></div> 
	<div class="sparhase" ></div>
	<div class="sparfuchs" ></div>
	<div class="sparvana" ></div>

  <input type="submit" name="send" id="myBtn" value="Wähle deine lieblings Supermärkte!" />


-->
<style>
@font-face {
    font-family: 'restoraextralight-1';
    src: url('/assets/fonts/restoraextralight-1-webfont.woff2') format('woff2'),
         url('/assets/fonts/restoraextralight-1-webfont.woff') format('woff');
    font-weight: normal;
    font-style: normal;
</style>

<div class="grid-container">

	<div class="header_top"> 
		<div class="title">Sparvana</div>
		
      <div class="first_headline">
        Mühelos einkaufsliste erstellen. 
		  </div>
      <div class="first_headline_text">
 Niemals Supermärkte prospekten um die beste Angeboten zu finden aussuchen.
	  	</div>
      
      <div class="second_headline">
			 Klug und Sparsam. 
		  </div>
		  <div class="second_headline_text">
Wir schatzen jeder Angebote gegen historiches durchscnnitt Preis und geben dir die Entscheidung. Sparen bis zu 30% jedes Monat! 
		  </div>
          <div class="third_headline">
 Personalisierte.
		  </div>
		  <div class="third_headline_text">
Sparvana sucht und findet die beste Angebote nach deine Auswahl, automatisch. Echte Angebote von deine lieblings Produkten erhalts du per email.
		  </div>      
    <div class="fourth_headline">
Unabhängig, gutes Karma inbegriffen. 
		  </div>
		  <div class="fourth_headline_text">
Sparvana is voll von jeder Supermarkte kette unhabhanging und von uns kriegs du sicher keine Werbungen und deine Daten teilen wir niemand.  
		  </div> 

 
	</div>

	<div class="content_middle" >

      <div class="sparmaus" >
        <div class="header">
          <h1>1</h1>
        </div>
        <div class="container">
          <p>Sparmaus</p>
        </div>
      </div>
      <div class="sparhase" >
          <div class="header">
          <h1>2</h1>
        </div>
        <div class="container">
          <p>Sparhase</p>
      </div>
      </div>  
      <div class="sparfuchs" >
        <div class="header">
          <h1>3</h1>
        </div>
        <div class="container">
          <p>Sparfuchs</p>
      </div>
      </div>
      <div class="sparvana" >
        <div class="header">
          <h1>4</h1>
        </div>
        <div class="container">
          <p>Sparvana</p>
      </div>      
      </div>
<div class="mailing_list">
  <form method="post" name="MyForm">
    <p>
      Vorname:
      <input type="text" name="name" id="name" />
       Nachname
      <input type="text" name="name" id="name" />
    </p>

    <p>
      Email:
      <input type="text" name="email" id="email" />
      Postcode:
      <input type="text" name="postcode" id="postcode"/>
    </p>

   <button id="myBtn">Wähle deine lieblings Supermärkte!</button>     

<!-- The Modal -->
<div id="myModal" class="modal">
  <!-- Modal content -->
  <div class="modal-content">
    <span class="close">&times;</span>
    <p>Some text in the Modal..</p>
  </div>
</div>
        
  </form>
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
  

