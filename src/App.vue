<template>
  <div id="app">
    <h1>{{title}}</h1>
    <TableView></TableView>
  </div>
</template>

<script>
import TableView from './components/table-view.vue'

export default {
  name: 'app',
  components: {
    TableView
  },
   data: function () {
    return {
      title: 'Random users vue app'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.d-flex {
  display: flex;
} 
.h-100 {
  height: 100%;
} 
.w-100 {
  width: 100%;
}
</style>
