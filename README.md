<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width,
initial-scale=1.0" />
<title>CSS</title>
<style>
    .container {
    margin: 0;
    padding: 0;
    height: 100vh;
    display: grid;
    grid-template-columns: repeat(12, 1fr);
    grid-template-rows: repeat(12, 1fr);
    grid-gap: 10px;
    }
    .container div {
    background-color: pink;
    font-size: 1.5rem;
    }
    .header {
    grid-column: 1 / span 12;
    }
    .sidebar {
    grid-column: 1 / span 3;
    grid-row: 2 / span 10;
    }
    .navigation {
    grid-column: 4 / span 6;
    }
    .ads {
    grid-column: 10 / span 3;
    grid-row: 2 / span 10;
    }
    .main {
    grid-column: 4 / span 6;
    grid-row: 3 / span 9;
    }
    .footer {
    grid-column: 1 / span 12;
    }
</style>
<link rel="stylesheet" href="style7.css" />
</head>
<body>
<div class="container">
<div class="header">header</div>
<div class="navigation">navigation</div>
<div class="sidebar">sidebar</div>
<div class="main">main</div>
<div class="ads">ads </div>
<div class="footer">footer </div>
</div>
</body>
</html>
