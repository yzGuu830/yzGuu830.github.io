---
layout: about
title: About
permalink: /
subtitle: A Graduate Student interested in Machine Learning and Artificial Intelligence

profile:
  align: right
  image: yuzhegu_headshot_new.jpg
  image_circular: false # crops the image to make it circular
  more_info:

news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page
---

<div style="font-family: 'Georgia', sans-serif;">

<p>I am a second-year master student in <a href="https://www.ese.upenn.edu">Department of Electrical and Systems Engineering</a> at the <a href="https://www.upenn.edu">University of Pennsylvania</a> with a concentration on Machine Learning and Data Science. I received my dual B.Sc. in Data Science from <a href="https://www.dukekunshan.edu.cn">Duke Kunshan University</a> and <a href="https://www.duke.edu">Duke University</a>, where I worked closely with <a href="https://diaoenmao.com/">Enmao Diao</a> and <a href="https://scholars.duke.edu/person/Peng.Sun1">Peng Sun</a>.</p>

<p>My research interest covers a wide range of topics related to learning representations and modern deep generative models:</p>
<ul>
  <li><strong style="font-weight: bold;">Discrete Representation Learning</strong>: advancing discrete latent variable models for generative models, efficient data compression, and multimodal application</li>
  <li><strong style="font-weight: bold;">Efficient LLMs</strong>: optimizing LLM decoding performance through improved KV cache mechanism and better long-context understanding ability</li>
</ul>

<p><span style="color: darkblue;">I am actively seeking a CS / ECE Ph.D. position related to Machine Learning and Natural Language Processing starting 2025 Fall.</span></p>

<!-- Spacing achieved through CSS margin for the table -->
<table style="margin-top: 20px;">
  <tr>
    <td>
      <strong>Email</strong>: tracygu [at] seas [dot] upenn [dot] edu<br>
      <strong>Google Scholar</strong>: <a href="https://scholar.google.com/citations?user=xdAB6asAAAAJ&hl=en">@scholar</a><br>
    </td>
  </tr>
  <tr>
    <td>
      <strong>Github</strong>: <a href="https://github.com/yzGuu830">@github/yzGuu830</a> <br>
      <strong>Linkedin</strong>: <a href="https://www.linkedin.com/in/yuzheguu">@in/yuzheguu</a><br>
    </td>
  </tr>
</table>

<br><br><br>

<h2>News</h2>

<style>
  /* Target only the 'ul' inside the News section by using a class or ID for News */
  .news-section ul {
    padding-left: 20px; /* Align bullets properly */
  }

  .news-section li {
    display: flex;
    align-items: flex-start;
    list-style-type: none; /* Remove default bullets */
    margin-bottom: 10px;
  }

  /* Add custom bullet back using ::before for News section only */
  .news-section li::before {
    content: "•"; /* Bullet symbol */
    margin-right: 10px; /* Space between bullet and text */
    font-size: 20px;
    line-height: 1.2;
    color: black; /* Bullet color */
  }

  /* Limit the horizontal length of the content text in the News section */
  .news-section .content-cell {
    max-width: 650px;  /* Control the wrapping */
    word-wrap: break-word;
  }

  /* Bold styling for the date */
  .news-section .news-date {
    font-weight: bold;
    margin-right: 10px;
  }
</style>

<!-- Add class to the News section to scope the bullet styling -->
<div class="news-section">
  <ul>
    <li>
      <span class="news-date">[Sep 20, 2024]</span>
      <span class="content-cell">Our work <a href="https://arxiv.org/abs/2404.19441">"ESC: Efficient Speech Coding with Cross-Scale Residual Vector Quantized Transformers"</a> is accepted to EMNLP 2024 main conference!</span>
    </li>
    <li>
      <span class="news-date">[Mar 13, 2024]</span>
      <span class="content-cell">My co-authored paper <a href="https://arxiv.org/abs/2404.19007">"How Did We Get Here? Summarizing Conversation Dynamics"</a> is accepted to NAACL 2024 main conference!</span>
    </li>
    <!-- Hidden content starts here -->
    <li id="moreContent" style="display: none;">
      <span class="news-date">[Jan 16, 2024]</span>
      <span class="content-cell">My independent study @DKU <a href="https://ieeexplore.ieee.org/document/10622693">"Towards Quantification of Covid-19 Intervention Policies from Machine Learning-based Time Series Forecasting Approaches"</a> got accepted to IEEE-ICC 2024!</span>
    </li>
    <li id="moreContent2" style="display: none;">
      <span class="news-date">[May 26, 2023]</span>
      <span class="content-cell">🎉 Officially graduated from Duke Kunshan / Duke University!</span>
    </li>
    <!-- End of hidden content -->
    <!-- Show More/Show Less Link -->
    <li>
      <a href="#" id="toggleLink" onclick="toggleContent(event);" style="text-decoration: underline; cursor: pointer;">
        show more
      </a>
    </li>
  </ul>
</div>

<script>
  function toggleContent(event) {
    event.preventDefault();  // Prevent default link behavior

    const moreContent = document.getElementById('moreContent');
    const moreContent2 = document.getElementById('moreContent2');
    const toggleLink = document.getElementById('toggleLink');
    
    // Toggle visibility of the hidden content
    if (moreContent.style.display === 'none') {
      moreContent.style.display = 'flex';
      moreContent2.style.display = 'flex';
      toggleLink.innerText = 'show less';
    } else {
      moreContent.style.display = 'none';
      moreContent2.style.display = 'none';
      toggleLink.innerText = 'show more';
    }
  }
</script>

<br><br><br>

<h2>Publications</h2>

<!-- Year on the left, publications on the right, with consistent width -->
<div style="display: flex; flex-direction: row; max-width: 600;">
  <!-- Year on the left -->
  <div style="font-weight: bold; font-size: 20; margin-left: 30px; margin-right: 20px; text-align: center;">
    2024
  </div>
  <!-- Publications on the right -->
  <div style="font-size: 15px; font-family: Georgia, sans-serif; word-wrap: break-word;">
    <!-- First publication -->
    <strong style="font-size: 16px; font-family: Georgia, sans-serif; font-style: italic; font-weight: bold;">ESC: Efficient Speech Coding with Cross-Scale Residual Vector Quantized Transformers</strong><br>
    <strong style="font-weight: bold;">Yuzhe Gu</strong>, Enmao Diao<br>
    <em>Proceedings of EMNLP, 2024</em><br>
    <a href="https://arxiv.org/abs/2404.19441">paper</a> / <a href="https://github.com/yzGuu830/efficient-speech-codec">code</a>
    <br><br>
    <!-- Second publication -->
    <strong style="font-size: 16px; font-family: Georgia, sans-serif; font-style: italic; font-weight: bold;">How Did We Get Here? Summarizing Conversation Dynamics</strong><br>
    Yilun Hua, Nicholas Chernogor, <strong style="font-weight: bold;">Yuzhe Gu</strong>, Seoyeon Julie Jeong, Miranda Luo, Cristian Danescu-Niculescu-Mizil<br>
    <em>Proceedings of NAACL, 2024</em><br>
    <a href="https://arxiv.org/abs/2404.19007">paper</a> / <a href="https://github.com/CornellNLP/scd?tab=readme-ov-file">code</a>
    <br><br>
    <!-- Third publication -->
    <strong style="font-size: 16px; font-family: Georgia, sans-serif; font-style: italic; font-weight: bold;">Towards Quantification of Covid-19 Intervention Policies from Machine Learning-based Time Series Forecasting Approaches</strong><br>
    <strong style="font-weight: bold;">Yuzhe Gu</strong>, Peng Sun, Azzedine Boukerche<br>
    <em>Proceedings of IEEE International Conference on Communications (ICC), 2024</em><br>
    <a href="https://ieeexplore.ieee.org/document/10622693">paper</a> / <a href="https://github.com/yzGuu830/epic-quant">code</a>
  </div>
</div>


</div>


<!-- 
<h2>Publications</h2> -->

<!-- <table>
  <tr>
    <td>
      <img src="../assets/img/publication_preview/esc.png" alt="Image description" width="150" style="margin-right: 50px;">
    </td>
    <td style="font-size: 16px; font-family: Georgia, sans-serif;">
      <strong style="font-family: Georgia, sans-serif; font-style:italic; font-weight: bold;">ESC: Efficient Speech Coding with Cross-Scale Residual Vector Quantized Transformers</strong><br>
      <strong style="font-weight: bold;">Yuzhe Gu</strong>, Enmao Diao<br>
      <em>Proceedings of EMNLP, 2024</em><br>
      <a href="https://arxiv.org/abs/2404.19441">paper</a> / <a href="https://github.com/yzGuu830/efficient-speech-codec">code</a> 
      <br>
      <div style="font-size: 13px; font-family: times, sans-serif">
      We propose Efficient Speech Codec (ESC), a lightweight, parameter-efficient speech codec based on a cross-scale residual vector quantization scheme and transformers. Our model employs mirrored hierarchical window transformer blocks and performs step-wise decoding from coarse-to-fine feature representations. ESC can achieve high-fidelity speech reconstruction with significantly lower complexity than state-of-the-art convolutional codecs.
      </div>
    </td>
  </tr>
</table> -->

<!-- <br><br> -->

<!-- <table>
  <tr>
    <td>
      <img src="../assets/img/publication_preview/scd.png" alt="Image description" width="150" style="margin-right: 50px;">
    </td>
    <td style="font-size: 16px; font-family: Georgia, sans-serif;">
      <strong style="font-family: Georgia, sans-serif; font-style:italic; font-weight: bold;">How Did We Get Here? Summarizing Conversation Dynamics</strong><br>
      Yilun Hua, Nicholas Chernogor, <strong style="font-weight: bold;">Yuzhe Gu</strong>, Seoyeon Julie Jeong, Miranda Luo, Cristian Danescu-Niculescu-Mizil<br>
      <em>Proceedings of NAACL, 2024</em><br>
      <a href="https://arxiv.org/abs/2404.19007">paper</a> / <a href="https://github.com/CornellNLP/scd?tab=readme-ov-file">code</a> 
      <br>
      <div style="font-size: 13px; font-family: times, sans-serif">
      We introduce the task of summarizing the dynamics of conversations, by constructing a dataset of human-written summaries, and exploring several automated baselines. We evaluate whether such summaries can capture the trajectory of conversations via an established downstream task: forecasting whether an ongoing conversation will eventually derail into toxic behavior. We show that they help both humans and automated systems with this forecasting task.
      </div>
    </td>
  </tr>
</table> -->

<!-- <br><br> -->

<!-- <table>
  <tr>
    <td>
      <img src="../assets/img/publication_preview/policy.png" alt="Image description" width="150" style="margin-right: 50px;">
    </td>
    <td style="font-size: 16px; font-family: Georgia, sans-serif;">
      <strong style="font-family: Georgia, sans-serif; font-style:italic; font-weight: bold;">Towards Quantification of Covid-19 Intervention Policies from Machine Learning-based Time Series Forecasting Approaches</strong><br>
      <strong style="font-weight: bold;">Yuzhe Gu</strong>, Peng Sun, Azzedine Boukerche<br>
      <em>Proceedings of IEEE International Conference on Communications (ICC), 2024</em><br>
      <a href="https://ieeexplore.ieee.org/document/10622693">paper</a> / <a href="https://github.com/yzGuu830/epic-quant">code</a> 
      <br>
      <div style="font-size: 13px; font-family: times, sans-serif">
      We design a policy-aware time series forecasting model to estimate COVID-19 trends by incorporating temporal information from 16 policy indicators. Through counterfactual analysis, we quantify the causal effect of indicators and propose two static metrics <em>lag period</em> and <em>average effect</em>. Our model verifies the effectiveness of all 16 policy indicators in controlling virus transmission in the US.
      </div>
    </td>
  </tr>
</table> -->