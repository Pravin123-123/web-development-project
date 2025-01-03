# web-development-project

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A simple landing page">
    <title>Landing Page</title>
        /* CSS styles go here */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            text-align: center;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 50px 0;
        }

        h1 {
            font-size: 3em;
            margin: 0;
        }

        p {
            font-size: 1.2em;
            margin: 20px 0;
        }

        .cta-button {
            background-color: #ff5733;
            color: white;
            padding: 15px 25px;
            text-decoration: none;
            font-size: 1.2em;
            border-radius: 5px;
        }

        .cta-button:hover {
            background-color: #e04e2f;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px 0;
        }

        footer a {
            color: #ff5733;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to My Landing Page</h1>
        <p>Your journey to amazing services starts here!</p>
        <a href="#cta" class="cta-button">Get Started</a>
    </header>

    <!-- Main Section -->
    <section id="cta">
        <h2>Sign Up Now</h2>
        <p>Enter your email and join the community!</p>
        <form>
            <input type="email" placeholder="Enter your email" required>
            <button type="submit">Join Now</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>© 2025 Landing Page. All Rights Reserved.</p>
        <p><a href="#">Privacy Policy</a> | <a href="#">Terms of Service</a></p>
    </footer>

</body>
</html>
