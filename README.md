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

header {
    background-color: #333;
    color: white;
    padding: 10px 20px;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin-top: 10px;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

.products {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

.product {
    background-color: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    width: 250px;
}

.product img {
    max-width: 100%;
    border-radius: 8px;
}

button {
    background-color: #28a745;
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
    border-radius: 4px;
}

button:hover {
    background-color: #218838;
}

.cart {
    margin-top: 50px;
    padding: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    margin-top: 30px;
}
