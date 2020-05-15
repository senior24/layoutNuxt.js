<template>
	<div class="services">
		<div class="container">
			<div class="services__row">

				<div class="services__item">
					<img src="~/assets/img/services/1.png" alt="services">
					<div class="services__content">
						<h2 class="services__title">SEO / marketing</h2>
						<p class="services__text">Give won't after land fill creeping  meat you, may</p>
					</div>
				</div>

				<div class="services__item">
					<img src="~/assets/img/services/1.png" alt="services">
					<div class="services__content">
						<h2 class="services__title">SEO / marketing</h2>
						<p class="services__text">Give won't after land fill creeping  meat you, may</p>
					</div>
				</div>

				<div class="services__item">
					<img src="~/assets/img/services/1.png" alt="services">
					<div class="services__content">
						<h2 class="services__title">SEO / marketing</h2>
						<p class="services__text">Give won't after land fill creeping  meat you, may</p>
					</div>
				</div>

				<div class="services__item">
					<img src="~/assets/img/services/1.png" alt="services">
					<div class="services__content">
						<h2 class="services__title">SEO / marketing</h2>
						<p class="services__text">Give won't after land fill creeping  meat you, may</p>
					</div>
				</div>

				<div class="services__item">
					<img src="~/assets/img/services/1.png" alt="">
					<div class="services__content">
						<h2 class="services__title">SEO / marketing</h2>
						<p class="services__text">Give won't after land fill creeping  meat you, may</p>
					</div>
				</div>

				<div class="services__item">
					<img src="~/assets/img/services/1.png" alt="">
					<div class="services__content">
						<h2 class="services__title">SEO / marketing</h2>
						<p class="services__text">Give won't after land fill creeping  meat you, may</p>
					</div>
				</div>

				<div class="services__item">
					<img src="~/assets/img/services/1.png" alt="">
					<div class="services__content">
						<h2 class="services__title">SEO / marketing</h2>
						<p class="services__text">Give won't after land fill creeping  meat you, may</p>
					</div>
				</div>

				<div class="services__item">
					<img src="~/assets/img/services/1.png" alt="">
					<div class="services__content">
						<h2 class="services__title">SEO / marketing</h2>
						<p class="services__text">Give won't after land fill creeping  meat you, may</p>
					</div>
				</div>

			</div><!-- services -->
		</div><!-- container -->
	</div><!-- services -->
</template>

<script>
export default {
	
}
</script>
 
<style  >
	.services{
		padding-top: 100px;
		padding-bottom: 40px;

		background-color: #f5f5f5;
	}

	.services__row{
		display: flex;
		justify-content: space-between;
		flex-wrap: wrap;
	}

	.services__item{
		margin-bottom: 60px;

		flex-basis: 21%;
		text-align: center;
	}

	.services__title{
		margin-top: 25px;
		margin-bottom: 8px;

		color: #000;
		font-size: 12px;
		font-weight: 500;
		line-height: 1.2;
		text-transform: uppercase;
		letter-spacing: 1.2px;
	}
	
	.services__text{
		color: #787878;
		font-family: "Nunito Sans";
		font-size: 16px;
		font-weight: 400;
		line-height: 1.5;
		letter-spacing: 0.08px;
	}

	
	@media (max-width: 940px){
		 .services{
			 padding-top: 30px;
			 padding-bottom: 30px;
		 }
	}

	@media (max-width: 833px){
		.services__item{
			flex-basis: 30%;
		}
		.services__item{
			margin-bottom: 30px;
		}
	}

	@media (max-width: 513px){
		.services__item{
			flex-basis: 45%;
		}
	}
	@media (max-width: 394px){
		.services__item{
			flex-basis: 100%;
		}
	}
</style>