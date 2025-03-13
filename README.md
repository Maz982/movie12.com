<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Movie Website</title>
    <link rel="stylesheet" href="style.css"> <!-- Link to the CSS file -->
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to My Movie Website</h1>
        <p>Explore featured movies and discover your next favorite film.</p>
    </header>

    <!-- Featured Movies Section -->
    <section id="movies">
        <h2>Featured Movies</h2>

        <!-- Movie 1 -->
        <div class="movie">
            <h3>Inception</h3>
            <img src="https://m.media-amazon.com/images/I/81p+xe8cbnL._AC_SY679_.jpg" alt="Inception Movie Poster">
            <p>A skilled thief is given a chance to have his criminal record erased if he can successfully perform an inception – planting an idea into someone's mind.</p>
            <a href="https://www.imdb.com/title/tt1375666/" target="_blank">Learn More</a>
        </div>

        <!-- Movie 2 -->
        <div class="movie">
            <h3>The Dark Knight</h3>
            <img src="https://m.media-amazon.com/images/I/51aFCzEx49L._AC_SY679_.jpg" alt="The Dark Knight Movie Poster">
            <p>When the menace known as The Joker emerges from his mysterious past, he wreaks havoc and chaos on the people of Gotham, forcing Batman to come out of retirement.</p>
            <a href="https://www.imdb.com/title/tt0468569/" target="_blank">Learn More</a>
        </div>

        <!-- Movie 3 -->
        <div class="movie">
            <h3>Interstellar</h3>
            <img src="https://m.media-amazon.com/images/I/71NAGxIWU-L._AC_SY679_.jpg" alt="Interstellar Movie Poster">
            <p>A team of explorers must find a new habitable planet for humanity after Earth becomes uninhabitable due to climate change and crop failures.</p>
            <a href="https://www.imdb.com/title/tt0816692/" target="_blank">Learn More</a>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 My Movie Website | Created by Your Name</p>
    </footer>

</body>
</html>
CSS (style.css)
css
Copy
/* General body styling */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

/* Header Section Styling */
header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px;
}

header h1 {
    margin: 0;
}

header p {
    font-size: 1.2em;
    margin: 10px 0 0;
}

/* Featured Movies Section Styling */
#movies {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 20px;
}

.movie {
    background-color: white;
    padding: 15px;
    margin: 15px;
    width: 250px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
}

.movie img {
    width: 100%;
    height: auto;
    border-radius: 5px;
}

.movie h3 {
    font-size: 1.5em;
    margin-top: 10px;
}

.movie p {
    font-size: 1em;
    color: #555;
    margin: 10px 0;
}

.movie a {
    text-decoration: none;
    color: #0066cc;
    font-weight: bold;
}

.movie a:hover {
    text-decoration: underline;
}

/* Footer Section Styling */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: absolute;
    width: 100%;
    bottom: 0;
}
