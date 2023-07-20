<template>
    <button @click="send" type="button">
        {{ button }} 
    </button>
</template>

<script>
    export default {
        data() {
            return {
                button : 'Send Data',
            }
        }, 

        methods : {
            send() {
                this.button = 'Sent'
                alert('data Sent')
            }
        }
    }
</script>

<style>
    button {
        background-color: rgb(182, 176, 227);
        border-radius: 12px;
        border: none;
        box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.445);
        width: 120px; height: 50px;
    }
</style>