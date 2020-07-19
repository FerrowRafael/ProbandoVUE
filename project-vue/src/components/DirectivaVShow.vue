<template>
    <div id="directiva-v-show">
        <button @click="interruptor">Click aqui</button>
        <p v-show="show">Me veo</p>
        <p v-show="!show">NO me veo!</p>
    </div>
   
</template>

<script>
export default {
    name: 'DirectivaVShow',
    data() {
        return{
            show: true
        }
    },
    methods:{
        interruptor(){
            return this.show=!this.show
        }
    }
}
</script>