# hello-world
Just another repository

Hello everyone, 
I'm new here and would love to understand GitHub and all it's benifits. 
I'm going to build a small website here only as an example to show my progress as I learn how to code.

Cheers


<!<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="description" content="Website">
<style>

  
#div {
  animation-duration: .5s;
  animation-name: slidein;
  animation-fill-mode: forwards;
  animation-timing-function: ease-in;
  flex-direction: column;
} 
@keyframes slidein {
  from {
    margin-right: 100%;
    width: 20%;
  }
  to {
    margin-right: 40%;
    width: 20%;
    
  }
}





h1 {
      color: blue;
      width: 100%;
      margin-left: auto;
      margin-right: auto;
      font-size: 40px;
      font-family: Arial;
      padding: 10px;
flex-direction: column;
align-items: stretch;
    }
h2 {
  font-size: 30px;
  margin-top: 10px;
flex-direction: column;
}

p {
  font-size: 30px;
}

  .black-border {
    border-color: black;
    border-width: 10px;
    border-radius: 50%;
    border-style: solid;

  }
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 20%;


}

.center2 {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 70%;
}

.center3 {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 30%;
}

.text-center {
  width: 70%;
}
li {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 20%;
}

</style>
</head>
<body>
<h1 id="rect">Website Name</h1>
<h2>Welcome to the homepage set up by me. If you'd like to leave feedback, you can email me <a href="mailto:email@address.com">here</a>.</h2>
<div>

<main>

  <img id="div" class="black-border center" src="#"
alt="A picture.">


<h3 class="center2">Things I Like:</h3>
<ul>
  <li class="center2"> Head scratches</li>
  <li class="center2"> Back scratches</li>
  <li class="center2"> Massages</li>
  </ul>
<h3 class="center2">Things I Don't Like:</h3>
<ul>
  <li class="center2"> Mornings</li>
  <li class="center2"> Meatloaf</li>
  <li class="center2"> Carrots</li>
  <li class="center2"> Raw Apple</li>

</ul>


<form>


  <label for="lovely" class="center2">
  <input id="lovely" type="checkbox" name="lovely">lovely</label>
  <label for="mouse" class="center2">
  <input id="mouse" type="checkbox" name="mouse">a little mouse</label>
  <label for="hair" class="center2">
  <input id="hair" type="checkbox" name="hair">hair</label>
  <label for="eyes" class="center2">
  <input id="eyes" type="checkbox" name="eyes"> Nice eyes</label>
 <br>

</form>


</main>

  </body>

</html>
