<script lang="ts" setup>
import { Splide, SplideSlide } from "@splidejs/vue-splide";
import "@splidejs/splide/dist/css/themes/splide-default.min.css";
</script>
<template>
    <div>
        <Splide :options="{ rewind: true }">
            <SplideSlide>
                <img src="https://source.unsplash.com/random" alt="Sample 1" />
            </SplideSlide>
            <SplideSlide>
                <img src="https://source.unsplash.com/random" alt="Sample 2" />
            </SplideSlide>
        </Splide>
    </div>
</template>
