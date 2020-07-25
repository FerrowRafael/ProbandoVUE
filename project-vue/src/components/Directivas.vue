<template>
    <div id="directivas">
        <p>Soy Directivas</p>
        <DirectivaVShow/>
        <DirectivaVIf/>
        <DirectivaVFor/> 
        <Tarea1/>
    </div>
   
</template>

<script>
import DirectivaVShow from "./DirectivaVShow.vue";
import DirectivaVIf from "./DirectivaVIf.vue";
import DirectivaVFor from "./DirectivaVFor.vue";
import Tarea1 from './Tarea1.vue';

export default {
    name: 'Directivas',
    components: {
        DirectivaVShow,
        DirectivaVIf,
        DirectivaVFor,
        Tarea1
    },
    data() {
        return{
            
        }
    }
}
</script>