<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
//import axios  from 'axios'  //导入插件
//import jsonp  from 'jsonp'
export default {
  name: 'App',
  components: {

  },
  data(){
    return{
      
    }
  },
  mounted(){



    // 跨域请求 实例
    // let url  = 'https://www.easy-mock.com/mock/5b012c1fe6e1035843aff/table/list';
    // axios.get(url).then((result)=>{
    //   console.log(result);
    // })
    // let url1 = '/api/common/adver-getadver';
    // let url2 = '/api/activity/servicetime';
    // jsonp(url2, (error, result)=>{ 
    //   console.log(result);
    // })
    // jsonp(url1, (error, result)=>{ 
    //   console.log(result);
    // })
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
