<template>
	<header>
		<nav class="navbar navbar-expand-lg p-3">
			<div class="container">
				<a href="#"><h1>VERSUS</h1></a>
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
					<ul class="menu my-lg-0">
						<li>
							<a href="#" class="navlink"
								><router-link to="/">Portfolio</router-link></a
							>
						</li>
						<li class="navitem">
							<a href="#" class="navlink"
								><router-link to="/about">About</router-link></a
							>
						</li>
						<li class="navitem">
							<a href="#" class="navlink"
								><router-link to="/contact">CONTACT</router-link></a
							>
						</li>
						<li class="navitem">
							<a href="#" class="navlink"
								><router-link to="/statistika">Statistika</router-link></a
							>
						</li>
						<a href="">salom</a>
					</ul>
				</div>
			</div>
		</nav>
		<div class="header-info">
			<h1>We build beautiful web and mobile apps. {{ alik }}</h1>
			<button>Get a quote</button>
		</div>
	</header>
	<RouterView />
</template>
<script>
export default {};
</script>
<style>
/* header */
header {
	width: 100%;
	height: 540px;
	background-image: url(./img/background.png);
	background-repeat: no-repeat;
	background-size: cover;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
}
/* navbar */
nav {
	width: 100%;
	position: fixed !important;
	top: 0 !important;
	background-color: black;
	opacity: 0.9;
	z-index: 1;
}
.collapse {
	display: flex;
	justify-content: flex-end;
}
nav a h1 {
	font-weight: 400;
	font-size: 34px;
	color: white;
}
nav ul {
	display: flex;
	gap: 40px;
}
/* header info */

.header-info {
	width: 465px;
	display: flex;
	flex-direction: column;
	align-items: center;
}
.header-info h1 {
	font-style: normal;
	font-weight: 400;
	font-size: 48px;
	line-height: 53px;
	text-align: center;
	color: #ffffff;
}
.header-info button {
	border: 1px solid #00d6b4;
	border-radius: 3px;
	background: transparent;
	color: #00d6b4;
	padding: 10px 26px;
	cursor: pointer;
	margin-top: 29px;
}
.header-info button:hover {
	background: #00d6b4;
	color: #cccccc;
	transition: all 0.3s;
}
@media (max-width: 468px) {
	.header-info {
		width: 300px;
	}
	.header-info h1 {
		font-size: 35px;
	}
}
</style>
