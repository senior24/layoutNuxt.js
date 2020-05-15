<template>

	<div class='works'>

		<div class="works__item">
			<div class="works__content">
				<img src="~/assets/img/works/increase.png" alt="increase">
			</div>
		</div>

		<div class="works__item">
			<div class="works__content">
				<img src="~/assets/img/works/increase.png" alt="increase">
			</div>
		</div>

		<div class="works__item">
			<div class="works__content">
				<img src="~/assets/img/works/increase.png" alt="increase">
			</div>
		</div>

		<div class="works__item">
			<div class="works__content">
				<img src="~/assets/img/works/increase.png" alt="increase">
			</div>
		</div>

		<div class="works__item">
			<div class="works__content">
				<img src="~/assets/img/works/increase.png" alt="increase">
			</div>
		</div>			

		<div class="works__item">
			<div class="works__content">
				<img src="~/assets/img/works/increase.png" alt="increase">
			</div>
		</div>	

		<div class="works__item">
			<div class="works__content">
				<img src="~/assets/img/works/increase.png" alt="increase">
			</div>
		</div>

		<div class="works__item">
			<div class="works__content">
				<img src="~/assets/img/works/increase.png" alt="increase">
			</div>
		</div>			
	</div><!-- works -->
	
</template>
 

<script>
export default {
	
}
</script>

<style  >

	.works{
		display: flex;
		flex-wrap: wrap;
	}

	.works__item{
		position: relative;

		width: 25%;
		height: 300px;

		overflow: hidden;

		background-color: #838383;
		background-image: url('~assets/img/works/1.jpg');
		background-position: center;
		background-repeat: no-repeat;
		background-size: cover;
	}

	.works__item:nth-child(2){
		background-image: url('~assets/img/works/2.jpg');
	}

	.works__item:nth-child(3){
		background-image: url('~assets/img/works/3.jpg');
	}

	.works__item:nth-child(4){
		background-image: url('~assets/img/works/4.jpg');
	}

	.works__item:nth-child(5){
		background-image: url('~assets/img/works/5.jpg');
	}

	.works__item:nth-child(6){
		background-image: url('~assets/img/works/6.jpg');
	}

	.works__item:nth-child(7){
		background-image: url('~assets/img/works/7.jpg');
	}

	.works__item:nth-child(8){
		background-image: url('~assets/img/works/8.jpg');
	}

	.works__item:nth-child(7){
		background-image: url('~assets/img/works/7.jpg');
	}

	.works__content{
		width: 100%;
		height: 100%;

		display: flex;
		justify-content: center;
		align-items: center;

		cursor: pointer;
		opacity: 0;

		transitioN: opacity .2s linear;

		background-color: rgba(20,20,20, .8) 
	}

	.works__content:hover{
		opacity: 1;
	}

	.works__conten:focus{
		opacity: 1;
	}
 
	@media (max-width: 954px){
		.works__item{
			flex-basis: 33%;
		}
	}
	@media (max-width: 637px){
		.works__item{
			flex-basis: 50%;
		}
	}
</style>