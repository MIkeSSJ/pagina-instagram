# pagina-instagram
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="Stylesheet" href="style.css">
    <Title>Instagram</Title>
</head>
<body>
    <div class="instagram-wrapper">
        <div class="instagram-phone">
            <img src="./Imgagens/insta celular.png" alt="Celular">
        </div>
    </div>
    <div class="instagram-continue">
        <div class="grup">
            <img src="./Imgagens/Logo.jpg" class="instagram-logo" alt="Instagram Logo">
            <div class="profile-photo">
                <img src="./Imgagens/perfil.jpg" alt="foto do perfil">
            </div>
            <a href="#" class="instagram-login">Continue a navegar</a>
            <a href="#" class="intagram-logout">Remover conta</a>
        </div>
        <div class="group">
            <p class="not-account">não é fulano</p>
            <p class="notcount">
                <span class="link-blue">Alternar contas</span>
                ou
                <span class="link-blue">Inscreva-se</span>
            </p>
        </div>
        <div class="get-the-app">

            <p class="get-app">baixo o aplicativo</p>
            <div class="download">
                <a href="#" class="app-download"></a>
                <a href="#" class="app-download"></a>
            </div>
        </div>

        </div>
    </div>
</body>
</html>

//////////////////////////////

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    text-decoration: none;
    font-family: sans-serif;
    font-size: 14px;
}

body{

    width: 100%;
    min-width: 100vh;
    background-color: rgb(243, 243, 243);
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
}

.instagram-wrapper{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 60%;
    height: 100vh;
}

.instagram-phone{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 50%;
}

.instagram-phone img{
    height: 50rem;
}

.instagram-continue{
    display: flex;
    align-items: center;
    justify-content: space-around;
    flex-direction: column;
    width: 50%;
    min-height: 34rem;
}

.group{
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    background-color: #ffffff;
    width: 100%;
    padding: 1.3rem 0;
    border: 1px solid lightgray;
}

.group:nth-child(1){
    min-height: 19rem;
}

.instagram-logo{
    height: 10rem;
}

.profile-photo{
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
    overflow: hidden;

}

.profile-photo img{
    height: 6rem;
}

.instagram-login{
    background-color: #0295f6;
    color: #ffffff;
    padding: 8px;
    border-radius: 4px;
}

.instagram-logout{
    color: #0295f6;
    margin-top: 1rem;


}

.not-account{
    color: rgb(160, 160, 160);

}

.link-blue{
    display: #0895f6;
}

.get-the-app{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    padding: 1.3rem 0;
}

.download{
    display: flex;
    width: 100%;
    justify-content: space-evenly;
    align-items: center;
    padding: 1rem;
}

.app-download{
    height: 3rem;
    width: 10rem;
    background-size: cover;
}

.app-download:inth-child(1){
    background-image: url('./Imgagens/Apple\ button\ 1.png')
}

.app-download:inth-child(2){
    background-image: url('./Imgagens/Google\ button.png');
}

@media(max-width:1024px){
    .instagram-wrapper{
        width: 90%;
    }
}

@media (max-width:650px){

    body{
        background-color: #ffffff;
    };
    .instagram-wrapper{
        width: 90%;
    }

    .instagram-phone{
        display: none;
    }

    .instagram-continue{
        width: 100%;
    }

    .group{
        border: 1px solid transparent;
    }
}
