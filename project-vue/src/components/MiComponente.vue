<template>
    <div id="mi-componente">
        <hr/>
        <h1>Este es mi componente</h1> 
        <h2 v-text="subtitulo"></h2>
        <a v-bind:href="link.href" v-bind="link.title" v-text="link.text" target="blank"></a>
        <hr/>
    </div>
   
</template>

<script>
export default {
    name: 'MiComponente',
    data() {
        return{
            subtitulo: 'Soy el subtitulo de Mi Componente',
            link: {
                text: 'Meneame',
                href: 'https://www.meneame.net/',
                title: 'Enlace web Meneame'
            }
        }
    }
}
</script>