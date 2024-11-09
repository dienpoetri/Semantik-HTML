# Semantik-HTML
mempelajari HTML dengan CSS
untuk file index.html yang ada di modul praktikum codingan masih ada yang kurang
file index.html ditambahi codingan seperti berikut 
<html lang="en">
    <head> 
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>HTML5 Semantic</title>
        <link rel="stylesheet" href="./assets/styles/styles.css">
        </head>
diletakkan diatas setelah <!DOCTYPE html> dan sebelum <body></body>
sedangkan untuk susunan file styles.css untuk body diletakkan diatas sendiri sebagai berikut
body {
    display: grid;
    grid-template-areas: 
    "header header header"
    "nav section section"
    "footer footer footer";
    grid-template-rows: 80px 1fr 50px;
    grid-template-columns: 20% 1fr 18%;
    grid-gap: 5px;
    height: 100vh;
}
header,nav, section, footer {
    padding: 5px;
 }

nav {
    background: #C9BFBF;
    grid-area: nav;
}
header {
    background: #707070;
    grid-area: header;
    text-align: center;
 }
section {
    background: #ABABAB;
    grid-area: section;
 }
footer {
    background: #707070;
    grid-area: footer;
    font-size: small;
    text-align: center;
 }
Begitulah susunan file styles.css yang benar 
