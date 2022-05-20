<template v-bind:style="{overflow}">
  <div >
      <div class="dash-header" >
    <div class="mjm-name">
        <a id="d-site-logo" href="#" class="logo">Job Portal</a>
        </div>
       <NavDash />
    <a href="#" class="alert-box">&nbsp; </a>
    <a title="Buy more units" href="#" class="units-num">
        <span id="s-unit-no"><b class="tc-o">₦0</b></span>
        <span id="unit-buyn">Top up</span>
    </a>
    <div @click="openNav" class="dash-menu">&nbsp;</div>
</div>

<div class="dash-nav"  v-bind:style="{display}" id="dash-nav-box" >
    <div class="colse-menu-house">
        <div @click="closeNav" class="close-menu">X</div>
    </div>
    <nuxt-link to="Employers/Post" class="post-job-a" id="n-post-job">Post Job</nuxt-link>

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
  </div>
</template>

<script>
import NavDash from "./NavDash";

export default {
    components: {
        NavDash
    },
data(){
        return {
            display: 'none',
            overflow: 'auto',
            top: '24px',
            visibility: 'hidden'
        }
    },
    methods: {
        openNav(){
           this.$data.display = 'block'
            this.$data.overflow = 'hidden'
    
            console.log('Success')
        },
        closeNav(){
            this.$data.display = 'none'
            this.$data.overflow = 'auto'

        },
        openDash(){
            this.$data.top= '-6px',
            this.$data.display= 'block'
           
        },
        closeDash(){
           this.$data.top= '24px',
           this.$data.display= 'none'
        }
    }
    
}
</script>

<style>

</style>