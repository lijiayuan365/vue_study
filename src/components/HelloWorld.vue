<template>
  <div class="table">
    <h2>借款单</h2>
    <div class="form-block table-header">
      <div class="form-item ">借款主题：291212112借款单</div>
      <div class="form-item">所属部门：人力资源部</div>
      <div class="form-item">填单日期：2019/11/20</div>
      <div class="form-item">单据类型：部门报销单</div>
      <div class="form-item">借款单号：J201510224717</div>
      <div class="form-item">审批状态：审批中</div>
    </div>
    <div class="form-block table-loan">
      <div class="form-item">借款金额</div>
      <div class="item-content form-item " style="flex: 1 1 52%;"></div>
      <div class="form-item">已还金额</div>
      <div class="form-item item-content" style="flex: 1 1 25%;"></div>
      <div class="form-item">未还金额</div>
      <div class="form-item item-content" style="flex: 1 1 25%;"></div>
      <div class="form-item">借款日期</div>
      <div class="form-item item-content" style="flex: 1 1 25%;"></div>
      <div class="form-item">截止还款日期</div>
      <div class="form-item item-content" tyle="flex: 1 1 25%;"></div>
      <div class="form-item" style="text-align: left;flex-basis: 100%">备注</div>
    </div>
    <h4>金额大小写</h4>
    <div>银行收款信息</div>
    <div>审批意见详情</div>
    <div>还款流程详情</div>
    <div>借款单底部</div>
    <!--<ul>-->
    <!--<li>text i</li>-->
    <!--<li>text i</li>-->
    <!--<li>text i</li>-->
    <!--<li>text i</li>-->
    <!--<li>text i</li>-->
    <!--<li>text i</li>-->
    <!--<li>text i</li>-->
    <!--<li>text i</li>-->
    <!--</ul>-->
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data() {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .table {
    margin: 40px 50px 0 50px;
    padding: 80px 40px 80px 40px;
    /*width: 60rem;*/
    /*height: 28rem;*/
    border: 1px solid black;
  }

  .form-block {
    display: flex;
    flex-wrap: wrap;
    /*border-left: 1px solid black;*/
    /*border-right: 1px solid black;*/
    /*border: 1px solid black;*/
    justify-content: space-between;
    text-align: left;
  }
  .item-content{
    flex: 1 1 25%;
    /*flex-grow: 1;*/
  }
  .form-item {
    /*flex-basis: 25%;*/
    /*flex-shrink: 0;*/
    flex:0 1 25%;
    padding: 6px;
    text-align: center;
    border-left: 1px solid black;
    border-top: 1px solid black;
  }

  .table-header .form-item {
    /*flex-basis: 26%;*/
    text-align: left;
    flex: 1 1 26%;
    border: none;
  }
</style>
