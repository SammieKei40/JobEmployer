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
       <div class="settings-cat">
    <h2>Personal Info</h2>
    <div class="mag-b bm-t-20">
        <form action="" enctype="multipart/form-data" method="post" class="mag-b-66 ts-14" id="user-info-detail">
            <div class="mag-b bm-b-40" id="warning_box">
                <h2>Warning</h2>
                <div id="warning_box_info">
                    <ul></ul>
                </div>
            </div>
            <div class="mag-b bm-b-15">
                <div class="user-info-5">First Name:</div>
                <div class="user-info-6"><input required="" name="first_name" class="user-input" type="text" ></div>
            </div>
            <div class="mag-b bm-b-20">
                <div class="user-info-5">Last Name:</div>
                <div class="user-info-6"><input required="" name="last_name" class="user-input" type="text" ></div>
            </div>
            <div class="mag-b bm-b-20">
                <div class="user-info-5">Birthday:</div>
                <div class="user-info-6">
                    <div class="mag-b-66">
                        <select class="user-input" name="bday" required="">
                            <option value="">dd</option>
                            <option>1</option>
                            <option>2</option>
                            <option>3</option>
                            <option>4</option>
                            <option>5</option>
                            <option>6</option>
                            <option>7</option>
                            <option>8</option>
                            <option>9</option>
                            <option>10</option>
                            <option>11</option>
                            <option>12</option>
                            <option>13</option>
                            <option>14</option>
                            <option>15</option>
                            <option>16</option>
                            <option>17</option>
                            <option>18</option>
                            <option>19</option>
                            <option>20</option>
                            <option>21</option>
                            <option>22</option>
                            <option>23</option>
                            <option>24</option>
                            <option>25</option>
                            <option>26</option>
                            <option>27</option>
                            <option>28</option>
                            <option>29</option>
                            <option>30</option>
                            <option>31</option>
                        </select>
                    </div>
                    <div class="mag-b-66">
                        <select class="user-input" name="bmonth" required="">
                            <option value="">mm</option>
                            <option value="1">Jan</option>
                            <option value="2">Feb</option>
                            <option value="3">Mar</option>
                            <option value="4">Apr</option>
                            <option value="5">May</option>
                            <option value="6">Jun</option>
                            <option value="7">Jul</option>
                            <option value="8">Aug</option>
                            <option value="9">Sep</option>
                            <option value="10">Oct</option>
                            <option value="11">Nov</option>
                            <option value="12">Dec</option>
                        </select>
                    </div>
                </div>
            </div>
            <div class="mag-b">
                <div class="user-info-5">&nbsp;</div>
                <div class="user-info-6"><input name="update-uzer" type="submit" value="Save" class=" update-but2 bg-o"></div>
            </div>
        </form>
    </div>
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