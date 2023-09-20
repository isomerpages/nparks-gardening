---
title: Folder Page
permalink: /example-folder/folder-page/
---
<style>
.wrapper {
  display: grid;
  border:solid 1px;
  grid-template-columns: repeat(auto-fit, minmax(3, 1fr));
  grid-auto-rows: 200px;
  column-gap: 10px;
  row-gap: 10px;
  padding:10px
}

.box{
  border: dotted 1px;
  border-radius: 5px;
  padding: 10px;
}
</style>

<div class="wrapper">
  <div class="box">One</div>
  <div class="box">Two</div>
  <div class="box">Three</div>
  <div class="box">Four</div>
  <div class="box">Five</div>
</div>