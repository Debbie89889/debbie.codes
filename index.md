---
layout: home
title: 資管女子的程式筆記本
---

<style>
body, .inner {
  background-color: #fefae0 !important;
}

h2 {
  color: #d17777;
}

.box {
  background: #fff7ed;
  border: 1px dashed #f4c4a4;
  border-radius: 12px;
  padding: 1.5em;
  margin: 1.5em auto;
  line-height: 1.8;
  width: 90%;
  max-width: 720px;
  box-shadow: 2px 2px 6px rgba(0, 0, 0, 0.05);
}
</style>

<h2>🎀 資管女子的程式筆記本</h2>

<div class="box">

🌸 歡迎來到我的 LeetCode 筆記倉庫！<br>
這裡記錄我學習程式 & 資料結構的旅程 💻<br>
我喜歡寫解題筆記 🧠、整理 Python 小技巧 🐍、分享考試經驗 ✍️<br>
如果你也在學演算法，我們一起加油 💪！

</div>

<div class="box">

📝 <strong>最新筆記</strong><br>
我會每週更新 LeetCode 題目 ✍️<br>
目前正在整理主題：Array、HashMap、DP、字串處理...

</div>

<div class="box">

🐾 <strong>小提醒</strong><br>
📌 點選藍色標題可以進入文章頁面<br>
🔖 我的筆記網址：<br>
👉 <a href="https://debbie89889.github.io/debbie.codes" target="_blank">https://debbie89889.github.io/debbie.codes</a>

</div>

---

## 📝 最近筆記列表

<ul>
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date: "%Y-%m-%d" }}</span> —
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

