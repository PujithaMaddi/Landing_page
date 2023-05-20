# Landing_page
<!DOCTYPE html>0
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instruments Sales</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Instruments Sales</h1>
    </header>

    <main>
        <section>
            <h2>Featured Instruments</h2>
            <div class="instrument">
                <img src="guitar.jpg" alt="Guitar">
                <h3>Guitar</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis semper nulla vitae urna lacinia tincidunt.</p>
                <a href="guitar.html">Learn More</a>
            </div>

            <div class="instrument">
                <img src="piano.jpg" alt="Piano">
                <h3>Piano</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis semper nulla vitae urna lacinia tincidunt.</p>
                <a href="piano.html">Learn More</a>
            </div>
        </section>

        <section>
            <h2>Contact Us</h2>
            <p>If you have any questions or would like to make a purchase, please contact us:</p>
            <ul>
                <li>Email: sales@instrumentsales.com</li>
                <li>Phone: 123-456-7890</li>
                <li>Address: 123 Instrument Street, City, State, ZIP</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Instruments Sales. All rights reserved.</p>
    </footer>
</body>
</html>

#css
body, h1, h2, h3, p, ul {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

h1 {
    font-size: 30px;
    margin-bottom: 10px;
}

main {
    max-width: 960px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
}

section {
    margin-bottom: 30px;
}]

h2 {
    font-size: 24px;
    margin-bottom: 10px;
}

.instrument {
    margin-bottom: 20px;
}

.instrument img {
    max-width: 100%;
}

.instrument h3 {
    font-size: 20px;
    margin: 10px 0;
}

.instrument p {
    font-size: 14px;
    margin-bottom: 10px;
}

.instrument a {
    display: inline-block;
    padding: 10px 20px;
    background-color: #333;
    color: #fff;
    text-decoration: none;
    border-radius: 4px;
    transition: background-color 0.3s ease;
}

.instrument a:hover {
    background-color: #555;
}

ul {
    list-style: none;
    margin-left: 20px;
}

footer {
    background-color: #333;
    }
