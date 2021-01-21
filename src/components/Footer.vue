<template>
    <footer>
        <p>Copyright 2021</p>
        <ul>
            <li><a href="https://github.com/book22"><i class="fab fa-github fa-3x"></i></a></li>
            <li><a href="mailto:info@blackaroww0122@gmail.com"><i class="fas fa-envelope fa-3x"></i></a></li>
            <li><a href="https://twitter.com/salon_honsan"><i class="fab fa-twitter fa-3x"></i></a></li>
        </ul>
    </footer>
</template>

<script>
    export default {
        name: 'footer'
    }
</script>

<style scoped>
 p {
     text-align: left;

 }

 footer {
     background-color: rgb(32, 51, 119);
     height: 160px;
     margin: 0;
     padding: 0;
 }

 ul {
     display: flex;
     margin: 0;
     padding-top: 30px;
 }

 li {
     list-style: none;
     padding-left: 20px;
 }

 i {
     color: blanchedalmond;
 }
</style>