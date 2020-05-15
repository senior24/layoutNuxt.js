<template>
  <div>
    <app-header/>
    <nuxt />
    <app-footer/>
  </div>
</template>

<script>
  import Header from "~/components/Header.vue";
  import Footer from "~/components/Footer.vue";

  export default {
    components: {
      appHeader: Header,
      appFooter: Footer
    }
  };
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');

  html {
    box-sizing: border-box;
  }

  body{
    font-family: 'Montserrat', 'Arial', sans-serif;
    font-weight: 500;
  }

  *,
  *:before,
  *:after {
    box-sizing: border-box;
    margin: 0;
  }

  ul, li{
    padding: 0;
  
    list-style: none;
  }

  .container {
    max-width: 1200px;
    padding-left: 15px;
    padding-right: 15px;
    margin-left: auto;
    margin-right: auto;
  }


  /* default styles global */

  a {
    display: inline-block;

    text-decoration: none;
  }

  .btn{
      padding: 18px 45px;

      color: #ffffff;
      font-size: 12px;
      font-weight: 500;
      text-transform: uppercase;
      letter-spacing: 1.2px;

      background-color: #10c9c3;

      transition: background-color .2s linear;
  }

  .btn:hover{
    background-color: #29a6a2;
  }

  .headline{
    text-align: center;

    color: #191919;
    font-size: 30px;
    font-weight: 500;
    line-height: 2;
    letter-spacing: 0.3px;
  }

  .headline__text{
    max-width: 620px;
    margin-left: auto;
    margin-right: auto;

    text-align: center;
    color: #787878;
    font-size: 16px;
    font-weight: 400;
    line-height: 1.5;
    letter-spacing: 0.08px;
  }

  @media(max-width: 940px){
    .headline{
      margin-bottom: 5px;

      line-height: 1.2;
    }
  }

</style>
