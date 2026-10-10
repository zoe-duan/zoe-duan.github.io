---
permalink: /
layout: home
title: ""
redirect_from:
  - /about/
  - /about.html
---

<header class="hero">
  <div class="hero__text">
    <h1 class="hero__name">{{ site.author.name }}</h1>
    <p class="hero__role">M.A. Student in Quantitative Methods and Social Analysis</p>
    <div class="hero__meta">
      <span>{% include icon.html name="landmark" %}University of Chicago</span>
      <span>{% include icon.html name="pin" %}{{ site.author.location }}</span>
    </div>
    <div class="bio">
      <p>I am an M.A. student in the <a href="https://mapss.uchicago.edu/">Master of Arts Program in the Social Sciences</a> at the University of Chicago, concentrating in Quantitative Methods and Social Analysis. I received my B.A. in Philosophy with a minor in Economics from Renmin University of China in 2026.</p>
      <p>My work asks how public policy and institutions shape the way firms finance themselves, using quasi-experimental designs such as staggered difference-in-differences and instrumental variables. My current project asks whether China’s digital invoice reform changed how firms borrow.</p>
    </div>
    <ul class="interests" aria-label="Research interests">
      <li>Public &amp; Labor Economics</li>
      <li>Corporate &amp; Household Finance</li>
      <li>Applied Microeconomics</li>
    </ul>
    <div class="links">
      <a href="mailto:{{ site.author.email }}">{% include icon.html name="mail" %}Email</a>
      <a href="https://github.com/{{ site.author.github }}">{% include icon.html name="github" %}GitHub</a>
      <a href="{{ '/files/resume.pdf' | relative_url }}">{% include icon.html name="file" %}CV</a>
    </div>
  </div>
  <img class="hero__photo" src="{{ '/images/profile-portrait.jpg' | relative_url }}" alt="Portrait of {{ site.author.name }}" width="640" height="800">
</header>

<section class="section" id="research">
  <h2 class="section__title">{% include icon.html name="flask" %}Research</h2>

  <article class="project">
    <div class="project__head">
      <h3 class="project__title">Can Digital Tax Infrastructure Improve Firms’ Loan Contract Design? Evidence from China’s Digital Invoice Reform</h3>
      <span class="project__date">2026</span>
    </div>
    <p class="project__meta"><span class="pill">In progress</span>Independent research</p>
    <p class="project__summary">Exploits the province-staggered rollout of fully digital invoices in a two-tier difference-in-differences design, using a panel of 20,679 firms (268,931 firm-years) across the A-share, BSE and NEEQ markets. Long-term borrowing responds much more strongly among less transparent NEEQ firms, consistent with lower verification costs.</p>
    <ul class="tags"><li>Staggered DID</li><li>Event study</li><li>Wild-cluster bootstrap</li></ul>
  </article>

  <article class="project">
    <div class="project__head">
      <h3 class="project__title">Digital Economy Development and Corporate Debt Maturity: Evidence from Chinese A-share Listed Firms</h3>
      <span class="project__date">2025–26</span>
    </div>
    <p class="project__meta"><span class="pill">Thesis</span>Advisor: Prof. Ying Wang, Renmin University of China</p>
    <p class="project__summary">Links a digital-economy index for more than 280 Chinese cities to 19,174 firm-years (2011–2023). Firms in more digitally developed cities hold a larger share of long-term debt, and the effect is weaker where financing constraints are tighter.</p>
    <ul class="tags"><li>Two-way fixed effects</li><li>IV-2SLS</li><li>System GMM</li></ul>
  </article>

  <h3 class="subhead">Research assistance &amp; earlier projects</h3>
  <ul class="rows">
    <li class="row">
      <p class="row__main">Budget disclosure and fiscal transparency in Chinese county governments</p>
      <span class="row__date">2025–26</span>
      <p class="row__sub">Research Assistant to Prof. Cong Qin, Renmin University of China</p>
    </li>
    <li class="row">
      <p class="row__main">Historical roots of China’s population modernization, from Ming–Qing genealogies</p>
      <span class="row__date">2025</span>
      <p class="row__sub">Research Assistant to Prof. Sijie Hu, University of Hong Kong</p>
    </li>
    <li class="row">
      <p class="row__main">Pricing and hedging derivatives under stochastic volatility</p>
      <span class="row__date">2025</span>
      <p class="row__sub">With Dr. Jaksa Cvitanić, California Institute of Technology</p>
    </li>
    <li class="row">
      <p class="row__main">China’s 12-year compulsory education reform and labor outcomes</p>
      <span class="row__date">2024</span>
      <p class="row__sub">With Prof. Weize Chen, Renmin University of China</p>
    </li>
  </ul>
</section>

<section class="section" id="experience">
  <h2 class="section__title">{% include icon.html name="briefcase" %}Industry Experience</h2>
  <ul class="rows">
    <li class="row">
      <p class="row__main">Data Analyst Intern, Baidu</p>
      <span class="row__date">Jul–Sep 2025</span>
      <p class="row__sub">Evaluated DeepSeek and GPT-based language models across datasets</p>
    </li>
    <li class="row">
      <p class="row__main">Quantitative Analyst Intern, Guotai Haitong Securities</p>
      <span class="row__date">May–Jul 2025</span>
      <p class="row__sub">Built and back-tested Barra-style equity factors on ten years of A-share data</p>
    </li>
  </ul>
</section>

<section class="section" id="education">
  <h2 class="section__title">{% include icon.html name="scholar" %}Education</h2>
  <ul class="rows">
    <li class="row">
      <p class="row__main">University of Chicago</p>
      <span class="row__date">2026–27</span>
      <p class="row__sub">M.A. in the Social Sciences, Quantitative Methods and Social Analysis</p>
    </li>
    <li class="row">
      <p class="row__main">Renmin University of China</p>
      <span class="row__date">2022–26</span>
      <p class="row__sub">B.A. in Philosophy, Minor in Economics</p>
    </li>
  </ul>
</section>

<section class="section" id="honors">
  <h2 class="section__title">{% include icon.html name="award" %}Honors &amp; Activities</h2>
  <ul class="rows">
    <li class="row">
      <p class="row__main">Member, Qualitative Methods Workshop, University of Chicago</p>
      <span class="row__date">2026–</span>
    </li>
    <li class="row">
      <p class="row__main">Second Prize, 4th “Jingcai Dachuang” Beijing College Students Innovation and Entrepreneurship Competition</p>
      <span class="row__date">2025</span>
    </li>
    <li class="row">
      <p class="row__main">Third Prize, 26th “Innovation Cup” Academic and Technological Works Competition, Renmin University of China</p>
      <span class="row__date">2024</span>
    </li>
  </ul>
</section>
