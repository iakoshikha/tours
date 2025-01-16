<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="" alt="Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#">Tours</a></li>
                <li><a href="#" class="lang-switch">Language</a></li>
                <li><button class="sign-up">Sign Up</button></li>
                <li><button class="log-in">Log In</button></li>
            </ul>
        </nav>
    </header>
    <main>
        <div class="filter-container">
            <div class="filter">
                <label><input type="checkbox"> მცხეთა-მთიანეთი</label>
                <label><input type="checkbox"> რაჭა-ლეჩხუმი</label>
                <label><input type="checkbox"> სვანეთი</label>
                <label><input type="checkbox"> სამეგრელო</label>
                <label><input type="checkbox"> ზემო აჭარა</label>
            </div>
        </div>
        <div class="content">
            <div class="item">
                <img src="photos/სვანეთი.jpg" alt="Image 1">
                <p>სვანეთი</p>
            </div>
            <div class="item">
                <img src="./photos/აჭარა.jpg" alt="Image 2">
                <p>ზემო აჭარა</p>
            </div>
            <div class="item">
                <img src="photos/სამეგრელო.png" alt="Image 3">
                <p>სამეგრელო</p>
            </div>
            <div class="item">
                <img src="./photos/მცხეთა.png" alt="Image 4">
                <p>მცხეთა-მთიანეთი</p>
            </div>
            <div class="item">
                <img src="./photos/რაჭა.png" alt="Image 5">
                <p>რაჭა-ლეჩხუმი</p>
            </div>
        </div>
    </main>
    <footer>
        <p>Phone: +995 593 363 419</p>
        <p>Address: ქ.თბილისი</p>
        <p>Facebook: <a href="#">where next?</a></p>
    </footer>
    <script src="script.js"></script>
</body>
</html>








body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #86cc88;
    color: white;
    padding: 10px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 10px;
}

nav ul li {
    display: inline;
}

.sign-up, .log-in {
    background-color: white;
    color: #9be59e;
    border: none;
    padding: 5px 10px;
    cursor: pointer;
}

.filter-container {
    width: 20%;
    float: left;
    padding: 10px;
    background-color: #ddf4dd;
    box-sizing: border-box;
}

.filter label {
    display: block;
    margin-bottom: 5px;
}

.content {
    width: 80%;
    float: right;
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    padding: 10px;
    box-sizing: border-box;
}

.item {
    background-color: #e1f9df;
    border: 1px solid #ddd;
    padding: 20px;
    flex: 1 1 calc(33.333% - 20px);
    box-sizing: border-box;
    transition: transform 0.3s, background-color 0.3s;
    text-align: center;
}

.item img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 0 auto 10px;
    width: 250px;
    height: 150px; 
    object-fit: cover;
}

.item:hover {
    transform: scale(1.05);
    background-color: #e0e0e0;
}

footer {
    clear: both;
    background-color: #232323;
    color: white;
    text-align: center;
    padding: 10px;
}






