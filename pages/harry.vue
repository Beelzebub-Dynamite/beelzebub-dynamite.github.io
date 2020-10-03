<template lang="pug">
div
	img.hero-image(src="../assets/images/vintage-test-two.jpeg")
	.hero-text
		h1.display-2 Old Harry
		h1.display-4.mb-4 Loitering at Crossroads
		.d-flex
			button.btn.btn-primary.btn-lg.mr-3 Theme Me  
			button.btn.btn-secondary-two.btn-lg.mr-3 Beam Me
			button.btn.btn-success-two.btn-lg Seme Me

</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
	components: {
		Logo
	}
}
</script>

<style>

#bg img {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  margin: auto;
  min-width: 50%;
  min-height: 50%;
  filter: grayscale(100%) contrast(80%) opacity(120%);
}

.hero-text {
	text-align: center;
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	margin-top: 110px;
	color: white;
}

#bg {
	filter: contrast(90%) brightness(40%);
}

.coward-image {
	background-image: url("../assets/images/vintage-test-two.jpeg");
	height: 100%;
	background-position: center;
	background-repeat: no-repeat;
	background-size: cover;
	position: relative;
	filter: grayscale(100%) contrast(40%) opacity(120%);
}

.contained {
	height: 100%;
	width: auto;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	text-align: center;
}

.hero-image {
	height: 100%;
	width: 100%;
	background-position: center;
	background-repeat: no-repeat;
	background-size: cover;
	position: relative;
	filter: grayscale(100%) contrast(40%) opacity(120%);
	background-color: #6699cc;
	background-blend-mode: multiply;
}

.container {
	min-height: 100vh;
	display: flex;
	justify-content: center;
	align-items: center;
	text-align: center;
}

</style>
