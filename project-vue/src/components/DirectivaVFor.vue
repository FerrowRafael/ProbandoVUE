<template>
    <div id="directiva-v-for">
        <p v-text="hola"></p>
        <ul>
            <li v-for="(fruta, index) in frutas" :key="index" v-text="fruta"></li>
        </ul>
        
        <!-- Lista objetos- clave valor -->
        <ul>
            <li v-for="(item, key, index) in object_list" :key="index">
                {{ key }}: {{item}}
            </li>
        </ul>

        <!-- Lista objetos complejos -->
        <ul>
            <li v-for="(item, key, index) in other_list" :key="index">
                Nombre: {{item.name}} <br/>
                Apellidos: {{item.last_name}} <br/>
                Nick: {{item.nick}} <hr/>
            </li>
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
            object_list:{
                name: "Pepe",
                last_name: "Pipa",
                nick: "PepePipa777"
            },
            other_list: [
                {
                name: "Pepe",
                last_name: "Pipa",
                nick: "PepePipa777"
            },
            {
                name: "Antonio",
                last_name: "Gomez",
                nick: "AntoGo"
            },
            {
                name: "Pili",
                last_name: "Mili",
                nick: "Pilimili"
            }
            ]
        }
    },
    methods:{
        
    }
}
</script>