<template>
  <div>
    <button id="add" @click="addName" >anniu</button>
  </div>
</template>

<script>

export default {
  name: 'Thankcctv',
  data () {
    return {
      ddd: {}
    }
  },
  methods: {
    addName: function () {
      // document.getElementById('add').innerHTML = 'dddd'
      this.$router.push('login')
      // var element = this
      // axios.get('http://119.23.63.32:8080/springnew/TestController/test.do', {
      // })
      //   .then(function (response) {
      //     element.ddd = response
      //     alert(response)
      //   })
      //   .catch(function (error) {
      //     console.log(error)
      //   })
    }
  }
}
</script>
