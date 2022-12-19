---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<!-- <style> -->
<!-- iframe { -->
<!--   height: 100%; -->
<!--   width: 175px !important; -->
<!--   display: inline; -->
<!--   vertical-align:middle; -->
<!--   margin:0px !important; -->
<!--   padding:0px !important; -->
<!--   width: 175px; -->
<!--   display: inline; -->
<!--   vertical-align:middle; -->
<!--   border: 1px solid red; -->
<!-- } -->
<!-- .col-md-3 { -->
<!--   margin:0px !important; -->
<!--   padding:0px !important; -->
<!--   overflow:hidden; -->
<!--   display: table-cell; -->
<!--   text-align:center; -->
<!--   background: white; -->
<!--   width: 175px; -->
<!--   border: 0px solid transparent; -->
<!--   border-radius:20px; -->
<!-- } -->
<!-- </style> -->

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
  <!-- border: 1px solid black; -->
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

  <!-- border: 5px solid red; -->
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- float: none; -->

## Research

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Point Cloud Prediction of Future Movements</h4>
We introduce a Graph Neural Network, that given a point cloud sequence can make accurate prediction of future frames.

We propose a Graph Neural Network that can process irregular point cloud sequences using a graph structure. To this end, we design a Graph-RNN cell that can leverage learned features, describing the local topology, to form spatio-temporal graphs, from where temporal correlations can be extracted as motion features.
The features are then processed by a novel attention model to predict future movements. The attention mechanism allows the network to dynamically model the composition of local and global motions.

</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Graph neural Networks Explanability</h4>

We explain hierarchical features in the context of dynamic point cloud processing. 
We developed a sequence to visualize learned features as motion vectors, and as a result, show what the network learns at each layer.

Specifically, using this technique we have shown: 
* 1) the interpretation of low- and high-level features as local and global motions;
* 2) the importance of different components (Stacking layer, and Multi-resolution layers) of the networks in current state-of-the-art models to achieve a better point cloud predictions. 

</div>
</div>
</div>




<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4> Light Field Image Compression </h4>

This project was focused on the development of efficient scalable light field image coding methods, with random access functionalities and compatible with existing or under development standard image and video (HEVC) encoders

</div>
</div>
</div>
