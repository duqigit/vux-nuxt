<template>
  <div>

   <box gap="10px 10px">
      <icon type="success"></icon>
      <icon type="info"></icon>
      <icon type="info-circle"></icon>
      <icon type="warn"></icon>
      <icon type="waiting"></icon>
      <icon type="waiting-circle"></icon>
      <icon type="safe-success"></icon>
      <icon type="safe_warn"></icon>
      <icon type="success-circle"></icon>
      <icon type="success-no-circle"></icon>
      <icon type="circle"></icon>
      <icon type="download"></icon>
      <icon type="cancel"></icon>
      <icon type="search"></icon>
      <icon type="clear"></icon>
      <br/>
      <icon type="success" is-msg></icon>
      <icon type="info" is-msg></icon>
      <icon type="warn" is-msg></icon>
      <icon type="waiting" is-msg></icon>
      <icon type="safe_success" is-msg></icon>
      <icon type="safe_warn" is-msg></icon>
    </box>

  </div>
</template>
<script>
  import { Box, Icon } from 'vux'
  export default {
    components: {
    Box,
    Icon
  },
    data() {
      return {
        value1: null,
        value2: null,
        color3: 'rgba(19, 206, 102, 0.8)',
         formInline: {
          user: '',
          region: ''
        }
      }
    },
    methods: {
      onSubmit() {
        console.log('submit!');
      }
    },
    mounted:function(){
        // console.log(vux+"-----");
    }
  }

</script>
<style>
.color{
  /*color: red;*/
}
</style>