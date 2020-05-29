<template>
  <!-- div消しても動くか今度テストする -->
  <div>
      <header class="header">
        <h1 class="header_title">
          <img src="/" class="header_title_logo" alt="タイトルロゴ">
        </h1>
        <address class="header_tel">
          <a href="tel:08089186908" class="header_telnumber">080-8918-6908</a>
        </address>
      </header>
      <div class="">
        <!-- この辺グリッドレイアウトを使う -->
        <!-- キャッチコピー -->
        <!-- 権威付け -->
        <!-- メインビジュアル -->
      </div>
      <button class="cv_btn">商品LPの制作を相談する[無料]</button>
      <!-- 導入・きっかけ -->
      <!-- ベネフィット -->
      <button class="cv_btn">商品LPの制作を相談する[無料]</button>
      <!-- 商品・サービス説明 -->
      <button class="cv_btn">商品LPの制作を相談する[無料]</button>
      <!-- お客様の声・口コミ -->
      <button class="cv_btn">商品LPの制作を相談する[無料]</button>
      <!-- FAQ -->
      <button class="cv_btn">商品LPの制作を相談する[無料]</button>
      <footer class="footer">
        <small>&copy; 2020 HP制作ブランド「Ratpost_hp」</small>
      </footer>
  </div>
</template>
<script>

</script>
<style scoped>
  a {
    text-decoration: none;
  }
  .header {
    display: flex;
    justify-content: space-around;
    align-items: center;
  }
  .header_telnumber {
    color: #000000;
    font-weight: bold;
  }
  .cv_btn {
    border: 0;
    background-color: #FF3300;
    border-radius: 4px;
    color: #ffffff;
    font-weight: bold;
    padding: 8px;
  }
  .footer {
    background-color: #2e2e2e;
    color: #ffffff;
    padding: 8px;
    text-align: center;
  }
</style>
