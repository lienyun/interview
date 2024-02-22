<template>
  <div class="title">
    <h1>文章</h1>
  </div>

  <div class="card">
    <h2>我好像想起</h2>

    <div class="card-content">
      <div class="card-text">
        <h3>張XX 2024-2-22</h3>
        <div class="article">止玩北，借一隻進筆，休來昔貓牙童登、耍行兒乞風四種立米丟戊水爸色下，父到但貝兩助蝴高河蝴，虎寫右百往定出汁幫晚外節三真雪、斤免細亭訴鳥立造教再陽米裏背課寺坐看。更干一手媽固？收乙後。

          對河錯習兩菜已。火寺誰力？里四要唱力；候夕羊牠嗎也果樹是月笑；友坡春許古成斤今松國拉豆火？教校叫士奶，寺幫早放裝想飽

          丟再她助寫，夏爬黃重夕他貓杯里長朵假汁邊，真條想綠綠錯明父師寫生品衣犬夏進。尤八事鴨定穿旁五良平爬哪東愛虎乙：行年年牛葉羽、步美生、說七現動兌圓蛋昔十飛胡多游朱千能平抄魚帶，是以婆豆流肖力登冰。

          浪兆星吉躲巴穿還完至牙院英條重。尾力陽亮弓發包力媽走三春，唱還己因今娘字走還：民乞封步南在候杯幾喝同何丁科，良神不少浪功國新坐冒「家了登你星從交貓」尤請夏蝴昔母。</div>
      </div>
      <div class="photo">
        <img src="/vite.svg" alt="">
      </div>
    </div>

    <div class="footer">
      <div class="tags">
        <span>美文</span>
        <span>故事</span>
        <span>經典</span>
      </div>
      <div class="comment">
        <span>點讚255．</span>
        <span>收藏36．</span>
        <span>評論6．</span>
        <span>觀看585</span>
      </div>

    </div>



  </div>
</template>

<script setup>

</script>

<style scoped>
* {
  outline: 1px pink solid;
}

body,
h2,
h3 {
  margin: 0;
  padding: 0;
}

.card-content {
  display: flex;
  max-height: 200px;
}

.card-text {
  width: 70%;
  flex-grow: 1;
}

.article {
  overflow: hidden;
  text-overflow: ellipsis;
  display: -webkit-box;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
}

.photo {
  width: 30%;
  min-width: 100px;
}

.photo>img {
  width: 100%;
  height: 100%;
}

.title {
  text-align: center;
}

.footer {
  display: flex;
  overflow: hidden;
  height: 24px;
}

.tags > span {
  background-color: yellow;
  margin-right: 0.5rem;
}


</style>
