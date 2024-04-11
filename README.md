# LucasandGawseeHappilyEverAfter/* Reset some basic elements */
body, h1, h2, h3, p, ul {
    margin: 0;
    padding: 0;
}

/* Body & Layout */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
    padding: 20px;
    max-width: 800px;
    margin: auto;
}

header {
    background: #fff;
    padding: 20px 0;
    border-bottom: 1px solid #dddddd;
}

nav ul {
    list-style: none;
    text-align: center;
}

nav ul li {
    display: inline-block;
}

nav ul li a {
    text-decoration: none;
    padding: 10px 20px;
    color: #333;
}

nav ul li a:hover {
    background-color: #e9e9e9;
}

/* Typography */
h1, h2, h3 {
    color: #444;
}

h1 {
    font-size: 2.5em;
    margin-bottom: 0.5em;
}

h2 {
    font-size: 2em;
    margin-bottom: 0.75em;
}

h3 {
    font-size: 1.5em;
    margin-bottom: 1em;
}

p {
    margin-bottom: 1em;
}

footer {
    margin-top: 20px;
    background: #fff;
    padding: 20px 0;
    text-align: center;
    border-top: 1px solid #dddddd;
}

footer p {
    color: #666;
}

/* Buttons and Links */
.button {
    display: inline-block;
    background: #444;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    transition: background 0.3s ease;
}

.button:hover {
    background: #333;
}

/* Photos Gallery */
.photos-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    grid-gap: 15px;
    margin-top: 20px;
}

.photos-grid img {
    width: 100%;
    border-radius: 5px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

/* Media Queries for responsiveness */
@media (max-width: 768px) {
    body {
        padding: 10px;
    }

    nav ul li a {
        padding: 10px 15px;
    }
}
