<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Mehrdad Zandigohar | Bioinformatics + Generative AI</title>

  <!-- Fonts & icons -->
  <link href="https://fonts.googleapis.com/css?family=PT+Sans:400,700|JetBrains+Mono&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>

  <!-- Bootstrap -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

  <!-- Typed tagline -->
  <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.16"></script>

  <style>
    :root{ --accent:#00e676; --dark:#111; }
    html,body{margin:0;font-family:'PT Sans',sans-serif;scroll-behavior:smooth;overflow-x:hidden;}
    section{padding:70px 0;}
    h2.code{font-family:'JetBrains Mono',monospace;color:var(--accent);margin:60px 0 25px;}
    a{color:var(--accent);} a:hover{text-decoration:none;color:#fff;}

    /* Nav */
    #topnav{background:var(--dark);border:none;}
    #topnav .nav>li>a{color:var(--accent);font-weight:bold;} 
    #topnav .nav>li>a:hover{color:#fff;}
    html{scroll-padding-top:60px;}

    /* Hero */
    #hero{
      height:100vh;color:#fff;text-align:center;
      background:#000 url('/assets/img/hero.jpg') center/cover fixed;
      display:flex;flex-direction:column;justify-content:center;align-items:center;
    }
    #hero h1{font-size:3.5rem;margin:10px 0;letter-spacing:1px;}
    #tagline{font-size:1.3rem;}

    /* Cards */
    .card{background:#1f1f1f;color:#ccc;border-radius:8px;padding:20px;margin-bottom:30px;min-height:170px;
          transition:transform .2s;}
    .card:hover{transform:translateY(-6px);}
    .card .time{color:var(--accent);font-size:.85rem;margin-top:8px;}

    /* Simple lists */
    ul{padding-left:20px;} li{margin-bottom:8px;}
  </style>
</head>

<body>

<!-- ===== Navbar ===== -->
<nav id="topnav" class="navbar navbar-default navbar-fixed-top">
  <div class="container">
    <ul class="nav navbar-nav">
      <li><a href="#about">WHO&nbsp;AM&nbsp;I</a></li>
      <li><a href="#experience">EXPERIENCE</a></li>
      <li><a href="#projects">PROJECTS</a></li>
      <li><a href="#publications">PUBLICATIONS</a></li>
      <li><a href="#contact">CONTACT</a></li>
    </ul>
  </div>
</nav>


<!-- ===== About ===== -->
<section id="about">
  <div class="container">
    <h2 class="code"># about</h2>
    <p><strong>PhD candidate in Bioinformatics (UIC, 2020 – 2025)</strong><br>
       Generative AI for single-cell & spatial genomics.<br>
       I build <em>interpretable</em> VAEs, transformers, and retrieval-augmented pipelines
       to map transcription-factor networks and cell–cell communication.</p>
  </div>
</section>

<!-- ===== Experience ===== -->
<section id="experience">
  <div class="container">
    <h2 class="code"># experience</h2>
    <div class="row">
      <div class="col-sm-4"><div class="card">
        <strong>Graduate Research Assistant – U Illinois Chicago</strong>
        <div class="time">2023 – 2025</div>
        Built <em>scRegulate</em>, a TF-aware VAE boosting AUROC 10-50 % and robust under 30 % dropout.
      </div></div>

      <div class="col-sm-4"><div class="card">
        <strong>Research Assistant – UIC</strong>
        <div class="time">2021 – 2023</div>
        Benchmarked latent inference for sparse scATAC-seq; first-author paper @ IEEE BIBM 2022.
      </div></div>

      <div class="col-sm-4"><div class="card">
        <strong>Lab Computing Lead – UIC</strong>
        <div class="time">2022 – present</div>
        Managed three GPU servers, won an NVIDIA GPU grant, mentored 10 + researchers on CUDA workflows.
      </div></div>
    </div>
  </div>
</section>

<!-- ===== Projects ===== -->
<section id="projects">
  <div class="container">
    <h2 class="code"># projects</h2>
    <ul>
      <li><strong>scRegulate</strong> – interpretable VAE for TF activity; CI/CD, PyPI, Conda.</li>
      <li><strong>RAGulate</strong> – retrieval-augmented LLM validating TF–gene links (in progress).</li>
      <li><strong>Single-cell Atlas of Uterine Fibroids</strong> – 16 cell types; <em>Human Reproduction 2022</em>.</li>
    </ul>
  </div>
</section>

<!-- ===== Publications ===== -->
<section id="publications">
  <div class="container">
    <h2 class="code"># publications</h2>
    <ul>
      <li><em>scRegulate: Single-Cell Regulatory-Embedded Variational Inference…</em> <strong>bioRxiv</strong> 2025.</li>
      <li><em>Macrophage Heterogeneity during Skin Wound Healing.</em> <strong>J Immunol</strong> 2024.</li>
      <li><em>Information Retrieval in Single-Cell Chromatin Analysis.</em> <strong>IEEE BIBM</strong> 2022.</li>
    </ul>
  </div>
</section>

<!-- ===== Contact ===== -->
<section id="contact">
  <div class="container">
    <h2 class="code"># contact</h2>
    <p>
      <strong>Email:</strong> <a href="mailto:mzandi2@uic.edu">mzandi2@uic.edu</a><br>
      <strong>GitHub:</strong> <a href="https://github.com/zandigohar">zandigohar</a><br>
      <strong>LinkedIn:</strong> <a href="https://linkedin.com/in/zandigohar">linkedin.com/in/zandigohar</a><br>
      <strong>CV:</strong> <a href="/assets/CV_mehrdad_v10.pdf">download PDF</a>
    </p>
  </div>
</section>

<!-- ===== Typed.js init ===== -->
<script>
  new Typed('#tagline',{
    strings:['PhD Candidate @ UIC','Single-cell & Spatial Genomics','Generative AI Scientist'],
    typeSpeed:45,backSpeed:25,backDelay:1500,loop:true
  });
</script>

</body>
</html>
