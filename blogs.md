<!DOCTYPE html>
<html>
<head>
<style>

p.small {
  font-variant: small-caps;
  font-size: 20px;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  width: 500px;
  margin-top: 50px;

}

li a {
  display: block;
  margin-top: 10px;
  color: #000;
  padding: 8px 16px;
  text-decoration: none;
  display: inline-block;
  padding: 1em 2em;
  text-align: center;
  background: white;

  background: linear-gradient(to left, white 50%, black 50%) right;
  background-size: 200%;
  transition: .5s ease-out;
}

li a:hover {
  background-position: left;
  color: white;
  -webkit-transform: scale(1);
  -ms-transform: scale(1);
  transform: scale(1);
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

li a.active {
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

<h1 class= "thicker {% if site.style == 'dark' %}class="text-white"{% endif %}">Blog !</h1>
<p class="f4 mb-4 {% if site.style == 'dark' %}text-white{% else %}text-gray{% endif %}">/blɒɡ/</p>

<p class="small">
  Work in progress !
</p>

</body>
</html>
