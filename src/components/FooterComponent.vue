<template>
  <b-container class="mx-auto m-0 p-0">
    <b-row class="footer mx-auto text-left">
      <b-col sm="10" md="10" lg="6" xl="6">
        <h4>Aliquam sed mauris</h4>
          <p class="text-justify footer-text">Sed lorem ipsum dolor sit amet et nullam consequat feugiat consequat magna adipiscing tempus etiam dolore veroeros. eget dapibus mauris. Cras aliquet, nisl ut viverra sollicitudin, ligula erat egestas velit, vitae tincidunt odio.</p>
        <b-button variant="outline-light" size="lg" class="footerBotton">Learn more</b-button>
      </b-col>
      <b-col sm="10" md="10" lg="6" xl="6">
        <h4>Etiam feugiat</h4>

          <b-row>
            <b-col cols="3">
              <div class="">
                <p>Address</p>
              </div>
              <div class="">
                <p>Phone</p>
              </div>
              <div class="">
                <p>Email</p>
              </div>
            </b-col>

            <b-col cols="9">
              <div class="footer-text">
                <p>1234 Somewhere Road • Nashville, TN 00000</p>
              </div>
              <div class="footer-text">
                <p>(000) 000-0000 x 0000</p>
              </div>
              <div class="footer-text">
                <p>information@untitled.tld</p>
              </div>
            </b-col>
          </b-row>
          <b-row>
            <b-col cols="12">
              <ul class="p-0">
                <li>
                  <font-awesome-icon icon="gem" class="footer-component-pic" style="color: #fff;"></font-awesome-icon>
                </li>

                <li>
                  <font-awesome-icon icon="gem" class="footer-component-pic" style="color: #fff;"></font-awesome-icon>
                </li>

                <li>
                  <font-awesome-icon icon="gem" class="footer-component-pic" style="color: #fff;"></font-awesome-icon>
                </li>

                <li>
                  <font-awesome-icon icon="gem" class="footer-component-pic" style="color: #fff;"></font-awesome-icon>
                </li>

                <li>
                  <font-awesome-icon icon="gem" class="footer-component-pic" style="color: #fff;"></font-awesome-icon>
                </li>

              </ul>
            </b-col>
          </b-row>
      </b-col>
    </b-row>

    <b-row>
      <b-col cols="4 mx-auto">
        <p class="last-lorem pt-3 pb-5">Sed lorem ipsum dolor.</p>
      </b-col>
    </b-row>

</b-container>

</template>

<script>
export default {

}
</script>

<style>

.footer {
  color:#fff;
  position: relative;
  width: 64em;
  max-width: calc(100% - 4em);
  padding: 1em;
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: 300;
  }

.footer-text {
  opacity: 0.65;
}

li {
  display: inline;
  font-size: 20pt;
  padding-right: 5%;
}

.last-lorem {
  color:#fff;
  opacity: 0.35;
  font-size: 10pt;
  }

.footerBotton {
  background-color: none;
  color: #fff !important;
  border-radius: 8px!important;
  border: 0;
  cursor: pointer;
  display: inline-block;
  font-weight: 300;
  text-align: center;
  border-color: #ddd!important;
  margin-top: 1.5rem;
  margin-bottom: 2.5rem;

  }

.footerBotton:hover {
  opacity: 0.7;
  background-color: rgba(222, 222, 222, 0.15)!important;
  transition: background-color 0.3s ease-in-out;
  box-shadow: inset 0 0 0 1px #8cc9f0;
}
.footer-component-pic
{
  margin-top: 1.5rem;
  margin-bottom: 1.5rem;
  border: 1px solid #dddddd;
  border-radius:100%;
  padding: 1.5%;
  font-size: 24pt;
}
.footer-component-pic:hover {
    background-color: rgba(222, 222, 222, 0.25)!important;
    box-shadow: 1px 1px 5px 4px white;
}
</style>
