---
layout: page
title: Infer
description: Inferring word meaning from text
img: /assets/img/infer.png
importance: 1
project_order: 1
category: ongoing research
---

This project is part of the <a href="https://www.boystownhospital.org/research/speech-language/word-learning/childrens-vocabulary-project">Children's Vocabulary Project</a> in the <a href="https://www.boystownhospital.org/research/speech-language/word-learning/">Word Learning Lab</a> at Boys Town National Research Hospital.
The Children's Vocabulary Project is a longitudinal project funded by the <a href="https://reporter.nih.gov/project-details/10194443">NIH</a> that aims to establish a developmental trajectory of word learning for children with DLD and the underlying cognitive mechanisms.


<img height=250 alt="Word Learning Lab Logo" src="/assets/img/wll_logo.png"> <br>

<h2> What we did </h2>

<h5> How do children infer the meanings of words? </h5>

<p>When we encounter an unfamiliar word, we often use context (the other words in the sentence & paragraph) to infer its meaning. Children with Developmental Language Disorder (DLD) struggle to learn new words. In this project, we compared how well children with and without DLD infer the meanings of words while reading and listening to short paragraphs.</p>

<p>To do this, we selected texts from grade-appropriate readers. From each text, we replaced one noun, one adjective, and one verb with blanks. We then asked 9- to 11-year-old children with and without DLD to guess the word that best fit in each blank.</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/infer_animaleyes.png' | relative_url }}" alt="" title="example paragraph"/>
    </div>
</div>
<div class="caption">
    Example of a paragraph from a fourth grade reader with one noun, one adjective, and one verb replaced with blanks.<br><a href="https://rpomper.github.io/assets/pdf/Infer_Stories.pdf">Click here</a> for the full set of stories included in the experiment.
</div>



<p>Children's guesses were scored as correct if they matched any of the words included in a set of 20 adults' responses. "Incorrect" guesses, those that were not include, in the adults' responses fell into several different categories: 
<ul>
  <li>Semantic: although technically true, the word is too generic or vauge</li>
  <li>Repetition: repeat of a word from the paragraph/sentence</li>
  <li>Syntactic: sentence is not grammatically correct</li>
  <li>IDK: "I don't know" or did not respond</li>
  <li>Unrelated: does not fit the theme of the paragraph/sentence</li>
  <li>Phrase: a multi-word answer (instructed to provide one word)</li>
  <li>Word Form: a made-up word (often resembling a real word)</li>
</ul>
</p>

<style>
  button{
    color: var(--global-text-color);
    border-color: var(--global-text-color);
    border: 1px solid var(--global-text-color);
    background-color: var(--global-bg-color);
    padding: 3px 18px;
    margin: 5px;
    }
  button:hover{
    color: var(--global-theme-color);
    border-color: var(--global-theme-color);
    }

  .btn.outline {
    padding-left: 1rem;
    padding-right: 1rem;
    padding-top: 0.25rem;
    padding-bottom: 0.25rem;
    color: var(--global-text-color);
    border-color: var(--global-text-color);
    border: 1px solid var(--global-text-color);
  }
  .btn.outline:hover {
    color: var(--global-theme-color);
    border-color: var(--global-theme-color);
    border: 1px solid var(--global-theme-color);
  }
</style>

<div style="text-align:center"> 
  <video id="video1" width="360" loop controls='true' autoplay>
    <source src="/assets/video/Infer_Example.mp4" type="video/mp4">
    Your browser does not support HTML video.
  </video>
  <br>
    <button type='button' class='btn outline z-depth-0' onclick="makeBig()">Big</button>
    <button type='button' class='btn outline z-depth-0' onclick="makeNormal()">Normal</button>
    <button type='button' class='btn outline z-depth-0' onclick="makeSmall()">Small</button>
    <!-- <button onclick="makeBig()">Big</button>
    <button onclick="makeNormal()">Normal</button>
    <button onclick="makeSmall()">Small</button> -->
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
    myVideo.width = 800; 
} 

function makeSmall() { 
    myVideo.width = 360; 
} 

function makeNormal() { 
    myVideo.width = 600; 
} 
</script> 

<h2> What we learned </h2>

<ul>
  <li>Children with DLD are less accurate at guessing the missing words</li>
  <li>This difficulty is _not_ specific to reading (inferring while listening is similarly compromised)</li>
  <li>Nouns are easier than verbs and adjectives for children with and witout DLD</li>
  <li>For children with DLD, a greater proportion of "incorrect" guesses were due to poor semantic fit, repetitions, or IDK responses</li>
</ul>

<h5> SRCLD </h5>

We presented this research at the 2023 <a href="https://srcldconference.com">Symposium on Research in Child Language Disorders</a>:

<div class="row">
    <div class="col-la mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/Infer_SRCLD.png' | relative_url }}" alt="" title="example paragraph"/>
    </div>
</div>
<div class="caption">
    <a href="https://rpomper.github.io/assets/img/Infer_SRCLD.png">Click here</a> to download our 2023 SRCLD poster. <br>
</div>

<a href="https://rpomper.github.io/assets/pdf/Infer_References.pdf">Click here</a> for the full list of references for our poster. <br>

Citation:
<!-- <blockquote font-size=12px > -->
Pomper, R., Reed, D. K., Eden, N., Arbisi-Kelm, T., & McGregor, K. K. (2023, June).
How children with and without Developmental Language Disorder infer word meaning from written and spoken text.
Poster presented at the Symposium for Research on Child Language Disorders, Madison, WI.
<!-- </blockquote> -->

<h2> Why it matters </h2>

<p>Word learning occurs across many contexts and is critical to academic, social, and professional success.</p>
<p>To help them learn new words, children with DLD not only need help with reading but also support for understanding and using spoken language.<br>This project suggests that <a href="https://journals.sagepub.com/doi/pdf/10.1177/0265659018815736">interventions improving oral inferential comprehension</a> may improve outcomes for children with DLD in both reading and listening contexts.</p>

 <a href="https://rpomper.github.io/assets/img/The%20Children's%20Vocabulary%20Project.png">Click here</a> to download a pdf summary of this project.


