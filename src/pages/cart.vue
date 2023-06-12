<template>
    <div>
     <OrderHeader></OrderHeader>
    cart
     <NavFooter></NavFooter>
    </div>   
  </template>
 
 <script>
 import NavFooter from "../components/NavFooter.vue"
 import OrderHeader from "../components/OrderHeader.vue"
 export default {
     name: 'detail',
     components: {
        NavFooter,
        OrderHeader
     }
 }
 </script>