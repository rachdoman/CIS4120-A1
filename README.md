# CIS4120-A1

(1) Run the code via index.html file. 

(2) AI attributions:

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Penn Course Registration</title>
    <link rel="stylesheet" href="styles.css">
</head>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html, body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Arial, sans-serif;
    background-color: #f2f4fa;
    color: #333;
    overflow: hidden;
}

.search-box {
    border: 1.5px solid black;
    box-sizing: border-box;
    height: 265px;
    width: calc(100% + 20px);
    margin: 0 -10px;
    overflow: hidden;
    background: transparent;
}

.search-header::before {
    content: '';
    position: absolute;
    right: 8px;
    top: 30%;
    transform: translateY(-20%);
    width: 20px;
    height: 20px;
    background-image: url('https://img.icons8.com/?size=100&id=476&format=png&color=FFFFFF');
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
}
