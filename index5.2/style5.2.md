
/* 1. Universal selector */
* {
    box-sizing: border-box;
}

/* 2. Element selector */
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f1f5f9;
    color: #263449;
}

h1 {
    font-size: 34px;
}

p {
    line-height: 1.7;
}

/* 3. Grouping selector */
h2, h3 {
    color: #1d4ed8;
}

/* Header */
header {
    background-color: #172554;
    color: white;
    text-align: center;
    padding: 25px;
}

header h1 {
    color: white;
}

/* Navigation */
nav {
    background-color: #2563eb;
    padding: 15px;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 12px;
}

/* 4. Class selector */
.card {
    background-color: white;
    padding: 20px;
    margin: 15px 0;
    border-radius: 10px;
    box-shadow: 0 3px 8px #00000015;
}

/* 5. ID selector */
#special {
    background-color: #dbeafe;
    border-left: 5px solid #2563eb;
    padding: 20px;
    margin-top: 20px;
}

/* 6. Cascade and specificity practice */
.demo {
    color: green;
}

p.demo {
    color: red;
}

/* Footer */
footer {
    background-color: #172554;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 25px;
}

footer p {
    color: white;
}
