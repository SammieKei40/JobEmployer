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
    <div class="dash-in-wrap">
        <div class="dash-page-title" style="border-bottom:none">
            <div class="mag-b center">Fund Your Job Portal Wallet</div>
        </div>
        <div class="dash-form-wrap">
            <div class="mag-b ts-14 bm-b-30">
                You have<b> ₦0 </b>left in your wallet. You can add more money to your existing balance.
            </div>
            <form action="javascript:;" method="post" enctype="multipart/form-data" onsubmit="processPaymentForm(this,'5000')">
                <div id="job-details-div">
                    <div class="grop-input">
                        <span class="post_div_in_span">How much do you want to deposit? <font color="#FF6600">A job cost ₦5,000</font></span><br>
                        <div class="mag-b">
                            <select class="price-sele-box" onchange="getPayAmount(this)" name="amount2" required="">
                                <option value="">Select Amount</option>
                                <option value="5000">₦5,000</option>
                                <option value="10000">₦10,000</option>
                                <option value="20000">Pay ₦20,000 get ₦30,000</option>
                                <option value="30000">Pay ₦30,000 get ₦45,000</option>
                                <option value="50000">Pay ₦50,000 get ₦75,000</option>
                                <option value="other">Other amount</option>
                            </select>
                        </div>
                        <input style="margin-top: 0px; display: none" id="payment-amount-input" name="amount" value="" placeholder="Enter Amount" class="price-sele-box" required="" type="number">
                        <div class="mag-b bm-t-10 italiz ts-12 tc-b6">Pay ₦20,000 and above to get <span class="tc-o">50% bonus</span></div>
                    </div>
                    <div id="fund-limit-error" class="mag-b ts-14  tc-r" style="display:none">The minimum amount you can fund is <span class="tc-b bold">₦5,000</span></div>
                    <p class="mag-b bm-t-10">
                        <input name="" type="submit" class="myButton2 bg-o bm-r-10" value="Pay Now">
                    </p>
                    <p class="mag-b ts-14 tc-b3"><b>Note:</b> You can pay online, via transfer or bank deposit</p>

                </div>
            </form>
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