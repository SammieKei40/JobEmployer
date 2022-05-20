<template>
  <div>
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
    <div class="job-result" style="width:94%; margin-bottom:30px; padding-bottom:30px;">
        <div class="dash-title center ts-12 tc-o" style="width:100%; color:#F60">Oops!</div>
        <div class="mag-b center ts-20 bold bm-t-20 bm-b-10" style="width:100%">Insufficient Funds</div>
        <div class="mag-b ts-14 tc-b9 center">
            You can't post a job now because you have insufficient funds</div>
        <nuxt-link to="Fund" class="post-new-job">Fund Your Account</nuxt-link>
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