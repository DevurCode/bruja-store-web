<!-- App.svelte -->
<script>
	import Footer from './Footer.svelte';
	import Header from './Header.svelte';
</script>

<html lang="en">
	<head>
		<link rel="preconnect" href="https://fonts.googleapis.com" />
		<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
		<link
			href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap"
			rel="stylesheet"
		/>
		<link
			rel="stylesheet"
			href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
			integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
			crossorigin="anonymous"
			referrerpolicy="no-referrer"
		/>
	</head>
	<body>
		<div class="app">
			<Header />
			<main>
				<slot />
			</main>
			<Footer />
		</div>
	</body>
</html>

<style>
	body {
		margin: 0;
	}
	html {
		font-family: 'Poppins', sans-serif;
	}
</style>
