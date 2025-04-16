# Nao-sei
index.html

<!DOCTYPE html>
<html lang="PT-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
<nav>

    <ul>
<li><a href="#Home">Home</a>
</li>
<li><a href="#about">Sobre Nos</a>
</li>
<li><a href="#contact">Contato</a>
</li>
    </ul>
    
</nav>

<div class="header-logo">
    <img src="https://upload.wikimedia.org/wikipedia/commons/b/bc/Logo_Cruzeiro_1996.png"alt="">
</div>
</header>

<main class="galeria">
<ul><img src="https://th.bing.com/th/id/OIP.6ckv2OuJ8q5z8VMLUesu8gHaE8?rs=1&pid=ImgDetMain" alt="Minerão Cruzeiro"></ul>
<ul><img src="https://portalcruzeirense.com.br/wp-content/uploads/2022/01/cruzeiro-titu.jpg" alt="Titulos"></ul>

</main>

</body>
</html>













style.css


* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;

}

ul{
    display: flex;
    gap: 12px;
    justify-content: center;
    align-items: center;
    list-style: none;
}

nav{
    height: 30px;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 45px;
    
}




a{
text-decoration: none;
color: rgb(255, 255, 255);
}

header{
    background-color: rgb(6, 3, 212);
    font-size: 18px;

}

.header-logo{
    background-color: rgba(3, 34, 207, 0.123);
    height: 88px;
    & > img{
        height: 68%;
    }

    align-items: center;
    display: flex;
    justify-content: center;
}



.galeria img:nth-child() {
    width: 100vw;

}
