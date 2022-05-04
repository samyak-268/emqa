---
layout: project
urltitle:  "Episodic Memory Question Answering"
title: "Episodic Memory Question Answering"
categories: embodied ai, egocentric, augmented reality, personal assistants, computer vision, natural language processing
permalink: /
favicon: "/emqa/static/img/emqa/favicon.png"
bibtex: true
paper: true
acknowledgements: "We are grateful to the developers of PyTorch for building an excellent framework.
The Georgia Tech effort was supported in part by NSF, ONR YIP, and ARO PECASE. The views and conclusions contained herein are those of the authors and should not be interpreted as necessarily representing the official policies or endorsements, either expressed or implied, of the U.S. Government, or any sponsor. The webpage template was borrowed from https://embodiedqa.org ."
---

<br>
<!-- paper title -->
<div class="row">
  <div class="col-xs-12">
    <center>
      <h1>Episodic Memory Question Answering</h1>
    </center>
  </div>
</div>

<!-- 
  author list (line 1)
  -- the negative top margin for the whole div is to get it closer to the title
-->
<br>
<div class="row" style="margin-top:-25px;">
  <div class="col-xs-12">
    <center>
      <a style="font-size: 20px;font-weight:200;" href="https://samyak-268.github.io/">
        Samyak Datta <sup>1</sup>
      </a>&nbsp; &nbsp;
      <a style="font-size: 20px;font-weight:200;" href="https://sameerdharur.github.io/">
        Sameer Dharur <sup>1</sup>
      </a>&nbsp; &nbsp;
      <a style="font-size: 20px;font-weight:200;" href="https://vincentcartillier.github.io/">
        Vincent Cartillier <sup>1</sup>
      </a>&nbsp; &nbsp;
      <a style="font-size: 20px;font-weight:200;" href="https://rutadesai.github.io/">
        Ruta Desai <sup>2</sup>
      </a>
    </center>
  </div>
</div>

<!-- 
  author list (line 2)
-->
<br>
<div class="row" style="margin-top:-25px;">
  <div class="col-xs-12">
    <center>
      <a style="font-size: 20px;font-weight:200;" href="https://mukulkhanna.github.io/">
        Mukul Khanna
      </a>&nbsp; &nbsp;
      <a style="font-size: 20px;font-weight:200;" href="https://faculty.cc.gatech.edu/~dbatra/">
        Dhruv Batra <sup>1,3</sup>
      </a>&nbsp; &nbsp;
      <a style="font-size: 20px;font-weight:200;" href="https://faculty.cc.gatech.edu/~parikh/">
        Devi Parikh <sup>1,3</sup>
      </a>
    </center>
  </div>
</div>

<!-- 
  affiliations list
-->
<br><br>
<div class="row" style="margin-top:-25px;">
  <div class="col-xs-12">
    <center>
      <span style="font-size: 20px;font-weight:200;" href="">
        <sup>1</sup> Georgia Tech
      </span>&nbsp; &nbsp;
      <span style="font-size: 20px;font-weight:200;" href="">
        <sup>2</sup> Meta Reality Labs Research
      </span>&nbsp; &nbsp;
      <span style="font-size: 20px;font-weight:200;" href="">
        <sup>3</sup> Meta AI Research
      </span>
    </center>
  </div>
</div>

<!-- 
  teaser figure
-->
<div class="row">
  <div class="col-xs-12">
    <center>
      <img src="{{ "/static/img/emqa/teaser.png" | prepend:site.baseurl }}">
    </center>
  </div>
</div>

<!-- 
  abstract
-->
<div class="row">
  <div class="col-xs-12">
    <center>
      <h1>Abstract</h1>
    </center>
    <br>
    <p>
      Egocentric augmented reality devices such as wearable glasses passively capture visual data as a human wearer tours a home environment. We envision a scenario wherein the human communicates with an AI agent powering such a device by asking questions (e.g., ``where did you last see my keys?''). In order to succeed at this task, the egocentric AI assistant must (1) construct semantically rich and efficient scene memories that encode spatio-temporal information about objects seen during the tour and (2) possess the ability to understand the question and ground its answer into the semantic memory representation. Towards that end, we introduce (1) a new task — Episodic Memory Question Answering (EMQA) wherein an egocentric AI assistant is provided with a video sequence (the tour) and a question as an input and is asked to localize its answer to the question within the tour, (2) a dataset of grounded questions designed to probe the agent’s spatio-temporal understanding of the tour, and (3) a model for the task that encodes the scene as an allocentric, top-down semantic feature map and grounds the question into the map to localize the answer. We show that our choice of episodic scene memory outperforms naive, off-the-shelf solutions for the task as well as a host of very competitive baselines and is robust to noise in depth, pose as well as camera jitter.
    </p>
  </div>
</div>

<br><br>
<hr>

<!-- 
  video
-->
<div class="row">
  <div class="col-xs-12">
    <center>
      <h1>Video</h1>
    </center>
    <br>
    <center>
      <iframe width="100%" height="500" src="https://youtube.com/embed/_K5CPq8kuRE" allowfullscreen></iframe>
    </center>
  </div>
</div>

<br><br>
<hr>

<!-- 
  paper
-->
<div class="row">
  <center>
    <h1>Paper</h1>
  </center>
  <div class="col-xs-6">
    <a href="https://arxiv.org/abs/2205.01652">
        <img height="400" width="400" src="{{ "/static/img/emqa/thumb.png" | prepend:site.baseurl }}">
    </a>
  </div>
  
  <div class="col-xs-6">
    <h2 style="color:#873e23;font-size:20px;font-weight:375;">
      Episodic Memory Question Answering
    </h2>

    <p style="font-size:15px;font-weight:400;">
      Samyak Datta, Sameer Dharur, Vince Cartillier, Ruta Desai, Mukul Khanna, Dhruv Batra, Devi Parikh
    </p>

    <p style="color:red;font-size:15px;font-weight:400;">
      CVPR 2022 (Oral)
    </p>
    <br>
    
    {% highlight bash %}
      @inproceedings{datta2022episodic,
      title={Episodic Memory Question Answering},
      author={Datta, Samyak and Dharur, Sameer and Cartillier, Vince and Desai, Ruta and Khanna, Mukul and Batra, Dhruv and Parikh, Devi},
      booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
      year={2022}
      }
    {% endhighlight %}
  </div>
</div>

<br><br>
<hr>

<!-- 
  data+code
-->
<div class="row">
  <center>
    <h1>Code + Data</h1><br>
    <span style="color:#873e23;font-size:20px;font-weight:375;">Coming soon!</span>
  </center>
</div>

<br>
<hr>

{% if page.acknowledgements %}
<div class="row">
  <div class="col-xs-12">
    <h2>Acknowledgements</h2>
  </div>
</div>
<a name="/acknowledgements"></a>
<div class="row">
  <div class="col-xs-12">
    <p>
      {{ page.acknowledgements }}
    </p>
  </div>
</div>
{% endif %}
