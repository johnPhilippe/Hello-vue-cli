<template>
          <div class="right_title">
            <h3>{{msg}} </h3><hr class="hr_bot_side">
            <ul class="p">
                <li>
                  <span>Elementary: St. Scholastica's Academy</span><br>
                  <span>Highschool: University of the Assumption</span><br>
                  <span>College   : Holy Angel University</span>
                </li>
               </ul>
          </div>
</template>

<script>
export default {
  name: 'Educuation',
  data () {
    return {
      msg: 'Education'
    }
  }
}
</script>