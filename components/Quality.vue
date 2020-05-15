<template>

	<div class="quality">
		<div class="container">
			<ul class="quality__list">

				<li class="quality__item">
					<div class="quality__number">548</div>
					<div class="quality__text">projects completed</div>
				</li>

				<li class="quality__item">
					<div class="quality__number">1465</div>
					<div class="quality__text">WORKING HOURS</div>
				</li>

				<li class="quality__item">
					<div class="quality__number">612</div>
					<div class="quality__text">POSITIVE FEEDBACKS</div>
				</li>

				<li class="quality__item">
					<div class="quality__number">735</div>
					<div class="quality__text">HAPPY CLIENTS</div>
				</li>

			</ul><!-- quality__list -->
		</div><!-- quality -->
	</div><!-- quality -->

</template>

<script>
 
  export default {
   
  };

</script>

<style>
 
	.quality{
		padding-top: 100px;
		padding-bottom: 100px;

		background-color: #10c9c3;
	}

	.quality__list{
		display: flex;
		justify-content: space-between;
	}
	
	.quality__item{
		position: relative;

		padding-left: 65px;
	}

	.quality__item::before{
		content: '';
		position: absolute;
		left: 0;
		top: 3px;
 

		width: 40px;
		height: 40px;
		
		background-image: url('~assets/img/quality/1.png');
		background-repeat: no-repeat;
	}

	.quality__item:nth-child(2)::before{
		background-image: url('~assets/img/quality/2.png');
	}

	.quality__item:nth-child(3)::before{
		background-image: url('~assets/img/quality/3.png');
	}

	.quality__item:nth-child(4)::before{
		background-image: url('~assets/img/quality/4.png');
	}
			
	.quality__number{
		color: #ffffff;
		font-size: 18px;
		font-weight: 500;
		line-height: 1.2;
		text-transform: uppercase;
		letter-spacing: 0.54px;
	}

	.quality__text{
		color: #ffffff;
		font-size: 12px;
		font-weight: 500;
		line-height: 30px;
		text-transform: uppercase;
		letter-spacing: 1.2px;
	}	 

	@media (max-width: 987px){
		.quality{
			padding-top: 30px;
			padding-bottom: 30px;
		}

		.quality__list{
			 
			flex-wrap: wrap;
		}
		.quality__item{
			margin-bottom: 20px;

			flex-basis: 32%;
		}
		.quality__text{
			margin-top: 5px;

			line-height: 16px;
		}
	}
 
	@media (max-width: 791px){
		.quality__item{
			flex-basis: 40%;
		} 
	}

 
	@media (max-width: 400px){
		.quality__item{
			flex-basis: 100%;
		}
	}
</style>
