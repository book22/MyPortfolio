<template>
  <div class="card">
    <h1>{{ title }}</h1>
    <table>
      <tr>
      <th>技術</th>
      <th>経験年数</th>
      </tr>
      <tr v-for="(item, index) in items" :key="index">
        <td>{{ item.context }}</td>
        <td>{{ item.value }}年</td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  props: ['title','items']
}
</script>
<style scoped>
 .card {
   height:420px;
   width: 43%;
   background-color: rgb(227, 232, 255);
   text-align: center;
   margin: auto;
   margin-top: 28px;
   font-size: 20px;
 }



 h1 {
   padding-top: 50px;
   padding-bottom: 30px;
   text-decoration: underline;
   font-size: 28px;
 }

 table {
   border: noen;
   width: 100%;
 }

 th {
   width: 50%;
 }

 td {
   text-align: left;
   padding-left: 20%;
 }
</style>