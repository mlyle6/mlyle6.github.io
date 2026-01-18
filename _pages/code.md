---
layout: archive
title: "Code"
permalink: /code/
author_profile: true
---

<style>
.code-page {
  max-width: 900px;
  margin: 0 auto;
}

.code-page h2 {
  color: #002878;
  font-weight: 400;
  margin-top: 3em;
  margin-bottom: 1.5em;
  font-size: 1.6em;
  border-bottom: 2px solid #f0f0f0;
  padding-bottom: 0.5em;
}

.code-intro {
  line-height: 1.8;
  margin-bottom: 3em;
  color: #333;
  font-size: 1.05em;
}

.project-list {
  margin-bottom: 3em;
}

.project-item {
  margin-bottom: 2.5em;
  padding: 1.5em;
  background: #fafafa;
  border-left: 4px solid #002878;
  border-radius: 4px;
}

.project-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  margin-bottom: 0.8em;
  flex-wrap: wrap;
}

.project-title {
  font-weight: 600;
  color: #333;
  font-size: 1.2em;
  margin-right: 1em;
}

.project-title a {
  color: #002878;
  text-decoration: none;
}

.project-title a:hover {
  color: #001850;
  text-decoration: underline;
}

.project-links {
  display: flex;
  gap: 1em;
  flex-wrap: wrap;
}

.project-link {
  font-size: 0.9em;
  color: #002878;
  text-decoration: none;
  padding: 0.3em 0.8em;
  border: 1px solid #002878;
  border-radius: 3px;
  transition: all 0.2s ease;
}

.project-link:hover {
  background: #002878;
  color: white;
}

.project-description {
  line-height: 1.7;
  color: #555;
  margin-bottom: 0.8em;
}

.project-tech {
  font-size: 0.9em;
  color: #777;
  font-style: italic;
}

.tech-tag {
  display: inline-block;
  background: #e8e8e8;
  padding: 0.2em 0.6em;
  margin-right: 0.5em;
  margin-top: 0.3em;
  border-radius: 3px;
  color: #555;
}
</style>

<div class="code-page">
  <div class="code-intro">
    <p>I develop open-source software and tools to support research and education. These projects reflect my commitment to reproducible research and making computational methods accessible to the broader community.</p>
    
    <p>All code is available on GitHub and released under permissive licenses. Contributions and collaborations are welcome.</p>
  </div>

  <h2>Research Software</h2>
  <div class="project-list">
    <div class="project-item">
      <div class="project-header">
        <div class="project-title">
          <a href="https://github.com/mlyle6" target="_blank">DataAnalysis Toolkit</a>
        </div>
        <div class="project-links">
          <a href="https://github.com/mlyle6" class="project-link" target="_blank">GitHub</a>
          <a href="#" class="project-link" target="_blank">Documentation</a>
        </div>
      </div>
      <div class="project-description">
        A comprehensive Python library for advanced data analysis and visualization. Includes implementations of novel algorithms for pattern detection, anomaly identification, and predictive modeling with emphasis on interpretability and ease of use.
      </div>
      <div class="project-tech">
        <span class="tech-tag">Python</span>
        <span class="tech-tag">NumPy</span>
        <span class="tech-tag">Pandas</span>
        <span class="tech-tag">Scikit-learn</span>
      </div>
    </div>

    <div class="project-item">
      <div class="project-header">
        <div class="project-title">
          <a href="https://github.com/mlyle6" target="_blank">ML Framework</a>
        </div>
        <div class="project-links">
          <a href="https://github.com/mlyle6" class="project-link" target="_blank">GitHub</a>
          <a href="#" class="project-link" target="_blank">Paper</a>
        </div>
      </div>
      <div class="project-description">
        An extensible machine learning framework designed for research applications. Features modular architecture, built-in experiment tracking, and support for custom model architectures. Optimized for both prototyping and production deployment.
      </div>
      <div class="project-tech">
        <span class="tech-tag">Python</span>
        <span class="tech-tag">PyTorch</span>
        <span class="tech-tag">TensorFlow</span>
        <span class="tech-tag">MLflow</span>
      </div>
    </div>

    <div class="project-item">
      <div class="project-header">
        <div class="project-title">
          <a href="https://github.com/mlyle6" target="_blank">Network Analysis Suite</a>
        </div>
        <div class="project-links">
          <a href="https://github.com/mlyle6" class="project-link" target="_blank">GitHub</a>
          <a href="#" class="project-link" target="_blank">Demo</a>
        </div>
      </div>
      <div class="project-description">
        Tools for analyzing complex networks with scalable algorithms for community detection, centrality analysis, and network visualization. Supports multiple input formats and provides both command-line and programmatic interfaces.
      </div>
      <div class="project-tech">
        <span class="tech-tag">Python</span>
        <span class="tech-tag">NetworkX</span>
        <span class="tech-tag">Graph-tool</span>
        <span class="tech-tag">D3.js</span>
      </div>
    </div>
  </div>

  <h2>Educational Resources</h2>
  <div class="project-list">
    <div class="project-item">
      <div class="project-header">
        <div class="project-title">
          <a href="https://github.com/mlyle6" target="_blank">Data Science Course Materials</a>
        </div>
        <div class="project-links">
          <a href="https://github.com/mlyle6" class="project-link" target="_blank">GitHub</a>
        </div>
      </div>
      <div class="project-description">
        Complete course materials including Jupyter notebooks, datasets, and exercises for teaching data science fundamentals. Covers data wrangling, statistical analysis, machine learning, and visualization.
      </div>
      <div class="project-tech">
        <span class="tech-tag">Jupyter</span>
        <span class="tech-tag">Python</span>
        <span class="tech-tag">R</span>
      </div>
    </div>

    <div class="project-item">
      <div class="project-header">
        <div class="project-title">
          <a href="https://github.com/mlyle6" target="_blank">Research Methods Tutorials</a>
        </div>
        <div class="project-links">
          <a href="https://github.com/mlyle6" class="project-link" target="_blank">GitHub</a>
        </div>
      </div>
      <div class="project-description">
        Interactive tutorials demonstrating best practices in computational research, including reproducible workflows, version control, and effective documentation strategies.
      </div>
      <div class="project-tech">
        <span class="tech-tag">Git</span>
        <span class="tech-tag">Docker</span>
        <span class="tech-tag">Jupyter</span>
        <span class="tech-tag">Make</span>
      </div>
    </div>
  </div>
</div>
