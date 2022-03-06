<template>
    <div>
        <h1>CSS</h1>
        <div>{{ url }}</div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            url: process.env.VUE_APP_URL,
        };
    },
};
</script>

<style lang="scss">
$color: red;

h1 {
    background-color: $color;
}
</style>
