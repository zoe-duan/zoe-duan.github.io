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
    <p class="hero__role">M.A. Student in the Social Sciences (QMSA)</p>
    <div class="hero__meta">
      <span>{% include icon.html name="landmark" %}University of Chicago</span>
      <span>{% include icon.html name="pin" %}{{ site.author.location }}</span>
    </div>
    <div class="bio">
      <p>I am a graduate student in the <strong>Master of Arts Program in the Social Sciences (MAPSS)</strong> at the <strong>University of Chicago</strong>, concentrating in <strong>Quantitative Methods and Social Analysis (QMSA)</strong> (expected June 2027). In June 2026, I graduated from <strong>Renmin University of China (RUC)</strong> with a B.A. in Philosophy and a Minor in Economics.</p>
      <p>My research interests lie in <strong>Public &amp; Labor Economics</strong>, <strong>Corporate &amp; Household Finance</strong>, and <strong>Applied Microeconomics</strong>. Methodologically, I specialize in quantitative empirical analysis, including staggered difference-in-differences (DID), causal inference, instrumental variables (IV-2SLS), Bayesian optimization, and panel econometrics using Python, Stata, and R.</p>
    </div>
    <div class="links">
      <a href="mailto:{{ site.author.email }}">{% include icon.html name="mail" %}Email</a>
      <a href="https://github.com/{{ site.author.github }}">{% include icon.html name="github" %}GitHub</a>
      <a href="{{ '/files/resume.pdf' | relative_url }}">{% include icon.html name="file" %}CV</a>
    </div>
  </div>
  <img class="hero__photo" src="{{ '/images/profile-portrait.jpg' | relative_url }}" alt="{{ site.author.name }}">
</header>

<section class="section" id="news">
  <h2 class="section__title">{% include icon.html name="news" %}News</h2>
  <ul class="rows">
    <li class="row row--news">
      <span class="row__date">Sep 2026</span>
      <p class="row__main">Began graduate studies in Quantitative Methods and Social Analysis (MAPSS) at the University of Chicago.</p>
    </li>
    <li class="row row--news">
      <span class="row__date">Jun 2026</span>
      <p class="row__main">Graduated from Renmin University of China with a B.A. in Philosophy and a Minor in Economics.</p>
    </li>
  </ul>
</section>

<section class="section" id="research">
  <h2 class="section__title">{% include icon.html name="flask" %}Research Experience</h2>
  <ul class="rows">
    <li class="row row--block">
      <p class="row__main"><strong>Can Digital Tax Infrastructure Improve Firms’ Loan Contract Design? Evidence from China’s Digital Invoice Reform</strong></p>
      <span class="row__date">Mar 2026 – Sep 2026</span>
      <p class="row__sub">Independent Research Project</p>
      <div class="row__desc">
        <ul>
          <li>Constructed and harmonized a panel of 20,679 firms and 268,931 firm-year observations across A-share, BSE, and NEEQ markets by linking iFinD, CSMAR, policy-timing, industry, and firm-history data; retained delisted, transferred, and removed firms to limit sample-selection bias.</li>
          <li>Exploited the province-staggered rollout of fully digital invoices and pre-period industry exposure in a two-tier difference-in-differences design; validated identification using event studies, modern staggered-DID estimators, placebo tests, leave-one-province-out checks, and wild-cluster-bootstrap inference in Python and R.</li>
          <li>Documented a substantially stronger long-term-debt response among less transparent NEEQ firms, consistent with lower verification costs; assessed competing mechanisms and sensitivity to sample construction.</li>
        </ul>
      </div>
    </li>

    <li class="row row--block">
      <p class="row__main"><strong>Research on the Impact of Digital Economy Development on Corporate Debt Maturity Structure and Its Mechanisms: Evidence from Chinese A-share Listed Firms</strong></p>
      <span class="row__date">Oct 2025 – Jun 2026</span>
      <p class="row__sub">Undergraduate Researcher, Thesis &middot; Advisor: Prof. Ying Wang, Renmin University of China</p>
      <div class="row__desc">
        <ul>
          <li>Matched firm financials to a digital-economy index covering more than 280 Chinese cities, constructing a panel of 19,174 firm-year observations from 2011–2023.</li>
          <li>Utilized DID in Python to estimate two-way fixed-effects, IV-2SLS, and system-GMM models with city-clustered inference and extensive robustness and heterogeneity analyses; found larger long-term-debt share where digital development is higher, with weaker effects under tighter financing constraints.</li>
        </ul>
      </div>
    </li>

    <li class="row row--block">
      <p class="row__main"><strong>Budget Disclosure Practices and Transparency in Chinese County Governments</strong></p>
      <span class="row__date">Sep 2025 – Jan 2026</span>
      <p class="row__sub">Research Assistant &middot; Supervisor: Prof. Cong Qin, Renmin University of China</p>
      <div class="row__desc">
        <ul>
          <li>Collected and structured budget and final-account disclosures for 100+ Chinese counties, recording disclosure timing, document type, accessibility, and webpage characteristics for research on local fiscal transparency.</li>
          <li>Cleaned and validated the resulting dataset, resolving inconsistent document names, missing disclosure years, broken links, and differences in local reporting formats using Stata.</li>
        </ul>
      </div>
    </li>

    <li class="row row--block">
      <p class="row__main"><strong>Tracing the Historical Roots of China’s Population Modernization in the Ming and Qing Dynasties</strong></p>
      <span class="row__date">Mar 2025 – Oct 2025</span>
      <p class="row__sub">Research Assistant &middot; Supervisor: Prof. Sijie Hu, University of Hong Kong</p>
      <div class="row__desc">
        <ul>
          <li>Constructed and validated a large-scale historical demographic database from Ming-Qing genealogical manuscripts for quantitative analysis of long-run population change.</li>
          <li>Extracted, cleaned, and standardized thousands of individual and kinship records (Excel), including births, marriages, burials, parent-child relationships, spouses, and adoptions, using cross-text verification.</li>
          <li>Developed systematic consistency checks to identify name ambiguity, contradictory family links, duplicate relationships, and missing observations, documenting recurring error patterns for data cleaning.</li>
        </ul>
      </div>
    </li>

    <li class="row row--block">
      <p class="row__main"><strong>Pricing and Hedging of Financial Derivatives under Stochastic Volatility Models</strong></p>
      <span class="row__date">Jan 2025 – May 2025</span>
      <p class="row__sub">Researcher &middot; Supervisor: Dr. Jaksa Cvitanić, California Institute of Technology</p>
      <div class="row__desc">
        <ul>
          <li>Conducted empirical analysis of derivative pricing and hedging using real-market equity and options data under Black-Scholes and stochastic-volatility frameworks.</li>
          <li>Developed Python workflows to scrape, clean, align, and preprocess S&P 500 equity and options datasets for volatility estimation and model calibration.</li>
          <li>Estimated historical and implied volatility and applied Bayesian parameter optimization to stochastic-volatility models, improving fit to market data by more than 15%.</li>
        </ul>
      </div>
    </li>

    <li class="row row--block">
      <p class="row__main"><strong>The Impact of China’s 12-Year Compulsory Education Reform on Labor Outcomes</strong></p>
      <span class="row__date">Oct 2024 – Dec 2024</span>
      <p class="row__sub">Researcher &middot; Supervisor: Prof. Chen Weize, Renmin University of China</p>
      <div class="row__desc">
        <ul>
          <li>Investigated how China’s 12-year compulsory education reform relates to labor productivity and wage outcomes using econometric analysis in Stata.</li>
          <li>Merged CFPS microdata with regional statistical yearbooks to construct measures of schooling attainment, wages, labor productivity, and local policy exposure in Zhuhai and Zhongshan.</li>
          <li>Conducted heteroskedasticity tests, robust regressions, and LM diagnostics to assess model validity and document relationships among educational attainment, wages, and productivity.</li>
        </ul>
      </div>
    </li>
  </ul>
</section>

<section class="section" id="experience">
  <h2 class="section__title">{% include icon.html name="briefcase" %}Professional Experience</h2>
  <ul class="rows">
    <li class="row row--block">
      <p class="row__main"><strong>Guotai Haitong Securities</strong> &middot; Shanghai, China</p>
      <span class="row__date">May 2025 – Jul 2025</span>
      <p class="row__sub">Quantitative Analyst Intern</p>
      <div class="row__desc">
        <ul>
          <li>Processed ten years of A-share daily data using Python and constructed factor pools for growth, value, momentum, volatility, and size within a Barra multi-factor framework.</li>
          <li>Developed back-testing modules for cross-sectional grouping, parameter tuning, and long-short portfolios; evaluated information coefficients (IC/ICIR), sensitivity, stability, and excess returns.</li>
        </ul>
      </div>
    </li>

    <li class="row row--block">
      <p class="row__main"><strong>Baidu Inc.</strong> &middot; Beijing, China</p>
      <span class="row__date">Jul 2025 – Sep 2025</span>
      <p class="row__sub">Data Analyst Intern</p>
      <div class="row__desc">
        <ul>
          <li>Evaluated DeepSeek and GPT-based large language models across multiple datasets, comparing preprocessing, model design, performance, prompt behavior, and computational efficiency.</li>
          <li>Proposed weighted-sampling and data-augmentation methods to reduce imbalance across high- and low-frequency domains.</li>
        </ul>
      </div>
    </li>
  </ul>
</section>

<section class="section" id="education">
  <h2 class="section__title">{% include icon.html name="scholar" %}Education</h2>
  <ul class="rows">
    <li class="row row--block">
      <p class="row__main"><strong>University of Chicago</strong> &middot; Chicago, IL</p>
      <span class="row__date">Sep 2026 – Expected Jun 2027</span>
      <p class="row__sub">M.A. in the Social Sciences &mdash; Quantitative Methods and Social Analysis (QMSA)</p>
      <div class="row__desc">
        <p><strong>Current Coursework (Fall 2026):</strong> Statistical Theory &amp; Methods, Marketing Strategy, Social Science Analysis</p>
      </div>
    </li>

    <li class="row row--block">
      <p class="row__main"><strong>Renmin University of China (RUC)</strong> &middot; Beijing, China</p>
      <span class="row__date">Sep 2022 – Jun 2026</span>
      <p class="row__sub">B.A. in Philosophy, Minor in Economics</p>
      <div class="row__desc">
        <p><strong>Economics Coursework:</strong> Econometrics, Public Finance, Finance, Intermediate Macroeconomics, Development Economics, Economic History, Game Theory</p>
        <p><strong>Quantitative Coursework:</strong> Statistics, Calculus, Linear Algebra &amp; Probability, Python Programming, Machine Learning and Causal Inference</p>
      </div>
    </li>
  </ul>
</section>

<section class="section" id="skills">
  <h2 class="section__title">{% include icon.html name="code" %}Skills &amp; Interests</h2>
  <div class="skills-grid">
    <div class="skill-card">
      <h3 class="skill-card__title">Research Interests</h3>
      <p class="skill-card__content">Public &amp; Labor Economics, Corporate &amp; Household Finance, Applied Microeconomics</p>
    </div>
    <div class="skill-card">
      <h3 class="skill-card__title">Quantitative Methods</h3>
      <p class="skill-card__content">Difference-in-Differences (DID &amp; Staggered DID), Causal Inference, Instrumental Variables (IV-2SLS), System-GMM, Event Studies, Wild Cluster Bootstrap, Bayesian Parameter Optimization, Linear Regressions</p>
    </div>
    <div class="skill-card">
      <h3 class="skill-card__title">Programming &amp; Tools</h3>
      <p class="skill-card__content"><strong>Languages:</strong> Python, Stata, R, SQL<br><strong>Tools:</strong> Git/GitHub, Office 365 (Excel), iFinD, CSMAR, CFPS</p>
    </div>
    <div class="skill-card">
      <h3 class="skill-card__title">Languages</h3>
      <p class="skill-card__content"><strong>English:</strong> IELTS 7.0 (Listening 7.5, Reading 8.0, Writing 6.5, Speaking 6.5)<br><strong>Chinese:</strong> Native</p>
    </div>
  </div>
</section>

<section class="section" id="honors">
  <h2 class="section__title">{% include icon.html name="award" %}Activities &amp; Honors</h2>
  <ul class="rows">
    <li class="row">
      <p class="row__main">Member, Qualitative Methods Workshop</p>
      <span class="row__date">2026 – Present</span>
      <p class="row__sub">University of Chicago</p>
    </li>
    <li class="row">
      <p class="row__main">2nd Prize, 4th “Jingcai Dachuang” Beijing College Students Innovation and Entrepreneurship Competition</p>
      <span class="row__date">2025</span>
      <p class="row__sub">Beijing, China</p>
    </li>
    <li class="row">
      <p class="row__main">3rd Prize, 26th “Innovation Cup” Extracurricular Academic &amp; Technological Works Competition</p>
      <span class="row__date">2024</span>
      <p class="row__sub">Renmin University of China</p>
    </li>
  </ul>
</section>
