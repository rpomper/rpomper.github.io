---
layout: page
title: Infer
description: Inferring word meaning from text
img: /assets/img/infer.png
importance: 1
project_order: 1
category: ongoing research
---


<div style="text-align:center"> 
  <video id="video1" width="420">
    <source src="/assets/video/Infer_Example.mp4" type="video/mp4">
    <!-- <source src="https://github.com/rpomper/rpomper.github.io/raw/master/assets/video/Infer_Example.mp4" type="video/mp4"> -->
    <!-- <img height=250 alt="Word Learning Lab Logo" src="/assets/img/wll_logo.png"> <br> -->
    <!-- <source src="https://github.com/rpomper/rpomper.github.io/blob/master/assets/video/Infer_Example.mp4" type="video/mp4"> -->
    <!-- <source src="/assets/video/infer.ogg" type="video/ogg"> -->
    Your browser does not support HTML video.
  </video>
  <br>
  <button onclick="playPause()">Play/Pause</button> 
  <button onclick="makeBig()">Big</button>
  <button onclick="makeSmall()">Small</button>
  <button onclick="makeNormal()">Normal</button>
  <br><br>
</div> 

<script> 
var myVideo = document.getElementById("video1"); 

function playPause() { 
  if (myVideo.paused) 
    myVideo.play(); 
  else 
    myVideo.pause(); 
} 

function makeBig() { 
    myVideo.width = 560; 
} 

function makeSmall() { 
    myVideo.width = 320; 
} 

function makeNormal() { 
    myVideo.width = 420; 
} 
</script> 


This project explores how 9- to 11-year-old children with and without Developmental Language Disorder (DLD) infer the meanings of words when reading and listening to text.  <br><br>
It is part of the <a href="https://www.boystownhospital.org/research/speech-language/word-learning/childrens-vocabulary-project">Children's Vocabulary Project</a> in the <a href="https://www.boystownhospital.org/research/speech-language/word-learning/">Word Learning Lab</a> at Boys Town National Research Hospital.
The Children's Vocabulary Project is a longitudinal project funded by the <a href="https://reporter.nih.gov/project-details/10194443">NIH</a> that aims to establish a developmental trajectory of word learning for children with DLD and the underlying cognitive mechanisms.


<img height=250 alt="Word Learning Lab Logo" src="/assets/img/wll_logo.png"> <br>

<a href="https://rpomper.github.io/assets/img/The%20Children's%20Vocabulary%20Project.png">Click here</a> for our a summary of what we did, what we learned, and why it matters. <br><br>
<a href="https://rpomper.github.io/assets/img/Infer_SRCLD.png">Click here</a> for our poster presented at SRCLD in 2023. <br>
<a href="https://rpomper.github.io/assets/pdf/Infer_References.pdf">Click here</a> for the full list of references for our poster. <br>
And <a href="https://rpomper.github.io/assets/pdf/Infer_Stories.pdf">click here</a> for the full set of stories included in the experiment.

Citation:
> Pomper, R., Reed, D. K., Eden, N., Arbisi-Kelm, T., & McGregor, K. K. (2023, June).
How children with and without Developmental Language Disorder infer word meaning from written and spoken text.
Poster presented at the Symposium for Research on Child Language Disorders, Madison, WI.


<div class="projects">
  <div class="contact-icons">
    <!-- <a href="https://osf.io/pzew4" title="OSF"><i class="ai ai-osf"></i></a> -->
    <!-- <a href="https://github.com/rpomper/PreFam" title="GitHub"><i class="fab fa-github"></i></a> -->
    </div>
<br>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/infer.png' | relative_url }}" alt="" title="example paragraph"/>
    </div>
</div>
<div class="caption">
    Example of a paragraph from a fourth grade reader with one noun, one adjective, and one verb replaced with blanks.
</div>
