<script>
	export let segment;
</script>

<style>
	@media (min-width: 769px) {
		nav {
			border-bottom: solid gray 1px;
		}
	}
</style>

<nav class="navbar" role="navigation" aria-label="main navigation">
	<div class="navbar-brand">
		<a href="/" class="navbar-item">
			<img src="virus-logo.png" alt="virus logo">
		</a>
		<span class="navbar-burger" aria-label="menu" aria-expanded="false">
			<span aria-hidden="true"></span>
			<span aria-hidden="true"></span>
			<span aria-hidden="true"></span>
		</span>
	</div>
	<div class="navbar-menu">
		<div class="navbar-start">
			<a href="/" class="navbar-item">Home</a>
			<a href="/about" class="navbar-item">About</a>
		</div>
	</div>
</nav>