<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Calculator</title>
</head>
<body>
    <div id="main">
        <form name="form">
            <input class="textview" name="textview">
        </form>
        <div class="grid-container">
            <input class="grid-item" type="button" value="C" onclick="clean()">
            <input class="grid-item" type="button" value="<" onclick="back()">
            <input class="grid-item" type="button" value="/" onclick="insert('/')">
            <input class="grid-item" type="button" value="X" onclick="insert('*')">
            <input class="grid-item" type="button" value="7" onclick="insert(7)">
            <input class="grid-item" type="button" value="8" onclick="insert(8)">
            <input class="grid-item" type="button" value="9" onclick="insert(9)">
            <input class="grid-item" type="button" value="-" onclick="insert('-')">
            <input class="grid-item" type="button" value="4" onclick="insert(4)">
            <input class="grid-item" type="button" value="5" onclick="insert(5)">
            <input class="grid-item" type="button" value="6" onclick="insert(6)">
            <input class="grid-item" type="button" value="+" onclick="insert('+')">
            <input class="grid-item" type="button" value="1" onclick="insert(1)">
            <input class="grid-item" type="button" value="2" onclick="insert(2)">
            <input class="grid-item" type="button" value="3" onclick="insert(3)">
            <input class="grid-item" id="equals" type="button" value="=" onclick="equal()">
            <input class="grid-item" id="zero" type="button" value="0" onclick="insert(0)">
            <input class="grid-item" type="button" value="." onclick="insert('.')">
          </div>
    
    </div>

    <script src="index.js"></script>
</body>
</html>
