<template>
	<header>
		<nav>
			<a href="#"><h1>VERSUS</h1></a>
			<ul>
				<li class="navitem">
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
			</ul>
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
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	margin-top: 72px;
}
/* navbar */
nav {
	position: fixed;
	top: 0;
	width: 100%;
	display: flex;
	align-items: center;
	justify-content: space-around;
	padding: 23px 0;
	background: rgba(0, 96, 119, 0.02);
	backdrop-filter: blur(29px);
}
nav a h1 {
	font-weight: 400;
	font-size: 24px;
	color: #ffffff;
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
