<template>
  <div class="container">
    <div class="heading">
      <h1 class="title">Todo List</h1>
      <add-item-form />
    </div>
    <list-view />
  </div>
</template>
<script>
import AddItemForm from "./AddItemForm.vue"
import ListView from "./ListView.vue"
export default {
    components:{
      AddItemForm,
      ListView
    }
} 
</script>
<style scoped>
  .container{
    width: 900px;
    margin: 0 auto;
  }
  .heading{
    background-color: #E6E6E6;
    padding: 10px;
  }
  .title{
    text-align: center;
  }
</style>
