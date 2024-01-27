# html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>ULTIMEZ Hackathon Design Challenge</title>
</head>

<body>
    <header>
        <h1>Your Website Name</h1>
        <p>Welcome to our website</p>
    </header>

    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <main>
        <section class="featured-section">
            <h2>Featured Content</h2>
            <p>This is where your featured content goes.</p>
        </section>

        <section class="additional-section">
            <h2>Additional Content</h2>
            <p>More content for your webpage.</p>
        </section>

        <section class="form-section">
            <h2>Contact Us</h2>
            <form action="#" method="post">
                <label for="company-name">Company Name</label>
                <input type="text" id="company-name" name="company-name" required>

                <label for="country">Country</label>
                <input type="text" id="country" name="country" required>

                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>

                <label for="phone-number">Phone Number</label>
                <input type="tel" id="phone-number" name="phone-number" required>

                <label for="city">City</label>
                <input type="text" id="city" name="city" required>

                <label for="message">Message</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">Submit</button>
            </form>
        </section>
    </main>

    <footer>
        <!-- Footer content goes here -->
    </footer>

</body>

</html>

