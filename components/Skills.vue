<template>

	<div class='skills'>
		<div class="skills__content  container">
			<h2 class="skills__title">
				Professional Skills
			</h2>

			<div class="skills__progress">
				<ul class="skills__progress-items">

					<li class="skills__progress-item">
						<p class="skills__progress-title">UI/UX Design    75%</p>
						<div class="skills__progress-bar">
							<div class="skills__progress-content  bar--1"></div>
						</div>
					</li>
 
					<li class="skills__progress-item">
						<p class="skills__progress-title">web development    90%</p>
						<div class="skills__progress-bar">
							<div class="skills__progress-content  bar--2"></div>
						</div>
					</li>

					<li class="skills__progress-item">
						<p class="skills__progress-title">marketing    65%</p>
						<div class="skills__progress-bar">
							<div class="skills__progress-content  bar--3"></div>
						</div>
					</li>

				</ul><!-- skills__progress-items -->
			</div><!-- skills__progress -->
		</div><!-- skills__content -->
	</div><!-- skills -->
	
</template>

<script>
	export default {
		
	}
</script>
   
<style >
	.skills{
		position: relative;
		
		background-color: #f8f9f9;
	}

	.skills::before{
		content: "";
		display: block;
		width: 50%;
	 	height: 100%;

		position: absolute;
		right: 0;

		background-color: #e9e9e9;

		background-image: url('~assets/img/skills/boy.jpg');
		background-repeat: no-repeat;
		background-size: cover;
		background-position: center;
	}

	.skills::before{
		content: "";

		display: block;
		width: 50%;
	 	height: 100%;

		position: absolute;
		right: 0;

		background-color: #e9e9e9;

		background-image: url('~assets/img/skills/boy.jpg');
		background-repeat: no-repeat;
		background-size: cover;
		background-position: center;
	}
	
	.skills__content{
		padding-top: 150px;
		padding-bottom: 150px;
	}

	.skills__title{
		color: #171717;
		font-size: 30px;
		font-weight: 500;
		line-height: 1.4;
		letter-spacing: 0.3px;
	}

	.skills__progress-title{
		color: #000000;
		font-size: 12px;
		font-weight: 500;
		line-height: 30px;
		text-transform: uppercase;
		letter-spacing: 1.2px;
	}

	.skills__progress{
		margin-top: 40px;
	}

	.skills__progress-item{
		margin-bottom: 30px;
	}

	.skills__progress-title{
		margin-bottom: 10px;
	}

	.skills__progress-bar{
		width: 500px;
		height: 3px;

		background-color: #d8d8d8;
	}

	.skills__progress-content{
		width: 75%;
		height: 100%;

		background-color: #10c9c3;
	}

	.skills__progress-content.bar--1{
		width: 75%;
	}

	.skills__progress-content.bar--2{
		width: 90%;
	}

	.skills__progress-content.bar--3{
		width: 65%;
	}

	@media (max-width: 1150px){
		.skills__content {
			padding-top: 30px;
			padding-bottom: 30px;
		}

		.skills__title{
			text-align: center;
		}

		.skills__progress-title{
			text-align: center;
		}

		.skills__progress-bar {
			width: 100%;
		}

		.skills:before{
			display: none;
		}
	}
	
	 

</style>