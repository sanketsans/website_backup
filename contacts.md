---
layout: default
---

<style>
p.small {
  font-variant: normal;
  font-size: 20px;
}
h1.thicker{
  font: 85px Arial, sans-serif;
  font-weight: 800;
}

a {
  color: #000;
  text-decoration: none;
  display: inline-block;
  text-align: center;

  background: linear-gradient(to left, white 50%, black 50%) right;
  background-size: 100%;
  transition: .5s ease-out;
}

a:hover {
  background-position: left;
  color: white;
  -webkit-transform: scale(1);
  -ms-transform: scale(1);
  transform: scale(1);
}
</style>

<h1 class= "thicker {% if site.style == 'dark' %}class="text-white"{% endif %}">Contatto !</h1>
<p class="f4 mb-4 {% if site.style == 'dark' %}text-white{% else %}text-gray{% endif %}">con·tàt·to</p>
<p class="small">
  You can reach out to me via : <br><br>
  
    <!-- <a href="mailto:sanket@diyhacking.com">sanket@diyhacking.com</a><br><br> -->

</p>
<p class="small">
  Or you can directly mail me :  <a href="mailto:sanket.thakut@iit.it">sanket.thakur@iit.it</a>
</p>
