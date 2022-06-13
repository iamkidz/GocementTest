<template>
  <body>
    <Header/>
    <Content1/>
    <Content2/>
    <Content3/>
    <Content4/>
  </body>
</template>

<script>
import Header from "./components/Header.vue"
import Content1 from "./components/Content1.vue"
import Content2 from "./components/Content2.vue"
import Content3 from "./components/Content3.vue"
import Content4 from "./components/Content4.vue"


export default {
  name : 'App',
  components: {
    Header,
    Content1,
    Content2,
    Content3,
    Content4
} }

</script>

<style>

body {
  position: relative;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 1000px;
  background-color: white;
  cursor: pointer;
  
}

.header-cs-image {
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 200px;
  height: 200px;
  background-color: #ff6900;
  border-radius: 100%;
  right: -1000px;
  top: 400px;
  bottom: 0px;
  z-index: 5;
}

.header-phone {
  background-image: url("assets/Icon-Phone.png");
  width: 100px;
  height: 100px;
  border-radius: 100%;
  background-repeat: no-repeat;
  background-size: cover;
}

.header-text {
  width: 100px;
  height: 75px;
  border-radius:0 50% 0 50% ;
}

.header {
  position: fixed;
  width: 100%;
  z-index: 2;
}

.text-nav {
  display: flex;
  background-color: orange;
  height: 30px;
  align-items: center;
  justify-content: center;
}

.navigation {
  position: relative;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  background-color: black;
  color: gray;
  
}

.navigation1  {
  display: flex;
  flex-direction: row;
}

.navigation2  {
  display: flex;
  flex-direction: row;
  margin-right: 20px;

}

li  {
  list-style-type: none;
  margin: 10px;
}

li>a  {
  text-decoration: none;
  color: white;
}

.image1 {
  position: absolute;
  width: 75px;
  height: 75px;
  background-size: contain;
  background-repeat: no-repeat;
  background-image: url("assets/gocementlogo.png");
  top: -20px;
  left: 60px;
  
}
.imagesecond {
  position: absolute;
  right: 30px;
  top: -40px;
  display: flex;
  justify-content: flex-end;
  flex-direction: row;
  align-items: center;
  box-sizing: border-box;
  margin-inline: 5px;
  width: 100px;
  height: 100px;
  
}

.imageback  {
  position: absolute;
  background-color: orange;
  width: 80px;
  height: 80px;
  border: 2px rgba(255, 68, 0, 0,4) solid;
  top: 30px;
  right: 50px;
  justify-content: center;
  display: flex;
  align-items: center;
  border-radius: 5px;
}  

.image2 {
  position: relative;
  display: flex;
  justify-content: center;
  line-height: 20px;
  width: 25px;
  height: 25px;
  margin-right: 10px;
  background-image: url("assets/GocMarket.png");
  background-size: contain;
  background-repeat: no-repeat;
  border-radius: 10%;
  bottom: 10px;
  

}

.image2 > a { 
  position: relative;
  text-decoration: none;
  display: flex;
  justify-content: center;
  align-items: center;
  top: 20px;
  left: 4px;
  color: white;
  text-align: center;
  font-size: small;
  top: 30px;

}

.imageback2  {
  position: relative;
  background-color: black;
  width: 68px;
  height: 68px;
  border: 2px rgba(255, 68, 0, 0,4) solid;
  top: 24px;
  right: -40px;
  justify-content: center;
  display: flex;
  align-items: center;
  border-radius: 5px;
  margin-right: 15px;

}

.image3 {
  position: absolute;
  top: 10px;
  width: 25px;
  height: 25px;
  background-image: url("assets/downloadapps.png");
  background-size: cover;
  background-repeat: no-repeat;
  border-radius: 10%;
  display: flex;
  justify-content: center;
  align-items: center;
  
}

.image3> a { 
  position: relative;
  height: 1000px;
  text-decoration: none;
  display: flex;
  justify-content: center;
  align-items: center;
  top: 0;
  left: 0;
  color: white;
  text-align: center;
  font-size: small;
  top: 30px;
}


.content1 {
  display: flex;
  justify-content: space-between;
  width: 100%;
  height: 600px;
  top: 100px;
  background-image: url("assets/Top-Banner-Homepage.jpg");
  background-size: cover;
  position: relative;
}

.text-content-1 {
  color: white;
  position: absolute;
  top: 90px;
  left: 150px;
  font-size: 40px;
}

.image-content-1  {
  background-image: url("assets/pakcor.png");
  position: absolute;
  width: 400px;
  height: 400px;
  background-size: cover;
  right: 100px;
  top: 125px;
}

.text-content-2 {
    color: white;
    position: absolute;
    font-size: 24px;
}

.image-content-2 {
  background-image: url("assets/googleplay.png");
  background-repeat: no-repeat;
  background-size: contain;
  width: 200px;
  height: 100px;
  margin-top: 20px;
}

p strong span {
  color: rgb(236, 69, 9);
}

.content2 {
  width: 100%;
  position: relative;
  background-color: #242424;
  padding-bottom: 200px;
  
}

.text-content2-1  {
  display: flex;
  justify-content: center;
  color: #f37e21;
  padding-top: 40px;
  box-sizing: border-box;
  font-size: larger;
  font-weight: 400;
  text-transform: uppercase;
}

.text-content2-2  {
  display: flex;
  justify-content: center;
  color: #f37e21;
  padding-top: 40px;
  box-sizing: border-box;
  font-size: larger;
  font-weight: 400;
  text-transform: uppercase;
}

.text-content2-2  {
  display: flex;
  justify-content: center;
  color: #f37e21;
  padding-top: 40px;
  box-sizing: border-box;
  font-size: larger;
  font-weight: 400;
  text-transform: uppercase;
}

.text-content2-3 {
  display: flex;
  justify-content: center;
  color: #f37e21;
  padding-top: 40px;
  box-sizing: border-box;
  font-size: smaller;
  font-weight: inherit;
}

.content2-1 {
  background-image: url("assets/content2-1.jpg");
  width: 80%;
  height: 200px;
  display: flex;
  justify-content: center;
  margin-inline: auto;
  margin-block: 10px;
  color: white;
  line-height: 200px;
  
}

.content2-2 {
  background-image: url("assets/content2-2.jpg");
  width: 80%;
  height: 200px;
  display: flex;
  justify-content: center;
  margin-inline: auto;
  margin-block: 10px;
  color: white;
  line-height: 200px;
  
}

.content2-3 {
  background-image: url("assets/content2-3.jpg");
  width: 80%;
  height: 200px;
  display: flex;
  justify-content: center;
  margin-inline: auto;
  margin-block: 10px;
  color: white;
  line-height: 200px;
}

.iframe {
  display: flex;
  justify-content: center;
}

.content3  {
  position: relative;
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-direction: column;
  margin-top: -23px;
  background-color: rgba(255,105,0,1);
  width: 100%;
  height: 500px;
  top: -100px;
  border-radius: 0 25% 25% 0;
  display: flex;
  flex-direction: row;
  
}

.content3-image {
  width: 400px;
  height: 300px;
  background-color: white;
  
}

.content3-image1 {
  position: absolute;
  width: 400px;
  height: 400px;
  background-size: contain;
  background-repeat: no-repeat;
  background-image: url("assets/Image-Sekarang-Waktunya.jpg");
}

.content3-image2 {
  position: absolute;
  width: 650px;
  height: 200px;
  background-size: cover;
  background-image: url("assets/Sekarang-waktunya-beralih-ke-yang-lebih-canggih.png");
  top: -50px;
  right: 100px;
}

.content3-text  {

 display: flex;
 justify-content: center;
 align-items: center;
 flex-direction: column;
 
}

.content3-text1  {
  
  width: 500px;
  font-size: 24px;
  color: white;
  font-weight: 600;
  box-sizing: border-box;
  margin-right: 100px;
  margin-top: 50px;

}

.content3-text2  {
  width: 800px;
  height: 100;
  color: white;
  font-size: 30px;
  font-weight: 900;
  margin-left: 100px;
  box-sizing: content-box;
  
}

.content3-text2 ul li {
    display: inline;
  
}

.content4 {
  position: relative;
  width: 100%;
}

.content4-text {
  font-size: 32px;
  font-weight: 600;
  margin-left: 150px;
}
.content4-text > span strong {
 color: #f37e21;
}

.handphone {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  margin-top: 75px;
  margin-left: 250px;
}

.content4-image1 {
  background-image: url("assets/Bisa-Pesan-Instant.png");
  background-repeat: no-repeat;
  background-size: contain;
  width:  400px;
  height: 400px;
}

.content4-image2 {
  background-image: url("assets/Ada-Kalkulator.png");
  background-repeat: no-repeat;
  background-size: contain;
  width:  400px;
  height: 400px;
}

.content4-image3 {
  background-image: url("assets/Pembayaran-Mudah.png");
  background-repeat: no-repeat;
  background-size: contain;
  width:  400px;
  height: 400px;
}

.content4-text-handphone {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  width: 100%;
  margin-top: 60px;
  margin-left: 60px;
  font-size: 24px;
  font-weight: 400;
  text-align: center;
}

.content4-text1 {
  
  width: 250px;
  height: 200px;
  margin-left: 100px;
  box-sizing: border-box;
  
}

.content4-text2 {
  
  box-sizing: border-box;
  width: 250px;
  height: 200px;
  margin-right: 0px;
}

.content4-text3 {
  box-sizing: border-box;
  margin-right: 120px;
  width: 250px;
  height: 200px;

}

.content4-proses {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  margin-left: 40px;
}

.content4-image4 {
  background-image: url("assets/Diantar-Sampai-Tujuan-New.png");
  background-repeat: no-repeat;
  background-size: contain;
  width:  250px;
  height: 250px;
}

.content4-image5 {
  background-image: url("assets/Produk-Berkualitas.png");
  background-repeat: no-repeat;
  background-size: contain;
  width:  250px;
  height: 250px;
}

.content4-image6 {
  background-image: url("assets/Harga-Stabil-New.png");
  background-repeat: no-repeat;
  background-size: contain;
  width:  250px;
  height: 250px;
}

.content4-text-proses {
  display: flex;
  justify-content: space-evenly;
  margin-top: 20px;
  text-align: center;
  font-size: 22px;
  font-weight: 400;
}

</style>
