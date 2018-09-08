<template>
  <div>
    <div class="form-block">
      <div class="item">借款金额</div>
      <div class="item" style="flex-basis: 75%"></div>
      <div class="item">已还金额</div>
      <div class="item"></div>
      <div class="item">未还金额</div>
      <div class="item"></div>
      <div class="item">还款日期</div>
      <div class="item item-content"></div>
      <div class="item">截止还款日期</div>
      <div class="item item-content"></div>
      <div class="item" style="flex-basis: 100%;justify-content: flex-start">备注</div>
    </div>
    话
    <h4>借款金额大写：</h4>
    <table>
      <tr class="">
        <td rowspan="3" style="border-top:0" class="">银行汇款信息</td>
        <td style="border-top:0">收款单位全称：</td>
      </tr>
      <tr class="">
        <td style="border-top:0">银行账号：</td>
      </tr>
      <tr class="">
        <td style="border-top:0">开户银行：</td>
      </tr>
    </table>
    <div class="form-block">
      <div class="item">银行收款信息</div>
      <div class="" style="display: flex">
        <div class="item" style="flex-basis: 50%">收款单位全称</div>
        <div class="item" style="flex-basis: 50%"></div>
        <br>
        <div class="item" style="flex-basis: 50%">银行账户</div>
        <div class="item" style="flex-basis: 50%"></div>
        <br>
        <div class="item" style="flex-basis: 50%">开户银行</div>
        <div class="item" style="flex-basis: 50%"></div>
      </div>
      <div class="item">图片/附件</div>
      <div class="item"></div>
    </div>
  </div>
</template>
<script>/* eslint-disable indent,semi */
export default {
  data() {
    return {};
  },
  components: {},

  computed: {},

  created() {
  },

  mounted() {
  },

  methods: {}
}
</script>

<style scoped>
  .form-block {
    /*width: 200px;*/
    /*height: 150px;*/
    background-color: black;
    display: flex;
    flex-flow: row wrap;
    align-content: flex-start;
    border-right: 1px solid black;
    border-bottom: 1px solid black;
  }

  .item {
    display: flex;
    box-sizing: border-box;
    background-color: white;
    flex: 0 0 25%;
    height: 50px;
    width: 15em;
    vertical-align: middle;
    justify-content: center;
    padding: 6px;
    border-left: 1px solid black;
    border-top: 1px solid black;
  }
  .item-content{
    flex: 1;
  }
</style>
