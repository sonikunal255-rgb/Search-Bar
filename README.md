* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #667eea, #764ba2);
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
}

.container {
    background: white;
    width: 100%;
    max-width: 450px;
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.2);
}

h1 {
    text-align: center;
    margin-bottom: 20px;
    color: #333;
}

input {
    width: 100%;
    padding: 12px;
    border: 2px solid #667eea;
    border-radius: 8px;
    font-size: 16px;
    outline: none;
    margin-bottom: 20px;
}

input:focus {
    border-color: #764ba2;
}

ul {
    list-style: none;
}

li {
    background: #f2f3ff;
    padding: 12px;
    margin-bottom: 8px;
    border-radius: 6px;
    color: #333;
    transition: 0.3s;
}

li:hover {
    background: #667eea;
    color: white;
}

#noResult {
    text-align: center;
    color: red;
    margin-top: 10px;
}# Search-Bar
