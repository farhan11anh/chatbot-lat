<template>
    <form >
        name : {{ nama }} <br/>
        <input class="name" v-model="nama" type="text">
    </form>    
</template>

<script>
    export default {
        data(){
            return{
                nama : ' Your Name '
            }
        }, 

        methods : {
            
        }
    }
</script>

<style>
    .name {
        width: 50%;
        margin-top: 20px; margin-bottom: 20px;
        height: 30px;
        border-radius: 10px;
        border : 0.1px solid rgba(0, 0, 0, 0.619);
        background-color: rgba(180, 180, 204, 0.301);

    }

    .name:hover {
        border: 0.1px solid black ;
        box-shadow: 5px 5px 50px rgba(171, 171, 88, 0.603);
    }
</style>