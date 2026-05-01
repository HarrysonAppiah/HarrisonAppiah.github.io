---
layout: page
title: About
permalink: /about/
---

<div class="about-wrapper">
  <div class="about-photo">
    <img src="{{ '/assets/profile.jpg' | relative_url }}" alt="Harrison Appiah" />
  </div>

  <div class="about-text">
    <h1>Harrison Appiah</h1>
    <p class="about-role">PhD &mdash; University of Idaho</p>

    <p>
      I am a researcher with a deep interest in turning waste into value. My work sits at the intersection of green chemistry, biomass valorization, and sustainable materials — exploring how agricultural residues, municipal solid waste, and end-of-life plastics can be transformed into useful fuels, chemicals, and packaging materials rather than discarded.
    </p>

    <p>
      My research spans catalytic fast pyrolysis, deep eutectic solvent systems for furfural synthesis, solvent-based plastic recovery, and the development of lignin- and xylan-derived bioproducts. A common thread runs through all of it: the conviction that a circular economy is not just an aspiration but an engineering problem — one that can be solved with the right chemistry and process design.
    </p>

    <p>
      What drives me is the global urgency of waste. Millions of tons of biomass, plastics, and municipal solid waste are generated every year with little recovery. I find it deeply motivating to work on systems that close those loops — recovering materials, generating energy, and reducing environmental burden all at once.
    </p>

    <p>
      Looking ahead, I am eager to bring this work into industry R&amp;D, where I can help scale sustainable technologies and embed circular economy principles into real-world manufacturing and materials pipelines.
    </p>

    <div class="about-links">
      <a href="{{ '/publications/' | relative_url }}">Publications</a>
      <a href="{{ '/research/' | relative_url }}">Research</a>
    </div>
  </div>
</div>

<style>
.about-wrapper {
  display: flex;
  gap: 2.5rem;
  align-items: flex-start;
  max-width: 820px;
  margin-top: 1.5rem;
}

.about-photo img {
  width: 180px;
  height: 180px;
  object-fit: cover;
  border-radius: 50%;
  display: block;
  flex-shrink: 0;
}

.about-text h1 {
  margin: 0 0 0.15rem;
  font-size: 1.5rem;
}

.about-role {
  font-size: 0.875rem;
  color: #888;
  margin: 0 0 1.25rem;
}

.about-text p {
  font-size: 0.95rem;
  line-height: 1.75;
  color: #333;
  margin-bottom: 1rem;
}

.about-links {
  margin-top: 1.5rem;
  display: flex;
  gap: 1rem;
}

.about-links a {
  font-size: 0.875rem;
  font-weight: 600;
  text-decoration: none;
  color: #1a56db;
  border-bottom: 1px solid #1a56db;
  padding-bottom: 1px;
}

.about-links a:hover {
  opacity: 0.7;
}

@media (max-width: 600px) {
  .about-wrapper {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
  .about-links {
    justify-content: center;
  }
}
</style>

