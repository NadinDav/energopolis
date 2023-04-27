<template>
  <Navbar />

  <div class="">
    <div class="hidden lg:block container">
      <div
        class="page-banner1 bg-grey-50">
        <div class="row justify-content-center align-items-center h-10">
          <div class="col-md-9">
            <nav aria-label="Breadcrumb">
              <ul class="breadcrumb justify-content-center py-0 bg-transparent">
                <li class="breadcrumb-item">
                  <router-link to="/">Главная</router-link>
                </li>
                <li class="breadcrumb-item active">Наши работы</li>
              </ul>
            </nav>
            <div class="bg-grey-50">
          <div
          class="flex flex-col lg:flex-row items-center justify-evenly space-x-15 h-full text-left py-5">
          <div
          class="bg-white rounded-xl drop-shadow-md mt-3 col-lg-4 ml-2 py-1 px-5 h-96 hover:-mt-3 cursor-default hover:shadow-lg hover:shadow-green-100">
          <lord-icon
          src="https://cdn.lordicon.com/sbgmyyba.json"
          trigger="hover"
          colors="primary:#4be1ec,secondary:#cb5eee"
          style="width:150px;height:150px">
          </lord-icon>

          <div class="text-2xl font-semibold text-green-800 mt-4 pl-1">
            Новое строительство
          </div>
          <p class="text-left text-base lg:text-sm leading-relaxed">
            Занимаемся возведением жилых домов.
          </p>
        </div>

        <div
          class="bg-white rounded-xl mt-3 drop-shadow-md col-lg-4 ml-2 py-1 px-5 h-96 hover:-mt-3 cursor-default hover:shadow-lg hover:shadow-green-100">
          <lord-icon
          src="https://cdn.lordicon.com/kxoxiwrf.json"
          trigger="hover"
          colors="primary:#4be1ec,secondary:#cb5eee"
          style="width:150px;height:150px">
          </lord-icon>
          <div class="text-2xl font-semibold text-green-800 mt-4 pl-1">
            Капитальные ремонты
          </div>
          <p class="text-left text-base lg:text-sm leading-relaxed">
            Реконструируем и ремонтируем объекты жилого фонда.
          </p>
        </div>

        <div
          class="bg-white rounded-xl drop-shadow-md mt-3 col-lg-4 ml-2 py-1 px-5 h-96 hover:-mt-3 cursor-default hover:shadow-lg hover:shadow-green-100">
          <lord-icon
          src="https://cdn.lordicon.com/wuziebcn.json"
          trigger="hover"
          colors="primary:#4be1ec,secondary:#cb5eee"
          style="width:150px;height:150px">
          </lord-icon>
          <div class="text-2xl font-semibold text-green-800 mt-4 pl-1">
            Строительство зарядных станций
          </div>
          <p class="text-left text-base lg:text-sm leading-relaxed">
            Устанавливаем зарядные станции для электромобилей.
          </p>
        </div>
        </div>
        </div>
        </div>
        </div>
      </div>
      </div>
    </div>
    <Footer />
 
</template>

<script>
import Navbar from "../components/Navbar";
import Footer from "../components/Footer";

export default {
  props: {
    blog: Array,
  },

  components: { Navbar, Footer },
};
</script>

<style></style>
