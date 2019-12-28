# The Duckietown Object Detection Dataset
<h2>Table of Contents</h2>
<p align="right">
  <a href="https://www.duckietown.org/"><img align="right" src="https://www.duckietown.org/wp-content/uploads/2018/05/duckie2-300x270.png" alt="Vehicle Avoidance Behind" style="width:100%"></a>
</p>
<ul>
      <li><a href="#download">Download</a></li>
      <li><a href="#overview">Overview</a></li>
      <li><a href="#categories">Category Details</a></li>
      <ol>
            <li><a href="#cones">Traffic Cones</a></li>
            <li><a href="#duckies">Duckies</a></li>
            <li><a href="#duckiebots">Duckiebots</a></li>
      </ol>
      <li><a href="#collection">Data Collection Procedure</a></li>
      <li><a href="#annotation">Data Annotation Procedure</a></li>
</ul>


<a name="download"/>
## Download
This dataset can be found <a href="https://drive.google.com/drive/folders/1cTBoKrXJb0kajBGxhuBxJpbKaotHPX7O">here</a>. We provide annotations and a sample script to load the annotations.

<a name="overview"/>
## Overview
In this work, we first identify most prominent objects. In the duckietown, we see duckies, duckiebots and cones on the road. To achieve this, we find useful logs containing all these obstacles. We preprocess these logs to get diverse set of frames with multiple obstacles. 
<table>
      <tr><td>Number of images</td><td>1956</td></tr>
      <tr><td>Number of object categories</td><td>3</td></tr>
      <tr><td>Number of objects annotated</td><td>5068</td></tr>
</table>

<a name="categories"/>

## Category Details
<ol>
<a name="cones"/>
<li><h3>Traffic Cones</h3>
<table>
      <tr><td>Category name</td><td>cone</td></tr>
      <tr><td>Number of instances</td><td>372</td></tr>
      <tr><td>Category id</td><td>1</td></tr>
</table></li>

<a name="duckies"/>
<li><h3>Duckies</h3>
<table>
      <tr><td>Category name</td><td>duckie</td></tr>
      <tr><td>Number of instances</td><td>2570</td></tr>
      <tr><td>Category id</td><td>2</td></tr>
</table></li>

<a name="duckiebots"/>
<li><h3>Duckiebots</h3>
<table>
      <tr><td>Category name</td><td>duckiebot</td></tr>
      <tr><td>Number of instances</td><td>2126</td></tr>
      <tr><td>Category id</td><td>3</td></tr>
      <tr><td>Number of older Duckiebot instances</td><td>1419</td></tr>
      <tr><td>Number of newer Duckiebot instances</td><td>707</td></tr>
</table></li>
</ol>
<a name="collection"/>
## Data Collection Procedure

<a name="annotation"/>
## Data Annotation Procedure

