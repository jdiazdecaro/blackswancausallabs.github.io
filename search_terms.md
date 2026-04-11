# PubMed & Preprint Search Terms
## Real-World Evidence (RWE) | Artificial Intelligence | Causal Inference

---

## Real-World Evidence (RWE) / Pharmacoepidemiology

### Core Terms
- `real-world evidence` OR `real-world data` OR `RWE` OR `RWD`
- `pharmacoepidemiology`
- `observational study` OR `observational research`
- `comparative effectiveness research` OR `CER`
- `electronic health records` OR `EHR` OR `claims data` OR `administrative data`
- `post-market surveillance` OR `post-authorization safety study` OR `PASS`

### PubMed MeSH Terms
- `Pharmacoepidemiology[MeSH]`
- `Comparative Effectiveness Research[MeSH]`
- `Electronic Health Records[MeSH]`

---

## Causal Inference

### Core Terms
- `causal inference`
- `target trial emulation` OR `trial emulation`
- `directed acyclic graph` OR `DAG` OR `causal diagram`
- `propensity score` OR `inverse probability weighting` OR `IPW`
- `instrumental variable`
- `difference-in-differences` OR `DiD`
- `regression discontinuity`
- `g-computation` OR `g-formula` OR `marginal structural model` OR `MSM`
- `counterfactual`
- `confounding` OR `unmeasured confounding` OR `residual confounding`
- `time-varying confounding`

### PubMed MeSH Terms
- `Propensity Score[MeSH]`
- `Confounding Factors, Epidemiologic[MeSH]`

---

## Artificial Intelligence / Machine Learning

### Core Terms
- `machine learning` OR `deep learning` OR `artificial intelligence`
- `large language model` OR `LLM` OR `generative AI`
- `natural language processing` OR `NLP`
- `prediction model` OR `prognostic model`
- `federated learning`
- `causal machine learning` OR `causal ML`
- `double machine learning` OR `DML`
- `targeted learning` OR `TMLE` OR `targeted maximum likelihood`
- `SuperLearner` OR `ensemble learning`

### PubMed MeSH Terms
- `Machine Learning[MeSH]`
- `Artificial Intelligence[MeSH]`
- `Natural Language Processing[MeSH]`

---

## Combination / Intersection Queries

```
("real-world evidence" OR "real-world data") AND ("causal inference" OR "target trial emulation")
```

```
("machine learning" OR "artificial intelligence") AND ("causal inference") AND ("observational study" OR "pharmacoepidemiology")
```

```
("large language model" OR "LLM" OR "generative AI") AND ("real-world evidence" OR "real-world data" OR "electronic health records" OR "claims data" OR "administrative data" OR "registry" OR "epidemiology" OR "digital health" OR "digital technologies")
```

```
("directed acyclic graph" OR "DAG") AND ("pharmacoepidemiology" OR "observational study")
```

```
("double machine learning" OR "TMLE" OR "targeted learning") AND ("real-world" OR "observational")
```

```
("large language model" OR "LLM" OR "generative AI") AND ("pharmacovigilance" OR "adverse event" OR "drug safety")
```

---

## Platform-Specific Tips

| Platform | Tips |
|---|---|
| **PubMed** | Use MeSH tags + `[tiab]` (title/abstract) for free text; combine with `AND hasabstract[text] AND "last 3 years"[PDat]` |
| **bioRxiv/medRxiv** | Free text only; search via site search or Google (`site:biorxiv.org "target trial emulation"`) |
| **Google Scholar** | Good for preprints + grey lit; use quotes for exact phrases |
| **SSRN / OSF** | Useful for health econ / policy-adjacent RWE work |

---

*Generated April 2026 — Black Swan Causal Labs*
