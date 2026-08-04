---
layout: default
title: Research
permalink: /research/
---

<header class="page-intro">
  <h1>Research</h1>
  <p class="page-deck">
    My work develops and applies simulation-based inference methods for experimental
    evolution, using stochastic simulation, Bayesian statistics, and deep learning.
  </p>
</header>

<section class="project-list" aria-label="Research projects">
  <article class="project featured-project">
    <div class="project-number">01</div>
    <div class="project-body">
      <h2>The collective posterior</h2>
      <p class="project-kicker">Methods · Accepted at PLOS Computational Biology</p>
      <h3>Inferring parameters from highly variable empirical replicates</h3>
      <p>
        High-throughput experimental evolution generates many independent replicates, each producing
        noisy and variable outcomes. I developed the <strong>collective posterior</strong>—a method
        that aggregates information across replicates using a robust product-of-experts scheme.
        It automatically reduces the influence of outlier replicates while improving accuracy and
        efficiency relative to existing methods.
      </p>
      <ul class="keyword-list" aria-label="Research themes">
        <li>Simulation-based inference</li>
        <li>Bayesian statistics</li>
        <li>Neural networks</li>
        <li>Product of experts</li>
      </ul>
      <a class="article-link" href="https://www.biorxiv.org/content/10.64898/2026.01.26.701673v1" target="_blank" rel="noopener">Preprint <span aria-hidden="true">↗</span></a>
    </div>
  </article>

  <article class="project">
    <div class="project-number">02</div>
    <div class="project-body">
      <h2>Posterior ensembles under fixed compute</h2>
      <p class="project-kicker">Methods · Ongoing work</p>
      <p>
        I study whether ensembles of neural posterior estimators improve inference because
        of model averaging itself or simply because they use more training compute. Across
        a diverse set of simulation models, compute-matched ensembles reveal a trade-off:
        they produce wider posteriors and better coverage, but generally poorer point
        estimates and proper scores. The work separates the effects of ensembling from the
        effects of additional computation.
      </p>
      <ul class="keyword-list" aria-label="Research themes">
        <li>Posterior ensembles</li>
        <li>Calibration</li>
        <li>Compute allocation</li>
      </ul>
    </div>
  </article>

  <article class="project">
    <div class="project-number">03</div>
    <div class="project-body">
      <h2>Bayesian experimental design for evolution experiments</h2>
      <p class="project-kicker">Methods · Research prototype</p>
      <p>
        I am developing a framework for deciding when and how deeply to sample microbial
        evolution experiments, both before an experiment begins and as data arrive. It
        combines mechanistic simulation, design-conditioned inference, and expected
        information gain to compare sampling schedules while accounting for experimental
        constraints and limited resources.
      </p>
      <ul class="keyword-list" aria-label="Research themes">
        <li>Experimental design</li>
        <li>Expected information gain</li>
        <li>Adaptive experiments</li>
      </ul>
    </div>
  </article>

  <article class="project">
    <div class="project-number">04</div>
    <div class="project-body">
      <h2>Copy-number variation in yeast evolution</h2>
      <p class="project-kicker">Collaboration · Gresham Lab, NYU</p>
      <p>
        I apply SBI to study the evolutionary dynamics of copy-number variants in yeast.
        Our work indicates that DNA template switching during replication (ODIRA) is a
        predominant mechanism generating adaptive gene amplifications, and that segmental
        duplications remain stable over hundreds of generations without selection pressure.
      </p>
      <ul class="keyword-list" aria-label="Research themes">
        <li>Experimental evolution</li>
        <li>Copy-number variation</li>
        <li>Yeast</li>
      </ul>
      <div class="inline-links">
        <a href="https://doi.org/10.7554/eLife.98934.3" target="_blank" rel="noopener">Chuong et al., 2025 <span aria-hidden="true">↗</span></a>
        <a href="https://academic.oup.com/mbe/article/43/4/msag095/8651694" target="_blank" rel="noopener">De et al., 2026 <span aria-hidden="true">↗</span></a>
      </div>
    </div>
  </article>

  <article class="project">
    <div class="project-number">05</div>
    <div class="project-body">
      <h2>RNA-virus evolution</h2>
      <p class="project-kicker">Application · Viral evolution</p>
      <p>
        Using neural posterior estimation, we inferred mutation rates, selection coefficients,
        and epistatic interactions from RNA-virus haplotype data. This work shows how SBI can
        recover evolutionary parameters from sequencing data that are inaccessible to traditional
        statistical methods.
      </p>
      <ul class="keyword-list" aria-label="Research themes">
        <li>RNA viruses</li>
        <li>Neural posterior estimation</li>
        <li>Epistasis</li>
      </ul>
      <a class="article-link" href="https://academic.oup.com/ve/article/9/1/vead033/7175026" target="_blank" rel="noopener">Caspi et al., 2023 <span aria-hidden="true">↗</span></a>
    </div>
  </article>

  <article class="project compact-project">
    <div class="project-number">06</div>
    <div class="project-body">
      <h2>Practical guidelines for SBI</h2>
      <p class="project-kicker">Open methods</p>
      <p>
        Tutorials, benchmarks, and practical guidance intended to make simulation-based
        inference accessible to experimentalists working across common evolution study designs.
      </p>
    </div>
  </article>

  <article class="project compact-project">
    <div class="project-number">07</div>
    <div class="project-body">
      <h2>SBI for microbial growth</h2>
      <p class="project-kicker">Current direction</p>
      <p>
        Extending SBI methods to infer parameters from microbial growth dynamics, bridging
        evolutionary and ecological modelling.
      </p>
    </div>
  </article>
</section>
