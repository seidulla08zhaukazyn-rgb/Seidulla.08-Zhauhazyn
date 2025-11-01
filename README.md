<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JS Starter</title>
</head>
<body>
    <h1>JavaScript Starter Page</h1>
    <p id="text">Hello! Click the button to run JavaScript:</p>

    <button onclick="runCode()">Run JS</button>

    <script src="script.js"></script>
</body>
</html>
function runCode() {
    document.getElementById("text").innerText = "JavaScript is working!";
    console.log("JS code executed successfully!");
}
