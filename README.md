<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Blog</title>
  <style>
     @media  screen and (min-width:100%) {
      body {
        margin: 1em 2em;
      } 
      
    }
    body {
      font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }

    .container {
      background-color: #5a9291;
      width: 100%;
    }

    .left img {
      width: 90px;
      margin: auto;
      display: block;

    }

    h1 {
      text-align: center;

    }

    .navbar {
      display: block;
      text-align: center;
      margin: 6px auto;
      /* padding: 4px; */
      width: 560px;
      border: 2px solid #f5e9e9;
      background-color: white;
      border-radius: 4px;



    }

    .navbar li {
      display: inline-block;
      font-size: 17px;
      padding: 15px;
    }

    .navbar li a {
      color: #5a9291;
      text-align: left;
      position: relative;
      left: 150px;

    }

    .img {
      display: block;
      width: 56%;
      margin: 12px auto;
      /* border: 2px solid green;  */

    }

    .input {
      display: block;
      text-align: center;
      margin: 6px auto;
      padding: 14px;
      width: 600px;
      border: 2px solid #f5e9e9;
      background-color: white;
      border-radius: 4px;
    }

    #btn {
      display: block;
      text-align: center;
      margin: 6px auto;
      padding: 6px;
      width: 130px;
      border: 2px solid #d63c1d;
      border-radius: 4px;
      position: relative;
      left: 370px;
      bottom: 51px;
      font-size: 20px;
    }

    /*     
    .midimage1 img {
      display: block;
      margin: 0 auto;
    } */



    .midimage2 {
      display: flex;

    }






    .inline-block {
      display: inline-block;

    }

    .inline-block img {
      width: 350px;
      height: 250px;
      margin: 12px;
      padding: 4px;
      border-radius: 12px;
    }

    .inline-block a {

      margin: auto 25px;
      font-size: 19px;
    }

    .bottom-container {

      /* background-color: #66bfbf; */
      padding: 50px 0 20px;
      text-align: center;
      margin: 50px auto auto;
      font-size: 19px;

    }

    .bottom-container footer {

      color: #11999E;
      font-family: sans-serif;
      margin: 10px 20px;


    }

    .bottom-container p {
      display: inline-block;
      margin: auto;
      position: relative;
      left: 140px;

    }
  </style>
</head>

<body style="margin: auto;">

  <!-- First Container -->
  <div class="container">
    <!-- left box for logo -->
    <div class="left">
      <img src="image/wordpress-png-icon (1).png" class="imag">
      <h1>BLOG</h1>

    </div>

    <ul class="navbar">
      <li><a href="index.html">Home</a></li>
      <li><a href="#">Blog</a></li>
      <li><a href="sample.html">Sample Page</a></li>
    </ul>

    <img src="image/image-1-2.png" class="img">
<form action="search.html">
    <div><input type="search" class="input" name="s" value="" placeholder="" required="">
      <button type="submit" class="bt" id="btn" style="background-color: #d63c1d">Search</button>
    </div></form>
  </div>




  <!-- Middle Container -->
  <div class="container2">



    <div class="inline-block">
      <img src="image/61ee66e1-f1f6-33f9-9c22-32b2ab8bea3e.jpg" alt="">
      <p><a href="img1.html">vitae qui veritatis veritatis officia</a></p>
    </div>

    <div class="inline-block">
      <img src="image/a366b86f-4a19-3c5f-82d6-01b283c57b70.jpg" alt="">
      <p><a href="img2.html">corporis id quae ut ducimus dolorum molestias</a></p>
    </div>

    <div class="inline-block">
      <img src="image/3e2ee2e7-a0e3-3007-a10c-e704d167f907.jpg" alt="">
      <p><a href="img3.html">deserunt est ut doloremque accusamus voluptas</a></p>
    </div>

    <div class="inline-block">
      <img src="image/0a65b44d-b9c0-3eba-92bf-645ca41b61bd.jpg" alt="">
      <p><a href="img4.html">molestiae ex accusamus quia in laborum</a></p>
    </div>

    <div class="inline-block">
      <img src="image/1ee18f7e-d314-34a4-b675-fb748ae66c9b.jpg" alt="">
      <p><a href="img5.html">eius maxime ut repellendus</a></p>
    </div>

    <div class="inline-block">
      <img src="image/c7aee6d5-e0fc-345c-9473-0584c4776744.jpg" alt="">
      <p><a href="img6.html">voluptas ex accusantium sit nulla qui nesciunt</a></p>
    </div>
  </div>

  <div class="bottom-container">
    <a class="footer" href="index.html" style="color: rgb(204, 81, 9);">My Blog</a>
    <p>Powered By<a class="footer" href="https://wordpress.org/">Wordpress</a></p>

  </div>
</body>

</html>
