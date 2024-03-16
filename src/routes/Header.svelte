<script>

  import { page } from "$app/stores";

</script>
  <!-- HEADER -->
<header id="home" class="vignette">
	<nav id="nav">
	  <div class="nav-text">
		<a href="/" aria-current={$page.url.pathname === '/' ? 'page' : undefined}>
			<h3>Mald <span>ron</span></h3>
		</a>
	  </div>
	  <img src="images/profile.png" alt="profile"/>
	</nav>
</header>

<style>
	a {
  color: inherit;
  text-decoration: none;
}
</style>