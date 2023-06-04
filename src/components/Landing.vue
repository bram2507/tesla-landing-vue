
<template>
	<main
		class="snap-y snap-mandatory relative w-full h-screen overflow-y-auto overflow-x-hidden scroll-smooth"
	>
		<div>
			<NavbarVue />
		</div>
	</main>
</template>

<script>
import NavbarVue from "./NavBar/Navbar.vue";

export default {
	components: {
		NavbarVue,
	},
};
</script>


<style scoped>
.read-the-docs {
	color: #888;
}
</style>
