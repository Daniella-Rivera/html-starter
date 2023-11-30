# microsite-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>UK Travel Website</title>
</head>
<body>

<div class="tabs">
    <button class="tablink" onclick="openTab('home')">Home</button>
    <button class="tablink" onclick="openTab('about')">About</button>
    <button class="tablink" onclick="openTab('cities')">Cities</button>
    <button class="tablink" onclick="openTab('food')">Food</button>
    <button class="tablink" onclick="openTab('experiences')">Experiences</button>
</div>

<div id="home" class="tabcontent">
    <h2>Home</h2>
    <p>Welcome to our UK Travel Website! Explore the beauty of the United Kingdom.</p>
</div>

<div id="about" class="tabcontent">
    <h2>About</h2>
    <p>Learn about the rich history and culture of the United Kingdom.</p>
</div>

<div id="cities" class="tabcontent">
    <h2>Cities</h2>
    <p>Discover the charm of cities like London, Edinburgh, and Manchester.</p>
</div>

<div id="food" class="tabcontent">
    <h2>Food</h2>
    <p>Indulge in the delicious and diverse cuisine of the United Kingdom.</p>
</div>

<div id="experiences" class="tabcontent">
    <h2>Experiences</h2>
    <p>Immerse yourself in unique experiences across the country.</p>
</div>

<script src="script.js"></script>
</body>
</html>

<html>
body {
    font-family: Arial, sans-serif;
}

.tabs {
    overflow: hidden;
    background-color: #f1f1f1;
}

.tablink {
    float: left;
    display: block;
    color: #000;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 18px;
    border: none;
    cursor: pointer;
}

.tablink:hover {
    background-color: #ddd;
}

.tabcontent {
    display: none;
    padding: 20px;
}

h2 {
    color: #333;
}
</html>
