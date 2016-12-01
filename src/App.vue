

<script>

    import TopBar from './modules/layout/TopBar.vue'
    import BottonBar from './modules/layout/BottonBar.vue'
    import Main from './modules/layout/Main.vue'

    export default {

        components: { TopBar, Main, BottonBar }

    }
  
</script>

<template>

    <div>
      
        <top-bar></top-bar>
        <main></main>
        <botton-bar></botton-bar>

    </div>

</template>