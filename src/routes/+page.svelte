<script>

  import { page } from "$app/stores";

</script>
<head>
	<title>Maldron</title>
	<script src="https://kit.fontawesome.com/f64b15de80.js" crossorigin="anonymous"></script>
	</head>
	<body>
		<!-- HERO SECTION -->
		<div class="hero">
		  <h1>Hi, I'm Maldron</h1>
		  <p>Game Programmer & Software engineer</p>
		  <div class="btns">
			<a href="/about" aria-current={$page.url.pathname === '/about' ? 'page' : undefined}>About</a>
			<a href="/skills" aria-current={$page.url.pathname === '/skills' ? 'page' : undefined}>Skills</a>
			<a href="/projects" aria-current={$page.url.pathname === '/projects' ? 'page' : undefined}>Projects</a>
		  </div>
		  <div class="icons">
			<a href="https://github.com/maldron0309" target="_blank"><i class="fa-brands fa-github"></i></a>
			<a href="https://maldron7.itch.io/" target="_blank"><i class="fa-brands fa-itch-io"></i></a>
			<a href="mailto:maldron0309@gmail.com" target="_blank"><i class="fa-solid fa-envelope"></i></a>
		  </div>
		</div>
</body>
