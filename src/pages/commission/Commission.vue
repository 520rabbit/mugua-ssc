<template>
  <div>
    <ul class="tab clearfix">
      <li class="item" :class="{current: num == 1}" v-on:click="change(1)">我的收益</li>
      <li class="item" :class="{current: num == 2}" v-on:click="change(2)">任务佣金</li>
      <li class="item" :class="{current: num == 3}" v-on:click="change(3)">分销佣金</li>
      <li class="item" :class="{current: num == 4}" v-on:click="change(4)">提现管理</li>
    </ul>
    <div class="content">
      <MyEarnings v-show="num == 1" @getMoney="getMoney"></MyEarnings>
      <TaskEarnings v-show="num == 2"></TaskEarnings>
      <AllotEarnings v-show="num == 3"></AllotEarnings>
      <Withdraw v-show="num == 4"></Withdraw>
    </div>
  </div>
</template>

<script>
import MyEarnings from './children/MyEarnings'
import TaskEarnings from './children/TaskEarnings'
import AllotEarnings from './children/AllotEarnings'
import Withdraw from './children/Withdraw'
export default {
  name: 'Commission',
  components: {
    MyEarnings,
    TaskEarnings,
    AllotEarnings,
    Withdraw
  },
  data() {
    return {
      num: 1
    }
  },
  methods: {
    getMoney (val) {
      if (this.$store.state.bankNumber ==  '-3') {
        this.num = val
      } else {
        this.$router.push('withdraw')
      }
    },
    change (num) {
      this.num = num
    }
  }
}
</script>

<style scoped>
.tab {
  margin-top: 20px;
  background: #fff;
  border-bottom: 2px solid #ccc;
  margin-right: 10px;
}
 
.tab .item {
  float: left;
  width: 100px;
  cursor: pointer;
  text-align: center;
  line-height: 36px;
}
 
.current {
  color: #fff;
  background: #FEAD1D;
}

.content {
  margin-right: 10px;
  /* background: #fff; */
}
</style>