/* Resetting default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    color: #333;
    line-height: 1.6;
}

header.cover {
    background: url('cover-image.jpg') no-repeat center center/cover;
    color: white;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}

.cover-content h1 {
    font-size: 3em;
}

.cover-content p {
    font-size: 1.5em;
}

.cover .cta-button {
    display: inline-block;
    margin-top: 1em;
    padding: 10px 20px;
    color: #fff;
    background-color: #007bff;
    text-decoration: none;
    border-radius: 5px;
}

.about, .services, .contact {
    padding: 2em;
    text-align: center;
}

h2 {
    font-size: 2em;
    margin-bottom: 0.5em;
    color: #007bff;
}

.services .service {
    margin: 1em 0;
}

.service ul {
    list-style-type: none;
}

.service ul li {
    margin: 0.5em 0;
}

.contact form {
    max-width: 400px;
    margin: auto;
}

.contact input, .contact textarea, .contact button {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
}

footer {
    text-align: center;
    padding: 1em;
    background-color: #333;
    color: white;
}
