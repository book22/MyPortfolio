<template>
<header>
  <div class="frame">
    <div class="btn">
    <router-link to="/">Home</router-link>
    </div>
    <div class="btn">
    <router-link to="/skills">Skills</router-link>
    </div>
  </div>
</header>
</template>

<script>
    export default {
        name: 'header'
    }
</script>

<style scoped>
.frame {
  background-color: rgb(255, 230, 230);
  height: 40px;
  padding: 40px;
}

a {
  color: rgb(109, 109, 109);
  text-decoration: none;
  font-size: 24px;
}

.btn {
  display: inline-block;
  width: 82px;
  padding: 0.6em 2em;
  cursor: pointer;
  transition: all 0.3s ease 0s;
}

.btn :hover {
  opacity: 0.7;
}



</style>