<template>
    <div>
        ini merupakan halaman {{ router }}
    </div>
</template>

<script>

export default {

    mounted() {
        console.log(this.$route.fullPath);
    },  
    data() {
        return{
            router : 123
        }
    }
}
</script>

<style lang="scss" scoped>

</style>