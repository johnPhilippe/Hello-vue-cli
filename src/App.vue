<template>
  <div class="container">
      <div class="top_side">
        <div>
          <h1 class="upper_name">John Philippe Conanan</h1><hr class="hr_name"><br>
          <h3 class="upper_job">Web Developer</h3>
          <img src="./assets/profile.png" alt="profile picture" class="profile_photo">
        </div>
      </div>
       <div class="bot_side">
        <div class="left_side">
          <profile></profile>
          <div class="social_part">
          </div>
        </div>
       <div class="right_side">
         
         <education></education> 
         <skills></skills>
       </div> 
        
       </div>
       
  </div>
</template>

<script>
import Profile from './Components/Profile.vue'
import Skills from './Components/Skills.vue'
import Education from './Components/Education.vue'

export default {
  name: 'app',

  components: {
    Profile,
    Skills,
    Education
  },
  data () {
    return {
      msg: 'Conanan, John Philippe D.'
    }
  }
}
</script>

<style>
*
{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Raleway';
}

body
{
  background: white;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;  
}

h1
{
  position: relative;
  left: 205px;
  font-size: 50px;
  color: #e8f6fa;
}

.hr_name
{
  margin-left: 205px;
  width: 78%;
}

.upper_name
{
  font-family: 'Poppins', sans-serif;
  text-transform: uppercase;
  letter-spacing: 4px;
}

.upper_job
{
  position: relative;
  left: 205px;
  font-size: 30px;
  color: #e8f6fa;
  font-family: 'Poppins', sans-serif;
  text-transform: uppercase;
  font-size: 22px;
  letter-spacing: 4px;
}

.container
{
  position: relative;
  width: 100%;
  max-width: 1000px;
  min-height: 1000px;
  margin: 50px;
  background-color: white;

}

.top_side
{
  position: relative;
  background-color: #0292cc;
  height: 250px;
  padding: 4.5% 0 0 5%;
}

.profile_photo
{
  position: relative;
  border-radius: 50%;
  width: 20%;
  height: 175px;
  bottom: 100px;

}

.bot_side
{
  position: relative;
  background-color: #dfdfdf;
  height: 1000px;
  display: grid;
  grid-template-columns: 1fr 1.8fr;
}

.left_side
{
  position: relative;
  background-color:white;
}

.right_side
{
  position: relative;
  background-color:#dfdfdf;
  padding: 5% 0 0 4%;
}

.profile_part
{
  position: relative;
  background-color:#2c3642;
  padding: 10% 0 0 10%;
  width: 100%;
  height: 70%;
}

.social_part
{
  position: relative;
  background-color:#dfdfdf;
  padding: 10% 0 0 10%;
  top: .2%;
  width: 100%;
  height: 30%;
  
}

.contact
{
  position: relative;
  text-transform: uppercase;
  margin-bottom: 50px;
  font-size: 30px;
  color: #e8f6fa;
}

li
{
  list-style-type: none;
  margin-top: 5px;
  line-height: 35px;
}

.title
{
  font-weight: bold;
  text-transform: uppercase;
  color: #e8f6fa;
}
.icon
{
  display: inline-block;
  width: 35px;
  font-size: 30px;
  color: #0292cc;
}

.details
{
  margin-left: 40px;
  font-size: 14px;
  color: #b2b2b2;
}

.right_title
{
  position: relative;
  text-transform: uppercase;
  margin-bottom: 50px;
  letter-spacing: 4px;
  font-size: 30px;
  color: #27262b;
}

.hr_bot_side
{
  margin-top: 5px;
  width: 50%;
  border: 1px solid #27262b;
}

.p
{
  margin: 30px 20% 50px 0;
  letter-spacing: 0px;
  position: relative;
  text-transform: none;
  font-size: 20px;
  color: #27262b;
}

</style>


