#  Fake News vs. Hard Content: Analyzing Thematic Diversity for Propagation Strategy 📰
---

## The Challenge: Challenging Assumptions about Fake News Content

Past research suggests that fake news is predominantly a **political weapon** focused on hard news topics. This project challenged that assumption by investigating whether fake news strategically prioritizes **soft news content** (e.g., health, entertainment) to maximize its reach and propagation among casual readers.

My analysis used **Topic Modeling (K-means clustering)**, **Discriminatory Word Analysis**, and **Classification Model Predictive Analysis** on a corpus of 14,543 newsletter emails categorized as either misinformation ("fake news") or hard content.

This is the final project for POLI 274: Text As Data

---

## Key Data-Driven Insights

The text-as-data analysis provided three key findings that contradict the political-centric assumption:

1. Thematic Prioritization: Health vs. Administration
- **Finding**: Fake news documents frequently featured **health-related topics** (e.g., "health," "organ," "vaccin") and product promotion themes.
- **Implication**: Hard content, conversely, was more focused on structural/administrative goals, featuring words like "address," "book," and "email" to prompt subscriptions. This suggests fake news optimizes for highly engaging **soft content**.

2. Content Strategy: Diversity vs. Focus
- **Finding**: Fake news documents exhibited a greater thematic diversity (nine topics identified, ranging from political to health/product-related).
- **Implication**: Hard content showed a narrower scope (four topics identified), concentrating on traditional areas like international news and regional law enforcement. Fake news uses a **diverse content mix** to cast a wider net for reader attention.

<p align="center">
  <img src="./Plots/Discriminatory-Words-across-Document-Type.png" alt="Discriminatory Words across Document Type" width="600"/>
  <br>
  <em>Figure: Discriminatory Words across Document Type</em>
</p>


3. Hard Content Proportion
- **Finding**: A classification model (Naïve Bayes, F-score 0.69) predicted that only **43.89%** of fake news documents were classified as "hard content."
- **Implication**: This result directly challenges the notion that fake news predominantly features hard content. The majority of the content focused on non-political or soft news topics, suggesting that **dissemination/reach** is a more important goal than purely political motivation.

---

## Actionable Recommendation
**Strategy**: Interventions aimed at combating misinformation should recognize and adapt to the diverse, non-political content strategies used by unreliable sources.
1. Shift Focus from Politics
- **Interventions**: Designing educational interventions that address **health misinformation** and **product-based pseudosciences**, rather than solely focusing on political literacy or hard news source analysis.
2. Analyze Multi-Modal Content
- **Refinement**:Future work should analyze the influence of **multimedia elements** (images, videos, external links) in newsletters, which were beyond the scope of this text-as-data investigation, to get a complete view of the propagation tactics.

---

## Conclusion & Next Steps

This study provides evidence to **reject the assumption** that fake news primarily contains politically motivated hard content, revealing instead a nuanced strategy leveraging a mix of soft and hard content to optimize reach.

- **Next Steps**:  Conduct follow-up research during a major election cycle to accurately model the **temporal shift** in content themes and quantify the effect of heightened partisan polarization.

 
[ **Full Analysis Report**: [Analyzing-Thematic-Diversity-in-Fake-News-and-Hard-Content.pdf](./Analyzing-Thematic-Diversity-in-Fake-News-and-Hard-Content.pdf) | **Analysis Scripts**: [Fake-News-Hard-Content.Rmd](./Fake-News-Hard-Content.Rmd.Rmd) ]
