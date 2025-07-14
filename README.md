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






