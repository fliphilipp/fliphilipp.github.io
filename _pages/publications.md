---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<hr>

<h2>Open Data Products & Software</h2>
<p>Archived with DOIs on Zenodo; further repositories are on <a href="https://github.com/fliphilipp">my GitHub</a>.</p>
<ul>
  <li><strong>FLUID-SuRRF source code</strong>: automated supraglacial lake detection and depth retrieval in ICESat-2 photon data, incl. a Singularity container for distributed high-throughput computing (2024). <a href="https://doi.org/10.5281/zenodo.10905941">doi:10.5281/zenodo.10905941</a></li>
  <li><strong>FLUID-SuRRF lake data</strong>: 1,249 ICESat-2 lake segments with along-track depths (2024). <a href="https://doi.org/10.5281/zenodo.10901737">doi:10.5281/zenodo.10901737</a></li>
  <li><strong>FLUIDSuRRF-figures</strong>: data and code for figure reproduction (2024). <a href="https://doi.org/10.5281/zenodo.10901826">doi:10.5281/zenodo.10901826</a></li>
  <li><strong>ICESat2Sentinel2</strong> (v0.1.0): open-source code for pairing ICESat-2 data with Sentinel-2 imagery (2025). <a href="https://doi.org/10.5281/zenodo.14722234">doi:10.5281/zenodo.14722234</a></li>
  <li><strong>Amery ice doline</strong>: data and code for Warner et al. (2021) (2021). <a href="https://doi.org/10.5281/zenodo.4747428">doi:10.5281/zenodo.4747428</a></li>
  <li><strong>ameryMeltLakesICESat2</strong> (v1.0.0): code for ICESat-2 melt-lake depth retrieval comparisons for Fricker et al. (2021) (2020). <a href="https://doi.org/10.5281/zenodo.4299237">doi:10.5281/zenodo.4299237</a></li>
  <li><strong>pondpicking</strong>: interactive Jupyter tool for ICESat-2 lake-depth retrieval, used in Lutz et al. (2024, <em>The Cryosphere</em>). <a href="https://github.com/fliphilipp/pondpicking">GitHub</a></li>
  <li><strong>ICESat-2 Cookbook chapter</strong>: Arndt, P. &amp; Roberts, C. (2026). Interactive Visualization with OpenAltimetry and Google Earth Engine. Project Pythia. <a href="https://doi.org/10.5281/zenodo.21298648">doi:10.5281/zenodo.21298648</a></li>
  <li><strong>ICESat-2 Hackweek 2022 and 2023</strong> websites and tutorials (co-author), eScience Institute, University of Washington. <a href="https://doi.org/10.5281/zenodo.6462479">doi:10.5281/zenodo.6462479</a>; <a href="https://doi.org/10.5281/zenodo.10519966">doi:10.5281/zenodo.10519966</a></li>
  <li><strong>Global Fishing Watch Sentinel-2 vessel detections</strong> (contributor, team product): a global, openly available dataset, 2025-present.</li>
</ul>
