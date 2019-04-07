<template>
  <div class="name" @click="gb" :class="{reds:istrue}">
    {{name}}
  </div>
</template>

<script>
  export default {
    name: "App",
    data() {
      return {
        name: "zhangwenjun",
        istrue:false
      }
    },
    methods:{
      gb:function () {
        this.istrue = !this.istrue;
        this.name = this.name + 'j';
      }
    }
  }
</script>

<style scoped>
  .name {
    padding: 15px;
  }
  .reds{
    color: crimson;
  }

</style>
