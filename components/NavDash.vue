<template>
  <div @click="openDash">
     <div class="uza-info" @click="closeDash"   v-bind:style="{top}">
        <span class="uza-pic"><img src="~/assets/Img/2.png"  width="100%"></span>
        <span class="uza-name">Username</span>
        <div style="margin: 14px">
            <ul   class="dash-menu-list" v-bind:style="{display}"  id="dash-menu-list">
            <li><nuxt-link to="settings">Company Settings</nuxt-link></li>
            <li><nuxt-link to="info">Personal Info</nuxt-link></li>
            <li><a href="#">Change Profile Photo</a></li>
            <li><a href='#'>Change Password</a></li>
            <li><a  href="https://jobportal01.netlify.app">Logout</a></li>
        </ul>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  data(){
    return {
          display: 'none',
            top: '24px',
    }
  },
  methods: {
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