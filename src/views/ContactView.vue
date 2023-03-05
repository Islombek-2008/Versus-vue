<template>
	<div class="contact">
		<h1>VERSUS Contact</h1>
		<div class="contact-info">
			<img
				src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTc8_fKedi-1qOaG57RViUVq-uJ914blT9a2A&usqp=CAU"
				alt="image"
			/>
			<contact>
				<ul class="cantact-link">
					<li class="cantact-menu"><span>Cantact:</span></li>
					<hr />
					<li>EMAIL : <span> in2008@gmail.com</span></li>
					<li>INST : <span> in2008</span></li>
					<li>
						CALLS :
						<a href="tel:+9989991735313"><span> +998 (99)-173-53-13</span></a>
					</li>
				</ul>
			</contact>
		</div>
	</div>
</template>
<script>
export default {};
</script>
<style>
.contact {
	width: 100%;
	padding-bottom: 45px;
	padding-top: 33px;
	background-color: #222222;
}
h1 {
	display: flex;
	justify-content: center;
	color: #fff;
}
.contact-info {
	display: flex;
	flex-wrap: wrap;
	justify-content: space-around;
	align-items: center;
	margin-top: 33px;
}
.cantact-link li {
	font-size: 24px;
	color: azure;
}
.cantact-link a {
	font-size: 24px;
	color: azure;
}
hr {
	margin-top: 15px;
	margin-bottom: 15px;
	width: 250px;
}
.cantact-menu span {
	font-size: 28px;
}
span {
	color: cornsilk;
}
</style>
