---
layout: base
title: Student Home 
description: Home Page
hide: true
---

<html lang="en">
    <head>
        <style>
            #terrariaboss {
                visibility: hidden;
                left: 100px;
            }
        </style>
        <script>
            const EOC = document.getElementByID('terrariaboss');
            let pos = 0;
            function spin(){
                EOC.style.left += 1;
                requestAnimationFrame(spin);
            }
        </script>
    </head>
    <body>
        <img id="terrariaboss" src="https://static.wikia.nocookie.net/terraria_gamepedia/images/7/70/Eye_of_Cthulhu_%28Phase_1%29.gif/revision/latest/scale-to-width-down/110?cb=20211114181102">
        <h1>Hello guys</h1>
        <a href="https://thegamer221148.github.io/clickit/">click me for free ice cream</a>
        <h2>GAMES I MADE IN JAVACRIPT</h2>
        <a href="https://thegamer221148.github.io/backrooms">Escape your Downloads Folder (unfinished)</a>
        <h2>Things i like</h2>
        <img src="https://upload.wikimedia.org/wikipedia/en/1/1a/Terraria_Steam_artwork.jpg">
        <br>
        <button onclick="spin()">Secret?</button>
        <h3>Terraria</h3>
    </body>
</html>