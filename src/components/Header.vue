<template>

<div class="header">
      <div class="text-nav">
        <h3>{{text1}}</h3>
      </div>
      <div class="navigation">
        <div  class="image1"></div>
        <ul class="navigation1">
          <li href="kelebihan"> {{text2}}</li>
          <li href="produk"> {{text3}}</li>
          <li href="cerita">{{text4}}</li>
        </ul>
        
        <ul class="navigation2">
          <li><a href="">{{text5}}</a></li>
          <li><a href="">{{text6}}</a></li>
          <li><a href="">{{text7}}</a></li>
          <li><a href="">{{text8}}</a></li>
          <li><a href="">{{text9}}</a></li>
          <li><a href="">{{text10}}</a></li>
        </ul>

        <div class="imagesecond">
            <div class="imageback">
              <div class="image2"><a href="">{{text11}}<br>{{text12}}</a></div>  
              </div>
            <div class="imageback2">
              <div class="image3"><a href="">{{text13}}<br>{{text14}}</a></div>
            </div>
        </div>
      </div>
    </div>
</template>>
<script>
import header from "../json/header.json";

export default {
    data() {
        return header;
    },
};
</script>