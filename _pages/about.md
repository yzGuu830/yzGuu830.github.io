---
layout: about
title: About
permalink: /
subtitle: A Graduate Student interested in Machine Learning and Artificial Intelligence

profile:
  align: right
  image: yuzhegu_headshot.jpg
  image_circular: true # crops the image to make it circular
  more_info:

news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page
---

<div style="font-family: 'Georgia', sans-serif;">

  I am a second-year master student in <a href="https://www.ese.upenn.edu">Department of Electrical and Systems Engineering</a> at the <a href="https://www.upenn.edu">University of Pennsylvania</a> with a concentration on Machine Learning and Data Science. I received my dual B.Sc. in Data Science from <a href="https://www.dukekunshan.edu.cn">Duke Kunshan University</a> and <a href="https://www.duke.edu">Duke University</a>, where I worked closely with <a href="https://diaoenmao.com/">Enmao Diao</a> and <a href="https://scholars.duke.edu/person/Peng.Sun1">Peng Sun</a>.
  <br>

  <p>My research interest covers a wide range of topics related to learning representations and modern deep generative models:</p>
  <ul>
    <li><strong>Discrete Representation Learning</strong>: advancing discrete latent variable models for generative models, efficient data compression, and multimodal application</li>
    <li><strong>Efficient LLMs</strong>: optimizing LLM decoding performance through improved KV cache mechanism and better long-context understanding ability</li>
  </ul>

  <span style="color: darkblue;">I am actively seeking a CS / ECE Ph.D. position related to Machine Learning and Natural Language Processing starting 2025 Fall.</span>
  <br>

  <table>
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
    /* Limit the horizontal length of the content cell */
    .content-cell {
      max-width: 700px;  /* Adjust this value to control the wrapping */
      word-wrap: break-word;  /* Ensures the text wraps within the max-width */
      display: inline-block;
    }
    /* Add more padding to the date cell */
    .date-cell {
      padding-right: 30px;  /* Adjust this value to control spacing */
    }
  </style>

  <table>
    <tr>
      <td style="white-space: nowrap; vertical-align: top;"><strong>Sep 20, 2024  </strong></td>
      <td class="content-cell" id="content1">
        Our work <a href="https://arxiv.org/abs/2404.19441"">"ESC: Efficient Speech Coding with Cross-Scale Residual Vector Quantized Transformers"</a> is accepted to EMNLP 2024 main conference!
      </td>
    </tr>
    <tr>
      <td style="white-space: nowrap; vertical-align: top;"><strong>Mar 13, 2024  </strong></td>
      <td class="content-cell" id="content2">
        My co-authored paper <a href="https://arxiv.org/abs/2404.19007"">"How Did We Get Here? Summarizing Conversation Dynamics"</a> is accepted to NAACL 2024 main conference!
      </td>
    </tr>
    <tbody id="moreContent" style="display:none;">
      <tr>
        <td style="white-space: nowrap; vertical-align: top;"><strong>Jan 16, 2024  </strong></td>
        <td class="content-cell" id="content3">
          My independent study @DKU <a href="https://ieeexplore.ieee.org/document/10622693"">"Towards Quantification of Covid-19 Intervention Policies from Machine Learning-based Time Series Forecasting Approaches"</a> got accepted to IEEE-ICC 2024!
        </td>
      </tr>
      <tr>
        <td style="white-space: nowrap; vertical-align: top;"><strong>May 26, 2023  </strong></td>
        <td class="content-cell" id="content4">
          🎉 Officially graduated from Duke Kunshan / Duke University!
        </td>
      </tr>
    </tbody>
    <!-- Show More/Show Less Link Inside the Table -->
    <tr>
      <td>
        <a href="#" id="toggleLink" onclick="toggleContent();" style="text-decoration: underline; cursor: pointer;">
          show more
        </a>
      </td>
      <td></td>
    </tr>
  </table>

  <script>
    function toggleContent() {
      event.preventDefault();

      const moreContent = document.getElementById('moreContent');
      const toggleLink = document.getElementById('toggleLink');
      
      // Toggle visibility of additional rows
      if (moreContent.style.display === 'none') {
        moreContent.style.display = 'table-row-group';
        toggleLink.innerText = 'show less';
      } else {
        moreContent.style.display = 'none';
        toggleLink.innerText = 'show more';
      }
    }
  </script>
  <br><br><br>


<h2>Publications</h2>

  <table>
    <tr>
      <td>
        <img src="../assets/img/publication_preview/esc.png" alt="Image description" width="200" style="margin-right: 80px;">
      </td>
      <td style="font-size: 16px; font-family: Georgia, sans-serif;">
        <strong style="font-family: Georgia, sans-serif; font-style:italic">ESC: Efficient Speech Coding with Cross-Scale Residual Vector Quantized Transformers</strong><br>
        <strong style="font-weight: bold;">Yuzhe Gu</strong>, Enmao Diao<br>
        <em>Proceedings of EMNLP, 2024</em><br>
        <a href="https://arxiv.org/abs/2404.19441">paper</a> / <a href="https://github.com/yzGuu830/efficient-speech-codec">code</a> 
        <br>
        <div style="font-size: 13px; font-family: times, sans-serif">
        We propose Efficient Speech Codec (ESC), a lightweight, parameter-efficient speech codec based on a cross-scale residual vector quantization scheme and transformers. Our model employs mirrored hierarchical window transformer blocks and performs step-wise decoding from coarse-to-fine feature representations. ESC can achieve high-fidelity speech reconstruction with significantly lower complexity than state-of-the-art convolutional codecs.
        </div>
      </td>
    </tr>
  </table>

  <br><br>

  <table>
    <tr>
      <td>
        <img src="../assets/img/publication_preview/scd.png" alt="Image description" width="200" style="margin-right: 80px;">
      </td>
      <td style="font-size: 16px; font-family: Georgia, sans-serif;">
        <strong style="font-family: Georgia, sans-serif; font-style:italic">How Did We Get Here? Summarizing Conversation Dynamics</strong><br>
        Yilun Hua, Nicholas Chernogor, <strong style="font-weight: bold;">Yuzhe Gu</strong>, Seoyeon Julie Jeong, Miranda Luo, Cristian Danescu-Niculescu-Mizil<br>
        <em>Proceedings of NAACL, 2024</em><br>
        <a href="https://arxiv.org/abs/2404.19007">paper</a> / <a href="https://github.com/CornellNLP/scd?tab=readme-ov-file">code</a> 
        <br>
        <div style="font-size: 13px; font-family: times, sans-serif">
        We introduce the task of summarizing the dynamics of conversations, by constructing a dataset of human-written summaries, and exploring several automated baselines. We evaluate whether such summaries can capture the trajectory of conversations via an established downstream task: forecasting whether an ongoing conversation will eventually derail into toxic behavior. We show that they help both humans and automated systems with this forecasting task.
        </div>
      </td>
    </tr>
  </table>

  <br><br>

  <table>
    <tr>
      <td>
        <img src="../assets/img/publication_preview/policy.png" alt="Image description" width="200" style="margin-right: 80px;">
      </td>
      <td style="font-size: 16px; font-family: Georgia, sans-serif;">
        <strong style="font-family: Georgia, sans-serif; font-style:italic">Towards Quantification of Covid-19 Intervention Policies from Machine Learning-based Time Series Forecasting Approaches</strong><br>
        <strong style="font-weight: bold;">Yuzhe Gu</strong>, Peng Sun, Azzedine Boukerche<br>
        <em>Proceedings of IEEE International Conference on Communications (ICC), 2024</em><br>
        <a href="https://ieeexplore.ieee.org/document/10622693">paper</a> / <a href="https://github.com/yzGuu830/epic-quant">code</a> 
        <br>
        <div style="font-size: 13px; font-family: times, sans-serif">
        We design a policy-aware time series forecasting model to estimate COVID-19 trends by incorporating temporal information from 16 policy indicators. Through counterfactual analysis, we quantify the causal effect of indicators and propose two static metrics <em>lag period</em> and <em>average effect</em>. Our model verifies the effectiveness of all 16 policy indicators in controlling virus transmission in the US.
        </div>
      </td>
    </tr>
  </table>

</div>