
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Selectors Practice</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>CSS Selectors Practice</h1>
        <p>Learn different CSS selectors with examples.</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#cards">Cards</a>
        <a href="#special">Special Section</a>
    </nav>

    <main id="home">
        <h2>Welcome to CSS</h2>
        <p>CSS makes web pages beautiful and attractive.</p>

        <section id="cards">
            <h2>Our Learning Cards</h2>

            <div class="card">
                <h3>HTML</h3>
                <p>HTML creates the structure of a webpage.</p>
            </div>

            <div class="card">
                <h3>CSS</h3>
                <p>CSS styles the webpage with colors and layouts.</p>
            </div>

            <div class="card">
                <h3>JavaScript</h3>
                <p>JavaScript adds interactivity to websites.</p>
            </div>
        </section>

        <section id="special">
            <h2>Special Section</h2>
            <p>This section is styled using an ID selector.</p>
        </section>

        <section>
            <h2>Cascade and Specificity</h2>
            <p class="demo">Observe which color wins in the CSS rules.</p>
        </section>
    </main>

    <footer>
        <p>Created for Assignment 5.2</p>
    </footer>

</body>
</html>
