# personal

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Your Travel Blog</title>
    <!-- Include CSS styles for your chosen theme -->
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <header>
        <h1>Your Travel Blog</h1>
        <!-- Navigation menu -->
        <nav>
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/about">About</a></li>
                <li><a href="/contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <!-- Blog content goes here -->
        <article>
            <h2>Traveling to [Destination]</h2>
            <p>Your travel story goes here...</p>
            <img src="image.jpg" alt="Destination Image">
        </article>
        
        <!-- More articles -->
        
    </main>
    
    <footer>
        <p>&copy; 2023 Your Travel Blog</p>
    </footer>
</body>
</html>


<!-- Add this code within your article -->
<div class="social-share">
    <button id="share-button">Share</button>
</div>

<script>
    // JavaScript for sharing on a social network
    document.getElementById("share-button").addEventListener("click", function () {
        // Implement sharing functionality here
        alert("Share this article on social media!");
    });
</script>
