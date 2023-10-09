---
title: Folder Page
permalink: /example-folder/folder-page/
---
<style>
	.wrapper {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(275px, 1fr));
		grid-template-rows: auto-fit;
		column-gap: 20px;
		row-gap: 20px;
	}

	.box {
		border: solid 1px #215732 ;
		border-radius: 5px;
		padding: 5px 10px 15px 10px;
		text-align:center;
	}
	
	a:link.button, a:visited.button {
		text-decoration:none;
		color:#215732
	}
	
	a:hover.button {
	 background-color:#f8f7f3;
	}
</style>

<div class="wrapper">
  <a class="button" href="/page-index/glossary/edible-plants/"><div class="box">
		<h4>Edible Plants</h4>
	     <img src="/images/Graphics/edibleplant_6oct.png"><br>
	</div></a>
	<a class="button" href="/page-index/glossary/ornamental-plants/"><div class="box">
		<h4>Ornamental Plants</h4>
	     <img src="/images/Graphics/ornamentalplant_6oct.png"><br>
	</div></a>
	<a class="button" href="/page-index/glossary/native-plants/"><div class="box">
		<h4>Native Plants</h4>
	     <img src="/images/Graphics/nativeplant_6oct.png"><br>
	</div></a>
	<a class="button" href="/page-index/glossary/biodiversity-attracting-plants/"><div class="box">
		<h4>Biodiversity Attracting Plants</h4>
	     <img src="/images/Graphics/biodivplant_6oct.png"><br>
	</div></a>
</div>