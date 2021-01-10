<template>
  <div id="app">
  <products-list-one></products-list-one>
  <products-list-two></products-list-two>  
  </div>
</template>

<script>
import ProductsListOne from "./components/ProductsListOne";
import ProductsListTwo from "./components/ProductsListTwo";

export default {
  name: 'App',
  components:{
    'products-list-one': ProductsListOne,
    'products-list-two': ProductsListTwo
  },
  data(){
    return{
      
    }
  }

}
</script>

<style>
</style>
