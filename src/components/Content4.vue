<template>
<div class="content4">
        <div class="content4-text"> 
          <span>{{text1}} <strong>{{text2}}</strong></span>
        </div>
        <div class="handphone" v-motion-pop-visible-once>
          <div class="content4-image1"></div>
          <div class="content4-image2"></div>
          <div class="content4-image3"></div>
        </div>
        <div class="content4-text-handphone" v-motion-slide-visible-once-bottom>
          <div class="content4-text1"> <span> {{text3}} <br> {{text4}} </span> </div>
          <div class="content4-text2"> <span> {{text5}} <br>{{text6}} <br>
          {{text7}}</span> </div>
          <div class="content4-text3"> <span> {{text8}} <br>{{text9}}</span> </div>
        </div>
        <div class="content4-proses" v-motion-pop-visible-once>
          <div class="content4-image4"></div>
          <div class="content4-image5"></div>
          <div class="content4-image6"></div>
        </div>
        <div class="content4-text-proses" v-motion-slide-visible-once-bottom>
          <span> {{text10}} </span>
          <span> {{text11}} <br> {{text12}}</span>
          <span> {{text13}} <br>{{text14}}</span>
        </div>
    </div>
</template>

<script>
import konten4 from "../json/konten4.json";

export default {
    data() {
        return konten4;
    },
};
</script>
