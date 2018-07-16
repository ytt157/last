<template>
  <div id="app">
   <h2 v-html="title"></h2>
   <h2 v-text="msg"></h2>
  </div>

</template>

<script>
export default {
data(){
  return{
    title:'武汉理工大学信息管理与信息系统',
    msg:'杨婷婷 1602班'
  }
  },
  methods(){

  },
  watch(){

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

}
 html{
   height: 100%; 
  }
body{
  display: flex;
   flex-direction: column;
  align-items:center;
  justify-content: center;
  height: 100%;
  }
</style>
