<template>
    <div id="directiva-v-for">
        <p v-text="hola"></p>
        <ul>
            <li v-for="(fruta, index) in frutas" :key="index" v-text="fruta"></li>
        </ul>
        
    </div>
   
</template>

<script>
export default {
    name: 'DirectivaVFor',
    
    data() {
        return{
            hola: "holiwi",
            frutas:['platano','pera','manzana','melon','uva'],
        }
    },
    methods:{
        
    }
}
</script>