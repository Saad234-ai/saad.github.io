<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css" >
</head>
<body>
    div{
        height: 200px;
        width: 200px;
     border-radius: 50%;
     border: 20px solid black;
     border-top: 20px soliod red;
     position:absolute;
     top:100px;
     left:200px;
     animation-name: coloranime;
     animation-duration: 1s;
     animation-timing-function: ease-in-out;
     animation-iteration-count: infinite;
     animation-direction:normal ;
     
    }
    @keyframes coloranimne{
        from{ transform: rotate(0deg)}
        from{ transform: rotate(360deg)}
    }
</body>
</html>
