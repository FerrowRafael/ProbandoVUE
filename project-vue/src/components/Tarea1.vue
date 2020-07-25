<template>
    <div @click="upps">
        <h1>{{titulo}}</h1>
        <button @click.stop="saludar">Saludar</button>

    </div>
   
</template>

<script>
export default {
    name: 'Tarea1',

    data() {
        return{
            titulo: 'Saludo para ti',
            nombre: "Rafa",
            pais: "Españita",
            clickAfuera: 'No hagas clic en el botón'
        }
    },
    methods:{
        upps(){
            alert(this.clickAfuera)
            return 
        },

        saludar(){
            alert(`Hola mi nombre es ${this.nombre} y soy de ${this.pais}`)
            return 
        }
    }
}
</script>