# 5ASSIGNMENT


Q-1 <!DOCTYPE>
<html>
<head>

     <title>  use css </title>
     <link rel="stylesheet" href="style.css">
<style>

        h1 {

         color: yellow;
} 





</style>

</head>
<body>


     <div>

        <!-- inline css -->


        <p style="color: green; font-weight: bolder;"> This is inline css  </p>


       <!--internal css in head use  -->
   
       <h1> this is internal css </h1>

       <! external css >
       <h2> this is external css <h2>

 </div> 

</body>
</html

second file q1 = style.css

code= h2 {


  color:red;
  backgrond-color:black;
}

Q-2 

<!DOCTYPE>
<html> 
<head>

       <title>   BEM styled paragraphs </title>
<style>



.content__paragraph--highlight{

    color:blue;
    font-weight: bolder;
    background-color:black;
    
}
   
.content__paragraph--note{

    color:red;
    font-weight: bolder;
    background-color:black;
    
}
   
.content__paragraph--warning{

    color:yellow;
    font-weight: bolder;
    background-color:black;
    
}
   
.content__paragraph--success{

    color:green;
    font-weight: bolder;
    background-color:black;
    
}
</style>
</head>
<body>


<p class="content__paragraph content__paragraph--highlight"> this is a highlighted  paragraph</p>
<p class="content__paragraph content__paragraph--note"> This paragraph serves as a neutral note.</p>
<p class="content__paragraph content__paragraph--warning">Warning! This paragraph alerts the user to a potential issue.</p>
<p class="content__paragraph content__paragraph--success">Success! This paragraph communicates a positive message.</p>




</body>
</html>

Q3

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Simple Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      padding: 20px;
    }

    h2 {
      text-align: center;
      color: #333;
    }

    form {
      background-color: #fff;
      padding: 20px;
      max-width: 400px;
      margin: auto;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    label {
      display: block;
      margin-top: 10px;
      color: #444;
    }

    input, textarea {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    input[type="submit"] {
      background-color: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
      margin-top: 15px;
    }

    input[type="submit"]:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>


  <h2>Contact Form</h2>

  <form>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="4" required></textarea>

    <input type="submit" value="Send">
  </form>


  

</body>
</html>





