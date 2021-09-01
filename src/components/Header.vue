<template>
  <div class="bg-header">
    <v-container class="my-10">
      <div class="d-flex justify-space-between">
        <div>
          <div class="main-logo"></div>
        </div>
        <div class="d-flex nav-menu">
          <router-link class="font-button-link responsive-button link" to="">Beranda</router-link>
          <router-link class="font-button-link responsive-button link" to="/1">Visi Dan Misi</router-link>          
          <router-link class="font-button-link responsive-button link" to="/2">Tentang Kami</router-link>          
        </div>
        <div class="d-flex nav-menu">
          <router-link to="/3" class="font-button-link responsive-button link mr-5">Masuk</router-link>          
          <v-btn v-bind="mainButton" class="mt-0">Daftar</v-btn>
        </div>
        <div class="responsive-menu">
          <v-btn @click="show = !show" icon>
            <v-icon color="white"> mdi-menu </v-icon>
          </v-btn>      
        </div>
      </div>
          <v-expand-transition>
          <div v-show="show" class="expand-transition-custom">
            <v-divider></v-divider>

            <v-list>
              <v-list-item-group>
                <v-list-item to="/">
                  <v-list-item-title>
                    Beranda
                  </v-list-item-title>
                </v-list-item>
                <v-list-item to="/1">
                  <v-list-item-title>
                    Visi dan Misi
                  </v-list-item-title>
                </v-list-item>
                <v-list-item to="/1">
                  <v-list-item-title>
                    Tentang Kami
                  </v-list-item-title>
                </v-list-item>
                <v-list-item to="/1">
                  <v-list-item-title>
                    Masuk
                  </v-list-item-title>
                </v-list-item>                
                <v-list-item>
                  <v-list-item-title>
                    <v-btn v-bind="mainButton" class="mt-0">Daftar</v-btn>
                  </v-list-item-title>
                </v-list-item>
              </v-list-item-group>              
            </v-list>
          </div>
        </v-expand-transition>
    </v-container>
  </div>
</template>
<script>
export default {
  props: ["mainButton", "textButton"],
  data : () => ({
    show : false
  }),
  mounted(){
    window.addEventListener("resize", () => {      
      if(window.innerWidth >= 960){
        this.show = false
      }      
    })
  }
};
</script>
<style scoped>
.bg-header {
  background-color: transparent;
}

div.responsive-menu {
  display: none;
}

div.expand-transition-custom{
  position: absolute;
  background-color: #1f1f1f;
  z-index: 2;
  width: 100%;
  right: 0;
  left: 0;      
}

div.expand-transition-custom div.v-list.v-sheet.theme--light{
  background-color: #1f1f1f;  
}

div.expand-transition-custom a.v-list-item.v-list-item--link.theme--light{
  color: white !important;
  background-color: transparent !important;  
}

div.expand-transition-custom a.v-list-item--link:before{
  background-color: transparent;
}

div.expand-transition-custom a.v-list-item.v-list-item--link.theme--light.v-list-item--active{
  background-color: #1f1f1f !important;  
  color: #FC7E40 !important;
}

@media (max-width: 960px) {
  div.d-flex.nav-menu {
    display: none !important;
  }
  div.responsive-menu {
    display: block;
  }
}
</style>