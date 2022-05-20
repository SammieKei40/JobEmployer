<template>
  <div>
      <NavBar />      


      <div class="dash-nav" id="dash-nav-box" >
  
        <nuxt-link to="Employers/Post" class="post-job-a" id="n-post-job">Post Job</nuxt-link>

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
                <div class="mag-b center">Update Company Profile</div>
            </div>
            <div class="dash-form-wrap">
                <div class="mag-b ts-13 bm-b-30">
                    <b class="tc-r">Note:</b><br>
                    This information will not be published on your job posts and will not be seen by website visitors.
                </div>
                <form action="" method="post">
                    <div id="job-details-div">
                        <div class="grop-input">
                            <span class="post_div_in_span">Company Name</span><input name="company_name" type="text"   class="input1" required="required">
                        </div>
                        <div class="grop-input"><span class="post_div_in_span">Industry</span>
                            <select name="industry" class="input1" required="required">
                                <option value="">- Select company industry -</option>
                                <option value="1">Engineering / Technical</option>
                                <option value="2">Healthcare / Medical</option>
                                <option value="3">Creative / Arts</option>
                                <option value="4">Education / Teaching</option>
                                <option value="5">Oil and Gas / Marine</option>
                                <option value="6">Manufacturing / Production / FMCG</option>
                                <option value="7">Media / Radio / TV</option>
                                <option value="8">Agriculture / Agro-Allied</option>
                                <option value="9">NGO / Non-Profit Associations</option>
                                <option value="11">Government</option>
                                <option value="12">Building / Construction</option>
                                <option value="13">Hospitality</option>
                                <option value="14">Insurance</option>
                                <option value="15">Law / Legal</option>
                                <option value="17">Consulting</option>
                                <option value="18">Banking / Financial Services</option>
                                <option value="19">Food Services</option>
                                <option value="20">ICT / Telecommunication</option>
                                <option value="21">Travel and Tours</option>
                                <option value="22">Logistics and Transportation</option>
                                <option value="23">Sales / Retail</option>
                                <option value="24">General</option>
                                <option value="25">Real Estate</option>
                                <option value="26">Security</option>
                                <option value="27">Aviation / Airline</option>
                                <option value="28">Pharmaceuticals</option>
                                <option value="29">Religious</option>
                                <option value="30">Advertising / Branding / PR</option>
                                <option value="31">Online Sales / Marketing</option>
                                <option value="32">Professional / Social Associations</option>
                                <option value="33">Janitorial Services / Environment</option>
                                <option value="34">Power / Energy</option>
                                <option value="35">Research</option>
                                <option value="36">Science</option>
                                <option value="37">Internet / E-commerce</option>
                                <option value="38">Raffle</option>
                                <option value="39">Blockchain</option>
                            </select>
                        </div>
                        <div class="grop-input"><span class="post_div_in_span">Company Type</span>
                            <select name="employer_type" class="input1" required="required">
                                <option value="">- Select Company Type -</option>
                                <option value="employer">Direct Employer</option>
                                <option value="recruiter">Recruiting Firm</option>
                            </select>
                        </div>
                        <div class="grop-input"><span class="post_div_in_span">Address</span><input name="address" type="text" placeholder="eg. No. 5 Afolabi Aina Street, Allen, Ikeja"  class="input1" required="required"></div>
                        <div class="grop-input"><span class="post_div_in_span">States</span>
                            <select name="state" class="input1" required="required">
                                <option value="">- Select company location -</option>
                                <option value="156">Abia</option>
                                <option value="155">Abuja</option>
                                <option value="157">Adamawa</option>
                                <option value="158">Akwa Ibom</option>
                                <option value="152">Anambra</option>
                                <option value="159">Bauchi</option>
                                <option value="160">Bayelsa</option>
                                <option value="161">Benue</option>
                                <option value="162">Borno</option>
                                <option value="163">Cross River</option>
                                <option value="164">Delta</option>
                                <option value="153">Ebonyi</option>
                                <option value="165">Edo</option>
                                <option value="166">Ekiti</option>
                                <option value="151">Enugu</option>
                                <option value="167">Gombe</option>
                                <option value="168">Imo</option>
                                <option value="169">Jigawa</option>
                                <option value="170">Kaduna</option>
                                <option value="171">Kano</option>
                                <option value="172">Katsina</option>
                                <option value="173">Kebbi</option>
                                <option value="174">Kogi</option>
                                <option value="175">Kwara</option>
                                <option value="154" ></option>
                                <option value="181">Nasarawa</option>
                                <option value="176">Niger</option>
                                <option value="177">Ogun</option>
                                <option value="178">Ondo</option>
                                <option value="179">Osun</option>
                                <option value="188">Other</option>
                                <option value="180">Oyo</option>
                                <option value="182">Plateau</option>
                                <option value="184">Rivers</option>
                                <option value="183">Sokoto</option>
                                <option value="185">Taraba</option>
                                <option value="186">Yobe</option>
                                <option value="187">Zamfara</option>
                            </select>
                        </div>
                        <div class="grop-input"><span class="post_div_in_span">Phone Number</span><input name="phone" type="text" placeholder=""  class="input1" required="required"></div>
                        <div class="grop-input"><span class="post_div_in_span">Number of Employees</span>
                            <select name="employee_count" class="input1" required="required">
                                <option value="">- No of Employees -</option>
                                <option value="1-5">1-5</option>
                                <option value="6-10" selected="selected">6-10</option>
                                <option value="11-20">11-20</option>
                                <option value="21-50">21-50</option>
                                <option value="51-100">51-100</option>
                                <option value="101-500">101-500</option>
                                <option value="501-5000">501-5000</option>
                                <option value="5001+">5001+</option>
                            </select>
                        </div>
                        <div class="grop-input"><span class="post_div_in_span">Website</span><input name="website" type="text" placeholder="www.yourcompany.com" class="input1"></div>
                        <div class="grop-input"><span class="post_div_in_span">Description</span>
                            <textarea name="description" required="required" class="input1" style="height:200px; padding-top: 15px"> </textarea>
                        </div>
                        <div class="grop-input">
                          <nuxt-link to="Employers/Dash"> 
                            <input name="submit_but" type="submit" class="myButton2 bg-o" value="Update Profile">
                          </nuxt-link></div>

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
    NavBar  }
}
</script>

<style scoped>

</style>