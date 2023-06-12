<template>
    <div>
    <OrderHeader></OrderHeader>
    orderlist
    <NavFooter></NavFooter>
    </div>   
  </template>
 
 <script>
 import NavFooter from "../components/NavFooter.vue"
 import OrderHeader from "../components/OrderHeader.vue"
 export default {
     name: 'order-list',
    components: {
        NavFooter,
        OrderHeader
    }
 }
 </script>