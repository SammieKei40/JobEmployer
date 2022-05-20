<template>
  <div>
      <NavBar />      


      <div class="dash-nav" id="dash-nav-box" >
  
        <nuxt-link to="Post" class="post-job-a" id="n-post-job">Post Job</nuxt-link>

    <ul class="nav-list">
        <li class="nav-list-li">
            <nuxt-link to="Dash" class="nav-da" >Dashboard</nuxt-link></li>
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
        <div class="job-result" id="job-col-full">
            <h2 class="dash-title center" style="width:100%">Are You Recruiting?</h2>
            <nuxt-link to="Post" class="post-new-job">Post A New Job</nuxt-link>
        </div>
        <ul class="dbox-ul">
            <li class="dbox-ul-li" id="pay-point">
                <div class="mag-b center ts-13 tc-b3 bm-t-80">You have <b>₦0</b> left in your wallet</div>
                <nuxt-link to="Fund" class="pay-job-d">Fund your wallet</nuxt-link>
            </li>
            <li class="dbox-ul-li" id="help-point">
                <div class="ts-18 bm-t-20 center mag-b bm-b-10"> Need help? </div>
                <div class="mag-b center ts-14 tc-b3">
                    <span class="tc-y">☎ Call</span> 07031513232 <br>
                    <span class="tc-y">✉ email</span> services@myjobmag.com
                </div>
                <a href="help" id="need-help-a" class="pay-job-d bg-b6">Send us Message</a>
            </li>
            <li class="dbox-ul-li" id="other-point" style="margin-right:0px;">
                <div class="ts-18 bm-t-20 mag-b bm-b-10 tc-w"> News/Offers </div>
                <ul class="news-offers">
                    <li><span>Load your wallet with a minimum of N20,000 and get a 50% bonus.
                            <nuxt-link class="tc-w" to="Fund">Fund Wallet</nuxt-link></span></li>
                </ul>
            </li>
        </ul>

       
        


    </div>
</div>
</div>
</template>

<script>
import NavBar from "@/components/NavBar";

export default {
  components: {
    NavBar,
  }
}
</script>

<style scoped>

</style>