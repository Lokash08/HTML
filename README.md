
<!DOCTYPE html>
<html>
<head>
    <title>My Awesome Website</title>
</head>
<body>

    <header>
        <h1>My Website Title</h1>
        <img src="logo.png" alt="Website Logo">
        <p>A brief description or tagline.</p>
    </header>

    <main>
        </main>

    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
        <p>Contact Us: contact@mywebsite.com</p>
    </footer>

</body>
</html>

3. Using <nav> for Menus/Links

<header>
    <h1>My Website Title</h1>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

4.
<main>
    <section>
        <h2>Latest Blog Posts</h2>
        <article>
            <h3>First Blog Post Title</h3>
            <p>This is the content of the first blog post.</p>
        </article>
        <article>
            <h3>Second Blog Post Title</h3>
            <p>This is the content of the second blog post.</p>
        </article>
    </section>
</main>

.
5.

<main>
    <article>
        <h2>Main Article Title</h2>
        <p>This is the primary content of the page...</p>
        <aside>
            <h4>Related Links</h4>
            <ul>
                <li><a href="#">Link 1</a></li>
                <li><a href="#">Link 2</a></li>
            </ul>
        </aside>
    </article>
</main>

6. Combining All Tags for a Complete Webpage Layout
Here's how to combine all the semantic tags to create a structured and complete webpage layout:
HTML Code:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Complete Webpage Layout</title>
</head>
<body>

    <header>
        <h1>Website Name</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#blog">Blog</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="welcome">
            <h2>Welcome to Our Website!</h2>
            <p>This is a brief introduction to our site and what we do.</p>
        </section>

        <section id="blog">
            <h2>Our Latest Articles</h2>
            <article>
                <h3>Article Title 1</h3>
                <p>This is the first article's content.</p>
                <p>Published on: September 22, 2025</p>
            </article>
            <article>
                <h3>Article Title 2</h3>
                <p>This is the second article's content.</p>
                <p>Published on: September 21, 2025</p>
            </article>
        </section>

        <aside>
            <h3>Related Content</h3>
            <p>Check out these related links and ads.</p>
            <ul>
                <li><a href="#">Ad 1</a></li>
                <li><a href="#">Ad 2</a></li>
            </ul>
        </aside>
    </main>

    <footer>
        <p>&copy; 2025 All Rights Reserved.</p>
        <p>
            <a href="#">Privacy Policy</a> | 
            <a href="#">Terms of Use</a>
        </p>
    </footer>

</body>
</html>
