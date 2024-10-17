<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Open New Tab Example</title>
</head>
<body>
    <h1>Welcome!</h1>
    <button id="openTabButton">Open My Portfolio</button>

    <script>
        document.getElementById('openTabButton').addEventListener('click', function() {
            // Open a new tab with your URL
            window.open('https://bncmnky.github.io', '_blank');  // Opens your link in a new tab
        });
    </script>
</body>
</html>
