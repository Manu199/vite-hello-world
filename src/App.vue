<script>
import Header from './components/Header.vue';

export default {
    name: 'App',
    components: {
        Header
    }
}
</script>
    
<template>
  <Header />
    <h1>Hello World!</h1>

</template>

<style>
    h1 {
        margin: 20px;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-size: 3rem;
        font-weight: 100;
    }
</style>