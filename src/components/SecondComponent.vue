<template>
  <b-container id="yak3">
    <b-row class="FirstComponent-block justify-content-center mx-auto">
      <b-col cols="10" lg="6" xl="6">
        <h2 class="text-center pt-5">Ipsum consequat</h2>
          <p class="">Donec imperdiet consequat consequat. Suspendisse feugiat congue
posuere. Nulla massa urna, fermentum eget quam aliquet.</p>
      </b-col>
    </b-row>

    <b-row class="mx-auto">
    <b-col cols="12 p-0">
        <b-row class="FirstComponent-block justify-content-center mx-auto">
            <b-col sm="10" md="10" lg="2" xl="2" v-for="(item, i) in items" :key="i" class="statistic"
            :style="{'background-color': item.background,}">
              <div class="p-4 text-white">
                <font-awesome-icon :icon="item.icon" class="StatItemIcon"></font-awesome-icon>
                <br>
                <span class="StatItemMessage">{{item.message}}</span>
                <br>
                <strong>{{ item.title }}</strong>
              </div>
            </b-col>
         </b-row>
       </b-col>
      </b-row>

  <b-row class="FirstComponent-block mx-auto p-0">
      <b-col cols="10" class="justify-content-center mx-auto">
        <p class="text-justify content">Nam elementum nisl et mi a commodo porttitor. Morbi sit amet nisl eu arcu faucibus hendrerit vel a risus. Nam a orci mi, elementum ac arcu sit amet, fermentum pellentesque et purus. Integer maximus varius lorem, sed convallis diam accumsan sed. Etiam porttitor placerat sapien, sed eleifend a enim pulvinar faucibus
          semper quis ut arcu. Ut non nisl a mollis est efficitur vestibulum. Integer eget purus nec nulla mattis et accumsan ut magna libero. Morbi auctor iaculis porttitor. Sed ut magna ac risus et hendrerit scelerisque. Praesent eleifend lacus in lectus aliquam porta. Cras eu ornare dui curabitur lacinia. </p>
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
    data() {
      return {
        items: [
          {
            message:'2120',
            title: 'Etiam',
            icon: 'code-branch',
            background: '#efa8b0'
          },
          {
            message:'8192',
            title: 'Magna',
            icon: 'folder-open',
            background: '#c79cc8'
          },
          {
            message:'2048',
            title: 'Tempus',
            icon: 'signal',
            background: '#a89cc8'
          },
          {
            message:'4096',
            title: 'Aliquam',
            icon: 'laptop',
            background: '#9bb2e1'
          },
          {
            message:'1024',
            title: 'Nullam',
            icon: 'gem',
            background: '#8cc9f0'
          },
        ]
      }

    }
}
</script>

<style>
.FC-hr {border-bottom: solid 1px #dddddd;}

.StatItemIcon {
font-size: 30pt;
}
.StatItemMessage {
  font-size: 24pt;
}

.content {
columns: 18em 2;
column-gap: 2em;
}

.FirstComponent-block {
color: #636363;
position: relative;
width: 64em;
max-width: calc(100% - 4em);
padding: 1em;
background-color: #f7f7f7;
font-family: 'Source Sans Pro', sans-serif;
}

.statistic:hover {
  box-shadow: 1px 1px 5px 1px #d3d3d3;
}


@media (min-width:721px) {
.statistic:first-child {
  border-top-left-radius: 5px;
  border-bottom-left-radius:5px;
}

.statistic:last-child {
    border-top-right-radius: 5px;
    border-bottom-right-radius: 5px;
}
}
@media (max-width: 720px) {
  .statistic:first-child {
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
    }

  .statistic:last-child {
      border-bottom-left-radius:5px;
      border-bottom-right-radius: 5px;
  }
  }


</style>
