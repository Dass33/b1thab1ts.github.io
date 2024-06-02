<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>B1tHaB1ts</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="left-section">
          <div class="logo">B1tHaB1ts</div>
          <nav>
              <a href="#">Root</a>
              <a href="#">Upgrades</a>
              <a href="#">Forum</a>
          </nav>
        </div>
        <div class="status-icons">
            <div class="status-item">
                <img src="Images/CPU Icon.svg" alt="CPU">
                <span>3,2GHz</span>
            </div>
            <div class="status-item">
                <img src="Images/RAM icon.svg" alt="RAM">
                <span>3/8GB</span>
            </div>
            <div class="status-item">
                <img src="Images/HDD Icon.svg" alt="HDD">
                <span>2TB</span>
            </div>
        </div>
    </header>
    <div class="row">
        <div class="column">
            <h2>Daili Scrum</h2>
            <ul id="dailiUL">
                <li>Hit the gym</li>
                
                <li>Meet George</li>
                <li>Buy eggs</li>
                <li>Read a book</li>
                <li>Organize office</li>
            </ul>
            <div class="bar-input">
                <span onclick="newElement()">$ add &nbsp</span>
                <input type="text" id="input-daili" > 
            </div>
        </div>
        <div class="column">
            <h2>Sprint Goals</h2>
            <div class="bar-input">
                <span>$ add &nbsp</span>
                <input type="text" id="input-todos">
            </div>
        </div>
        <div class="column">
            <h2>Forum</h2>
            <div class="bar-input">
                <span>$ echo &nbsp</span>
                <input type="text" id="input-chat">
            </div>
        </div>
    </div>
<script src="script.js"></script>
</body>
</html>
