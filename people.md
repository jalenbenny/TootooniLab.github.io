---
layout: page
title: People
permalink: /people/
---

<style>
  .roster {
    --navy: #1B2A4A;
    --slate: #4A5A72;
    --paper: #EDF1F5;
    --card: #FFFFFF;
    --amber: #C97A2B;
    --hairline: #D8DFE7;
    font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, sans-serif;
    color: var(--navy);
  }

  .roster * {
    box-sizing: border-box;
  }

  .roster-intro {
    max-width: 640px;
    margin: 0 0 2.5rem 0;
    padding-bottom: 1.5rem;
    border-bottom: 1px solid var(--hairline);
  }

  .roster-eyebrow {
    font-family: 'Courier New', monospace;
    font-size: 0.72rem;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    color: var(--amber);
    margin-bottom: 0.5rem;
  }

  .roster-intro h1 {
    font-family: Georgia, 'Times New Roman', serif;
    font-size: 2.1rem;
    font-weight: 600;
    margin: 0 0 0.6rem 0;
    color: var(--navy);
  }

  .roster-intro p {
    font-size: 0.98rem;
    line-height: 1.55;
    color: var(--slate);
    margin: 0;
  }

  .roster-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 1.5rem;
  }

  .card {
    background: var(--card);
    border: 1px solid var(--hairline);
    border-radius: 3px;
    padding: 1.5rem;
    display: flex;
    flex-direction: column;
    gap: 0.9rem;
    position: relative;
  }

  .card::before {
    content: attr(data-index);
    position: absolute;
    top: 1.1rem;
    right: 1.3rem;
    font-family: 'Courier New', monospace;
    font-size: 0.68rem;
    letter-spacing: 0.08em;
    color: var(--hairline);
  }

  .card-header {
    display: flex;
    align-items: center;
    gap: 0.9rem;
  }

  .avatar {
    width: 52px;
    height: 52px;
    min-width: 52px;
    border-radius: 50%;
    background: var(--navy);
    color: var(--paper);
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: Georgia, serif;
    font-size: 1.05rem;
    font-weight: 600;
  }

  .card-header h2 {
    font-family: Georgia, 'Times New Roman', serif;
    font-size: 1.15rem;
    font-weight: 600;
    margin: 0;
    color: var(--navy);
  }

  .role {
    font-family: 'Courier New', monospace;
    font-size: 0.72rem;
    letter-spacing: 0.03em;
    color: var(--slate);
    margin-top: 0.15rem;
  }

  .bio {
    font-size: 0.9rem;
    line-height: 1.55;
    color: #33415A;
    margin: 0;
  }

  .tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
    padding-top: 0.6rem;
    border-top: 1px solid var(--hairline);
  }

  .tag {
    font-family: 'Courier New', monospace;
    font-size: 0.66rem;
    letter-spacing: 0.03em;
    color: var(--amber);
    background: #FBF0E4;
    padding: 0.2rem 0.5rem;
    border-radius: 2px;
  }
</style>

<div class="roster">

  <div class="roster-intro">
    <div class="roster-eyebrow">Health Informatics &amp; Data Science Lab</div>
    <h1>People</h1>
    <p>The lab at Loyola University Chicago, working at the intersection of artificial intelligence and clinical care.</p>
  </div>

  <div class="roster-grid">

    <div class="card" data-index="01">
      <div class="card-header">
        <div class="avatar">AV</div>
        <div>
          <h2>Alessandra Vellucci</h2>
          <div class="role">Graduate Research Assistant</div>
        </div>
      </div>
      <p class="bio">Alessandra Vellucci is a Graduate Research Assistant in the Health Informatics and Data Science Lab at Loyola University Chicago. Her research interests include artificial intelligence, natural language processing, clinical informatics, and machine learning applications in healthcare. She is currently working on clinical concept extraction and chunk detection from electronic health records using Spark NLP, while also contributing to an AI-as-a-Judge project designed to evaluate and validate the performance, reliability, and safety of AI systems used in healthcare applications.</p>
      <div class="tags">
        <span class="tag">NLP</span>
        <span class="tag">Clinical Informatics</span>
        <span class="tag">Spark NLP</span>
        <span class="tag">AI Evaluation</span>
      </div>
    </div>

    <div class="card" data-index="02">
      <div class="card-header">
        <div class="avatar">M</div>
        <div>
          <h2>Maryum</h2>
          <div class="role">Data Science Master's Student</div>
        </div>
      </div>
      <p class="bio">I am a Data Science master's student with a background in Bioinformatics in Dr. Tootooni's research group. I am particularly interested in healthcare applications of data science. Currently, I am contributing to projects involving topic modeling and the analysis of stroke triage and mis-triage in clinical settings.</p>
      <div class="tags">
        <span class="tag">Topic Modeling</span>
        <span class="tag">Stroke Triage</span>
        <span class="tag">Bioinformatics</span>
      </div>
    </div>

    <div class="card" data-index="03">
      <div class="card-header">
        <div class="avatar">U</div>
        <div>
          <h2>Ubeyd</h2>
          <div class="role">Research Assistant, Parkinson School of Health Sciences and Public Health</div>
        </div>
      </div>
      <p class="bio">I am a Research Assistant in the Parkinson School of Health Sciences and Public Health, and recently completed my M.S. in Business Data Analytics at Loyola University Chicago. My primary research focuses on healthcare analytics, health economics, and AI driven decision support systems. I currently lead a stroke triage project investigating the clinical and economic burden of patient mis-triage using nationwide emergency department data (HCUP). My broader interests include healthcare operations, predictive modeling, and the use of data science to improve patient outcomes.</p>
      <div class="tags">
        <span class="tag">Health Economics</span>
        <span class="tag">Stroke Triage</span>
        <span class="tag">Decision Support</span>
      </div>
    </div>

    <div class="card" data-index="04">
      <div class="card-header">
        <div class="avatar">PA</div>
        <div>
          <h2>Pharel Adjeyi</h2>
          <div class="role">BSN Student, Loyola Lakeshore Campus</div>
        </div>
      </div>
      <p class="bio">Hi everyone! I'm Pharel Adjeyi, a rising third-year Bachelor of Science in Nursing student at Loyola University Chicago's Lakeshore Campus. This summer, I'm conducting a research project evaluating the use of artificial intelligence visualization tools in healthcare research. My work focuses on assessing various AI platforms based on their ability to generate accurate, clear, and effective visualizations for academic and clinical research settings. Through this project, I aim to explore the strengths, limitations, usability, and potential risks associated with using AI-generated visual content in healthcare research, while identifying best practices for their responsible implementation.</p>
      <div class="tags">
        <span class="tag">AI Visualization</span>
        <span class="tag">Nursing</span>
        <span class="tag">Research Methods</span>
      </div>
    </div>

    <div class="card" data-index="05">
      <div class="card-header">
        <div class="avatar">A</div>
        <div>
          <h2>Adnan</h2>
          <div class="role">Medical Student, Loyola Stritch School of Medicine, Class of 2027</div>
        </div>
      </div>
      <p class="bio">I'm a medical student at Loyola Stritch (Class of 2027). My research examines how AI/ML tools translate into real clinical impact at the system, provider, and patient level. I serve as first author on a study of paramedic perceptions of an ML-based stroke triage tool, and as a co-investigator on a retrospective study quantifying the financial burden of stroke mistriage at non-specialized hospitals.</p>
      <div class="tags">
        <span class="tag">Clinical AI</span>
        <span class="tag">Stroke Triage</span>
        <span class="tag">Health Economics</span>
      </div>
    </div>

  </div>
</div>
