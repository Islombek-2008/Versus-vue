<template>
	<div class="portfolio">
		<h4>Latest Work</h4>
		<div class="image">
			<div class="img">
				<img src="../img/portfolio/IMAGE-1.png" alt="IMAGE-1" />
				<img src="../img/portfolio/IMAGE-2.png" alt="IMAGE-2" />
				<img src="../img/portfolio/IMAGE-3.png" alt="IMAGE-3" />
			</div>
			<div class="img">
				<img src="../img/portfolio/IMAGE-4.png" alt="IMAGE-4" />
				<img src="../img/portfolio/IMAGE-5.png" alt="IMAGE-5" />
				<img src="../img/portfolio/IMAGE-6.png" alt="IMAGE-6" />
			</div>
			<div class="img">
				<img src="../img/portfolio/IMAGE-7.png" alt="IMAGE-7" />
				<img src="../img/portfolio/IMAGE-8.png" alt="IMAGE-8" />
				<img src="../img/portfolio/IMAGE.png" alt="IMAGE-9" />
			</div>
		</div>
	</div>
</template>
<script>
export default {};
</script>
<style>
.portfolio {
	width: 100%;
	background-color: #222222;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	padding-bottom: 79.5px;
}
.portfolio h4 {
	font-style: normal;
	font-weight: 400;
	font-size: 25px;
	line-height: 30px;
	text-align: center;
	color: #ffffff;
	margin-bottom: 33px;
}
.image {
	display: flex;
	flex-direction: column;
	gap: 22px;
}
.img {
	gap: 20px;
	display: flex;
	flex-wrap: wrap;
}
@media (max-width: 1177px) {
	.img {
		justify-content: center;
	}
}
</style>
