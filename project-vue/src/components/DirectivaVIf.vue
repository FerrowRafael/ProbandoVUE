<template>
    <div id="directiva-v-if">
        <div v-if="Math.random() > 0.5">
            Now you see me
        </div>
        <div v-else>
            Now you don't
        </div>
    </div>
   
</template>

<script>
export default {
    name: 'DirectivaVIf',

    data() {
        return{
        }
    },
    methods:{
        
    }
}
</script>