<template>
    <div id="app">
        <div class="m-image-padding" v-if="aspectRatio" :style="{height:'100px', backgroundColor: 'red' }">
        </div>
        <h2>2222222222</h2>
    </div>
</template>

<script>
export default {
    data() {
        return {
            aspectRatio: typeof window === 'undefined' ? undefined : 2,
        };
    },
    mounted() {
        console.log(this.aspectRatio)
    }
};
</script>
