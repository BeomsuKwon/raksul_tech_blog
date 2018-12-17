<template>
  <div>
    <el-row>
      <el-button icon="el-icon-search" circle @click="auth()"> {{button}} </el-button>
  </el-row>
  </div>
</template>

<script>
export default {
  data(){
    return {
      button : "login"  
    }
  },
  methods : {
    auth () {
      alert("test")
    }
  }
}

</script>
