<footer class="footer">
	<main class="encabezado">
		<span class="encabezado__titulo">Suscribete para resivir boletinis</span>
		<div class="encabezado__contenido">
			<input type="email" class="encabezado__input" placeholder="Su dirección electronico" />
			<p class="encabezado__parrafo">suscribirse</p>
		</div>
	</main>
	<section class="seccion">
		<article class="articulo">
			<figure>
				<img
					src="https://labrujastore.com/wp-content/uploads/2023/03/logolabruja-2-300x169.png"
					alt="imagen"
					class="articulo__imagen"
				/>
			</figure>
			<div class="contenido">
				<p class="contenido__descripcion">
					Consigue las mejores marcas a los mejores
					<span class="contenido__span">precios, aquí en La Bruja Store.</span>
				</p>
				<p class="contenido__ubicacion">Sígenos en Arequipa:</p>
				<div class="iconos">
					<div class="icono__padre">
						<a
							href="https://www.instagram.com/labrujastoreaqp/?hl=es-la"
							class="icono__style"
							target="_blank"
						>
							<i class="fa-brands fa-instagram"></i>
						</a>
					</div>
					<div class="icono__padre">
						<a
							href="https://www.facebook.com/LaBrujaStoreOficial"
							class="icono__style"
							target="_blank"
						>
							<i class="fa-brands fa-facebook"></i>
						</a>
					</div>
					<div class="icono__padre">
						<a
							href="https://www.tiktok.com/@labrujastoreaqp?lang=es"
							class="icono__style"
							target="_blank"
						>
							<i class="fa-brands fa-tiktok"></i>
						</a>
					</div>
				</div>
				<p class="contenido__ubicacion">Sigenos en Lima:</p>
				<div class="iconos">
					<div class="icono__padre">
						<a
							href="https://www.instagram.com/labrujastoreaqp/?hl=es-la"
							class="icono__style"
							target="_blank"
						>
							<i class="fa-brands fa-instagram"></i>
						</a>
					</div>
					<div class="icono__padre">
						<a
							href="https://www.facebook.com/LaBrujaStoreOficial"
							class="icono__style"
							target="_blank"
						>
							<i class="fa-brands fa-facebook"></i>
						</a>
					</div>
				</div>
			</div>
		</article>
		<article class="contacto">
			<div class="container">
				<h2 class="contacto__titulo">CONTÁCTANOS</h2>
				<div class="conacto__dividir"></div>
			</div>
			<div class="contacto__borde"></div>
			<div class="contacto__iconos">
				<a href="/contacto" target="_blank">
					<span><i class="fa-brands fa-whatsapp"></i></span>AREQUIPA: 921906558 / 985909840
				</a>
				<a href="/contacto" target="_blank">
					<span><i class="fa-brands fa-whatsapp"></i></span>LIMA: 985872694 / 982518156 / 927993661
				</a>
				<a href="/contacto">
					<span><i class="fa-solid fa-location-dot"></i></span>AREQUIPA: C.C. CompuArequipa Tienda
					133 y 219
				</a>
				<a href="/">
					<span><i class="fa-solid fa-location-dot"></i></span>LIMA: C.C. Cyberplaza tienda 140
					sector 2 B
				</a>
				<a href="/">
					<span><i class="fa-solid fa-envelope"></i></span>
					labrujastore@uotlook.com
				</a>
			</div>
		</article>
		<article class="informacion">
			<div class="container">
				<h2 class="informacion__titulo">INFORMACIÓN</h2>
				<div class="informacion__dividir"></div>
			</div>
			<ul class="informacion__lista">
				<li>Nosotros</li>
				<li>Novedades</li>
				<li>Destacados</li>
				<li>Ofertas del día</li>
				<li>
					<a href="/">Politicas de Privacidad</a>
				</li>
				<li>
					<a href="/">Terminos y Condiciones</a>
				</li>
			</ul>
		</article>
	</section>
	<div class="copyright">Labrujastore© 2023 todos los derechos reservados.</div>
</footer>

<style>
	* {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
	}

	.encabezado {
		background-color: #ed1d24;
		max-width: 1100px;
		margin: 0 auto;
		padding: 0.52rem;
		border-radius: 5px;
		display: flex;
		position: relative;
		align-items: center;
		bottom: 1.7rem;
	}
	.encabezado .encabezado__titulo {
		text-transform: uppercase;
		padding-right: 4rem;
		padding-left: 2rem;
		font-size: 1.15rem;
	}

	.encabezado__contenido {
		display: flex;
		align-items: center;
	}

	.encabezado .encabezado__input {
		width: 280px;
		height: 40px;
		border: none;
		outline: none;
		padding-left: 0.7rem;
		border-radius: 5px;
		margin-right: 1rem;
	}
	@media screen and (max-width: 768px) {
		.encabezado {
			max-width: 560px;
			padding: 0;
			margin: 0;
		}
	}
	.encabezado .encabezado__input:placeholder-shown {
		color: #323232;
	}

	.encabezado .encabezado__parrafo {
		text-transform: uppercase;
	}

	.footer {
		background-color: #000000;
		color: white;
		width: 100%;
	}

	.seccion {
		display: flex;
		justify-content: center;
		align-items: center;
		gap: 5rem;
	}

	@media screen and (max-width: 768px) {
		.seccion {
			flex-direction: column;
			align-items: flex-start;
			gap: 0;
			margin: 0 1rem 1rem;
		}
	}

	.contenido .contenido__descripcion .contenido__span {
		display: block;
	}

	.contenido .contenido__descripcion {
		margin-bottom: 1rem;
	}

	.iconos {
		display: flex;
		gap: 1rem;
		margin-bottom: 1rem;
		margin-top: 1rem;
	}

	.iconos .icono__padre {
		background-color: #666;
		display: flex;
		justify-content: center;
		align-items: center;
		border-radius: 50%;
		transition: background-color 500ms ease;
	}

	.iconos .icono__padre:hover {
		background-color: white;
		color: #000000;
	}

	.icono__padre i {
		padding: 0.35rem;
	}

	.icono__style {
		color: white;
	}

	.icono__padre:hover .icono__style {
		color: #000000;
	}

	/* Contactos */

	.contacto .contacto__titulo,
	.informacion__titulo {
		font-size: 1.59rem;
	}
	@media screen and (max-width: 768px) {
		.informacion__titulo {
			margin-top: 1.5rem;
		}
	}

	.container {
		max-width: 800px;
		text-align: left;
	}

	.container .conacto__dividir,
	.informacion__dividir {
		width: 170px;
		height: 2px;
		margin: 1.55rem 0;
		background-color: white;
	}

	.contacto__iconos {
		margin-top: 1rem;
		display: flex;
		flex-direction: column;
	}

	.contacto__iconos a {
		margin-top: 1rem;
		text-decoration: none;
		color: white;
	}

	.contacto__iconos a span {
		margin-right: 1rem;
	}

	/* Información */

	.informacion__lista li {
		margin-top: 1rem;
		font-size: 0.85rem;
		list-style: none;
	}

	.informacion__lista li a {
		text-decoration: none;
		color: white;
	}

	.informacion__lista li a:active {
		text-decoration: underline;
	}

	.footer .copyright {
		background-color: #323232;
		text-align: center;
		padding: 1.5rem 0;
	}
</style>
