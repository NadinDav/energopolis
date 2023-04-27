<template>
  <header>
  <div class="row">
    <div class="center-block">
    <div class="text-box">
      <strong>ЭНЕРГОПОЛИС</strong>
      <div id="p">С нами всегда светло</div>
    </div>
  </div>
</div>         
  </header>
</template>

<script>
import { directive as motion } from "@vueuse/motion";

export default {};
</script>

<style>
.center-block {
background-image: url(file:///C:/Users/user/Documents/vuejs-tailwind-portfolio-main/src/assets/1.jpg);
background-position: center;
background-size: cover;
height: 100%;
padding-bottom: 500px;
}
.text-box {
    font-family: 'Exo 2', sans-serif;   
    font-size: 63px;
    font-weight: 200;
    line-height: 56px;
    text-align: start;
    justify-content: center;
    padding-top: 100px;
    color: rgb(253, 253, 253);
}
strong {
    text-align: center;
    padding-left: 25px;
        text-shadow: 
/*несколько слоев белого*/
0 0 0.10em rgb(146, 144, 144),
0 0 0.11em rgb(146, 144, 144),
0 0 0.12em rgb(146, 144, 144),
/*несколько слоев цвета*/
0 0 0.10em #f6db13,
0 0 0.11em #f6db13,
0 0 0.12em #f6db13,
0 0 0.13em #f6db13,
0 0 0.14em #f6db13;
}

#p {
padding-top: 100px;
padding-left: 25px;
    text-shadow: 
/*несколько слоев белого*/
0 0 0.10em rgb(85, 83, 83),
0 0 0.11em rgb(85, 83, 83),
0 0 0.12em rgb(85, 83, 83),
/*несколько слоев цвета*/
0 0 0.10em #f6db13,
0 0 0.11em #f6db13,
0 0 0.12em #f6db13,
0 0 0.13em #f6db13,
0 0 0.14em #f6db13;
}
</style>
