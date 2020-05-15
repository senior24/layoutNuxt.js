<template>
	<div class="testimonails  container">
	
		<div class="testimonails__item">
			<img src="~/assets/img/testimonails/1.png" alt="testimonials">
		</div>

		<div class="testimonails__item">
			<img src="~/assets/img/testimonails/2.png" alt="testimonials">
		</div>

		<div class="testimonails__item">
			<img src="~/assets/img/testimonails/3.png" alt="testimonials">
		</div>

		<div class="testimonails__item">
			<img src="~/assets/img/testimonails/4.png" alt="testimonials">
		</div>

		<div class="testimonails__item">
			<img src="~/assets/img/testimonails/5.png" alt="testimonials">
		</div>

	</div>
</template>

<script>
export default {
	
}
</script>

<style>
	.testimonails{
		padding-top: 60px;
		padding-bottom: 60px;

		display: flex;
		justify-content: space-between;
		flex-wrap: wrap;
	}


	@media (max-width: 669px){
		.testimonails{
			padding-top: 30px;
			padding-bottom: 0;
		}
		.testimonails__item{
			text-align: center;
			
			flex-basis: 33%;
			margin-bottom: 30px;
		}
	}

	@media (max-width: 463px){
		.testimonails__item{
			flex-basis: 48%;
		}
	}
 
</style>