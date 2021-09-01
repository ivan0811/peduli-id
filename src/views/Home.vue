<template>
  <div> 
    <div class="elipse" style="top: 10px; left: 280px;"></div>   
    <div class="rectangle1" style="top: 300px; left: 220px;"></div>
    <div class="rectangle2" style="top: 600px; left: 340px;"></div>
    <v-container class="mr-0 pa-0 custom-container mt-12" style="margin-bottom: 150px;">
      <v-row justify="space-between" class="custom-height">
        <v-col class="d-flex flex-column animation-fade-left-in" style="margin-bottom: 80px" lg="3" md="12" sm="12">              
          <div class="mb-auto">                 
            <div class="font-header1 white--text">Ulurkan tanganmu dan bantulah mereka</div>          
            <div class="font-subheader white--text mt-10">Sesungguhnya kamu akan mendapatkan pahala dari hal itu</div>
          </div>                          
          <div class="mt-auto">
            <v-btn v-bind="mainButton">Donasi Sekarang</v-btn>            
          </div>              
        </v-col>
        <v-col lg="9" md="0" sm="0" class="img-jumbroton animation-fade-right-in">          
          <v-img class="header-img" src="../assets/img/header_image.png"></v-img> 
          <div class="rectangle7"></div>                   
          <div></div>
          <div class="d-flex my-5 img-jumbroton">            
              <v-btn width="80" class="mr-4" icon>              
                <span style="width: 80px; height: 10px" class="icon icon-arrow-left icon-mask white"></span>            
              </v-btn>
              <v-btn width="80" icon>              
                  <span style="width: 80px; height: 10px" class="icon icon-arrow-right icon-mask white"></span>            
              </v-btn>            
          </div>
        </v-col>                
      </v-row>       
    </v-container>      
    <v-sheet color="white">
       <div class="rectangle3" style="top: 920px; left: 60%;"></div>
        <div class="rectangle4" style="top: 1090px; left: 65%;"></div>
        <v-container class="custom-container-counter">          
          <v-row id="counter">
            <v-col class="mb-5">
              <div class="text-center">
                <div class="font-header2 primary--text counter">
                  290,000 +
                </div>
                <div class="font-header3">
                  Donatur
                </div>
              </div>
            </v-col>
            <v-col class="mb-5">
              <div class="text-center">
                <div class="font-header2 primary--text counter">
                  Rp 890Jt +
                </div>
                <div class="font-header3">
                  Donasi Terkumpul
                </div>
              </div>
            </v-col>
            <v-col>               
              <div class="text-center">
                <div class="font-header2 primary--text counter">
                  2,300 +
                </div>
                <div class="font-header3">
                  Galang Dana
                </div>
              </div>
            </v-col>
          </v-row>                   
        </v-container>
      </v-sheet>
      <v-container class="custom-container-counter" style="margin-bottom: 300px">
        <div class="elipse" style="top: 1150px; left: 340px;"></div>   
        <div data-aos="fade-up" class="font-header1 text-center white--text" data-aos-duration="3000">Bantu Mereka</div>
        <div data-aos="fade-up" class="font-subheader white--text text-center mx-auto" data-aos-duration="3000">Sedikit dari Anda akan menjadi sangat berarti untuk meringankan beban mereka.</div>
        <v-row class="mt-8" data-aos="fade-up" data-aos-duration="3000">
          <v-col lg="4" md="6" sm="12">
            <v-card color="white" style="height: 100%" class="d-flex flex-column">             
              <div class="mb-auto">
                <v-img src="../assets/img/content_image1.png"></v-img>
                <v-container class="d-flex flex-column pb-0" fluid>                
                  <p class="font-title-bold">
                    Bantu Sedekah buku, dan pakaian untuk adik kita yang terdampak banjir
                  </p> 
                </v-container>                  
              </div>               
                  <v-container class="pt-0 mt-auto" fluid>
                     <p class="font-text primary--text mb-0">
                    Ivan Faathirza
                  </p>                                 
                   <div class="font-text primary--text" style="margin-left: 30%">38%</div>
                   <v-progress-linear
                      height="9"
                      background-color="secondary lighten-3"
                      color="primary"
                      value="35"
                      class="mb-2"
                    ></v-progress-linear>    
                    <div class="d-flex justify-space-between mb-1">
                      <p class="font-text mb-0">
                      Terkumpul
                    </p>       
                    <p class="font-text mb-0">
                      Sisa Waktu
                    </p>       
                    </div>   
                    <div class="d-flex justify-space-between">
                      <p class="font-title-bold">
                      Rp 15.780.235
                    </p>       
                    <p class="font-title-bold">
                      38 Hari
                    </p>       
                    </div> 
                  </v-container>                                
            </v-card>
          </v-col>
          <v-col cols="" lg="4" md="6" sm="12">
              <v-card style="height: 100%" class="d-flex flex-column">
                <div class="mb-auto">
                  <v-img src="../assets/img/content_image2.png"></v-img>                
                  <v-container class="d-flex flex-column pb-0 mb-auto" fluid>                
                    <p class="font-title-bold">
                      #KitaPeduli Gotong Royong | Bantu saudara kita dapatkan hunian baru
                    </p>
                  </v-container>                                    
                </div>                
                  <v-container class="mt-auto pt-0" fluid>
                    <p class="font-text primary--text mb-0">
                      Hayin Ananta
                    </p>  
                    <div class="font-text primary--text" style="margin-left: 55%">60%</div>
                    <v-progress-linear
                        height="9"
                        background-color="secondary lighten-3"
                        color="primary"
                        value="60"
                        class="mb-2"
                      ></v-progress-linear>                   
                      <div class="d-flex justify-space-between mb-1">
                        <p class="font-text mb-0">
                        Terkumpul
                      </p>       
                      <p class="font-text mb-0">
                        Sisa Waktu
                      </p>                         
                      </div>   
                      <div class="d-flex justify-space-between">
                        <p class="font-title-bold">
                        Rp 43.939.764
                      </p>       
                      <p class="font-title-bold">
                        42 Hari
                      </p>       
                    </div> 
                  </v-container>                                
              </v-card>
          </v-col>
          <v-col cols="" lg="4" md="6" sm="12">
              <v-card style="height: 100%" class="d-flex flex-column">
                <div class="mb-auto">
                  <v-img src="../assets/img/content_image3.png"></v-img>
                  <v-container class="pb-0" fluid>                
                    <p class="font-title-bold mb-auto pb-0">
                      Ayo saling bantu untuk Indonesia sehat #KitaPeduli
                    </p>            
                  </v-container>
                </div>                
                <v-container class="pt-0 mt-auto" fluid>
                  <p class="font-text primary--text mb-0">
                    Ilham Zaki
                  </p>                                
                  <div class="font-text primary--text" style="margin-left: 65%">70%</div>
                   <v-progress-linear
                      height="9"
                      background-color="secondary lighten-3"
                      color="primary"
                      value="70"
                      class="mb-2"
                    ></v-progress-linear>        
                    <div class="d-flex justify-space-between mb-1">
                      <p class="font-text mb-0">
                      Terkumpul
                    </p>       
                    <p class="font-text mb-0">
                      Sisa Waktu
                    </p>     
                    </div>   
                    <div class="d-flex justify-space-between">
                      <p class="font-title-bold">
                      Rp 45.780.235
                    </p>       
                    <p class="font-title-bold">
                      45 Hari
                    </p>       
                    </div> 
                </v-container>
              </v-card>
          </v-col>          
        </v-row>
        <div class="d-flex custom-margin-link2" data-aos="fade-up" data-aos-duration="3000">
          <!-- <v-btn plain v-bind="textButton" class="mx-auto my-10" color="white">Lihat lainya <i class="ml-1 icon icon-arrow-right-sm icon-mask white" style="width: 32px; height: 10px"></i></v-btn>       -->
          <router-link to="/3" class="font-button-link2 responsive-button link mx-auto my-6">Lihat lainya <i class="ml-1 icon icon-arrow-right-sm icon-mask white" style="width: 32px; height: 10px"></i></router-link>          
        </div>        
        <v-row data-aos="fade-up" data-aos-duration="3000" justify="space-between">    

        <v-col class="pr-16" cols="" lg="8" md="0" sm="0">        
          <v-card elevation="0" color="transparent">
            <v-img class="header-img" src="../assets/img/content_image4.png"></v-img>                    
            <v-img class="img-custom-col3 header-img" src="../assets/img/content_image5.png"></v-img>
          </v-card>                                
        </v-col>  
        <!-- <div class="elipse" style="top: 2300px; left: 90%;"></div>   -->
         <v-col class="d-flex flex-column" lg="4" md="12" sm="12">              
          <div class="mb-auto">
            <div class="font-header1 white--text">Visi dan Misi kami membantu mereka.</div>          
            <div class="font-subheader white--text mt-10">Rezeki lancar dengan melakukan donasi kepada mereka yang membutuhkan. #KitaPeduli</div>
          </div>                          
          <div class="mt-auto">
            <v-btn v-bind="mainButton">Bantu Mereka</v-btn>            
          </div>              
        </v-col>    

      </v-row>     
      </v-container>    
      <div class="rectangle5" style="top: 2700px; left: 300px;"></div>
      <div class="rectangle6" style="top: 3060px; left: 440px;"></div>
      <div class="elipse" style="top: 3100px; left: -20px;"></div>  
      <v-container data-aos="fade-up" data-aos-duration="3000" style="margin-bottom: 200px">
      <v-row justify="space-between">
        <v-col lg="4" md="12" sm="12" class="d-flex flex-column custom-height" style="margin-bottom: 80px">              
          <div class="mb-auto">
            <div class="font-header1 white--text">Apa Itu Peduli.id?</div>          
            <div class="font-subheader white--text mt-10">
              Peduli.id adalah website yang dibangun 
              khusus untuk membantu mengumpulkan dana, barang, obat-obatan, dan pakaian 
              bagi mereka yang membutuhkan. #KitaPeduli</div>
          </div>                          
          <div class="mt-auto">
            <v-btn v-bind="mainButton">Jadi bagian dari kami</v-btn>            
          </div>              
        </v-col>        
        <v-col class="img-jumbroton" lg="8" md="0" sm="0">          
          <v-img class="header-img" src="../assets/img/content_image6.png"></v-img>                              
          <div class="d-flex my-5">            
              <v-btn width="80" class="mr-4" icon>              
                <span style="width: 80px; height: 10px" class="icon icon-arrow-left icon-mask white"></span>            
              </v-btn>
              <v-btn width="80" icon>              
                  <span style="width: 80px; height: 10px" class="icon icon-arrow-right icon-mask white"></span>            
              </v-btn>            
          </div>
        </v-col>                
      </v-row>       
    </v-container>             
  </div>  
</template>

<script>    
  export default {
    name: 'Home',    
    props: ["mainButton", "textButton"],
    data: () => ({
      donatur: 0,
      donasi_terkumpul: 0,
      galang_dana: 0
    }),
    mounted(){
      window.addEventListener('scroll', () => {        
        const scrollTop = window.pageYOffset
        const getCounter = document.querySelectorAll('.counter')        
        getCounter.forEach(item => {          
          if(scrollTop + window.innerHeight - 190 >= item.offsetTop){
            this.donatur = 0
            this.donasi_terkumpul = 0
            this.galang_dana = 0
          }
        })
      })
    }    
  }
</script>
