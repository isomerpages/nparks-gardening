---
title: Folder Page
permalink: /example-folder/folder-page/
---
<style>
	.wrapper {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
		grid-template-rows: auto-fit;
		column-gap: 10px;
		row-gap: 10px;
	}

	.box{
		border: dotted 1px;
		border-radius: 5px;
		padding: 10px;
	}
	
	.button-primary {
    background-color: #215732;
    border: 2px solid #215732;
    padding: 0.5rem 1rem;
  	border-radius: 1rem;
    color: white !important;
	  text-decoration: none !important;
  }
</style>

<div class="wrapper">
  <div class="box">
		<h4>Soil Calculator</h4>
	      <img style="height:150px; width:200px" src="/images/Digital%20Tools/soilcalc1.png">
				 Find out the volume of soil required for your planter<br>
			<br>
			<a class="button-primary" href="https://staging.dmhtu0pi4p9u7.amplifyapp.com/digital-tools/soilcalculator/">Try it now!</a>
	</div>
  <div class="box">Two</div>
  <div class="box">Three</div>
  <div class="box">Four</div>
  <div class="box">Five</div>
</div>