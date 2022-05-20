<template>
  <div>
      <template>
  <div>
      <NavBar />      


      <div class="dash-nav" id="dash-nav-box" >
  
           <nuxt-link to="Post" class="post-job-a" id="n-post-job">Post Job</nuxt-link>

    <ul class="nav-list">
        <li class="nav-list-li">
            <nuxt-link to="Employers/Dash" class="nav-da" >Dashboard</nuxt-link></li>
        <li class="nav-list-li" id="post-job-li"><nuxt-link to="Post" class="nav-da" id="n-post-job">Post Job</nuxt-link></li>
        <li class="nav-list-li"><nuxt-link to="Fund" class="nav-da" id="n-manage-job" style="  ">Manage Jobs</nuxt-link></li>
        <li class="nav-list-li" id="setting-li"><nuxt-link to="Fund" class="nav-da" id="n-pay-job" style=" background-color:  ">Make Payment</nuxt-link></li>
        <li class="nav-list-li" id="pay-job-li"><nuxt-link to="Transact" class="nav-da" id="n-trans-job" style="  ">Transactions</nuxt-link></li>
        <li class="nav-list-li" id="setting-li"><a href="#" class="nav-da" id="n-help-job" style="  ">Help</a></li>
    </ul>
    <div class="mag-pb-5">
        <a class="mag-pb-2" id="dash-ad" href="#">
            Let's help you hire!
        </a>
    </div>

        </div>


         <div class="dash-house">
            <div class="dash-content">
    <h1 id="trans-h1" class="cd-job-title">Transactions</h1>
    <a href="/employers/payment" class="anko-a  bm-b-5 ts-13 bm-t-5 fl-r bg-o tc-w bp-bt-5 br-5 bp-lr-10">Make Payment</a>
    <a href="/employers/orders" class="anko-a bm-b-5 ts-13 bm-t-5 fl-r bg-b6 tc-w bp-bt-5 br-5 bp-lr-10" style="margin-right: 10px;">View Orders</a>
    <div class="mag-pb-5 bg-w  bp-tb-30 ">
        <ul class="transactions">
            <li id="trans-head" class="bold bm-b-10 tc-o">
                <div id="trans-date" class="mag-b-2">Date</div>
                <div class="mag-b-2">Ref no.</div>
                <div id="trans-desc" class="mag-b-2">Description</div>
                <div class="mag-b-1 center">Type</div>
                <div class="mag-b-2 ta-r">Amount</div>
                <div class="mag-b-2 ta-r">Balance</div>
                <div class="mag-b-1 ta-r">&nbsp;</div>
            </li>
        </ul>
        <div class="mag-b bg-w" style="margin-top: 20px">
        </div>
    </div>

    

</div>
        </div>
</div>
</template>

<script>
import NavBar from "@/components/NavBar";

export default {
  components: {
    NavBar
  }
}
</script>

<style scoped>

</style>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>