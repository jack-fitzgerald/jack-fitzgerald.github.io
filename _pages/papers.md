---
title: 
layout: single
classes: wide
permalink: /papers/
---
<br/> 

# <center> Published and Forthcoming Papers </center>
- - -

**Is There a Foreign Language Effect on Workplace Bribery Susceptibility? Evidence from a Randomized Controlled Vignette Experiment** (with [Paul Stroet](https://paulstroet.netlify.app/), [Arjen van Witteloostuijn](https://research.vu.nl/en/persons/arjen-van-witteloostuijn), and [Kristina S. Weißmüller](https://www.ksweissmueller.com/)). *Journal of Business Ethics*, 2024. <br/>
<small>[ <a href="#/" onclick="visib('fle_bribery')">Abstract</a> | [Article (Open Access)](https://doi.org/10.1007/s10551-024-05731-x) | [Draft](https://jack-fitzgerald.github.io/files/JBE_manuscript.pdf) | [Code](https://doi.org/10.17605/OSF.IO/Y3NQ7) ] </small>

<div id="fle_bribery" style="display: none; text-align: justify; line-height: 1.2" ><small>

Theory and evidence from the behavioral science literature suggest that the widespread and rising use of <i>lingua francas</i> in the workplace may impact the ethical decision-making of individuals who must use foreign languages at work. We test the impact of foreign language usage on individual susceptibility to bribery in workplace settings using a vignette-based randomized controlled trial in a Dutch student sample. Results suggest that there is not even a small foreign language effect on workplace bribery susceptibility. We combine traditional null hypothesis significance testing with equivalence testing methods novel to the business ethics literature that can provide statistically significant evidence of bounded or null relationships between variables. These tests suggest that the foreign language effect on workplace bribery susceptibility is bounded below even small effect sizes. <i>Post hoc</i> analyses provide evidence suggesting fruitful further routes of experimental research into bribery.

</small><br><br/></div>

# <center> Working Papers </center>
- - -

**US States That Mandated COVID-19 Vaccination See Higher, Not Lower, Takeup of COVID-19 Boosters and Flu Vaccines**. 2024. *R&R, PNAS* <br/>
<small>[ <a href="#/" onclick="visib('pnas_replication')">Abstract</a> | [Data & Code](https://osf.io/mdfb4/)] </small>

<div id="pnas_replication" style="display: none; text-align: justify; line-height: 1.2" ><small>

Rains & Richards (2024, <i>PNAS</i>) find that compared to US states that instituted bans on COVID-19 vaccination requirements, states that imposed COVID-19 vaccination mandates exhibit lower adult and child uptake of flu vaccines, and lower uptake of COVID-19 boosters. These differences are generally interpreted causally. However, further inspection reveals that these results are driven by the inclusion of a single bad control variable. When removed, the data instead shows that states which mandated COVID-19 vaccination experience higher COVID-19 booster and flu vaccine takeup than states that banned COVID-19 vaccination requirements.

</small><br><br/></div>

**The Need for Equivalence Testing in Economics**. [<i>Institute for Replication Discussion Paper Series</i>, No. 125](https://hdl.handle.net/10419/296190), 2024. <br/>
<small>[ <a href="#/" onclick="visib('equiv-test')">Abstract</a> | [Draft](https://jack-fitzgerald.github.io/files/The_Need_for_Equivalence_Testing_in_Economics.pdf) | [Online Appendix](https://jack-fitzgerald.github.io/files/The_Need_for_Equivalence_Testing_in_Economics_Online_Appendix.pdf) | [30-Minute Presentation](https://youtu.be/ltkuhpcH9mA) ] </small>

<div id="equiv-test" style="display: none; text-align: justify; line-height: 1.2" ><small>

Equivalence testing methods can provide statistically significant evidence that relationships are practically equal to zero. I demonstrate their necessity in a systematic reproduction of estimates defending 135 null claims made in 81 articles from top economics journals. 37-63% of these estimates cannot be significantly bounded beneath benchmark effect sizes. Though prediction platform data reveals that researchers find these equivalence testing 'failure rates' to be unacceptable, researchers actually expect unacceptably high failure rates, accurately predicting that failure rates exceed acceptable thresholds by around 23 percentage points. To obtain failure rates that researchers deem acceptable, one must contend that over 75% of published effect sizes in economics are practically equivalent to zero, implying that Type II error rates are likely quite high throughout economics. This paper provides economists with empirical justification, guidelines, and commands in Stata and R for conducting credible equivalence testing in future research.

</small><br><br/></div>

**Does Technological Innovation Mitigate Agricultural Damage from Climate Change?** 2024. <br/>
<small>[ <a href="#/" onclick="visib('MS23')">Abstract</a> | [Draft](https://jack-fitzgerald.github.io/files/MS23_Replication.pdf) | [Data & Code](https://osf.io/d7wz9/) ] </small>

<div id="MS23" style="display: none; text-align: justify; line-height: 1.2" ><small>

Moscona & Sastry (2023, <i>Quarterly Journal of Economics</i>) - henceforth MS23 - find that cropland values are significantly less damaged by extreme heat exposure (EHE) when crops are more exposed to technological innovation. However, MS23's 'innovation exposure' variable does not directly measure innovation, instead proxying innovation based on crops' national EHE. A critical re-examination of MS23's replication data shows that this proxy will moderate EHE impacts for reasons unrelated to innovation. Specifically, the proxy is practically indistinguishable from local EHE, so MS23's models examining interaction effects between their proxy and local EHE are effectively interacting local EHE with itself. Resultantly, I show that modelling agricultural land values as a second-order polynomial of local EHE produces qualitative conclusions that are nearly identical to those obtained by MS23. I then construct direct measures of innovation exposure from MS23's crop variety and patenting data. Replacing MS23's proxy with these direct measures of innovation decreases MS23's moderating effect estimates by at least 99.8% in standardized units; none of these new estimates are statistically significantly different from zero. These results cast doubt on MS23's aggregate projections of historical and future climate change damage mitigation from innovation, and on the general capacity for market innovations to mitigate agricultural damage from climate change.

</small><br><br/></div>

[//]: This java script is the button to show abstract
<script>
 function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>

[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>
