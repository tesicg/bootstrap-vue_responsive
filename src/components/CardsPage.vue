<template>
  <b-container>
    <b-row>
      <b-col>
        <h1><strong>LICOTA® — ПРОФЕССИОНАЛЬНЫЙ ИНСТРУМЕНТ ВЫСШЕГО КЛАССА ДЛЯ АВТОСЕРВИСОВ И ПРОМЫШЛЕННЫХ ПРЕДПРИЯТИЙ</strong></h1>
      </b-col>
    </b-row>
    <b-row class="mt-1">
      <b-col class="info-block__column" :cols="12" :md="6" :lg="4">
        <b-card class="info-block__card--no-border h-100" :img-src="require('../assets/info-item-1.png')" img-alt="Image" img-top="img-top">
          <b-card-text>Имеет TUV сертификат ISO 9001:2008. Соответствует требованиям GS, CE, EAC и превышает нормы DIN и ГОСТ</b-card-text>
        </b-card>
      </b-col>
      <b-col class="info-block__column" :cols="12" :md="6" :lg="4">
        <b-card class="info-block__card--no-border h-100" :img-src="require('../assets/info-item-2.png')" img-alt="Image" img-top="img-top">
          <b-card-text>Один из ведущих производителей инструмента в мире с трехуровневым контролем качества</b-card-text>
        </b-card>
      </b-col>
      <b-col class="info-block__column" :cols="12" :md="6" :lg="4">
        <b-card class="info-block__card--no-border h-100" :img-src="require('../assets/info-item-3.png')" img-alt="Image" img-top="img-top">
          <b-card-text>Инструмент адаптирован к российским условиям и имеет пожизненную гарантию на брак изготовителя</b-card-text>
        </b-card>
      </b-col>
      <b-col class="info-block__column" :cols="12" :md="6" :lg="4">
        <b-card class="info-block__card--no-border h-100" :img-src="require('../assets/info-item-4.png')" img-alt="Image" img-top="img-top">
          <b-card-text>Наши клиенты из автомобильного сегмента, которые выбрали Licota®</b-card-text>
        </b-card>
      </b-col>
      <b-col class="info-block__column" :cols="12" :md="6" :lg="4">
        <b-card class="info-block__card--no-border h-100" :img-src="require('../assets/info-item-5.png')" img-alt="Image" img-top="img-top">
          <b-card-text>Эти промышленные предприятия уверенно работают с Licota®</b-card-text>
        </b-card>
      </b-col>
      <b-col class="info-block__column" :cols="12" :md="6" :lg="4">
        <b-card class="info-block__card--no-border h-100" :img-src="require('../assets/info-item-6.png')" img-alt="Image" img-top="img-top">
          <b-card-text>Дилеры Licota® по всей России, от Калининграда до Камчатки</b-card-text>
        </b-card>
      </b-col>
    </b-row>
    <b-row class="mt-1">
      <b-col class="info-block__column" :cols="12" :md="4">
        <b-button class="btn btn-lg btn-block info-block__button">О ПРОИЗВОДИТЕЛЕ</b-button>
      </b-col>
      <b-col class="info-block__column" :cols="12" :md="4">
        <b-button class="btn btn-lg btn-block info-block__middle-button">КАТАЛОГ ТОВАРОВ</b-button>
      </b-col>
      <b-col class="info-block__column" :cols="12" :md="4">
        <b-button class="btn btn-lg btn-block info-block__button">ГДЕ КУПИТЬ?</b-button>
      </b-col>
    </b-row>
  </b-container>
</template>

<style>
.info-block {
  font-size: 16px;
  text-align: center;
}
.info-block__column {
  padding: 10px;
}
.info-block__card--no-border {
  border: none;
}
.info-block__button {
  background-color: #eee;
  background-image: -webkit-linear-gradient(bottom, #ccc 0%, #eee 100%);
  border: 1px solid #cccccc;
  color: black;
  font-size: 18px;
  font-weight: bold;
  line-height: 2;
  text-shadow: 0.5px 0.866px 0 white;
}
.info-block__middle-button {
  background-color: #007dfa;
  background-image: -webkit-linear-gradient(bottom, #00468c 0%, #007dfa 100%);
  border: 1px solid rgb(0, 70, 140);
  color: white;
  font-size: 18px;
  font-weight: bold;
  line-height: 2;
  text-shadow: 0.5px 0.866px 0 rgb(0, 30, 60);
}
</style>
