<template>
    <footer class="footer">
      <div class="container">
        <div class="footer-content">
          <p>京都デザイン&テクノロジー専門学校</p>
          <p>〒600-8357京都府京都市下京区五条通猪熊西入柿本町596 · ~37.8 km</p>
          <p>0120-109-525</p>
        </div>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    // コンポーネントの設定
  }
  </script>
  
  <style scoped>
  .footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
  }
  .container {
    max-width: 1200px;
    margin: 0 auto;
  }
  .footer-content {
    display: flex;
    flex-direction: column;
  }
  .footer-content p {
    margin: 5px 0;
  }
  </style>
  