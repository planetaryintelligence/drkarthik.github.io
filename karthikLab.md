---
layout: default
title: karthikLab
nav_order: 1
has_children: true
permalink: /karthikLab/
---

# karthikLab

Adjunct Professor, [KAIST](https://gggs.kaist.ac.kr) &nbsp;|&nbsp;<span id="k-email"></span>

<noscript>
  <!-- Fallback if JS is disabled or GitHub preview strips <script> -->
  <a href="&#109;&#97;&#105;&#108;&#116;&#111;&#58;&#100;&#114;&#107;&#97;&#114;&#116;&#104;&#105;&#107;&#64;&#107;&#97;&#105;&#115;&#116;&#46;&#97;&#99;&#46;&#107;&#114;">
    &#100;&#114;&#107;&#97;&#114;&#116;&#104;&#105;&#107;&#64;&#107;&#97;&#105;&#115;&#116;&#46;&#97;&#99;&#46;&#107;&#114;
  </a>
</noscript>

{% raw %}
<script type="text/javascript">
(function () {
  /* 1 – address parts (Unicode‑escaped) */
  var u = "\u0064\u0072\u006B\u0061\u0072\u0074\u0068\u0069\u006B";            /* drkarthik */
  var d = "\u006B\u0061\u0069\u0073\u0074\u002E\u0061\u0063\u002E\u006B\u0072";/* kaist.ac.kr */

  /* 2 – build the mailto: link */
  var a = document.createElement("a");
  a.href  = "mailto:" + u + "@" + d;
  a.title = u + "@" + d;

  /* 3 – mail icon (swap `src` if you prefer another icon) */
  var img = document.createElement("img");
  img.src    = "https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/gmail.svg";
  img.alt    = "Email";
  img.width  = 24;
  img.height = 24;
  img.style.verticalAlign = "middle";

  /* 4 – inject into the page */
  a.appendChild(img);
  document.getElementById("k-email").appendChild(a);
})();
</script>
{% endraw %}

AI for complex systems: learning across scales, connecting scientific knowledge, and acting under uncertainty.

**Research themes:** AI for complex systems · Scientific ML · Earth system science · Energy markets · Reinforcement learning

[All publications]({{ '/karthikLab/publications/' | relative_url }}) · [Climate]({{ '/karthikLab/kClimate/' | relative_url }}) · [Energy]({{ '/karthikLab/kEnergy/' | relative_url }}) · [Earth]({{ '/karthikLab/kEarth/' | relative_url }})

## Graph learning across scales

Architecture diagrams from KDD, IJCAI and WSDM. Select a figure to open it at full resolution.

<article class="paper" id="bounded-multiscale-forecasting-with-hierarchical-and-sequential-mesh-refinement-of-graph-neural-networks"><div class="paper-meta">2026 · Proceedings of the 32nd ACM SIGKDD Conference on Knowledge Discovery and Data Mining</div><h3><a href="https://doi.org/10.1145/3770855.3818890">Bounded Multiscale Forecasting with Hierarchical and Sequential Mesh Refinement of Graph Neural Networks</a></h3><p class="paper-authors">T Bailie, SK Mukkavilli, V Vetrova, YS Koh</p><figure class="paper-figure"><a href="{{ '/assets/images/papers/flow.png' | relative_url }}"><img src="{{ '/assets/images/papers/flow.png' | relative_url }}" alt="The Flow framework: hierarchical and sequential mesh refinement for multiscale forecasting." loading="lazy"></a><figcaption>The Flow framework: hierarchical and sequential mesh refinement for multiscale forecasting. <a href="https://doi.org/10.1145/3770855.3818890">Figure 1 · T Bailie et al., 2026</a></figcaption></figure><p class="paper-links"><a href="https://doi.org/10.1145/3770855.3818890">Read publication</a> · <a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=DKFiD7cAAAAJ&amp;sortby=pubdate&amp;citation_for_view=DKFiD7cAAAAJ:P7Ujq4OLJYoC">Google Scholar</a></p></article>

<article class="paper" id="addressing-downward-memory-loss-in-hierarchical-gnn-forecasters-through-memory-buffered-decoding"><div class="paper-meta">2026 · IJCAI</div><h3><a href="https://ijcai-preprints.s3.us-west-1.amazonaws.com/2026/4495.pdf">Addressing Downward Memory Loss in Hierarchical GNN Forecasters Through Memory-Buffered Decoding</a></h3><p class="paper-authors">T Bailie, SK Mukkavilli, V Vetrova, YS Koh</p><figure class="paper-figure"><a href="{{ "/assets/images/papers/higflow-architecture.png" | relative_url }}"><img src="{{ "/assets/images/papers/higflow-architecture.png" | relative_url }}" alt="HiGFlow architecture: graph coarsening learns global trends, while a memory-buffered downward pass preserves information across scales." loading="lazy"></a><figcaption>HiGFlow architecture: graph coarsening learns global trends, while a memory-buffered downward pass preserves information across scales. <a href="https://ijcai-preprints.s3.us-west-1.amazonaws.com/2026/4495.pdf">Figure 3 · Bailie et al., 2026</a></figcaption></figure><p class="paper-links"><a href="https://ijcai-preprints.s3.us-west-1.amazonaws.com/2026/4495.pdf">Read publication</a> · <a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=DKFiD7cAAAAJ&amp;sortby=pubdate&amp;citation_for_view=DKFiD7cAAAAJ:nZcligLrVowC">Google Scholar</a></p></article>

<article class="paper" id="hoga-higher-order-graph-attention-via-diversity-aware-k-hop-sampling"><div class="paper-meta">2026 · WSDM 2026</div><h3><a href="https://doi.org/10.1145/3773966.3777960">HoGA: Higher-Order Graph Attention via Diversity-Aware k-Hop Sampling</a></h3><p class="paper-authors">T Bailie, YS Koh, SK Mukkavilli</p><figure class="paper-figure"><a href="{{ "/assets/images/papers/hoga-architecture.png" | relative_url }}"><img src="{{ "/assets/images/papers/hoga-architecture.png" | relative_url }}" alt="HoGA architecture: k-hop graph sampling, adjacency matrices and higher-order attention combine information at multiple graph distances." loading="lazy"></a><figcaption>HoGA architecture: k-hop graph sampling, adjacency matrices and higher-order attention combine information at multiple graph distances. <a href="https://doi.org/10.1145/3773966.3777960">Figure 2 · Bailie et al., 2026</a></figcaption></figure><p class="paper-links"><a href="https://doi.org/10.1145/3773966.3777960">Read publication</a> · <a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=DKFiD7cAAAAJ&amp;sortby=pubdate&amp;citation_for_view=DKFiD7cAAAAJ:r_AWSJRzSzQC">Google Scholar</a></p></article>

## Learning and control

<article class="paper" id="position-train-robustly-and-certify-at-runtime-under-partial-observability"><div class="paper-meta">2026 · 1st IJCAI Workshop on Safe Physical AI (position paper)</div><h3><a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=DKFiD7cAAAAJ&amp;sortby=pubdate&amp;citation_for_view=DKFiD7cAAAAJ:OP4eGU-M3BUC">Position: Train Robustly and Certify at Runtime Under Partial Observability</a></h3><p class="paper-authors">C Zhou, SK Mukkavilli, Y Gao</p><figure class="paper-figure"><a href="{{ '/assets/images/papers/safe-ai.png' | relative_url }}"><img src="{{ '/assets/images/papers/safe-ai.png' | relative_url }}" alt="Robust policy training and runtime certification under partial observability." loading="lazy"></a><figcaption>Robust policy training and runtime certification under partial observability. <a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=DKFiD7cAAAAJ&amp;sortby=pubdate&amp;citation_for_view=DKFiD7cAAAAJ:OP4eGU-M3BUC">Figure 1 · C Zhou et al., 2026</a></figcaption></figure><p class="paper-links"><a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=DKFiD7cAAAAJ&amp;sortby=pubdate&amp;citation_for_view=DKFiD7cAAAAJ:OP4eGU-M3BUC">Read publication</a> · <a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=DKFiD7cAAAAJ&amp;sortby=pubdate&amp;citation_for_view=DKFiD7cAAAAJ:OP4eGU-M3BUC">Google Scholar</a></p></article>

<article class="paper" id="model-based-reinforcement-learning-for-ultrasound-driven-autonomous-microrobots"><div class="paper-meta">2025 · Nature Machine Intelligence 7, 1076–1090</div><h3><a href="https://doi.org/10.1038/s42256-025-01054-2">Model-based reinforcement learning for ultrasound-driven autonomous microrobots</a></h3><p class="paper-authors">M Medany, L Piglia, L Achenbach, SK Mukkavilli, D Ahmed</p><figure class="paper-figure"><a href="{{ '/assets/images/papers/microrobots.png' | relative_url }}"><img src="{{ '/assets/images/papers/microrobots.png' | relative_url }}" alt="Experimental platform and learning workflow for autonomous ultrasound-driven microrobots." loading="lazy"></a><figcaption>Experimental platform and learning workflow for autonomous ultrasound-driven microrobots. <a href="https://doi.org/10.1038/s42256-025-01054-2">Figure 1 · M Medany et al., 2025</a></figcaption></figure><p class="paper-links"><a href="https://doi.org/10.1038/s42256-025-01054-2">Read publication</a> · <a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=DKFiD7cAAAAJ&amp;sortby=pubdate&amp;citation_for_view=DKFiD7cAAAAJ:3htObqc8RwsC">Google Scholar</a></p></article>

<article class="paper" id="ai-driven-autonomous-microrobots-for-targeted-medicine"><div class="paper-meta">2024 · Nature Reviews Bioengineering</div><h3><a href="https://doi.org/10.1038/s44222-024-00232-y">AI-driven autonomous microrobots for targeted medicine</a></h3><p class="paper-authors">M Medany, SK Mukkavilli, D Ahmed</p><figure class="paper-figure"><a href="{{ '/assets/images/papers/targeted-medicine.png' | relative_url }}"><img src="{{ '/assets/images/papers/targeted-medicine.png' | relative_url }}" alt="A conceptual framework for AI-driven microrobots in precision medicine." loading="lazy"></a><figcaption>A conceptual framework for AI-driven microrobots in precision medicine. <a href="https://doi.org/10.1038/s44222-024-00232-y">Figure 1 · M Medany et al., 2024</a></figcaption></figure><p class="paper-links"><a href="https://doi.org/10.1038/s44222-024-00232-y">Read publication</a> · <a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=DKFiD7cAAAAJ&amp;sortby=pubdate&amp;citation_for_view=DKFiD7cAAAAJ:IRz6iEL74y4C">Google Scholar</a></p></article>

## Earlier preprint

[Reducing Smoothness with Expressive Memory Enhanced Hierarchical Graph Neural Networks](https://arxiv.org/abs/2504.00349). Thomas Bailie, Yun Sing Koh, S. Karthik Mukkavilli and Varvara Vetrova (2025).

## Graduates, PhDs, Postdocs

Please apply directly to KAIST, then indicate interest in AI co-supervision with me alongside a KAIST [professor](https://gggs.kaist.ac.kr/english/all-professor/index) focusing on a domain.
