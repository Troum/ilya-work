<template>
  <b-container>
    <b-row class="head">
      <b-col cols="10" class="justify-content-center mx-auto">
        <img src="../assets/logo.svg" alt="Ильюша" class="headerpic pb-2">
        <p class="text-center headertitle p-3">Aliquam</p>
          <p class="headertext lg-pb-5 xl-pb-5">Just another free, fully responsive site template built by @ajlkn for HTML5 UP.</p>
      </b-col>
    </b-row>

</b-container>

</template>

<script>
export default {

}
</script>

<style>
.head {
  color:#fff;
  font-family: 'Source Sans Pro', sans-serif;
}

@keyframes show{
	 0%{
		 opacity:0;
	 }

	 100% {
		 opacity:1;
	 }
}


.headerpic{
  border-radius: 200px;
  margin-top: 15%;
  max-width: 100px;
  max-height: 100px;

  opacity:0; /*Элемент полностью прозрачный (невидимый)*/
	transition: 1s; /*Скорость перехода состояния элемента*/
	animation: show 3s 1; /* Указываем название анимации, её время и количество повторов*/
  animation-fill-mode: forwards; /* Чтобы элемент оставался в конечном состоянии анимации */
  animation-delay: 0.3s; /* Задержка перед началом */
}

.headertitle
{font-size: 2.5em!important;
font-weight: 300!important;

opacity:0; /*Элемент полностью прозрачный (невидимый)*/
transition: 1s; /*Скорость перехода состояния элемента*/
animation: show 3s 1; /* Указываем название анимации, её время и количество повторов*/
animation-fill-mode: forwards; /* Чтобы элемент оставался в конечном состоянии анимации */
animation-delay: 1.3s; /* Задержка перед началом */
}

.headertext {
  opacity: 0.65;
  opacity:0; /*Элемент полностью прозрачный (невидимый)*/
  transition: 1s; /*Скорость перехода состояния элемента*/
  animation: show 3s 1; /* Указываем название анимации, её время и количество повторов*/
  animation-fill-mode: forwards; /* Чтобы элемент оставался в конечном состоянии анимации */
  animation-delay: 1.8s; /* Задержка перед началом */
}

</style>
