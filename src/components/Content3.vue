<template>
    <div class="content3">
      <div class="content3-image">
        <div class="content3-image1" v-motion-slide-visible-left></div>
        <div class="content3-image2" v-motion-pop-visible-once ></div>
      </div>
      <div class="content3-text">
        <div class="content3-text1" v-motion-pop-visible-once>
            
            <span>{{text1}}</span>
            <span>{{text2}}</span>
            <span>{{text3}}</span>
            <span>{{text4}}</span>
        </div>
        <div class="content3-text2" v-motion-slide-visible-once-right>
          <ul>
            <li>{{text5}}</li>
            <li>{{text6}}</li>
            <li>{{text7}}</li>
          </ul>
        </div>
      </div>
    </div>
</template>

<script>
import konten3 from "../json/konten3.json";

export default {
    data() {
        return konten3;
    },
};
</script>
