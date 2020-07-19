<template>
    <div id="directivas">
        <p>Soy Directivas</p>
        <DirectivaVShow/>
        <DirectivaVIf/>
        <DirectivaVFor/> 
    </div>
   
</template>

<script>
import DirectivaVShow from "./DirectivaVShow.vue";
import DirectivaVIf from "./DirectivaVIf.vue";
import DirectivaVFor from "./DirectivaVFor.vue";

export default {
    name: 'Directivas',
    components: {
        DirectivaVShow,
        DirectivaVIf,
        DirectivaVFor
    },
    data() {
        return{
            
        }
    }
}
</script>