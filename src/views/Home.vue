<template>
<div >
  <div class="main">
    <div class="wrap">
    <h1>自己紹介</h1>
    <div class="self">
      <div class="pic">
        <img src="../assets/image.jpeg" alt="pic" width="220px">
      </div>
      <div class="text">
      <ul>
        <li>名前：本條祐一朗</li>
        <li>出身：大阪（東京在住）</li>
        <li>学歴：日本大学経済学部</li>
        <li>趣味：読書・筋トレ</li>
        <p> 高校時代は野球で大阪ベスト４。<br>
            大学時代に広告研究でWEB媒体に惹かれ独学を開始。<br>
            大学２年生になるとWEB制作の長期インターンに勤めた。
        </p>
      </ul>
      </div>
    </div>
    </div>

    <div class="wrap">
    <div class="text">
    <p>
      経済学部に在学中なので文系ですが、独学でプログラミングを勉強開始。<br>
      躓いたことも少なくなかったけれど、検索する力や解決能力が向上するように試行錯誤勉強してきました。<br>
      習得する勉強だけでなく、新しい物事を見つけ出す勉強を心掛けてきました。<br>
      これからは勉強ももちろんなことですが、人々がより良い生活を送っていけるサービスを提供する人材になりたいです。
    </p>
    </div>
    </div>

    <div class="about">
    <h4>このページについて</h4>
    <p>
      VueRouterを用いて作成。GitHubPagesに載せています。<br>
      前回はReact.jsで作成しました！
    </p>
    <a class="btn" href="https://book22.github.io/Portfolio/">React</a>

    </div>
  </div>

</div>
</template>

<style scoped>
.main {
  width: 80%;
  margin: auto;
  font-size: 22px;
  color: rgb(82, 82, 82);
}

.wrap {
  margin-top: 80px;
}

ul {
  list-style: none;
}

.self {
  display: flex;
  justify-content:space-around;
}

.text {
  /* width: 40%; */
  text-align: left;
}

img {
  border-radius: 50%;
}

p {
  font-size: 18px;
}

a {
  text-decoration: none;
}

.about {
  text-align: left;
  margin-top: 120px;
}

.about > p {
  font-size: 15px;
}

.btn{
  display: inline-block;
  width: 180px;
  height: 46px;
  text-align: center;
  line-height: 46px;
  color: #fff;
  background: rgb(95, 95, 95);
  border: 2px solid rgb(77, 76, 76);
  position: relative;
  padding: 0 0 0 10px;
}
.btn:before {
  content: "";
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 5px 0 5px 10px;
  border-color: transparent transparent transparent #fff;
  position: absolute;
  top: 40%;
  left: 0;
  right: 90px;
  margin: auto;
}
.btn:hover{
  color: #333;
  background: #fff;
}
.btn:hover:before{
  border-color: transparent transparent transparent #333;
}
</style>

