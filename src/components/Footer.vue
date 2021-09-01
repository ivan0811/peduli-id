<template>
  <div class="bg-footer">
    <v-container class="custom-footer-container">
      <v-row>
        <v-col cols="" lg="4" md="6" sm="12">
          <div class="d-flex flex-column">
            <div class="mb-auto">
              <div class="main-logo"></div>
              <p class="font-title white--text mt-6">
                <b>Peduli.id</b> situs web yang dibangun khusus untuk menggalang
                dana bantuan dan donasi secara online. #KitaPeduli
              </p>
            </div>
            <div class="d-flex mt-auto">
              <v-btn icon>
                <span class="icon icon-instagram icon-24 white"></span>
              </v-btn>
              <v-btn icon>
                <span class="icon icon-linkedin icon-24 white"></span>
              </v-btn>
              <v-btn icon>
                <span class="icon icon-twitter icon-24 white"></span>
              </v-btn>
            </div>
          </div>
        </v-col>
        <v-col cols="" lg="2" md="6" sm="12">
          <div class="font-subheader2 white--text mb-3">Kebaikanmu</div>
          <v-list color="transparent">
            <v-list-item link class="px-0">
              <v-list-item-content>
                <v-list-item-title class="font-title white--text"
                  >Donasi</v-list-item-title
                >
              </v-list-item-content>
            </v-list-item>

            <v-list-item link class="px-0" to="">
              <v-list-item-content>
                <v-list-item-title class="font-title white--text"
                  >Bantuan</v-list-item-title
                >
              </v-list-item-content>
            </v-list-item>

            <v-list-item link class="px-0">
              <v-list-item-content>
                <v-list-item-title class="font-title white--text"
                  >Zakat</v-list-item-title
                >
              </v-list-item-content>
            </v-list-item>
          </v-list>
        </v-col>
        <v-col cols="" lg="3" md="6" sm="12">
          <div class="font-subheader2 white--text mb-3">
            Pelajari selengkapnya
          </div>
          <v-list color="transparent">
            <v-list-item link class="px-0">
              <v-list-item-content>
                <v-list-item-title class="font-title white--text"
                  >Cara Donasi</v-list-item-title
                >
              </v-list-item-content>
            </v-list-item>

            <v-list-item link class="px-0" to="">
              <v-list-item-content>
                <v-list-item-title class="font-title white--text"
                  >Tentang Kami</v-list-item-title
                >
              </v-list-item-content>
            </v-list-item>

            <v-list-item link class="px-0">
              <v-list-item-content>
                <v-list-item-title class="font-title white--text"
                  >FAQ</v-list-item-title
                >
              </v-list-item-content>
            </v-list-item>
          </v-list>
        </v-col>
        <v-col cols="" lg="3" md="6" sm="12">
          <div class="font-subheader2 white--text mb-3">Newsletter kami</div>
          <p class="font-title white--text">
            Berlangganan email newsletter kami, disini:
          </p>
          <v-text-field solo flat label="Email Anda" class="custom-text-field">
            <template v-slot:append>
              <v-btn
                elevation="0"
                min-width="max-content"
                color="primary"
                class="pa-2"
                v-bind="textfieldButton"
              >
                <span
                  class="icon icon-haruki icon-24 white"
                  style="width: 24px"
                ></span>
              </v-btn>
            </template>
          </v-text-field>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>
<script>
export default {
  props: ["mainButton", "textButton", "textfieldButton"],
};
</script>
<style>
.bg-footer {
  background-color: #fc7e40;
}

div.custom-text-field {
  border-radius: 0;
}

div.custom-text-field label.v-label {
  padding-left: 10px;
  font-size: 14px;
  color: #fc7e40;
}

div.custom-footer-container {
  padding: 150px 0px;
}

div.custom-footer-container div.v-sheet.v-list {
  padding: 40px 0px;
}

div.custom-footer-container div.v-sheet.v-list {
  padding: 40px 0px;
}

div.custom-footer-container p.font-title {
  margin: 60px 0px;
}

@media (max-width: 2090px) {
  div.custom-footer-container {
    padding: 140px 0px;
  }

  div.custom-footer-container div.v-sheet.v-list {
    padding: 40px 0px;
  }

  div.custom-footer-container div.v-sheet.v-list {
    padding: 40px 0px;
  }

  div.custom-footer-container p.font-title {
    margin: 40px 0px;
  }
}

@media (max-width: 1870px) {
  div.custom-footer-container {
    padding: 130px 0px;
  }

  div.custom-footer-container div.v-sheet.v-list {
    padding: 40px 0px;
  }

  div.custom-footer-container div.v-sheet.v-list {
    padding: 40px 0px;
  }

  div.custom-footer-container p.font-title {
    margin: 40px 0px;
  }
}

@media (max-width: 1800px) {
  div.custom-footer-container {
    padding: 120px 0px;
  }

  div.custom-footer-container div.v-sheet.v-list {
    padding: 40px 0px;
  }

  div.custom-footer-container div.v-sheet.v-list {
    padding: 40px 0px;
  }

  div.custom-footer-container p.font-title {
    margin: 40px 0px;
  }
}

@media (max-width: 1776px) {
  div.custom-footer-container {
    padding: 120px 0px;
  }

  div.custom-footer-container div.v-sheet.v-list {
    padding: 40px 0px;
  }

  div.custom-footer-container div.v-sheet.v-list {
    padding: 40px 0px;
  }

  div.custom-footer-container p.font-title {
    margin: 40px 0px;
  }
}

@media (max-width: 1559px) {
  div.custom-footer-container {
    padding: 80px 0px;
  }

  /* div.custom-footer-container div.v-sheet.v-list{        
            padding: 10px 0px;
        } */

  div.custom-footer-container div.v-sheet.v-list {
    padding: 10px 0px;
  }

  div.custom-footer-container p.font-title {
    margin: 30px 0px;
  }
}

@media (max-width: 1264px) {
  div.custom-footer-container {
    padding: 60px 0px;
  }

  div.custom-footer-container div.v-sheet.v-list {
    padding: 40px 0px;
  }

  div.custom-footer-container div.v-sheet.v-list {
    padding: 20px 0px;
  }

  div.custom-footer-container p.font-title {
    margin: 20px 0px;
  }
}
</style>