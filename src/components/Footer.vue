<template>
    <footer>
        <p>Copyright 2021</p>
        <ul>
            <li><a href="https://github.com/book22"><i class="fab fa-github fa-2x"></i></a></li>
            <li><a href="mailto:info@blackaroww0122@gmail.com"><i class="fas fa-envelope fa-2x"></i></a></li>
            <li><a href="https://twitter.com/salon_honsan"><i class="fab fa-twitter fa-2x"></i></a></li>
            <li class="btn">
                <a href="https://chatbot-demo-4565a.web.app/" class="btn-square">チャットボット</a>
            </li>
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
     color: rgb(109, 109, 109);
    font-size: 8px;
 }

 footer {
     background-color: rgb(255, 230, 230);
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
     color: rgb(109, 109, 109);
 }

 .btn{
     margin-left: auto;
     padding-right: 30px;
 }

.btn-square {
  display: inline-block;
  padding: 0.5em 1em;
  text-decoration: none;
  background: #66d8d8;
  color: #FFF;
  border-bottom: solid 4px #629592;
  border-radius: 6px;
}
.btn-square:active {
  /*ボタンを押したとき*/
  -webkit-transform: translateY(4px);
  transform: translateY(4px);
  border-bottom: none;
}

</style>