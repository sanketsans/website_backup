<!DOCTYPE html>
<html>
<head>
<style>

p.small {
  font-variant: normal;
  font-size: 20px;
}

a:link, a:visited {
  display: block;
  color: #000;
  text-decoration: none;
  display: inline-block;
  text-align: center;
  background: white;

  background: linear-gradient(to left, white 50%, black 50%) right;
  background-size: 200%;
  transition: .5s ease-out;
}

a:hover, a:active {
  background-position: left;
  color: white;
  -webkit-transform: scale(1);
  -ms-transform: scale(1);
  transform: scale(1);
}

h1.thicker{
  font: 55px Arial, sans-serif;
  font-weight: 800;
}

</style>
</head>
<body>

  <h1 class= "thicker {% if site.style == 'dark' %}class="text-white"{% endif %}">Contatto !</h1>
  <p class="f4 mb-4 {% if site.style == 'dark' %}text-white{% else %}text-gray{% endif %}">con·tàt·to</p>
  <p class="small">
    You can contact me at: <br><br>
      <a href="mailto:sanket@diyhacking.com">sanket@diyhacking.com</a><br><br>
      <a href="mailto:sanket.thakut@iit.it">sanket.thakur@iit.it</a>
  </p>

</body>
</html>
