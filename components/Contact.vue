<template>
	<div  class="contact">

		<div class="container">
			<h2 class="headline">
				Our Work Process
			</h2>
			<p class="headline__text">
				Was years it seasons was there form he in in them together over that, 
				third sixth gathered female creeping bearing behold years.
			</p>

 
			<form class="contact__form">
				<div class="contanct__row">
					<input class="contact__input" type="text"  placeholder="Your Name">
					<input class="contact__input" type="text"  placeholder="Your Email">
				</div>
				<input class="contact__input-title" type="text"  placeholder="Your Title">
				<textarea class="contact__input-textarea"  placeholder="Your Comment"></textarea>

				<button class="btn  contact__form">send message</button>
			</form>
		</div>
	</div>
</template>

<script>
export default {
	
}
</script>

<style >
	.contact{
		padding-top: 100px;
		padding-bottom: 100px;

		background-color: #f5f5f5;
	}

	.contact__form{
		margin-top: 50px;
		max-width: 670px;
		margin-left: auto;
		margin-right: auto;

		text-align: center;
	}

	.contanct__row{
		display: flex;
		justify-content: space-between;
		flex-wrap: wrap;
	}

	 .contact__input{
		padding-left: 20px;
		padding-right: 20px;

		 
		width: 320px;
		height: 48px;
		background-color: #ffffff;

		border: none;
		
		transition: all .2s linear;
	}
	
	.contact__input-title{
		padding-left: 20px;
		padding-right: 20px;

		margin-top: 30px;
		margin-bottom: 30px;

		border: none;
		
		width: 100%;
		height: 48px;
		background-color: #ffffff;

		transition: all .2s linear;
	}

	.contact__input-textarea{
		padding: 20px;

		border: none;

		width: 100%;
		height: 170px;

		transition: all .2s linear;


		resize: vertical;
	}

	.contact__input:hover,
	.contact__input-title:hover,
	.contact__input-textarea:hover{
		box-shadow: 0 0 10px  #000;
	}

	.contact__input:focus,
	.contact__input-title:focus,
	.contact__input-textarea:focus{
		outline: none;
		box-shadow: 0 0 10px #000;
	}

	.contact__form{
		cursor: pointer;
		border: none;
	}

	@media (max-width: 940px){
		.contact{
			padding-top: 30px;
			padding-bottom: 30px;
		}
	}

	@media (max-width: 692px){
		.contact__input{
			width: 100%;
			margin-top: 30px;
		}
		.contact__input:nth-child(1){
			margin-top: 0;
		}
		.contact__form{
			margin-top: 0;
		}
		.contact__form{
			margin-top: 30px;
		}
	}
	
</style>