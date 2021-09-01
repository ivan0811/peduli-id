<template>
  <v-app style="width: 100%">
    <Header :mainButton="mainButton" :textButton="textButton"></Header>
    <v-main>
      <router-view :mainButton="mainButton" :textButton="textButton" />
    </v-main>
    <Footer
      :mainButton="mainButton"
      :textfieldButton="textfieldButton"
    ></Footer>
  </v-app>
</template>

<script>
import Header from "./components/Header";
import Footer from "./components/Footer";
export default {
  name: "App",
  components: {
    Header,
    Footer
  },
  data: () => ({
    textButton: {
      elevation: 0,
      class: "mx-0 pa-0 font-button-link responsive-button link",
      width: "max-content",
    },
    mainButton: {
      tile: true,
      color: "primary",
      elevation: 0,
      class: "font-button custom-margin-top responsive-button",
    },
    textfieldButton: {
      tile: true,
      color: "primary",
      elevation: 0,
      class: "font-button",
    },    
  }),
};
</script>
<style>
@import "./assets/css/icon.css";
@import "./assets/css/font.css";
@import "./assets/css/style.css";
@import "./assets/css/animation.css";
div.theme--light.v-application {
  background-color: #1f1f1f;
}

html,
body {
  width: 100%;  
}

.main-logo {
  background-image: url("./assets/logo.svg");
  width: 98px;
  height: 38px;
}

div.remove-flex > span {
  width: max-content;
}

button.v-btn.responsive-button {
  padding: 40px 60px !important;
  color: #fff;
}

a.responsive-button.link {
  text-decoration: none;  
  color: #fff;
  background-color: transparent;
  padding: 28px 70px;
}

a.responsive-button.link:hover {  
  color: #fc7e40;  
  transition: 0.5s;
}

a.responsive-button.link.router-link-active {
  color: #fc7e40;
}

button.v-btn.responsive-button.link.active {
  color: #fc7e40;
}

button.v-btn.responsive-button.link:hover {
  color: #fc7e40;
  background-color: transparent !important;
}

 div.container.custom-container {
    max-width: 93%;
  }

  div.container * {
    z-index: 1;
  }

  div.container {
    max-width: 87%;
  }

  div.container.container--fluid {
    max-width: 90%;    
    padding: 30px 0;
  }

   div.container.custom-container {
    max-width: 93%;
  }

  div.container * {
    z-index: 1;
  }

  div.container {
    max-width: 87%;
  }

  div.container.custom-container-counter{
    padding: 130px 20px;    
  }

  div.container.custom-container-counter div.font-header2,
  div.container.custom-container-counter div.font-header1{
    margin-bottom: 45px;
  }    

  div.container.custom-container-counter div.font-subheader{
    margin-bottom: 100px;
    max-width: 1000px;
  }

  div.custom-margin-link2{
    margin-top: 60px;
    margin-bottom: 400px;
  }

  div.img-jumbroton{
    display: block;
    position: relative;
  }

  @media (max-width: 2090px) {
     button.v-btn.responsive-button {
      padding: 35px 60px !important;    
      color: #fff;
    }

    a.responsive-button.link {    
      padding: 25px 50px;
    }   

    div.container.container--fluid {
      max-width: 90%;
    }
  }

  @media (max-width: 1800px) {
   button.v-btn.responsive-button {
    padding: 30px 60px !important;    
    color: #fff;
  }

  a.responsive-button.link {    
    padding: 19px 50px;
  }     
}

 @media (max-width: 1559px) {
   div.container.custom-container-counter{
        padding: 60px 20px;    
      }
     
      div.container.custom-container-counter div.font-header1{
        margin-bottom: 30px;
      }    

       div.container.custom-container-counter div.font-header2{
         margin-bottom: 10px;
       }

      div.container.custom-container-counter div.font-subheader{
        margin-bottom: 50px;
        max-width: 700px;
      }

      div.custom-margin-link2{
        margin-top: 40px;
        margin-bottom: 200px;
      }

   button.v-btn.responsive-button {
    padding: 25px 40px !important;    
    color: #fff;
  }

  a.responsive-button.link {    
    padding: 14px 35px;
  }   

  div.container.container--fluid {
    max-width: 95%;
    padding: 20px 0;
  }
}


/* @media (max-width: 1264px) {
   button.v-btn.responsive-button {
    padding: 20px 40px !important;    
    color: #fff;
  }

  a.responsive-button.link {    
    padding: 5px 10px;
  }     
} */

@media (max-width: 1264px) {
  div.container.custom-container {
    max-width: 95%;
  }

  div.container {
    max-width: 95%;
    /* z-index: 1; */
  }  

  div.theme--light.v-image.header-img {
    display: none;
  }

  button.custom-margin-top {
    margin-top: 50px;
  }

  div.img-jumbroton {
    display: none;
  }
}

@media (max-width: 960px) {
  button.v-btn.responsive-button {
    padding: 12px 40px !important;    
    height: 50px !important;
    color: #fff;
  }

  div.container.custom-container {
    max-width: 95%;
  }

  div.container {
    max-width: 95%;
  }  

  div.theme--light.v-image.header-img {
    display: none;
  }

  button.custom-margin-top {
    margin-top: 50px;
  }

  div.img-jumbroton {
    display: none;
  }
}

@media (max-width: 600px) {
  div.theme--light.v-image.header-img {
    display: none;
  }

  button.custom-margin-top {
    margin-top: 50px;
  }

  div.img-jumbroton {
    display: none;
  }
}

.img-custom-col3.v-responsive {
  position: absolute;
  top: calc(100% - 260px);
  left: calc(-10% - (40px));
}
</style>
