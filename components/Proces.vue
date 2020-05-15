<template>
	<div  class="proces  container">
		<h2 class="headline">
			Our Work Process
		</h2>
		<p class="headline__text">
			Was years it seasons was there form he in in them together over that, 
			third sixth gathered female creeping bearing behold years.
		</p>

		<div class="proces__video">
			<a class="proces__video-link" href="#"></a>
		</div>
	</div><!-- proces -->
</template>

<script>
export default {
	
}
</script>

<style >
	.proces{
		padding-top: 100px;
		padding-bottom: 100px;
	}

	.proces__video{
		margin-top: 50px;

		display: flex;
		justify-content: center;
		align-items: center;

		height: 571px;

		background-color: #e9e9e9;
		background-image: url('../assets/img/proces/bg.jpg');
		background-repeat: no-repeat;
		background-size: cover;
		background-position: center;
	}

	.proces__video-link{
		position: relative;
		width: 85px;
		height: 85px;

		transition: background-color .2s linear;

		border-radius: 50%;
		background-color: #10c9c3;
	}

	.proces__video-link::before{
		content: "";

		position: absolute;
		left: 57%;
		top: 50%;

		transition: border .2s linear;

		transform: translate3d(-50%, -50%, 0);
	
		border: 10px solid transparent; border-left: 10px solid #fff;
	}

	.proces__video-link:hover{
		background-color: yellow;
	}

	.proces__video-link:hover::before{
		border: 10px solid transparent; border-left: 10px solid #000;
	}

	@media(max-width: 940px){
		.proces{
			padding-top: 30px;
			padding-bottom: 30px;
		}
 
		.proces__video{
			max-width: 100%;
		}
	}
	
	@media (max-width: 740px){
		.proces__video{
			height: 258px;
		}
	}
</style>