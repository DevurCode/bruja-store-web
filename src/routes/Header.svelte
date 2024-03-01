 
<header>
    <div id="head-div-1">

        <div class="contenedor">
            <div class="head-div-1-sub">
                <p>Correo electrónico: <a href="mailto:labrujastore@outlook.com">labrujastore@outlokk.com</a></p>
            </div>
    
            <div class="dropdown">
                <p class="dropdown-toggle">Mi cuenta</p>
                <ul class="dropdown-menu">
                    <li><a href="#">Mi cuenta</a></li>
                    <li><a href="#">Contraseña perdida</a></li>
                </ul>
            </div>
        </div>
        
    </div>
    <div id="head-div-2">
        
        <div class="head-div-2-part1">
            <div class="contenedor-2">
                <!--Logo Header-->
                <div class="head-div-2-part1-1">
                    <img src="/img/logo.png" alt="Logo La Bruja Store">
                </div>
                
                <!--Buscador-->
                <div class="head-div-2-part1-2">
                    <form class="form-busqueda" action="" method="post">
                        <div><label for="btn-menu">Todas las Categorias</label></div>
                        <div class="form-busqueda-input"><input placeholder="Estoy buscando..."></div>
                        <div><button><img src="/icon/lupa.png" alt=""></button></div>
                    </form>
                </div>

                <!--Favorito y Carrito-->
                <div class="head-div-2-part1-3">

                    <!--Contador de favoritos-->
                    <a class="link-bnt" href="https://www.google.com/search?q=gato&oq=g&gs_lcrp=EgZjaHJvbWUqDggCEEUYJxg7GIAEGIoFMgYIABBFGDwyDggBEEUYJxg7GIAEGIoFMg4IAhBFGCcYOxiABBiKBTIGCAMQRRg8MgYIBBBFGDwyBggFEEUYPDIGCAYQRRg8MgYIBxBFGDzSAQgxNzI2ajBqN6gCALACAA&sourceid=chrome&ie=UTF-8">
                        <div>
                            <img src="/icon/corazon.png" alt="Corazon de favoritos">
                            <span class="contador">3</span>
                        </div>
                    </a>
                    
                    <!--Contador de carrito-->
                    <a class="link-bnt" href="#">
                        <div>
                            <img src="/icon/carrito-de-compras.png" alt="Carritos de compra">
                            <span class="contador">2</span>
                        </div>
                    </a>

                </div>
            </div>
        </div>

        <div class="head-div-2-part2">
                <div class="contenedor-3">
                    <a class="cont-lista-op" href="">INICIO</a>
                    <a class="cont-lista-op" href="">PRODUCTOS</a>
                    <a class="cont-lista-op" href="">CONTACTANOS</a>
                    <a class="cont-lista-op" href="">ACERCA DE</a>
                    <a class="cont-lista-op" href="">CARRITO</a>
                    <a class="cont-lista-op" href="">COTIZACIÓN</a>
                </div>
        </div>
    </div>
</header>

<!-- Silebar -->
<input type="checkbox" id="btn-menu">
<div class="container-menu">
  <div class="cont-menu">
    <nav>
      <a href="#">Categoría 1</a>
      <ul>
        <li><a href="#">Subcategoría 1.1</a></li>
        <li><a href="#">Subcategoría 1.2</a></li>
      </ul>
      <a href="#">Categoría 2</a>
      <ul>
        <li><a href="#">Subcategoría 2.1</a></li>
        <li><a href="#">Subcategoría 2.2</a></li>
      </ul>
      <!-- Agrega más categorías y subcategorías según sea necesario -->
    </nav>
    <label for="btn-menu">✖️</label>
  </div>
</div>
 
<style>
    *{
        font-family: sans-serif;
    }
    /*HEADER PARTE 1*/
    #head-div-1 {
        background-color: #1b1b1b;
        display: flex;
        justify-content: center;
        padding: 15px 0;
    }

    .contenedor {
        width: 1465px;
        display: flex;
        justify-content: space-between;
    }

    .contenedor-2{
        width: 1500px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .contenedor-3{
        width: 1460px;
        display: flex;
        justify-content: flex-start;
    }

    .head-div-1-sub{
        margin: 0 30px;
        
    }

    .head-div-1-sub p{
        color: #909090;
    }

    .head-div-1-sub a{
        color: #fff;
        text-decoration: none;
        transition: 0.1s;
    }

    .head-div-1-sub a:hover{
        color: #ed0909;
        
    }

    /* Estilos para el menú desplegable */
    .dropdown {
      position: relative;
      display: inline-block;
      margin: 0 30px;
    }

    .dropdown-toggle {
        color: #fff;
        background-color: #99999900;
        border: 1px solid rgba(204, 204, 204, 0)e8e;
        cursor: pointer;
        display: inline-block;
        transition: 0.1s;
    }

    .dropdown-toggle:hover {
        color: #ed0909;
    }

    .dropdown-menu {
      display: none;
      position: absolute;
      background-color: #fff;
      box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
      z-index: 1;
      list-style: none;
      padding: 0;
      margin: 0;
      right: 0;
    }

    .dropdown-menu a {
      text-decoration: none;
      color: #666;
      display: block;
      padding: 15px;
    }

    .dropdown-menu a:hover {
      background-color: #f0f0f0;
    }

    /* Mostrar el menú al hacer hover en el botón */
    .dropdown:hover .dropdown-menu {
      display: block;
    }

    /*HEADER PARTE 2*/
    #head-div-2{
        display: flex;
        flex-direction: column;
    }

    .head-div-2-part1 {
        display: flex;
        background-color: #000000;
        justify-content: space-evenly;
        padding: 15px;
    }

    .head-div-2-part1-1{
        width: 25%; /* ajusta el ancho según tus necesidades */
        overflow: hidden;
        margin-right: 5%;
    }

    .head-div-2-part1-1 img {
        max-width: 100%;
        height: auto;
        display: block;
    }

    .head-div-2-part1-2 {
        display: flex;
        background-color: #ffffff;
        border-radius: 3px;
        width: 50%;
        height: 45px;
        align-items: center;
    }

    .form-busqueda {
        width: 100%;
        height: 40px;
        display: flex;
        align-items: center;
        justify-content: space-around; 
    }

    .form-busqueda-input{
        width: 55%;
    }

    .form-busqueda label{
        color: #666;
        text-decoration: none;
        transition: 0.2s;
    }

    .form-busqueda label:hover {
        color: rgb(0, 0, 0);
        cursor: pointer;
    }

    .form-busqueda input{
        width: 100%;
        height: 30px;
        border: none;
        border-radius: 20px;
        padding-left: 10px;
        transition: border-color 0.2s ease-in-out;
    }

    .form-busqueda input:focus{
        outline: none;
        border-color: #4CAF50;
        box-shadow: 0 0 5px rgba(76, 175, 80, 0.5);
    }

    .form-busqueda img{
        width: 27px;
    }

    .form-busqueda button{
        border: none;
        background-color: white;
        transition: 0.1s;
    }

    .form-busqueda button:hover{
        cursor: pointer;
    }

    .head-div-2-part1-3 {
        display: flex;
        width: 360px;
        flex-direction: row;
        justify-content: flex-end;
    }

    .head-div-2-part1-3 img{
        width: 27px;
        margin: 0 17px;
    }

    .head-div-2-part1-3 div{
        display: flex;
    }
    
    .head-div-2-part2{
        background-color: #bc0707;
        display: flex;
        justify-content: center;
    }

    .cont-lista-op{
        text-decoration: none;
        color: #ffffff;
        margin-right: 35px;
        margin: 20px;
    }

    /*Menù lateral*/
	#btn-menu{
		display: none;
	}
	.container-menu{
		position: absolute;
		background: rgba(0,0,0,0.5);
		width: 100%;
		height: 100vh;
		top: 0;left: 0;
		transition: all 500ms ease;
		opacity: 0;
		visibility: hidden;
	}
	#btn-menu:checked ~ .container-menu{
		opacity: 1;
		visibility: visible;
	}
	.cont-menu{
		width: 100%;
		max-width: 250px;
		background: #ffffff;
		height: 100vh;
		position: relative;
		transition: all 500ms ease;
		transform: translateX(-100%);
	}
	#btn-menu:checked ~ .container-menu .cont-menu{
		transform: translateX(0%);
	}
	.cont-menu nav{
		transform: translateY(15%);
	}
	.cont-menu nav a{
		display: block;
		text-decoration: none;
		padding: 20px;
		color: #ff3a3a;
		border-left: 5px solid transparent;
		transition: all 400ms ease;
	}
	.cont-menu nav a:hover{
		border-left: 5px solid #c7c7c7;
		background: #000000;
	}
	.cont-menu label{
		position: absolute;
		right: 5px;
		top: 10px;
		color: #fff;
		cursor: pointer;
		font-size: 18px;
	}

    .cont-menu ul {
        list-style: none;
        margin: 0;
        padding: 0;
    }

    .cont-menu li {
        margin-left: 20px; /* Ajusta el espacio entre la categoría y la subcategoría */
    }

    .cont-menu li a {
        color: #000000;
        border-left: 5px solid transparent;
        transition: all 400ms ease;
        display: block;
        padding: 10px;
    }

    .cont-menu li a:hover {
        border-left: 5px solid #c7c7c7;
        background: #e3d5d5;
    }

    .contador{
        position: relative;
        background-color: white;
        border: 2px white solid;
        border-radius: 50%;
        right: 30px;
        top: -16px;
        color: #000000;
        height: 30px;
        width: 30px;
        text-align: center;
        line-height: 30px;
        transition: 0.1s;
    }
    
    .contador:hover{
        background-color: #ff0000;
        border: 2px #ff0000 solid;
        color: white;
    }

    .link-bnt{
        text-decoration: none;
    }

    @media screen and (max-width: 980px) { 
        .head-div-2-part1-3 {
            width: 200px;
        }
    }

    @media screen and (max-width: 855px) { 
        .contenedor-2 {
            flex-direction: column;
        }

        .head-div-2-part1-2{
            margin-top: 15px;
            margin-bottom: 29px;
            width: 85vw;
        }

        .head-div-2-part1-1{
            width: 384px;
        }
    }

    @media screen and (max-width: 780px) { 
        
    }

</style>