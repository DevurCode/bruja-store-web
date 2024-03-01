<svelte:head>
	<title>Contacto</title>
	<meta name="description" content="About this app" />
</svelte:head>

<section class="contactos">
	<div class="contactos__header">
		<div class="seguimiento">
			<a href="/" class="seguimiento__etiqueta">
				Hogar <i class="fa-solid fa-angle-right"></i><span class="seguimiento__contacto">
					Contactanos
				</span>
			</a>
		</div>
		<div class="seguimiento__dos">
			<h2 class="seguimiento__titulo">CONTACTANOS</h2>
		</div>
	</div>
	<hr />
	<article class="main">
		<div class="flex__cajas">
			<div class="bloque__uno">
				<h1 class="bloque__titulo">Lima <span>(ASESORES)</span></h1>
				<div class="caja">
					<div class="card">
						<img
							src="https://labrujastore.com/wp-content/uploads/2023/11/operador.png"
							alt=""
							class="card__img"
						/>
						<p class="card__autor">YERSON LOZADA</p>
						<span class="card__phone">982 518 158</span>
					</div>
					<div class="card">
						<img
							src="https://labrujastore.com/wp-content/uploads/2023/11/operador.png"
							alt=""
							class="card__img"
						/>
						<p class="card__autor">VICTOR TORRES</p>
						<span class="card__phone">957 173 141</span>
					</div>
				</div>
				<div class="caja">
					<div class="card">
						<img
							src="https://labrujastore.com/wp-content/uploads/2023/11/operador.png"
							alt=""
							class="card__img"
						/>
						<p class="card__autor">YERSON LOZADA</p>
						<span class="card__phone">982 518 158</span>
					</div>
					<div class="card">
						<img
							src="https://labrujastore.com/wp-content/uploads/2023/11/operador.png"
							alt=""
							class="card__img"
						/>
						<p class="card__autor">VICTOR TORRES</p>
						<span class="card__phone">957 173 141</span>
					</div>
				</div>
			</div>
			<div class="bloque__dos">
				<h1 class="bloque__titulo">Arequipa<span>(ASESORES)</span></h1>
				<div class="caja">
					<div class="card">
						<img
							src="https://labrujastore.com/wp-content/uploads/2023/11/operador.png"
							alt=""
							class="card__img"
						/>
						<p class="card__autor">EDINSON LOZADA</p>
						<span class="card__phone">921 906 558</span>
					</div>
					<div class="card">
						<img
							src="https://labrujastore.com/wp-content/uploads/2023/11/operador.png"
							alt=""
							class="card__img"
						/>
						<p class="card__autor">FERNANDO PANDIA</p>
						<span class="card__phone">918 310 475</span>
					</div>
				</div>
			</div>
		</div>
	</article>
	<article class="ubicacion">
		<h1 class="ubicacion__titulo">Ubicanos</h1>
		<div class="mapas">
			<div>
				<h3>(Lima)</h3>
				<div>
					<iframe
						src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3901.804184383345!2d-77.0418232249387!3d-12.056989988180627!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9105c9babbe694bd%3A0x282693d962c25f2f!2sLa%20Bruja%20Store!5e0!3m2!1ses-419!2spe!4v1709167610627!5m2!1ses-419!2spe"
						width="600"
						height="450"
						style="border: 0"
						allowfullscreen=""
						loading="lazy"
						referrerpolicy="no-referrer-when-downgrade"
					></iframe>
					<ul>
						<li>C.C. CYBERPLAZA TIENDA 140 SECTOR 2B</li>
						<li>
							HORARIO DE ATENCIÓN
							<ul>
								<li>LUNES – SABADO: 10:00 AM a 8:00 PM</li>
								<li>DOMINGO: 10:00 AM a 6:00 PM</li>
							</ul>
						</li>
					</ul>
				</div>
			</div>
			<div>
				<h3>(Arequipa)</h3>
			</div>
		</div>
	</article>
</section>

<style>
	.contactos {
		max-width: 1400px;
		margin: 0 auto;
		padding: 1rem;
	}

	hr {
		color: #f5f5f5;
		margin: 1rem 0 2rem 0;
	}

	.seguimiento .seguimiento__etiqueta {
		text-decoration: none;
		color: #818181;
	}

	.seguimiento .seguimiento__contacto {
		color: #ff0202;
	}

	.contactos__header {
		display: flex;
		align-items: center;
		justify-content: space-between;
	}

	.main {
		max-width: 1116px;
		margin: 0 auto;
	}

	.flex__cajas {
		display: flex;
		justify-content: space-around;
	}

	.bloque__uno {
		border-right: 4px solid #ff0202;
		text-align: center;
	}

	.caja {
		display: flex;
		gap: 2rem;
		text-align: center;
	}

	.caja .card {
		width: 250px;
		margin-bottom: 1rem;
		padding: 1rem;
		border-radius: 0.55rem;
	}

	.card .card__autor {
		color: #ff0202;
		margin-top: 1.5rem;
		margin-bottom: 0.55rem;
		font-size: 1.2rem;
		font-weight: 800;
	}

	.card .card__img {
		max-width: 100%;
		display: flex;
		justify-content: center;
		align-items: center;
		margin: 0 auto;
	}

	.card:nth-child(2) {
		margin-right: 1rem;
	}

	.bloque__dos {
		text-align: center;
	}

	.bloque__titulo {
		font-size: 2rem;
		text-transform: uppercase;
		letter-spacing: 5px;
	}

	.bloque__titulo span {
		display: block;
		margin-bottom: 1rem;
		font-size: 1rem;
	}

	.bloque__dos .card:nth-child(2) {
		margin-right: 0;
	}

	.ubicacion {
		margin-top: 4rem;
		border-top: 4px solid #ff0202;
	}

	.ubicacion .ubicacion__titulo {
		text-align: center;
		font-size: 2rem;
		text-transform: uppercase;
		margin-top: 2rem;
	}

	.mapas {
		display: flex;
		justify-content: space-around;
	}
</style>
