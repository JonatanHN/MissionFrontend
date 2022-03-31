<template>
	<nav class="navbar navbar-expand-lg navbar-light bg-light">
		<div class="container-fluid">
			<a class="navbar-brand" href="#">
        <img class="logo" src="../assets/logo.png" alt="logo">
      </a>
			<button
				class="navbar-toggler"
				type="button"
				data-bs-toggle="collapse"
				data-bs-target="#navbarSupportedContent"
				aria-controls="navbarSupportedContent"
				aria-expanded="false"
				aria-label="Toggle navigation"
			>
				<span class="navbar-toggler-icon"></span>
			</button>
			<div class="collapse navbar-collapse" id="navbarSupportedContent">
				<ul class="navbar-nav me-auto mb-2 mb-lg-0">
					<li class="nav-item">
						<router-link class="nav-link active" to="/">Inicio</router-link>
					</li>
					<li class="nav-item">
						<router-link class="nav-link" to="/pastelero">Pastelero</router-link>
					</li>
				</ul>
			</div>
		</div>
	</nav>
</template>

<script>
	// @ is an alias to /src
	import NavBar from "@/components/NavBar.vue";

	export default {
		name: "HomeView",
		components: {
			NavBar,
		},
	};
</script>


<style>
  .logo{
    width: 40px;
    height: 40px;
  }
  .nav-link{
    font-size: 1rem;
  }
</style>