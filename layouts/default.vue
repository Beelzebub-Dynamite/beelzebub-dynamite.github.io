<template lang="pug">
div
	nav.navbar.sticky-top.navbar-expand-lg.navbar-light.bg-light
		a.navbar-brand(href='/')
			i.fas.fa-sun.fa-2x.mr-2
			| Engenho Infernal Redux
		button.navbar-toggler(type='button' data-toggle='collapse' data-target='#navbarSupportedContent' aria-controls='navbarSupportedContent' aria-expanded='false' aria-label='Toggle navigation')
			span.navbar-toggler-icon
		.collapse.navbar-collapse#navbarSupportedContent
			ul.navbar-nav.mr-auto
				li.nav-item.active
					a.nav-link(href='#')
						| In Principio
						span.sr-only (current)
				li.nav-item
					a.nav-link(href='#') In Media Res
				li.nav-item.dropdown
					a.nav-link.dropdown-toggle#navbarDropdown(href='#' role='button' data-toggle='dropdown' aria-haspopup='true' aria-expanded='false').

						Diogo Anhanguera

					.dropdown-menu(aria-labelledby='navbarDropdown')
						a.dropdown-item(href='/harry')
							i.fas.fa-chess.fa-2x.mr-3
							| Old Harry
						a.dropdown-item(href='/scratch')
							i.material-icons.md-48.mr-3 all_inclusive
							| Old Scratch
						.dropdown-divider
						a.dropdown-item(href='/flies')
							i.material-icons.md-48.mr-3 build
							| Lord of the Flies
						a.dropdown-item(href='/lucifer') 
							i.material-icons.md-48.mr-3 api
							| Light Bearer
						a.dropdown-item(href='father-lies') 
							i.material-icons.md-48.mr-3 account_balance
							| Father of Lies
						a.dropdown-item(href='morning') 
							i.material-icons.md-48.mr-3 music_note
							| Son of the Morning
						a.dropdown-item(href='/dickens') 
							i.material-icons.md-48.mr-3 wifi
							| The Dickens
						a.dropdown-item(href='tchort') 
							i.material-icons.md-48.mr-3 beach_access
							| Ya Tchort
						a.dropdown-item(href='/boogie') 
							i.material-icons.md-48.mr-3 settings_input_antenna
							| Boogie Man
						a.dropdown-item(href='/slewfoot') 
							i.material-icons.md-48.mr-3 rowing
							| Slewfoot
						a.dropdown-item(href='deuce') 
							i.material-icons.md-48.mr-3 pool
							| The Deuce You Say
						a.dropdown-item(href='/prince-darkness')
							i.material-icons.md-48.mr-3 directions_bike
							| Prince of Darkness
						a.dropdown-item(href='/diogo')
							i.material-icons.md-48.mr-3 directions_boat
							| Diogo Anhanguera
				li.nav-item.ml-auto
					button.btn.btn-primary.ml-5(data-target='#DropDrawers' data-toggle='navdrawer' type='button') Navegar

				.navdrawer#DropDrawers(aria-hidden='true' tabindex='-1')
					.navdrawer-content
						.navdrawer-header
							a.navbar-brand.px-0(href='#') Engenhoca Saudosa Maloca
						nav.navdrawer-nav
							a.nav-item.nav-link.active(href='#') Active
							a.nav-item.nav-link.disabled(href='#') Disabled
							a.nav-item.nav-link(href='#') Link
						.navdrawer-divider
						p.navdrawer-subheader Navdrawer subheader
						ul.navdrawer-nav
							li.nav-item
								a.nav-link.active(href='#')
									i.material-icons.mr-3 alarm_on
									|  Active with icon
							li.nav-item
								a.nav-link.disabled(href='#')
									i.material-icons.mr-3 alarm_off
									|  Disabled with icon
							li.nav-item
								a.nav-link(href='#')
									i.material-icons.mr-3 link
									|  Link with icon


	nuxt


</template>

<style>

	.navbar-brand {
		font-size: 28px;
	}

body, html {
		font-family: "News Cycle", sans-serif !important;
		font-weight: 300 !important;
		height: 100%;
		width: 100%;

	}

	h1, h2, h3, h4, h5, h6, .display-1 {
		font-family: "News Cycle", sans-serif !important;
	}

	.dignity {
		font-family: "News Cycle", sans-serif !important;
	}

	i,.material-icons {
		vertical-align: middle !important;
	}


.contained {
	height: 100%;
	width: 100%;
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
	/* position: relative; */
	filter: grayscale(100%) contrast(90%) opacity(75%);
	/* background-color: #6699cc; */
	/* background-blend-mode: multiply; */
}

.hero-text {
	text-align: center;
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	color: white;
}

#bg {
  position: fixed;
  top: -50%;
  left: -50%;
  width: 200%;
  height: 200%;
}
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

</style>
