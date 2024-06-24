<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Exercise</title>
    <style>
        /* 1. Set the background color of the header to light blue */
        header {
            background-color: #ADD8E6; /* Light blue */
        }

        /* 2. Set the text color of h1 inside the header to your favorite color */
        header h1 {
            color: #4CAF50; /* Example favorite color - green */
        }

        /* 3. Add a bottom border of 2px solid black to the nav */
        nav {
            border-bottom: 2px solid black;
        }

        /* 4. Set the font size of nav ul li a to 18px */
        nav ul li a {
            font-size: 18px;
        }

        /* 5. Center align the text inside the footer */
        footer {
            text-align: center;
        }

        /* 6. Set the background color of the .box class to light grey and give it a padding of 20px */
        .box {
            background-color: #D3D3D3; /* Light grey */
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to CSS Exercise</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <section>
        <h2>Main Content</h2>
        <p>This is a paragraph of text.</p>
        <div class="box">
            <p>This is inside a box.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 CSS Exercise</p>
    </footer>
</body>
</html>
