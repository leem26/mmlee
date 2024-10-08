---
## Configure page content in wide column
title: "" # leave blank to exclude
number_featured: false # pulling from mainSections in config.toml
use_featured: false # if false, use most recent by date
number_categories: 0 # set to zero to exclude
show_intro: true
intro: |
  <img src="/img/alps_circle.jpeg"
     alt="Markdown Monster icon"
     style="display:block;float:top;margin-top:-100px;margin-bottom:50px;margin-left:auto;margin-right:auto;width:30%"/>

  I'm a postdoctoral research fellow at the Harvard University T.H. Chan School of Public Health, in the Department of Social and Behavioral Sciences My research is focused on evaluating existing and potential social policies and program that are poised to reduce cardiometabolic disease, with a particular emphasis on applying causal inference and simulation based methods. Previously, I completed by PhD in Population Health Sciences at Harvard University (track: Public Health Nutrition) and an SM in Biostatistics at the T.H. Chan School of Public Health (2024). I also completed a Master of Science degree in Epidemiology (2019) as well as a Bachelor of Arts in Public Health (2017) at the University of California, Berkeley, where I first developed my interests in health science. When I'm not knee-deep in `R` code or any ongoing data analysis, I enjoy playing the oboe/English horn ([watch me playing principal oboe on Mahler Symphony No. 6 with the UC Berkeley Symphony Orchestra](https://youtu.be/YQmFBxPhSzw?t=2200)), trying to find the sunniest of hikes, and making (and eating) new foods. Below are examples of some perhaps *less-than-perfectly-healthy* things I've cooked up recently. :cooking: :ramen: :dumpling:

  \- Matt 
  <br><br><br>
  <style>
  * {
    box-sizing: border-box;
  }

  body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
  }

  .header {
    text-align: center;
    padding: 32px;
  }

  .row {
    display: -ms-flexbox; /* IE 10 */
    display: flex;
    -ms-flex-wrap: wrap; /* IE 10 */
    flex-wrap: wrap;
    padding: 0 4px;
  }

  /* Create two equal columns that sits next to each other */
  .column {
    -ms-flex: 33.333%; /* IE 10 */
    flex: 33.333%;
    padding: 0 4px;
  }

  .column img {
    margin-top: 8px;
    vertical-align: middle;
  }

  /* Style the buttons */
  .btn {
    border: none;
    outline: none;
    padding: 10px 16px;
    background-color: #f1f1f1;
    cursor: pointer;
    font-size: 18px;
  }

  .btn:hover {
    background-color: #ddd;
  }

  .btn.active {
    background-color: #666;
    color: white;
  }
  </style>

  <div class="row"> 
  <div class="column">
    <img src="/img/chick.jpg" style="width:100%">
    <img src="/img/matcha.jpg" style="width:100%">
    <img src="/img/beef.jpeg" style="width:100%">
  </div>
  <div class="column">
    <img src="/img/cookies.jpg" style="width:100%">
    <img src="/img/beans.jpeg" style="width:100%">
    <img src="/img/mille.jpg" style="width:100%">
  </div>  
  <div class="column">
    <img src="/img/taco.jpeg" style="width:100%">
    <img src="/img/bread.jpeg" style="width:100%">
    <img src="/img/dukk.jpeg" style="width:100%">
  </div>  
  </div>
  <br><br><br><br><br><br>
  
  

show_outro: false
outro: |
  <i class="fas fa-glass-cheers pr2"></i>Sincere thanks to [Maëlle Salmon](https://masalmon.eu/) for her help naming this Hugo theme!
---

** index doesn't contain a body, just front matter above.
See about/list.html in the layouts folder **

