<template>
  <b-container id="yak2" class="scroller">
    <b-row class="FirstComponent-block mx-auto">
      <b-col cols="12">
        <h2 class="text-center pt-5">Magna veroeros</h2>
      </b-col>
    </b-row>
  <b-row class="FirstComponent-block mx-auto p-4">
    <b-col sm="12" md="12" lg="4 "xl="4">
      <font-awesome-icon icon="code" class="first-component-pic" style="color: #efa8b0;"></font-awesome-icon>
        <h3>Ipsum consequat</h3>
      <p>Sed lorem amet ipsum dolor et amet nullam consequat a feugiat consequat tempus veroeros sed consequat.</p>
    </b-col>

    <b-col sm="12" md="12" lg="4 "xl="4">
      <span>
            <font-awesome-icon icon="copy" class="first-component-pic" style="color: #a89cc8;"></font-awesome-icon>
      </span>
        <h3>Amed sed feugiat</h3>
      <p>Sed lorem amet ipsum dolor et amet nullam consequat a feugiat consequat tempus veroeros sed consequat.</p>
    </b-col>

    <b-col sm="12" md="12" lg="4 "xl="4">
      <font-awesome-icon icon="gem" class="first-component-pic" style="color: #8cc9f0;"></font-awesome-icon>
        <h3>Dolor nullam</h3>
      <p>Sed lorem amet ipsum dolor et amet nullam consequat a feugiat consequat tempus veroeros sed consequat.</p>
    </b-col>
  </b-row>

  <b-row class="FirstComponent-block mx-auto FC-hr pb-5">
    <b-col cols="12">
      <b-button href="#">Learn more</b-button>
    </b-col>
  </b-row>
</b-container>

</template>

<script>
export default {

}
</script>

<style>
/* .FC-hr {border-bottom: solid 1px #dddddd;} */

.FirstComponent-block {
color: #636363;
position: relative;
width: 64em;
max-width: calc(100% - 4em);
background-color: #f7f7f7;
font-family: 'Source Sans Pro', sans-serif;
font-weight: 300;
}

.first-component-pic {
border: 10px double #dddddd;
border-radius: 150px 150px / 150px 150px;
padding: 30px;
height: 180px;
width: 180px!important;
margin: 0 0 1em 0;
}

html {
  scroll-behavior: smooth;
}

</style>
