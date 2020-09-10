<template lang="pug">
div
	img.hero-image(src="../assets/images/vintage-test-two.jpeg")
	.hero-text
		h1.display-2 Test Pattern Indigene 
		h1.display-4.mb-4 Mephistofelian Material
		.d-flex
			button.btn.btn-primary.btn-lg.mr-3 Theme Me  
			button.btn.btn-secondary-two.btn-lg.mr-3 Seme Me
			button.btn.btn-success-two.btn-lg(type='button' data-toggle='modal' data-target='#exampleModalCenter') Depeche Modal

	.modal.fade#exampleModalCenter(tabindex='-1' role='dialog' aria-labelledby='exampleModalCenterTitle' 	aria-hidden='true')
		.modal-dialog.modal-dialog-centered(role='document')
			.modal-content
				.modal-header
					h5.modal-title#exampleModalCenterTitle Gambiarra Ignara LLP
					button.close(type='button' data-dismiss='modal' aria-label='Close')
						span(aria-hidden='true') &times;

				.modal-body
					| Mel et vocent propriae, fugit dissentiet mel ea, inani detraxit signiferumque ex ius. Ius amet delenit te, eu dictas recteque referrentur duo. Mel et vocent propriae, fugit dissentiet mel ea, inani detraxit signiferumque ex ius. Ius amet delenit te, eu dictas recteque referrentur duo. Mel et vocent propriae, fugit dissentiet mel ea, inani detraxit signiferumque ex ius. Ius amet delenit te, eu dictas recteque referrentur duo.

				.modal-footer
					button.btn.btn-secondary(type='button' data-dismiss='modal') Clausurar
					button.btn.btn-primary(type='button') Escancarar

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
	overflow: hidden;
}

#bg {
	filter: contrast(90%) brightness(40%);
}

.coward-image {
	background-image: url("../assets/images/vintage-test-one.jpg");
	height: auto;
	width: 100%;
	background-position: center;
	background-repeat: no-repeat;
	background-size: cover;
	position: relative;
	background-color: #848482;
	background-blend-mode: multiply;
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
	background-image: url("../assets/images/vintage-test-one.jpg");
	height: auto;
	width: 100%;
	background-position: center;
	background-repeat: no-repeat;
	background-size: cover;
	position: relative;
	background-color: #848482;
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
