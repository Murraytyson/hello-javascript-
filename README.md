<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript</title>
</head>
<body>
    <h4>using JavaScript inline html</h4>
    <p id="demo"></p>
    <script>
        let text1 = "hello ";
        text1 += "world";
        document.getElementById("demo").innerHTML =text1;
    </script>
</body>
</html>
