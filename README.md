# CssHover
property of another object when you hover over it

<html>
<head>
    <style>
        .box{
            width: 200px;
            height: 100px;
            background-color: chartreuse;
            float: left;
            margin: 20px;
        }
      
      #box1:hover + #box2{
            transition: 1s;
            background-color: red;
        }
    </style>
</head>
<body>
    <div class="box" id="box1"></div>
    <div class="box" id="box2"></div>
    
</body>
</html>
