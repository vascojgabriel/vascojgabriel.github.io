---
layout: page
title: Code & data
permalink: /code/
nav: true
nav_order: 6
---

<style>
body {
  background-image:
    linear-gradient(rgba(255,255,255,0.8), rgba(255,255,255,0.8)),
    url("{{ '/assets/img/sjuliao.jpg' | relative_url }}");
  background-size: 100% 100%, cover;
  background-position: center;
  background-repeat: no-repeat;
  background-attachment: fixed;
}
html[data-theme="dark"] body {
  background-image:
    linear-gradient(rgba(20,20,20,0.8), rgba(20,20,20,0.8)),
    url("{{ '/assets/img/sjuliao.jpg' | relative_url }}");
}

/* Photograph caption — same styling as About */
.gafaria-caption {
  position: fixed !important;
  right: 16px !important;
  bottom: 58px !important;
  z-index: 9999 !important;
  color: rgba(48, 48, 48, 0.55) !important;
  background-color: transparent !important;
  padding: 4px 7px;
  border-radius: 3px;
  font-size: 11px;
  font-style: italic;
  font-weight: 400;
  line-height: 1.3;
  white-space: nowrap;
  pointer-events: none;
}

@media (max-width: 600px) {
  .gafaria-caption {
    right: 9px !important;
    bottom: 88px !important;
    font-size: 11px;
  }
}

</style>

Publicly available replication materials associated with my publications. Full citations, coauthors and DOI links appear on the [Publications page]({{ '/publications/' | relative_url }}).

## Replication files

- **[Idle Monetary Policy? Evidence from Monetary Policy Shocks for Pakistan](https://doi.org/10.1016/j.econlet.2026.113207)** (2026) — Narrative monetary-policy shocks and quarterly transmission estimates; Python and Stata files. [Code & data (Mendeley)](https://data.mendeley.com/datasets/bn868kmhd5/2).
- **[Taking the Highway or the Green Road? Conditional Temperature Forecasts under Alternative SSP Scenarios](https://doi.org/10.1016/j.ijforecast.2026.04.010)** (2026) — MATLAB code and data for SSP-conditional forecasts, counterfactuals and forecast evaluation. [Replication files (GitHub)](https://github.com/vascojgabriel/replication-package-conditional-temperature-forecasts).
- **[GMM Model Averaging Using Higher Order Approximations](https://doi.org/10.1016/j.ecosta.2022.09.004)** (2025) — GMM model-averaging research archive. [Replication files (GitHub)](https://github.com/vascojgabriel/GMM-Model-Averaging-Using-Higher-Order-Approximations).
- **[LAMP, Informality and Monetary Growth Rules in an Emerging Economy](https://doi.org/10.1016/j.econmod.2024.106946)** (2025) — Data and model replication material for an emerging-economy DSGE analysis. [Code & data (Mendeley)](https://data.mendeley.com/datasets/yv263k5cmv/2).
- **[Predicting Tail Risks and the Evolution of Temperatures](https://doi.org/10.1016/j.eneco.2023.107286)** (2024) — Public archive containing replication material and a paper PDF. [Replication files (GitHub)](https://github.com/vascojgabriel/Predicting-Tail-Risks-and-the-Evolution-of-Temperatures).
- **[Institutional Arrangements and Inflation Bias](https://doi.org/10.1111/jmcb.12935)** (2023) — Dynamic heterogeneous-panel research archive. [Replication files (GitHub)](https://github.com/vascojgabriel/Institutional-Arrangements-and-Inflation-Bias-A-Dynamic-Heterogeneous-Panel-Approach).
- **[Partial Dollarization and Financial Frictions in Emerging Economies](https://doi.org/10.1111/roie.12639)** (2023) — Emerging-economy DSGE model archive. [Replication files (GitHub)](https://github.com/vascojgabriel/Partial-Dollarization-and-Financial-Frictions-in-Emerging-Economies).
- **[Individual Incentives and Workers’ Contracts](https://doi.org/10.1093/oep/gpz061)** (2021) — Field-experiment research archive. [Replication files (GitHub)](https://github.com/vascojgabriel/Individual-Incentives-and-Workers-Contracts-Evidence-from-a-Field-Experiment).
- **[The Cost Channel Reconsidered](https://doi.org/10.1111/j.1538-4616.2010.00361.x)** (2010) — Identification-robust cost-channel research archive. [Replication files (GitHub)](https://github.com/vascojgabriel/The-Cost-Channel-Reconsidered-A-Comment-Using-an-Identification-Robust-Approach).
- **[An Estimated DSGE Model of the Indian Economy](https://doi.org/10.1093/oxfordhb/9780199734580.013.0029)** (2012) — DSGE model archive accompanying the Oxford Handbook chapter. [Replication files (GitHub)](https://github.com/vascojgabriel/An-Estimated-DSGE-Model-of-the-Indian-Economy).

## Further resources

Publisher or institutional appendices are linked beside the corresponding papers on the [Publications page]({{ '/publications/' | relative_url }}). Browse [all my public GitHub repositories](https://github.com/vascojgabriel?tab=repositories) for additional research software and teaching materials.

*Public availability does not imply that every archive has been independently tested for computational reproducibility. The Pakistan replication package excludes underlying proprietary central-bank forecasts.*

<div class="gafaria-caption">Photo: São Julião, Setúbal</div>
