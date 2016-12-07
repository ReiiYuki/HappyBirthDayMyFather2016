<template lang="html">
  <div class="topping section " align="center">
    <img class="circle image is-128x128" src="../assets/head.jpg"/>
    <h1 class="title is-1">{{msg}}</h1>
    <h1 class="title is-2">ขอให้มีความสุขมากๆ สุขภาพแข็งแรงนะครับ</h1>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg:"Happy Birthday My Father <3"
    }
  },
  computed: {},
  mounted () {},
  methods: {},
  components: {}
}
</script>
<style>
.topping{
  top: 50%;
  left:50%;
  position: fixed;
  z-index: 999;
	transform: translateY(-50%) translateX(-50%);
}
.section {
  /*border-radius: 2%;*/
  background: #ffffff;
  opacity: 0.9;
  width: 100%;
  font-family: 'Prompt', sans-serif;
}
.circle{
  border-radius: 100%;
}
</style>
