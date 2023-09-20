<!DOCTYPE html>
<html lang="es"> <!--"poner el idioma: Español"-->
<head>
    <meta charset="UTF-8"> <!--Codifico de -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diseñador Freelancer</title>
    <!--Para que cargue mas rapido la pagina web "rel = preload"-->
    <link rel="preload" href="css/normalize.css">
    <!--Para que en todos los navegadores web se vea de la misma forma-->
    <!--Nota: Cada vez que cambie de version cambia archivo-->
    <!--<link href="https://fonts.googleapis.com/css2?family=Anton&display=swap" rel="stylesheet">-->
    <link href="https://fonts.googleapis.com/css2?family=Anton&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/style.css">
    
</head>
<body>
    <header>
        <h1 class="titulo">Carlos Gómez Casas <span>Freelancer</span></h1>
    </header>

    <div class="nav-bg">
        <nav class="navegacion_principal contenedor">
            <a href="#">Inicio</a>
            <a href="#">Sobre Mi</a>
            <a href="#">Clientes</a>
            <a href="#">Contacto</a>
        </nav>
    </div> 
    <!-- Esto es una barra de navegacion ya que hay varios-->
    <section class="hero">
        <div class="contenido-hero">     
            <h2 class="">Diseño y Desarrollo Web Freelancer</h2>
                <div class="ubicacion">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-map-2" width="48" height="48" viewBox="0 0 24 24" stroke-width="2" stroke="#ff9300" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <line x1="18" y1="6" x2="18" y2="6.01" />
                        <path d="M18 13l-3.5 -5a4 4 0 1 1 7 0l-3.5 5" />
                        <polyline points="10.5 4.75 9 4 3 7 3 20 9 17 15 20 21 17 21 15" />
                        <line x1="9" y1="4" x2="9" y2="17" />
                        <line x1="15" y1="15" x2="15" y2="20" />
                    </svg>
                    <p>Murcia, España</p>
                </div>
                

            <a class="boton" href="#">Contact</a>
            <!-- No es recomendable ponerlo con mayusculas, ya que lo haremos con CSS-->
        </div>
    </section>

    <main class="contenedor sombra"> <!-- Lo consideramos con un contenido principal -->
        <h2>Mis Servicios</h2>

        <div class="servicios">
            <section class="servicio"> <!-- Se coloca al tener un h3 -->
                <h3>Diseño Web</h3>
                <div class="iconos">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-palette" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#7f5345" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <path d="M12 21a9 9 0 1 1 0 -18a9 8 0 0 1 9 8a4.5 4 0 0 1 -4.5 4h-2.5a2 2 0 0 0 -1 3.75a1.3 1.3 0 0 1 -1 2.25" />
                        <circle cx="7.5" cy="10.5" r=".5" fill="currentColor" />
                        <circle cx="12" cy="7.5" r=".5" fill="currentColor" />
                        <circle cx="16.5" cy="10.5" r=".5" fill="currentColor" />
                    </svg>
                </div>
                <p>Cras finibus elit eu convallis rhoncus. 
                Class aptent taciti sociosqu ad litora torquent per conubia nostra, 
                per inceptos himenaeos.</p>
            </section>    
    
            <section class="servicio">
                <h3>Aplicaciones Moviles</h3>
                <div class="iconos">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-devices" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#7f5345" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <rect x="13" y="8" width="8" height="12" rx="1" />
                        <path d="M18 8v-3a1 1 0 0 0 -1 -1h-13a1 1 0 0 0 -1 1v12a1 1 0 0 0 1 1h9" />
                        <line x1="16" y1="9" x2="18" y2="9" />
                    </svg>
                </div>
                <p>Cras finibus elit eu convallis rhoncus. 
                Class aptent taciti sociosqu ad litora torquent per conubia nostra, 
                per inceptos himenaeos.</>
            </section>

            <section class="servicio">
                <h3>E-Commerce</h3>
                <div class="iconos">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-shopping-cart" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#7f5345" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <circle cx="6" cy="19" r="2" />
                        <circle cx="17" cy="19" r="2" />
                        <path d="M17 17h-11v-14h-2" />
                        <path d="M6 5l14 1l-1 7h-13" />
                    </svg>
                </div>
                <p>Cras finibus elit eu convallis rhoncus. 
                Class aptent taciti sociosqu ad litora torquent per conubia nostra, 
                per inceptos himenaeos.</p>
            </section>  
        </div> <!--Cierre de la Clase de Servicios-->       
        <section> <!-- Ya que dentro tendremo un formulario-->
            <h2>Contacto</h2>
            <form class="formulario">
                <fieldset>
                   <legend>Contactanos para mas información:</legend> 
                   <div class="contenedor-campos"> 
                        <div class="campo">
                            <label>Nombre: </label> 
                            <input class="input-text"  type="text" placeholder=" Tu Nombre"> 
                        </div>
                        
                        <div class="campo">
                            <label>Teléfono: </label> 
                            <input class="input-text" type="tel" placeholder=" Tu Telefono">
                        </div>
                        
                        <div class="campo">
                            <label>Correo: </label> 
                            <input class="input-text" type="email" placeholder=" Tu Correo Electronico">  
                        </div>

                        <div class="campo">
                            <label>Mensaje: </label> 
                            <textarea class="input-text"></textarea>
                        </div>
                    </div> <!-- Contenedor de los campos-->
                        <div class="alinear-derecha flex">
                            <button class="boton w-sm-100" type="submit" value="Enviar">Enviar</button>
                        </div> 
                           
                </fieldset>
            </form>
        </section>
    </main>        
        <footer class="footer"> <!--Ya que es la parte de abajo siendo la mas importante para poner la información legal y demas cosas -->
            <p>Todos los derechos reservados. Carlos Gómez Casas Freelancer</p>
        </footer> 
</body>
</html>