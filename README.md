<!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Logo Design</title> 
  <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #2a9d8f;
        }
        .cyber-circle {
            width: 300px;
            height: 300px;
            border-radius: 50%;
            background-color: #2a9d8f;
            position: relative;
        }
        .robot-human {
            width: 100px;
            height: 150px;
            background-color: #ade8f4;
            position: absolute;
            bottom: 50%;
            left: 50%;
            transform: translate(-50%, 50%);
            border: 5px solid #0096c7;
        }
        .thinking-mimic {
            position: absolute;
            top: -30px;
            left: 50%;
            transform: translateX(-50%);
            font-size: 24px;
            color: #fff;
        }
    </style> 
 </head> 
 <body> 
  <div class="cyber-circle"> 
   <div class="robot-human"></div> 
   <div class="thinking-mimic">
     ? 
   </div> 
  </div> 
 </body>
</html>
