# Avtaar_Assignment
Assignment_1

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        var name = prompt("Please Enter Your Name");
        var a = Math.random() * (100000 - 1) + 1
        var t1 = new Date();
        var t2 = new Date();
        var date = t1.getFullYear()+'-'+(t1.getMonth()+1)+'-'+t1.getDate();
        var time = t2.getHours()+':'+t2.getMinutes()+':'+t2.getSeconds();
        if(name != null){
            console.log(name);
            console.log(a);
            console.log(date);
            console.log(time);
        }
    </script>
</body>
</html>
