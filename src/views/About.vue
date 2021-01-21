<template>
  <div class="skills">
    <Skillcard 
    :title="'コーディング'"
    :items="[
      {context: 'HTML', value: 3},
      {context: 'CSS', value: 3}
    ]"
    />
    <Skillcard 
    :title="'フロントエンド'"
    :items="[
      {context: 'JavaScript', value: 3},
      {context: 'Vue.js', value: 1},
      {context: 'React.js', value: 1}
    ]"
    />
    <Skillcard 
    :title="'バックエンド'"
    :items="[
      {context: 'node.js', value: 1},
      {context: 'Ruby on Rails', value: 2},
      {context: 'php(wp)', value: 2}
    ]"
    />
    <Skillcard 
    :title="'DB'"
    :items="[
      {context: 'Sqlite3', value: 1},
      {context: 'Firebase', value: 1}
    ]"
    />
    <Skillcard 
    :title="'その他'"
    :items="[
      {context: 'git', value: 2},
      {context: 'slack', value: 2},
      {context: 'Photoshop', value: 3},
      {context: 'PremierPro', value: 3}
    ]"
    />
  </div>
</template>

<script>
 import Skillcard from '../components/Skillcard.vue'

  export default {
    components: {Skillcard},
  }
</script>

<style scoped>
 .skills {
   display: flex;
   flex-wrap: wrap;
   width: 80%;
   margin: auto;
   font-size: 22px;
 }
</style>