<template>
    <div class="content1">
        <h1>
            <span class="text-content-1">
                {{ text1 }}
                <br />
                {{ text2 }}
                <br />
                {{ text3 }}
                <br />
                {{ text4 }}
                <br>
                <br>
                <p class="text-content-2">
                Pakai
              <strong>
                <span> Aplikasi Gocement</span>
              </strong>
                ya!
                </p>
                <br>
                <div class="image-content-2"></div>
            </span>
        </h1>

        <div class="image-content-1"></div>
        
    </div>
</template>

<script>
import konten1 from "../json/konten1.json";

export default {
    data() {
        return konten1;
    },
};
</script>
