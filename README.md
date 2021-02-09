# fallingMoon
*{
    margin: 0%;
    padding: 0%;
}
body{
    background-image: url(spooky-tree-against-big-moon.jpg);
}
.text{
    text-align: center;
    font-style: italic;
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: crimson;
    text-shadow: rgb(247, 241, 241) 5px 10px 20px;
    font-size: 50px;
}

#game{
    width: 300px;
    height: 600px;
    border: black solid 10px;
    position: relative;
    left: 300px;
    overflow: hidden;
    background-image: url(spooky-tree-against-big-moon.jpg);
    image-resolution: 10%;
    image-orientation: flip;
}
#karakter{
    width: 100px;
    height: 100px;
    border: solid 1px;
    background: url(—Pngtree—vector\ cartoon\ owl\ scooters_2576390.png) bottom center no-repeat;
    image-orientation: from-image;
    background-size: 100%;
    position: relative;
    top: 400px;

}
#block{
    width: 100px;
    height: 100px;
    border-radius: 50%;
    border: solid 1px;
    background-image: linear-gradient(to top, #ff0844 0%, #ffb199 100%);
    position: relative;
    animation: jatuh 2s infinite;

}
@keyframes jatuh{
    0%{top : 100px}
    100%{ top : 600px }
}
