<template>
  <div class="bg-blue-50 page-section pt-5 -mb-5">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 py-3 wow zoomIn">
          <div class="img-place text-center hidden lg:flex">
            <lottie-player
              src="https://assets9.lottiefiles.com/packages/lf20_YR05grvKPF.json"
              background="transparent"
              speed="1"
              style="max-width: 500px; max-height: 500px"
              autoplay></lottie-player>
          </div>
        </div>

        <div class="col-lg-6 p-4">
          <h2 class="title-section text-2xl">
            Все о нас
          </h2>
          <div class="divider"></div>

          <div>
            <p>
             ООО "Энергополис" - организация, основанная в 2018 году в г.Минске. 
             С момента нашего основания география наших работ и поставок значительно увеличилась, и с тех пор расширила свои горизонты
             по всей Республике Беларусь.
            </p>
          </div>

          <div>
            <p>
             Наша компания не останавливается на достигнутом и регулярно заключает выгодные контракты. 
             При производстве работ мы руководствуемся нормативными актами, а также действующим законодательством 
             Республики Беларусь. 
            </p>
          </div>

          <div>
            <p class="hidden lg:flex">
             Наша цель - приносить пользу обществу, расширяться, улучшая качество и скорость выполнения работ.
            </p>
          </div>
        </div>
      </div>
    </div>
    <!-- .container -->
  </div>
  <!-- .page-section -->

  <div class="bg-green-50 page-section">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 p-4 -mt-9 lg:mt-0">
          <h2 class="title-section text-2xl">
            Наши достижения
          </h2>
          <div class="divider"></div>
          <p class="mb-4">
           За тот период, что наша организация осуществляет деятельность, мы
           успели поработать с такими заказчиками как ПО "Белоруснефть". Стараниями наших специалистов
           были установлены зарядные станции для электромобилей, благодаря чему жизнь многих обладателей
           автомобилей с электродвигателями стала проще и комфортнее.
          </p>
          <p class="mb-4">
            Также наша организация выполняет капитальные ремонты жилого фонда. Полный комплекс работ от наших 
            профессионалов дает "вторую" жизнь жилым домам с утерянными потребительскими свойствами.
          </p>
          <p class="mb-5 hidden lg:flex">
            ООО "Энергополис" принимает участие и на объектах нового строительства. Качество наших работ высоко оценены крупными
            застройщиками Республики Беларусь.
          </p>
        </div>
        <div class="col-lg-6 py-3 wow zoomIn">
          <div class="img-place text-center">
            <lottie-player
              src="https://assets8.lottiefiles.com/packages/lf20_bP3BLu.json"
              background="transparent"
              speed="0.5"
              style="max-width: 550px; max-height: 550px"
              loop
              autoplay></lottie-player>
          </div>
        </div>
      </div>
    </div>
    <!-- .container -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      scrollPosition: 0,
    };
  },

  methods: {
    handleScroll(e) {
      this.scrollPosition = e.target.scrollTop;

      if (this.scrollPosition > 100) {
        console.log("UP");
      } else {
        console.log("DOWN");
      }
    },
  },
};
</script>

<style></style>
