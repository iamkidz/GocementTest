<template>
    <div class="content2">
      <h1>
        <span class="text-content2-1"> {{text5}} </span>
      </h1>
      <div class="content2-image">
        <div class="content2-1" v-motion-slide-visible-once-left>
        <h1><span> {{text6}} </span></h1>
        </div>
        <div class="content2-2" v-motion-slide-visible-once-right>
        <h1><span> {{text7}} </span></h1>
        </div>
        <div class="content2-3" v-motion-slide-visible-once-bottom>
        <h1><span> {{text8}} </span></h1>
        </div>
      </div>
      <h1 v-motion-slide-visible-once-bottom>
        <span class="text-content2-2"> {{text9}} </span>
        <p class="text-content2-3">{{text10}}</p>
      </h1>
      <div class="iframe" v-motion-slide-visible-once-left>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/nG-5hjaBugc" 
        title="YouTube video player" frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen></iframe>
      </div>
    </div>
</template>

<script>
import konten2 from "../json/konten2.json";

export default {
    data() {
        return konten2;
    },
};
</script>