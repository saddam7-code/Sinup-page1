<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            background-color: lightblue;
        }
        #king{
            text-align: center;
            margin-top: 100px;
            background-color: rgb(255, 215, 165);
        }
        .container{
            font-size: 30px;
            font-weight: bold;
            background-color: white;
            text-align: center;
            margin: 10px;
            padding: 10px;
            border-radius: 10px;


        }   
        .can{
             font-size: 20px;
            font-weight: bold;
            background-color: white;
            text-align: center;
            margin: 10px;
            padding: 20px;
            border-radius: 10px;

        } 
        .can :hover{
            border-radius: 10px;
            border-color: blue;
            background-color: rgb(231, 231, 231);

           
        } 
        .button
        {
            text-align: center;
            margin: 10px;
            padding: 20px;
            border-radius: 10px;
        

        }
        .button :hover{
            box-sizing: border-box;
            color: rgb(241, 222, 222);
            background-color: rgb(194, 71, 71);
           
        }
        #all{
            background-color: rgb(1, 0, 0);
            width: 500px ;
            margin: 200px auto;
            display: block;
            border-radius: 100px;
            

            
        }

    </style>
</head>
<body>
    <div id="all">

    
  
        <div class="container">
            Sinup Your account
         </div>
         <div class="can">
           Enter your First Name <input type="text">
         </div>
          <div class="can">
           Enter your Last Name <input type="text">
         </div>
          <div class="can">
        Enter your password  <input type="text">
        </div>
            <div class="can">
           Repeat your password <input type="text">
         </div>
         <div class="button">
         <input type="button"Sinup value="Sinup Now">
         </div>

         </div>
   
    
</body>
</html>
