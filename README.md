# smak-em-processo
um pouco mais sobre o projeto smak

fiz esse projeto para treinar meus conhecimentos em css puro

// css da pagina inicial
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;1,100;1,200;1,300&display=swap');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins";
}

body{
    width: 100%;
    height: 100%;
}

header{
    width: 100%;
    background-color: #a60404 ;
    height: 300px;
}

.menu{
    position: relative;
    width: 940px;
    margin: 0 auto;
}

nav{
    position: absolute;
    top: 140px;
    right: 0;
}

nav li{
    display: inline;
    list-style: none;
    margin: 0 0 0 2.2rem ;
}

nav a{
    text-decoration: none;
    font-size:1.5rem;
    color: white;
    transition: 1s;
}

nav a:hover{
    color: black;
}

h1 img{
    margin-top: 6rem;
}

.img_principal{
    width: 100%;
}

.img_principal img{
    width: 100%;
    height: 720px;
    box-sizing: border-box;
    margin: 0;
    padding: 0;

}

.mapa{
    position: relative;
    display: block;
    width: 100%;
}

.mapinha{
    width: 100%;
}

.icones{
    display: flex;
}

.icones ul{
    display: flex;
    text-decoration: none;
    margin: auto;
}

.icones li{
    padding: 2rem 5rem;
    list-style: none;
    text-align: center;
}

.icones i{
    display: inline-block;
    font-size: 3rem;
    color: #a60404;
}

.icones span{
    font-size: 2rem;
}

.icones li p{
    font-size: 1.5rem;
}


.historia-smak{
    text-align: justify;
    height: auto;
    background:#f4f4f4;
}

.sobre{
    margin: auto;
    width: 50%;
    padding: 2rem;
}

.sobre p{
    font-weight: 400;
    padding: 0.8rem 0;
}

.contato{
    width: 100%;
    height: auto;
    background: #222222;
}

.contato section i{
    font-size: 3rem;
    color: white;
}

.fale-conosco{
    width: auto;
    margin: auto;
    text-align: center;
    padding: 3rem;
}

.fale-conosco h2{
    display: inline-block;
    padding: 0 0.2rem;
    font-size: 2rem;
    color: white;
}

.formulario{
    padding: 0.3rem 0;
}

.formulario input{
    width: 35%;
    height: 3rem;
    outline: none;
    border: none;
    padding: 0 0.6rem;
    border-radius: 2px;
}

.formulario input::placeholder{
    opacity: 0.7;
}

.formulario button{
    width: 15%;
    height: 3rem;
    border: none;
    padding: 0 0.3rem;
    border-radius: 2px;
    background: #a60404;
    color: white;
    font-weight: 900;
}

.instagram-seguir{
    height: auto;
    width: 100%;
    margin: auto;
    padding: 5rem;
    text-align: center;
}

.insta{
    width: 100%;
    display: flex;
    margin: auto;
}

.instagram-seguir a{
    text-decoration: none;
    color: #a60404;
    transition: 0.3s;
}

.instagram-seguir a:hover{
    color: #fbff00;
    letter-spacing: 0.1rem;
}

.instagram-seguir i{
    color: #a60404;
    font-size: 2.5rem;
    padding-right: 1.1rem;
}

.instagram-seguir h1{
    padding-bottom: 1.2rem;
}

.texto-contato{
    width: 100%;
    display: flex;
}

.texto1{
    position: relative;
    margin: auto;
    padding: 2rem 0;
}

.texto1 h4{
    color: white;
    padding: 0.9rem 0;
}

.texto1 p{
    color: #acacac;
    font-weight: 200;
    padding: 0.5rem 0;
}

.texto1 i{
    padding-right: 0.3rem;
}

.texto1 .p1::after{
    content: '';
    display: block;
    margin: 0.9rem 0;
    position: absolute;
    height: 1px;
    width: 100%;
    background: #acacac;
}

.texto1 .p2{
    padding: 0.9rem 0;
}

// css da pagina de login

@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;1,100;1,200;1,300&display=swap');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins";
}
body{
    background-color: #a60404 ;
}

main{
    display: flex;
    align-items: center;
    justify-content: center;
}

header{
    width: 100%;
    background-color: #a60404 ;
    height: 300px;
}

.menu{
    position: relative;
    width: 940px;
    margin: 0 auto;
}

nav{
    position: absolute;
    top: 140px;
    right: 0;
}

nav li{
    display: inline;
    list-style: none;
    margin: 0 0 0 2.2rem ;
}

nav a{
    text-decoration: none;
    font-size:1.5rem;
    color: white;
    transition: 1s;
}

nav a:hover{
    color: black;
}

h1 img{
    margin-top: 6rem;
}

.container{
    margin-top: 5rem;
    background-color: rgb(255, 255, 255) ;
    width: 50%;
    min-height: 40vh;
    padding: 3rem;
    border-radius: 25px;
}

main h2{
    margin-bottom: 2rem;
    font-weight: 600;
    position: relative;
}

main h2::before{
    content: '';
    position: absolute;
    height: 4px;
    width: 25px;
    bottom: 3px;
    left: 0;
    border-radius: 10px;
    background: black;
}

.formulario{
    position: relative;
}

.formulario input{
    width: 100%;
    outline: none;
    font-size: 1rem;
    padding: 8px;
    transition: 1s;
    border: none;
}

.formulario::before{
    content: '';
    position: absolute;
    height: 2px;
    width:100% ;
    bottom: 3px;
    background: rgb(0, 0, 0, 0.5);
}


.formulario:first-child{
    margin-bottom: 1.5rem;
}


input::placeholder{
    opacity: 0.5;
}

form{
    display: flex;
    flex-direction: column;
}


.botoes{
    display: flex;
    justify-content: center;
    margin-top: 1rem;

}

form #entrar{
    margin-top: 1rem;
    padding: 0.4rem;
    cursor: pointer;
    width: 100%;
    font-size: 0.9rem;
    font-weight: bold;
    border-radius: 7px;
    border: none;
    color: white;
    background-color:black ;
    transition: 0.3s;

}

form #entrar:hover{
    transform: scale(1.03);
    letter-spacing: 0.1rem;
}


form #twiter{
    margin-right: 1rem;
    padding: 0.4rem;
    cursor: pointer;
    width: 32%;
    font-size: 0.9rem;
    font-weight: bold;
    border-radius: 7px;
    border: none;
    color: white;
    background-color:rgb(6, 167, 216) ;
    transition: 0.8s;
}

form #twiter:hover{
    background-color: rgb(97, 149, 184);
}

form #face{
    margin-right: 1rem;
    padding: 0.4rem;
    cursor: pointer;
    width: 32%;
    font-size: 0.9rem;
    font-weight: bold;
    border-radius: 7px;
    border: none;
    color: white;
    background-color:rgb(45, 87, 226) ;
    transition: 0.8s;
}

form #face:hover{
    background-color: rgb(97, 149, 184);
}

form #insta{
    padding: 0.4rem;
    cursor: pointer;
    width: 32%;
    font-size: 0.9rem;
    font-weight: bold;
    border-radius: 7px;
    border: none;
    color: white;
    background: linear-gradient(90deg,rgb(13, 26, 211),rgb(253, 11, 213),rgb(248, 244, 0),rgb(245, 3, 3),rgb(253, 11, 213));
    transition: 0.8s;
}

form #insta:hover{
    background-color: rgb(255, 238, 0);
}

.outros{
    position: relative;
    display: flex;
    justify-content: center;
    margin-top: 0.7rem;
}

.outros::before{
    content: '';
    position: absolute;
    align-self: center;
    left: 0;
    height: 1px;
    width:45%;
    background: rgb(0, 0, 0, 0.5);
}
.outros::after{
    content: '';
    position: absolute;
    align-self: center;
    right: 0;
    height: 1px;
    width:45%;
    background: rgb(0, 0, 0, 0.5);
}

.registrar{
    margin-top: 1rem;
}

.registrar span a{
    text-decoration: none;
}
