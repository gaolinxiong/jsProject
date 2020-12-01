<template>
    <div class="container">
        <p @click="handleName">高林雄</p>
      {{todoList}}
      {{onShowList}}
      <btn :text="msg"></btn>
    </div>
</template>
<script>
import btn from 'vuecomponentstemplate'

export default ({
    name: 'app',
    data () {
        return {
            todoList: [],
            onShowList: [123],
            msg: '成功'
        }
    },
    components: {
        btn
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
