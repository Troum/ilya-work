<template>
  <b-container id="yak1">
  <b-row class="intro-block mx-auto FC-hr">
    <b-col class="text-sm-center text-md-center text-lg-left text-xl-left intro-text" sm="12" md="12" lg="8" xl="8">
  <h1>Ipsum sed adipiscing</h1>
    <p class="pb-4">Sed lorem ipsum dolor sit amet nullam consequat feugiat consequat magna adipiscing magna etiam amet veroeros. Lorem ipsum dolor tempus sit cursus. Tempus nisl et nullam lorem ipsum dolor sit amet aliquam.</p>
  <b-button href="#">Learn more</b-button>
    </b-col>
    <b-col sm="12" md="12" lg="4" xl="4">
      <img src="../assets/pic01.jpg" alt="" class="intro-pic">
    </b-col>
  </b-row>
</b-container>

</template>

<script>
import NavBarMenu from './NavBarMenu.vue'

export default {
}
</script>

<style>
.intro-block {
color: #636363;
position: relative;
width: 64em;
max-width: calc(100% - 4em);
padding: 1em;
background-color: #f7f7f7;
font-family: 'Source Sans Pro', sans-serif;
padding: 7%;
font-weight: 300;
}

h1,h2, h3,h4{font-size: 1.5em!important;
   font-weight: 300!important;}

h1:after {
display: block;
content: '';
width: 3.25em;
height: 2px;
margin: 0.7em 0 1em 0;
border-radius: 2px;
background-image: linear-gradient(90deg, #efa8b0, #a89cc8, #8cc9f0);
}

h2:after {
display: block;
content: '';
width: 3.25em;
height: 2px;
margin: 0.7em 0 1em 0;
border-radius: 2px;
background-image: linear-gradient(90deg, #efa8b0, #a89cc8, #8cc9f0);
margin-left: auto;
margin-right: auto;
}

.btn-secondary {
background-color: #f7f7f7!important;
box-shadow: inset 0 0 0 1px #dddddd;
color: #636363 !important;
border-radius: 8px!important;
border: 0;
cursor: pointer;
display: inline-block;
font-weight: 300;
height: 2.75em;
line-height: 2.75em;
min-width: 9.25em;
padding: 0 1.5em;
text-align: center;
text-decoration: none;
white-space: nowrap;
border-color: #dddddd!important;

opacity:0; /*Элемент полностью прозрачный (невидимый)*/
transition: 1s; /*Скорость перехода состояния элемента*/
animation: show 3s 1; /* Указываем название анимации, её время и количество повторов*/
animation-fill-mode: forwards; /* Чтобы элемент оставался в конечном состоянии анимации */
animation-delay: 3s; /* Задержка перед началом */
}
.btn-secondary:hover{
  background-color: rgba(222, 222, 222, 0.25)!important;
  transition: background-color 0.4s ease-in-out;
}

.intro-pic {
  border: solid 1px;
  border-color: #dddddd;
  border-radius: 100%;
  padding: 7%;
  width: 16em;
  height: 16em;
  order: 1;

  opacity:0; /*Элемент полностью прозрачный (невидимый)*/
  transition: 1s; /*Скорость перехода состояния элемента*/
  animation: show 3s 1; /* Указываем название анимации, её время и количество повторов*/
  animation-fill-mode: forwards; /* Чтобы элемент оставался в конечном состоянии анимации */
  animation-delay: 3s; /* Задержка перед началом */
}

@media  (max-width: 992px) {
  .intro-text {
    text-align: center!important;
    order: 5;}

    .intro-pic {
      width: 12em;
      height: 12em;
      margin-bottom: 8%;
    }
    h1:after {
      margin-left: auto;
      margin-right: auto;
      }
}

</style>
