---
marp: true
size: 16:9
---


<style>
section {
  padding: 0 !important;
  background-color: lightyellow;
}

/*
   スライド内の最初の要素が持つ上マージンや、
   最後の要素が持つ下マージンも消したい場合に追加すると、
   より端までコンテンツが配置されます。
*/
section > :first-child {
  margin-top: 0 !important;
}
section > :last-child {
  margin-bottom: 0 !important;
}

/* 横並びレイアウトのためのコンテナ */
.columns-container {
  display: flex; /* Flexbox を有効にする */
  align-items: flex-start; /* アイテムの上端揃え (center, stretch なども可) */

}

/* 横並びにする各アイテム */
.column-item {
  width: 400px;
  background-color: #f0f0f0; /* 背景色 (視覚的な確認のため) */
  border: 1px solid #ccc;    /* 境界線 (視覚的な確認のため) */
  padding: 15px;              /* 内側の余白 */
  box-sizing: border-box;     /* padding と border を width に含める */
  min-height: 350px;
}
</style>

<div class="columns-container">
  <div class="column-item">
    <h3>アイテム 1</h3>
  </div>
  <div class="column-item">
    <h3>アイテム 2</h3>
  </div>
  <div class="column-item">
    <h3>アイテム 3</h3>
  </div>
</div>
<div class="columns-container">
  <div class="column-item">
    <h3>アイテム 1</h3>
  </div>
  <div class="column-item">
    <h3>アイテム 2</h3>
  </div>
  <div class="column-item">
    <h3>アイテム 3</h3>
  </div>
</div>
