<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <el-button>element-ui默认按钮</el-button>
    <el-button type="primary" v-on:click="getData">axios get请求</el-button>
  </div>
</template>

<script>
  import axios from 'axios'
  export default {
    name: 'hello',
    data () {
      return {
        msg: 'Welcome to Your Vue Template Project'
      }
    },
    methods: {
      getData: function () {
        let that = this
        axios.get('/user?ID=12345')
        .then(function (response) {
          console.log(response)
        })
        .catch(function (error) {
          console.log(error)
          that.$message({
            message: 'error:404',
            type: 'warning'
          })
        })
      }
    }
  }

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1, h2 {
    font-weight: normal;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }
</style>
