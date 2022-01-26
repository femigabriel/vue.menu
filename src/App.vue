<template>
  <div id="app">
    <Header />
  <Submenu />
  <Search />
 
  <div class="card">
  <Card
    username=" Liman Restaurant"
    tag="Innovative cooking, paired with fine wines"
    phone="+44 20 1324 21"
    address="60 Penton Street"
    mark="https://main.mylistingtheme.com/wp-content/themes/my-listing/assets/images/tick.svg"
    logo="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/msclogo-150x150.png"
    image="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/photo-1508006728353-6ecef00dcbb8-768x512.jpg"
  />


  <Card
    username="Typing Room"
    tag="European fare and notable wines."
    phone="+44 20 1324 21"
      mark="https://main.mylistingtheme.com/wp-content/themes/my-listing/assets/images/tick.svg"
    address="Patriot Square"
    logo="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/DjUcpuxI-150x150.png"
    image="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/photo-1533777857889-4be7c70b33f7.jpg"
  />

  <Card
    username="The Active People"
    tag="Edwardian picture house, screening mainstream films"
    phone="+44 20 8467 123"
    address="27 Old Gloucester Street"
    logo="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/boatt_1x-150x150.jpg"
    image="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/photo-1485967249725-2d0b975fa8a2-768x512.jpg"
  />

  <Card
    username="Museum Of London"
    tag="Edwardian picture house, screening mainstream films"
    phone="+44 20 8467 123"
    address="150 London Wall"
    logo="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/lgoom-150x150.jpg"
    image="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/tunnel-the-archaeology-of-crossrail-exhibition-at-museum-of-london-docklands_262158-768x513.jpg"
  />

  <Card
    username="Electric Cinema"
    tag="Edwardian picture house, screening mainstream films"
    phone="+44 20 8467 123"
    address="191 Portobello Road"
    logo="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/logo60-1-150x150.jpg"
    image="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/4.2.2_dolbycinema_innovativeseating_promo4V2-768x328.jpg"
  />

  <Card
    username="The Lebury"
    tag="Innovative cooking, paired with fine wines"
    phone="+44 20 1324 21"
    address="Carlton Hill"
    logo="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/screenshot_2015-11-24_14.16.17-150x150.png"
    image="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/photo-1519671282429-b44660ead0a7-768x512.jpg"
  />

  <Card
    username="  Ministry Of Sound"
    tag="Flagship all-night club with dance and house music brand."
    phone="+44 20 1324 21"
    address="103 Gaunt Street"
    logo="https://ml0xnijd7w94.i.optimole.com/w:auto/h:auto/q:75/http://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/uk-ministry.jpg"
    image="http://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/whereslugo-410902-unsplash.jpg"
  />
  </div>
  <Footer />
   </div>
</template>

<script>
import Header from "./components/Header"
import Submenu from "./components/Submenu";
import Search from "./components/Search";
import Card from "./components/Card";
import Footer from "./components/Footer"

export default {
  name: "App",
  components: {
    Header,
    Submenu,
    Search,
    Card,
    Footer
  },
};
</script>

<style scoped>
@import url(https://fonts.googleapis.com/css?family=Open+Sans);

*,
*::before,
*::after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
body{
   
  font-family: 'Glacial Indifference Regular';
}
#app {
   background: #f4f4f4;
}
.card{
display: ;

}


@media screen and (min-width: 400px) {


.card {
  display: grid;
   grid-template-columns: repeat(3, 1fr);
  gap: 35px 1px;
 transition: all 0.3s ease;
 margin: 120px 0px;
 padding-left: 40px;
 }
}
</style>

