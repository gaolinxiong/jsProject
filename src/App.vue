<template>
    <div class="container">
        <p @click="handleName">高林雄</p>
      {{todoList}}
      {{onShowList}}
    </div>
</template>
<script>
  export default ({
    name: 'app',
    data() {
      return {
        todoList: [],
        onShowList: [123]
      }
    },
    methods: {
      handleName() {
        console.log('高林雄')
      }
    }
  })
</script>

<style>
    @import 'assets/index.less';
</style>
