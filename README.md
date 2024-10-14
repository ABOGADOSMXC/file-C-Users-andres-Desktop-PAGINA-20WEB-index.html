* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

.header {
    background: #002244;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

.header h1 {
    font-size: 2.5rem;
}

.areas, .sobre-nosotros, .contacto {
    padding: 20px 0;
}

h2 {
    text-align: center;
    color: #002244;
    margin-bottom: 20px;
}

ul {
    list-style-type: none;
    text-align: center;
}

ul li {
    font-size: 1.2rem;
    padding: 5px 0;
}

.contacto p {
    text-align: center;
}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 20px;
}

form input, form textarea {
    width: 100%;
    max-width: 500px;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    background-color: #002244;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

form button:hover {
    background-color: #00509e;
}

.footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}
