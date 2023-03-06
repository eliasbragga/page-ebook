<template>
    <v-layout row wrap style="height: 600px; display: flex;" >
        <v-flex md6 class="container_description">
            <h1>Segredos do primeiro emprego</h1>
         <h1>como <span class="highlighted_text">Front-end</span></h1>
         <p class="mt-2 container_subtitle">O caminho certo na direção certa</p>
        </v-flex>
        <v-flex md6 class="container_card">
          <v-img/>
          <div class="card">
            <div class="coupon">
              <span class="span_coupon">Cupon de desconto</span>
              <span class="text_coupon">
                AGBSGCPAGAMENOS
                <v-btn x-small text color="white" ></v-btn>
              </span>
             
            </div>
            <div class="text_value">
              <span>19,99</span>
            </div>
            <div class="buttonEbook">
              <v-btn color="primary" block height="50">Garantir ebook</v-btn>
            </div>
          </div>
        </v-flex>
    </v-layout>
  </template>
  
  <script lang="ts">
  export default {
      name:"HomePage",
  }
  </script>
  
  <style scoped>

.container_description {
  display: flex;
  flex-direction:column ;
  align-items: start;
  justify-content: center;
  font-size: 1.5rem;
}

  .highlighted_text {
    color: #9ddc30;
    text-decoration: underline ;
  }

  .container_card {
    display: flex;
    align-items: center;
    
  }
  .card {
    width: 650px;
    height: 500px;
    max-width: 80%;
    max-height: 70%;
    background: white;
    border-radius: 6px;
    padding: 2rem;
  }

  .container_subtitle {
    color:rgba(255, 255, 255, 0.624)
  }

  .container_card p,span {
    color: black;
  }
  
  .coupon {
    display: flex;
    justify-content: space-around;
    align-items: center;
  }
  .span_coupon {
    display: flex;
    align-items: center !important;
    justify-content: center;
    width: 190px;
    height: 45px;
    text-align: center;
    text-transform: uppercase;
    background: black;
    color: white;
    border-radius: 6px;
  }

.text_coupon {
  font-size:1.4rem;
  font-weight: 500;
  background: #9ddc33;
  padding: 1rem;
  border-radius: 5px;
}


 .text_value {
 }

 .text_value span {
  font-size: 11rem;
  font-weight: bold;

 }

 .buttonEbook button {
  font-size: 1.3rem;
 }

 .buttonEbook button:hover {
  transform: scale(1.1);
 }

 
 
  
  </style>