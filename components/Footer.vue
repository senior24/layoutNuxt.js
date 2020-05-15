<template>
	<div class="footer">
		<div class="footer__row  container">
			<div class="footer__desing">
				<h3 class="footer__title">Piroll Design, Inc.</h3>
				<p class="footer__text">© 2017 Piroll. All rights reserved.
					Designed by robirurk.</p>
			</div>
			<div class="footer__contacts">
				<a class="footer__email" href="mailto:hello@pirolltheme.com">hello@pirolltheme.com</a>	 
				<a class="footer__phone" href="tel:+44987065908">+44 987 065 908 </a>
			</div>
			<div class="footer__lists">

				<ul class="footer__nav">
					<li><a class="footer__nav-link" href="#">Projects</a></li>
					<li><a class="footer__nav-link" href="#">About</a></li>
					<li><a class="footer__nav-link" href="#">Services</a></li>
					<li><a class="footer__nav-link" href="#">Carreer</a></li>
				</ul>

				<ul class="footer__nav">
					<li><a class="footer__nav-link" href="#">News</a></li>
					<li><a class="footer__nav-link" href="#">Events</a></li>
					<li><a class="footer__nav-link" href="#">Contact</a></li>
					<li><a class="footer__nav-link" href="#">Legals</a></li>
				</ul>

				<ul class="footer__nav">
					<li><a class="footer__nav-link" href="#">Facebook</a></li>
					<li><a class="footer__nav-link" href="#">Twitter</a></li>
					<li><a class="footer__nav-link" href="#">Instagram</a></li>
					<li><a class="footer__nav-link" href="#">Dribbble</a></li>
				</ul>

			</div><!-- footer__lists -->
		</div><!-- footer__row -->
	</div><!-- footer -->
</template>
 

<script>
export default {
	
}
</script>

<style>
	.footer{
		padding-top: 100px;
		padding-bottom: 100px;

		background-color: #141414;
	}

	.footer__row{
		display: flex;
		justify-content: space-between;
		align-content: flex-start;
	}

	.footer__title{
		margin-bottom: 25px;

		color: #ffffff;
		font-size: 18px;
		font-weight: 500;
		line-height: 1.2;
		letter-spacing: 0.18px;
	}

	.footer__text{
		max-width: 250px;

		color: #bcbcbc;
		font-size: 15px;
		font-weight: 400;
		line-height: 1.6;
		letter-spacing: 0.07px;
	}

	.footer__email{
		display: block;
	}

	.footer__email, .footer__phone {
		color: #bcbcbc;
		font-size: 15px;
		font-weight: 400;
		line-height: 1.6;
	}

	.footer__email:hover,
	.footer__phone:hover {
		color: #10c9c3;
	}
	.footer__lists{
		display: flex;
		flex-wrap: wrap;
	}

	.footer__nav-link{
		color: #bcbcbc;
		font-size: 15px;
		font-weight: 400;
		line-height: 1.6;
		letter-spacing: 0.07px;
	}

	.footer__nav-link:hover{
		color: #10c9c3;
	}

	.footer__nav:nth-child(2){
		margin-left: 50px;
	}

	.footer__nav:nth-child(3){
		margin-left: 130px;
	}
	
	@media (max-width: 966px){
		.footer{
			padding-top: 30px;
			padding-bottom: 30px;
		}
		.footer__nav:nth-child(3){
			margin-left: 50px;
		}
	}

	@media(max-width: 881px){
		.footer__contacts{
			margin-top: 10px;
		}
		.footer__row{
			flex-direction: column;
		}
		.footer__lists{
			margin-top: 40px;
		}
	}

	@media (max-width: 385px){
		.footer__nav{
			flex-basis: 100%;

			margin-bottom: 20px;
		}
		.footer__nav:nth-child(3){
			margin-left: 0;
		}
		.footer__nav:nth-child(2){
			margin-left: 0;
		}
	}
</style>