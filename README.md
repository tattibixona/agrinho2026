# agrinho2026
<script src="script.js"></script>
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f4f1e8;
    color: #2f3e2f;
}

<link rel="stylesheet" href="style.css">
    background: #2f5d3a;
    color: white;
    text-align: center;
    padding: 20px;
}

nav {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    background: #6b8e23;
}

nav a {
    color: white;
    padding: 10px 15px;
    text-decoration: none;
}

nav a:hover {
    background: #556b2f;
}

main {
    padding: 20px;
    max-width: 1000px;
    margin: auto;
}

section {
    background: white;
    margin: 15px 0;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 0 5px rgba(0,0,0,0.1);
}

h2 {
    color: #2f5d3a;
}

#simulador {
    background: #e8f5e9;
}

input, select, button {
    padding: 10px;
    margin: 5px 0;
    width: 100%;
    max-width: 300px;
    display: block;
}

button {
    background: #2f5d3a;
    color: white;
    border: none;
    cursor: pointer;
}

button:hover {
    background: #1e3d27;
}

footer {
    text-align: center;
    padding: 15px;
    background: #2f5d3a;
    color: white;
    margin-top: 20px;
}

/* Responsivo */
@media (max-width: 600px) {
    nav {
        flex-direction: column;
        align-items: center;
    }
}
