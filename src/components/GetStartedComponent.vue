<template>
  <b-container id="yak4">
    <b-row class="FirstComponent-block mx-auto">
      <b-col cols="12">
        <h2 class="text-center pt-5">Congue imperdiet</h2>
          <p class="">Donec imperdiet consequat consequat. Suspendisse feugiat congue
posuere. Nulla massa urna, fermentum eget quam aliquet.</p>
      </b-col>
    </b-row>
  <b-row id="last-back-blok" class="FirstComponent-block mx-auto FC-hr">
    <b-col cols="12 pb-5">
      <b-button variant="primary" href="#" class="getstartbotton m-2">Get Started</b-button>
      <b-button href="#" class="m-2">Learn more</b-button>
    </b-col>
  </b-row>
</b-container>

</template>

<script>
export default {

}
</script>

<style>

.FirstComponent-block {
color: #636363;
position: relative;
width: 64em;
max-width: calc(100% - 4em);
padding: 1em;
background-color: #f7f7f7;
font-family: 'Source Sans Pro', sans-serif;
}
.getstartbotton {
  background-color: #8cc9f0!important;
  box-shadow: inset 0 0 0 1px #8cc9f0;
  color: #fff!important;
  border-radius: 8px!important;
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
  border-color:transparent!important;
  }

.getstartbotton:hover {
  opacity: 0.8;
  transition: opacity 0.4s ease-in-out;
}

@media (max-width: 720px) {
.getstartbotton {margin-bottom: 5%!important;
  }
}
#last-back-blok {
     border-bottom-left-radius:5px;
     border-bottom-right-radius: 5px;
}

</style>
