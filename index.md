---
layout: default
title: index
---

index file
[README]({{site.baseurl}}/README.html)    
[auth handler](https://eerste-project-d1c12.firebaseapp.com/__/auth/handler)

<script src="https://www.gstatic.com/firebasejs/4.6.2/firebase.js"></script>
<script>
  // Initialize Firebase
  var config = {
    apiKey: "AIzaSyDr5owojQtXVFY72TvF-znr9CuiGc1XqjI",
    authDomain: "eerste-project-d1c12.firebaseapp.com",
    databaseURL: "https://eerste-project-d1c12.firebaseio.com",
    projectId: "eerste-project-d1c12",
    storageBucket: "eerste-project-d1c12.appspot.com",
    messagingSenderId: "440664841529"
  };
  firebase.initializeApp(config);
</script>
<script src="https://www.gstatic.com/firebasejs/4.6.2/firebase-app.js"></script>
<script src="https://www.gstatic.com/firebasejs/4.6.2/firebase-auth.js"></script>
<script src="https://www.gstatic.com/firebasejs/4.6.2/firebase-database.js"></script>
<script src="https://www.gstatic.com/firebasejs/4.6.2/firebase-messaging.js"></script>

<!-- Leave out Storage -->
<!-- <script src="https://www.gstatic.com/firebasejs/4.6.2/firebase-storage.js"></script> -->

<script>
  var config = {
    // ...
  };
  firebase.initializeApp(config);
</script>
