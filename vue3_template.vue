<template>
  <div class="自定义">
    <h2>自定义内容</h2>
  </div>
</template>

<script>
  export default {
    name: "自定义",
    components:{},
    props:[],
    data(){
      return {
          
      }
    },
    setup(){},
    methods:{},
    computed:{},
    watch:{},
    // 声明周期函数
    beforeCreate() {},
    created() {},
    beforeMount() {},
    mounted() {},
    beforeUpdate() {},
    updated() {},
    beforeUnmount(){},
    unmounted(){},
    // 使用keep-alive生效
    activated() {},
    deactivated() {}
  }
</script>
<style lang='less'>
  .自定义 {
    display: block;
};
</style>