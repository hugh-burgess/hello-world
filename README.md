# hello-world
Just another repository

This is the the current project I'm working on.


<!<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="description" content="Website">


<style>

  body {
    background-color: #FFFFDD;
    grid-template-areas: ". header ." ". main ." ". footer .";


  }


  form {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 70%;

  }


  #div {
    animation-duration: 1s;
    animation-name: slidein;
    animation-fill-mode: forwards;
    animation-timing-function: ease-in;
    flex-direction: row;
  }

  @keyframes slidein {
    from {
    margin-right: 100%;
    width: 0%;
    }
    to {
    margin-right: 35%;
    width: 40%;

    }
  }





  h1 {
    color: blue;
    width: 50%;
    display: block;
    margin-left: auto;
    margin-right: auto;
    font-size: 40px;
    font-family: Arial;
    padding: 10px;
  }

  h3 {
    position: relative;
    margin-left: auto;
    margin-right: auto;
    width: 30%;  

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

  #box-container {
    display: flex;
    height: 100px;
    flex-wrap: wrap;
    justify-content: center;
    flex-direction:row;
    grid-template-rows: 60px 60px 60px;
    grid-template-columns: 60px;
    margin-left: auto;
    margin-right: auto;
    width: 70%;

  }

  #box-1 {
    background-color: dodgerblue;
    height: 30px;
    width: 600px;
  }

  #box-2 {
  background-color: orangered;

    height: 30px;
    width: 600px;
  }


</style>


</head>

<body>

<header>  
  <h1 id="rect">Website Name</h1>
</header>

<main>

   <h2>Welcome to the homepage set up by me. If you'd like to leave feedback, you can email me <a href="mailto:email@address.com">here</a>.</h2>
  <div>

  <img id="div" class="black-border center" src="https://cdn.pixabay.com/photo/2020/09/06/22/11/neptune-5550216__340.jpg"
  alt="A picture of Neptune.">


  <h3>Things I Like:</h3>
  <ul>
    <li> Head scratches</li>
    <li> Back scratches</li>
    <li> Massages</li>
  </ul>
  <h3>Things I Don't Like:</h3>
  <ol>
    <li> Mornings</li>
    <li> Meatloaf</li>
    <li> Carrots</li>
    <li> Raw Apple</li>

  </ol>

  <form>

  <fieldset>
      <legend>Here's a few more things:</legend>

    <label for="lovely" class="center2">
    <input id="lovely" type="checkbox" name="lovely">lovely</label>
    <br>
    <label for="mouse" class="center2">
    <input id="mouse" type="checkbox" name="mouse">a little mouse</label>
    <br>
    <label for="hair" class="center2">
    <input id="hair" type="checkbox" name="hair">hair</label>
    <br>
    <label for="eyes" class="center2">
    <input id="eyes" type="checkbox" name="eyes"> Nice eyes</label>
    <br>

  </fieldset>

  </form>  

</main>

<footer>
  <div class="container" id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
  </div>

</footer>

</body>

</html>
