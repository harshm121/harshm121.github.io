---
title: "Publications"
---

<head>
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-NB6TYSXY61"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-NB6TYSXY61');
</script>
</head>


## **Publications**:
**\* Equal Contribution** 

(1) Shreyas S\*, **Harsh Maheshwari\***, Avijit Saha\*, Samik Datta\*, Shashank Jain, Disha Makhija, Anuj Nagpal, Sneha Shukla, Suyash S, "Audience Creation for Consumables - Simple and Scalable Precision Merchandising for a Growing Marketplace", Under Review at ICDE'21,  \[[preprint](https://arxiv.org/abs/2011.08575)\]
<details><summary>Abstract</summary>
<div>
<p style="background-color:#ffffcc;"> 
<i>Consumable categories, such as grocery and fast-moving consumer goods, are quintessential to the growth of e-commerce marketplaces in developing countries. In this work, we present the design and implementation of a precision merchandising system, which creates audience sets from over 10 million consumers and is deployed at Flipkart Supermart, one of the largest online grocery stores in India. We employ temporal point process to model the latent periodicity and mutual-excitation in the purchase dynamics of consumables. Further, we develop a likelihood-free estimation procedure that is robust against data sparsity, censure and noise typical of a growing marketplace. Lastly, we scale the inference by quantizing the triggering kernels and exploiting sparse matrix-vector multiplication primitive available on a commercial distributed linear algebra backend. In operation spanning more than a year, we have witnessed a consistent increase in click-through rate in the range of 25-70% for banner-based merchandising in the storefront, and in the range of 12-26% for push notification-based campaigns.
</i>
</p>
</div>
</details>
<br>

(2) **Harsh Maheshwari\***, Shreyas Shetty\*, Nayana Bannur, Srujana Merugu, "Managing an SIR Epidemic Systemvia Optimal Control of Transmission Rate" - ICLR'21 Workshop MLPCP
<details><summary>Abstract</summary>
<div>
<p style="background-color:#ffffcc;"> 
<i>Shaping an epidemic with adaptive contact restriction policies has been the holy grail during the COVID-19 pandemic. In this paper, we explore the problem of determining the optimal control policy for transmission rate assuming SIR dynamics. We first demonstrate that the SIR model with infectious patients and susceptible contacts (i.e., product of transmission rate and susceptible population) interpreted as predators and prey respectively maps to a Lotka-Volterra (LV) predator-prey model. The modified SIR system (LVSIR) has a stable equilibrium point, an ???energy??? conservation property, and exhibits bounded cyclic behaviour similar to an LV system. We exploit this mapping using a control-Lyapunov approach to design a novel, practical control policy (CoSIR) that nudges the SIR model to the desired equilibrium. Empirical comparison with periodic lockdowns on simulated and real COVID-19 data demonstrates the efficacy and adaptability of our approach. 
</i>
</p>
</div>
</details>
<br>


(3) **Harsh Maheshwari\***, Shreyas Shetty\*, Nayana Bannur, Srujana Merugu, "CoSIR: Optimal control of SIR epi-demic dynamics by mapping to Lotka-Volterra System" -  Under review at UAI'21 \[[preprint](https://www.medrxiv.org/content/10.1101/2020.11.10.20211995v2.full.pdf+html)\]
<details><summary>Abstract</summary>
<div>
<p style="background-color:#ffffcc;"> 
<i>Shaping an epidemic with an adaptive contact restriction policy that balances the disease and socioeconomic impact has been the holy grail during the COVID-19 pandemic. Most of the existing work on epidemiological models focuses on scenario-based forecasting via simulation but techniques for explicit control of epidemics via an analytical framework are largely missing. In this paper, we consider the problem of determining the optimal policy for transmission control assuming SIR dynamics, which is the most widely used epidemiological paradigm. We first demonstrate that the SIR model with infectious patients and susceptible contacts (i.e., product of transmission rate and susceptible population) interpreted as predators and prey respectively reduces to a Lotka-Volterra (LV) predator-prey model. The modified SIR system (LVSIR) has a stable equilibrium point, an energy conservation property, and exhibits bounded cyclic behaviour similar to an LV system. This mapping permits a theoretical analysis of the control problem supporting some of the recent simulation-based studies that point to the benefits of periodic interventions. We use a control-Lyapunov approach to design adaptive control policies (CoSIR) to nudge the SIR model to the desired equilibrium that permits ready extensions to richer compartmental models. We also describe a practical implementation of this transmission control method by approximating the ideal control with a finite, but a time-varying set of restriction levels and provide simulation results to demonstrate its efficacy.
</i>
</p>
</div>
</details>
<br>

(4) Nayana Bannur, **Harsh Maheshwari**, Sansiddh Jain, Shreyas Shetty, Srujana Merugu, Alpan Raval, "Adaptive COVID-19 Forecasting via Bayesian Optimization", in CoDS-COMAD 2021 \[[paper](https://doi.org/10.1101/2020.10.19.20215293)\]
<details><summary>Abstract</summary>
<div>
<p style="background-color:#ffffcc;"> 
<i>Accurate forecasts of infections for localized regions are valuable for policy making and medical capacity planning. Existing compartmental and agent-based models for epidemiological forecasting employ static parameter choices and cannot be readily contextualized, while adaptive solutions focus primarily on the reproduction number. In the current work, we propose a novel model-agnostic Bayesian optimization approach for learning model parameters from observed data that generalizes to multiple application-specific fidelity criteria. Empirical results demonstrate the efficacy of the proposed approach with SEIR-like compartmental models on COVID-19 case forecasting tasks. A city-level forecasting system based on this approach is being used for COVID-19 response in a few highly impacted Indian cities.</i>
</p>
</div>
</details>
<br>

(5) Sansiddh Jain, Avtansh Tiwari, Nayana Bannur, Ayush Deva, Siddhant Shingi, Vishwa Shah, Mihir Kulkarni, Namrata Deka, Keshav Ramaswami, Vasudha Khare, **Harsh Maheshwari**, Soma Dhavala, Jithin Sreedharan, Jerome White, Srujana Merugu, Alpan Raval, "A Flexible Data- Driven Framework for COVID-19 Case Forecasting Deployed in a Developing- world Public Health Setting",  Under Review at KDD???21: ACM Conference on Knowledge Discovery and Data Mining.
<details><summary>Abstract</summary>
<div>
<p style="background-color:#ffffcc;"> 
<i>Forecasting infection case counts and estimating accurate epidemiological parameters are critical components of managing the response to a pandemic. This paper describes a modular, extensible framework for a COVID-19 forecasting system, primarily deployed in Mumbai and Jharkhand, India. We employ a variant of the SEIR compartmental model motivated by the nature of the available data and operational constraints. We estimate best fit parameters using Sequential Model-Based Optimization (SMBO), and describe the use of a novel, fast and approximate Bayesian model averaging method (ABMA) for parameter uncertainty estimation that compares well with a more rigorous Markov Chain Monte Carlo (MCMC) approach in practice. We address on-the-ground deployment challenges such as spikes in the reported input data using a novel weighted smoothing method. We describe extensive empirical analyses to evaluate the accuracy of our method on ground truth as well as against other state-of-the-art approaches. Finally, we outline deployment lessons and describe how inferred model parameters were used by government partners to interpret the state of the epidemic and how model forecasts were used to estimate staffing and planning needs essential for addressing COVID-19 hospital burden
</i>
</p>
</div>
</details>
<br>
