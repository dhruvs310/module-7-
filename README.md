# module-7-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="
    viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        // Original user object
const user = { name: "John Smith", age: 35 };

// Convert user object to JSON
const userJSON = JSON.stringify(user);
console.log(userJSON);

// Parse JSON back into object
const parsedUser = JSON.parse(userJSON);
console.log(parsedUser);

    </script>
</body>
</html>
