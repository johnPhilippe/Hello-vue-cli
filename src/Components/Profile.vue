<template>
  <div class="profile_part">
            <h3 class="contact">{{msg}}</h3>
            <ul>
              <li>
                <span class="title">Objective</span><br>
                <span class="details">As an aspiring full stack web developer, I am currently attending the Holy Angel university to further my skills in order for me to provide a great service in the future company that I will work on.</span>
              </li>
              <li>
                <span class="title">Name</span><br>
                <span class="details">Conanan, John Philippe D.</span>
              </li>
              <li>
                <span class="title">Course</span><br>
                <span class="details">BS in information technology</span>
              </li>
              <li>
                <span class="title">Specialization</span><br>
                <span class="details">Web development</span>
              </li>
            </ul>
          </div>
</template>

<script>
export default {
  name: 'Profile',
  data () {
    return {
      msg: 'Profile'
    }
  }
}
</script>