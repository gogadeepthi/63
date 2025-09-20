<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>declaring function</title>
    <style>
        .out{color: blueviolet; font-weight: bold;}
    </style>
</head>
<body>
    <h2> Function with user-name </h2>
    <p id="demo1" class="out"> </p>
    <script>
        function hi(){
            return "Hello Students, How are you!!!";
        }
        document.getElementById("demo1").innerText=hi();
    </script>
</body>
</html>
