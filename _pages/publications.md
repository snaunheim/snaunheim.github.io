---
layout: page
permalink: /publications/
title: publications.
description: The publications shown here refer only to previously published journal articles. A complete list of publications including talks, conference papers, pre-prints and awards can be requested.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="publications">

<!-- Google Scholar Profile -->
<div class="scholar-profile" style="margin-bottom: 1.5rem; padding: 1rem 1.5rem; background-color: var(--global-code-bg-color); border-radius: 6px; display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; gap: 1rem;">
  <div style="display: flex; align-items: center; gap: 1rem;">
    <i class="ai ai-google-scholar" style="font-size: 2.5rem; color: #4285F4;"></i>
    <div style="text-align: left;">
      <h3 style="margin: 0; font-size: 1.2rem;">Google Scholar Profile</h3>
      <p style="color: var(--global-text-color); opacity: 0.8; margin: 0.25rem 0 0 0; font-size: 0.9rem;">
        View complete metrics and citations
      </p>
    </div>
  </div>
  <a href="https://scholar.google.com/citations?user={{ site.scholar_userid }}"
     target="_blank"
     rel="noopener noreferrer"
     style="display: inline-block; padding: 0.6rem 1.5rem; background-color: #4285F4; color: white; text-decoration: none; border-radius: 4px; font-weight: 500;">
    <i class="ai ai-google-scholar" style="margin-right: 0.5rem;"></i>
    Visit Profile
  </a>
</div>

{% bibliography %}

</div>
