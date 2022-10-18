<template>
    <div class="row">
        <div class="col-12 col-md-6">
            <h1>Formularios</h1>
            <img width="100" :src="url" :alt="msg" class="my-4">
        </div>
    </div>
    <hr />
</template>

<script>
export default {
    data: () => ({
        url: "https://cdn.svgporn.com/logos/vue.svg",
        msg: "Vue.js",
    }),
};
</script>
