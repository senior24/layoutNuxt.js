<template>

 <div class="header">
    <div class="header__top  container">

      <div class="header__logo">
			<a href="#">  
				<img src="~/assets/img/logo.png" alt="logo">
			</a>
      </div>

      <nav>
        <ul class="header__menu">

          <li class="header__menu-item">
            <a class="header__menu-link" href="#">home</a>
          </li>

          <li class="header__menu-item">
            <a class="header__menu-link" href="#">about</a>
          </li>

          <li class="header__menu-item">
            <a class="header__menu-link" href="#">work</a>
          </li>

          <li class="header__menu-item">
            <a class="header__menu-link" href="#">process</a>
          </li>

          <li class="header__menu-item">
            <a class="header__menu-link" href="#">services</a>
          </li>

          <li class="header__menu-item">
            <a class="header__menu-link" href="#">testimonials</a>
          </li>

          <li class="header__menu-item">
            <a class="header__menu-link" href="#">contact</a>
          </li>

        </ul><!-- header__menu -->
      </nav>

    </div><!-- header__top -->
  
	<div class="container">

		<div class="header__intro-content">
			<h1 class="header__intro-title">
				We Design and Develop
			</h1>
			<p class="header__intro-desk">
				We are a new design studio based in USA. We have over 
				20 years of combined experience, and know a thing or two 
				about designing websites and mobile apps.
			</p>
			<a class="btn  header__btn" href="#">contact us</a>
		</div>
		
	</div><!-- header__intro -->

  </div><!-- header -->	

</template>

<script>
	export default {};
</script>

<style >
	.header{
		background-image: url('~assets/img/header-bg.jpg');
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;

		padding-bottom: 200px;
	}

	.header__top{
		padding-top: 40px;

		display: flex;
		justify-content: space-between;
	}

	.header__menu{
		display: flex;
	}

	.header__menu-item:not(:last-child){
		margin-right: 25px;
	}

	.header__menu-link{
		color: #191919;
		 
		font-size: 12px;
		font-weight: 500;
		line-height: 1;
		text-transform: uppercase;
		letter-spacing: 1.2px;
		
		transition: color .2s linear;
	}

	.header__menu-link:hover{
		color: #10c9c3;
	}

	.header__intro-title{
		color: #1d1d1d;
		font-size: 38px;
		font-weight: 500;
		line-height: 1.26;
		letter-spacing: 0.38px;
	}

	.header__intro-content{
		max-width: 470px;
		margin-top: 180px;

		margin-left: auto;
	}

	.header__intro-desk{
		margin-top: 30px;
		margin-bottom: 40px;

		color: #787878;
		font-size: 18px;
		font-weight: 400;
		line-height: 1.5;
		letter-spacing: 0.09px;
	}

	@media (max-width: 916px){
		.header__intro-content{
			margin-left: 0;
			margin-right: auto;
		}
	}

	@media(max-width: 742px){
		.header{
			padding-top: 30px;
			padding-bottom: 30px;
		}
		.header__top{
			padding-top: 0;
		}
		.header__intro-content{
			margin-top: 50px;
		}
		.header__menu{
			display: none;
		}
	}
</style>