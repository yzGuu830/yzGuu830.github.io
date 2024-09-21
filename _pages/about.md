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

<!-- ## About Me -->
<div style="font-family: 'Georgia', sans-serif;">

  I am a second year master student in [Department of Electrical and Systems Engineering](https://www.ese.upenn.edu) at the [University of Pennsylvania](https://www.upenn.edu) with a concentration on Machine Learning and Data Science. I received my dual B.Sc. in Data Science from [Duke Kunshan University](https://www.dukekunshan.edu.cn) and [Duke University](https://www.duke.edu), where I worked closely with [Enmao Diao](https://diaoenmao.com/) and [Peng Sun](https://scholars.duke.edu/person/Peng.Sun1). 

  <!-- My research interest primarily revolves around enhancing **efficiency** and promoting **trustworthiness** in existing generative models. I am also interested in exploring the theory and application of learning quantized representations. My long-term objective is to develop intelligent systems that are both effective and reliable.  -->

  My research interest covers a wide range of topics related to learning representations and modern deep generative models: 
  - **Discrete Representation Learning**: advancing discrete latent variable models for generative models, efficient data compression, and multimodal application
  - **Efficient LLMs**: optimizing LLM decoding performance through improved KV cache mechanism and better long-context understanding ability
  <!-- - **Trustworthy LLMs**: re-examination of bias, fairness and robustness in LLMs -->

  <!-- My overall objective is to develop intelligent systems that are both efficient and reliable. -->

  <span style="color: #0a47a9;">I am actively seeking for a CS / ECE Ph.D. position related to Machine Learning and Natural Language Processing starting 2025 Fall. </span>

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

</div>

## News
<div style="font-family: 'Georgia', sans-serif;">
  <table>
    <tr>
      <td style="white-space: nowrap;"><strong>Sep 20, 2024</strong></td>
      <td>Our work "ESC: Efficient Speech Coding with Cross-Scale Residual Vector Quantized Transformers" is accepted to EMNLP 2024 main conference!</td>
    </tr>
    <tr>
      <td style="white-space: nowrap;"><strong>Mar 13, 2024</strong></td>
      <td>My co-authored paper "How Did We Get Here? Summarizing Conversation Dynamics" is accepted to NAACL 2024 main conference!</td>
    </tr>
    <!-- more content -->
    <tbody id="moreContent" style="display:none;">
      <tr>
        <td><strong>Jan 16, 2024</strong></td>
        <td>My independent study @DKU "Towards Quantification of Covid-19 Intervention Policies from Machine Learning-based Time Series Forecasting Approaches" got accepted to IEEE-ICC 2024!</td>
      </tr>
      <tr>
        <td style="white-space: nowrap;"><strong>May 26, 2023</strong></td>
        <td>🎉 Officially graduated from Duke Kunshan / Duke University!</td>
      </tr>
    </tbody>
  </table>

  <button onclick="document.getElementById('moreContent').style.display = (document.getElementById('moreContent').style.display == 'none' ? 'table-row-group' : 'none'); this.innerText = (this.innerText == 'Show More' ? 'Show Less' : 'Show More');">
  Show More
  </button>
</div>

## Publications 

<table>
  <tr>
    <td>
      <img src="../assets/img/publication_preview/esc.png" alt="Image description" width="200" style="margin-right: 80px;">
    </td>
    <td style="font-size: 16px; font-family: Georgia, sans-serif;">
      <strong>ESC: Efficient Speech Coding with Cross-Scale Residual Vector Quantized Transformers</strong><br>
      <strong>Yuzhe Gu</strong>, Enmao Diao<br>
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
      <strong style="font-family: Georgia, sans-serif">How Did We Get Here? Summarizing Conversation Dynamics</strong><br>
      Yilun Hua, Nicholas Chernogor, <strong>Yuzhe Gu</strong>, Seoyeon Julie Jeong, Miranda Luo, Cristian Danescu-Niculescu-Mizil<br>
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
      <strong style="font-family: Georgia, sans-serif">Towards Quantification of Covid-19 Intervention Policies from Machine Learning-based Time Series Forecasting Approaches</strong><br>
      <strong>Yuzhe Gu</strong>, Peng Sun, Azzedine Boukerche<br>
      <em>Proceedings of IEEE International Conference on Communications (ICC), 2024</em><br>
      <a href="https://ieeexplore.ieee.org/document/10622693">paper</a> / <a href="https://github.com/yzGuu830/epic-quant">code</a> 
      <br>
      <div style="font-size: 13px; font-family: times, sans-serif">
      We design a policy-aware time series forecasting model to estimate COVID-19 trends by incorporating temporal information from 16 policy indicators. Through counterfactual analysis, we quantify the causal effect of indicators and propose two static metrics <em>lag period</em> and <em>average effect</em>. Our model verifies the effectiveness of all 16 policy indicators in controlling virus transmission in the US.
      </div>
    </td>
  </tr>
</table>