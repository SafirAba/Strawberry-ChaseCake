<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Safir Prettner</title>
    <style>
      /*img {
        width: 500px;
        border-radius: 5px;
        float: left;

        margin-top: 200px;
      }*/

      /* Container holding the image and the text */
      #object1 {
        width: 100%;
        height: 100%;
        background-color: green;
        object-fit: fill;
        object-position: center;
        display: block;
        margin-left: auto;
        margin-right: auto;
        position: absolute;
        /* String value */
      }

      /* Centered text */
      .centertext {
        z-index: 100;
        position: absolute;
        color: #abcdab;
        font-size: 50px;
        font-weight: bold;
        font-family: Arial, Helvetica, sans-serif;
        left: 40%;
        top: 50%;
        text-shadow: 2px 2px 10px #010101;
      }
      .container {
        height: 100%;
        width: auto;
        position: relative;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <img id="object1" src="background.jpg" alt="background image" />
      <div class="centertext">Safir Prettner</div>
    </div>
  </body>
</html>
