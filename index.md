---
layout: default
---
<style>
  .publications {
    max-width: 800px;
    margin: 0 auto;
  }
  
  .publication-item {
    margin-bottom: 2rem;
    padding: 1.5rem;
    border-radius: 8px;
    background: #ffffff;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }
  
  .pub-title {
    font-size: 1.2rem;
    font-weight: bold;
    color: #2c3e50;
    margin-bottom: 0.5rem;
  }
  
  .pub-title a {
    color: inherit;
    text-decoration: none;
  }
  
  .pub-title a:hover {
    color: #3498db;
  }
  
  .pub-authors {
    font-style: italic;
    margin-bottom: 0.5rem;
    color: #34495e;
  }
  
  .pub-venue {
    font-weight: 500;
    color: #7f8c8d;
    margin-bottom: 1rem;
  }
  
  .pub-abstract {
    color: #2c3e50;
    line-height: 1.6;
    margin-bottom: 1rem;
  }
  
  .pub-links {
    display: flex;
    gap: 1rem;
  }
  
  .pub-links a {
    color: #3498db;
    text-decoration: none;
  }
  
  .pub-links a:hover {
    text-decoration: underline;
  }
</style>

# Mohamed Ashraf Abdelsalam
I am a Senior ML Research Engineer at Samsung AI Center in Toronto, where my research focuses on multimodal AI, working at the intersection of vision and language. Previously, I completed my Master's in Machine Learning at Mila and University of Montreal with Dr. Sarath Chandar, where I mainly worked on lifelong and incremental learning systems. I hold a Bachelor's in Aerospace Engineering from Zewail University of Science and Technology. Check out my personal <a href="/CV.pdf">CV</a> for more details!

### Publications
<div class="publications">
  <div class="publication-item">
    <div class="pub-title">
      <a href="https://arxiv.org/abs/2407.11393">CIC-BART-SSA: Controllable Image Captioning with Structured Semantic Augmentation</a>
    </div>
    <div class="pub-authors">
     Kalliopi Basioti, <b>Mohamed A. Abdelsalam</b>, Federico Fancellu, Vladimir Pavlovic, Afsaneh Fazly
    </div>
    <div class="pub-venue">ECCV 2024</div>
    <div class="pub-abstract">
      A novel approach for controllable image captioning using structured semantic representations. The method automatically generates focused and diverse image descriptions by leveraging Abstract Meaning Representation (AMR) graphs, improving both caption quality and controllability.
    </div>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2407.11393">Paper</a>
     <a href="https://github.com/SamsungLabs/CIC-BART-SSA">Code</a>
    </div>
  </div>
 
  <div class="publication-item">
    <div class="pub-title">
      <a href="https://arxiv.org/abs/2310.08312">GePSAn: Generative Procedure Step Anticipation in Cooking Videos</a>
    </div>
    <div class="pub-authors">
      <b>Mohamed A. Abdelsalam</b>, Samrudhdhi B. Rangrej, Isma Hadji, Nikita Dvornik, Konstantinos G. Derpanis, Afsaneh Fazly
    </div>
    <div class="pub-venue">ICCV 2023</div>
    <div class="pub-abstract">
      A generative deep learning model to predict next steps in procedural videos using natural language. The model excels in generating diverse and plausible outcomes through zero-shot transfer from text to video, setting new benchmarks on YouCookII.
    </div>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2310.08312">Paper</a>
     <a href="https://github.com/SamsungLabs/GePSAN">Code</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="pub-title">
      <a href="https://arxiv.org/abs/2210.14862">Visual Semantic Parsing: From Images to Abstract Meaning Representation</a>
    </div>
    <div class="pub-authors">
      <b>Mohamed A. Abdelsalam</b>, Zhan Shi, Federico Fancellu, Kalliopi Basioti, Dhaivat J. Bhatt, Vladimir Pavlovic, Afsaneh Fazly
    </div>
    <div class="pub-venue">CoNLL 2022</div>
    <div class="pub-abstract">
      A novel method for visual scene understanding using Abstract Meaning Representation (AMR) to create linguistically informed visual AMR graphs for higher-level semantic concepts.
    </div>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2210.14862">Paper</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="pub-title">
      <a href="https://chandar-lab.github.io/IIRC/">IIRC: Incremental Implicitly-Refined Classification</a>
    </div>
    <div class="pub-authors">
      <b>Mohamed A. Abdelsalam</b>, Mojtaba Faramarzi, Shagun Sodhani, Sarath Chandar
    </div>
    <div class="pub-venue">CVPR 2021</div>
    <div class="pub-abstract">
      A setup and benchmark for evaluating lifelong learning models in more dynamic and realistic scenarios.
    </div>
    <div class="pub-links">
      <a href="https://chandar-lab.github.io/IIRC/">Homepage</a>
      <a href="https://arxiv.org/abs/2012.12477">Paper</a>
      <a href="https://iirc.readthedocs.io/en/latest/">Documentation</a>
      <a href="https://github.com/chandar-lab/IIRC/">Code</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="pub-title">
      <a href="https://arxiv.org/abs/2106.10619">A Brief Study on the Effects of Training Generative Dialogue Models with a Semantic loss</a>
    </div>
    <div class="pub-authors">
      Prasanna Parthasarathi, <b>Mohamed A. Abdelsalam</b>, Joelle Pineau, Sarath Chandar
    </div>
    <div class="pub-venue">SIGDial 2021</div>
    <div class="pub-abstract">
      An exploration of semantic loss as an auxiliary objective to improve diversity in dialogue response generation, showing particular effectiveness for smaller datasets.
    </div>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2106.10619">Paper</a>
    </div>
  </div>
</div>

     
### Primers
<div class="publications">
  <div class="publication-item">
    <div class="pub-title">
      <a href="https://arxiv.org/pdf/2207.04354.pdf">An Introduction to Lifelong Supervised Learning</a>
    </div>
    <div class="pub-authors">
     Shagun Sodhani, Mojtaba Faramarzi, Sanket Vaibhav Mehta, Pranshu Malviya, <b>Mohamed A. Abdelsalam</b>, Janarthanan Janarthanan, Sarath Chandar
    </div>
    <div class="pub-abstract">
      This primer is an attempt to provide a detailed summary of the different aspects of lifelong supervised learning.
    </div>
  </div>
</div>
