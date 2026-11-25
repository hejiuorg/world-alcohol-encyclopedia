---
schema_version: 1
id: term:acidity
type: term
lang: en
slug: acidity
title: Acidity
summary: Acidity describes the amount and strength of acids in a drink, commonly through total acidity in g/L and pH, two different measures; it supports freshness, balance and ageing potential, and affects sulfur dioxide effectiveness.
status: reviewed
revision: 3
translation_of: term:acidity
source_lang: zh
source_revision: sha256:f6e98598e2be6387e3d9008cc15b70290609d54d7d5570e02cbac30a40710b9d
source_sha256: f6e98598e2be6387e3d9008cc15b70290609d54d7d5570e02cbac30a40710b9d
translation_status: reviewed
legacy_refs: []
aliases:
  - acidity
  - total acidity
  - 酸度
  - 总酸
tags:
  - term
  - chemistry
  - wine
related:
  - relation: about
    target_id: drink-style:wine
  - relation: about
    target_id: drink-style:white-wine
  - relation: about
    target_id: variety:riesling
  - relation: about
    target_id: drink-style:beer
  - relation: about
    target_id: drink-style:sake
  - relation: about
    target_id: process:fermentation
references:
  - key: wine
    target_id: drink-style:wine
  - key: white-wine
    target_id: drink-style:white-wine
  - key: riesling
    target_id: variety:riesling
  - key: beer
    target_id: drink-style:beer
  - key: sake
    target_id: drink-style:sake
  - key: fermentation
    target_id: process:fermentation
sources:
  - key: oiv-definitions
    title: OIV International Code of Oenological Practices — Part I Definitions
    url: https://www.oiv.int/standards/international-oenological-codex/part-i-definitions
    publisher: International Organisation of Vine and Wine (OIV)
    note: Used to check definitions of total acidity, pH and volatile acidity in wine; no source text is reproduced.
    accessed: 2026-11-07
  - key: oiv-total-acidity
    title: OIV-MA-AS313-01 Total acidity (Type-I method)
    url: https://www.oiv.int/standards/annex-a-methods-of-analysis-of-wines-and-musts/section-3-chemical-analysis/section-3-1-organic-compounds/section-3-1-3-acids/total-acidity-(type-i)
    publisher: International Organisation of Vine and Wine (OIV)
    note: Used to check the titration endpoint, conversion factors and expression of total acidity; no source text is reproduced.
    accessed: 2026-11-07
  - key: oxford-wine
    title: The Oxford Companion to Wine
    publisher: Oxford University Press
    note: Used for entries on acidity, pH and tartaric acid.
    accessed: 2026-11-07
    url: https://global.oup.com/academic/product/the-oxford-companion-to-wine-9780198871316
  - key: asbc
    title: American Society of Brewing Chemists — Methods of Analysis
    publisher: ASBC
    note: Used to check common methods for measuring beer acidity and pH; no method text is reproduced.
    accessed: 2026-11-07
    url: https://www.asbcnet.org/methods
  - key: wsu-acidity
    title: Managing High Acidity in Grape Must and Wine
    url: https://wine.wsu.edu/managing-high-acidity-in-grape-must-and-wine/
    publisher: Washington State University — Viticulture & Enology
    note: Used to check total-acidity targets for red must and pH ranges for finished wine; no source text is reproduced.
    accessed: 2026-11-07
  - key: oiv
    title: OIV-MA-AS313-01 Total acidity (Type-I method)
    url: https://www.oiv.int/standards/annex-a-methods-of-analysis-of-wines-and-musts/section-3-chemical-analysis/section-3-1-organic-compounds/section-3-1-3-acids/total-acidity-
    publisher: type-i
    note: Migrated from the former reference list at the end of the article; access date not re-verified.
  - key: ref
    title: The Oxford Companion to Wine (Oxford University Press).
    publisher: Unattributed
    note: Migrated from the former reference list at the end of the article; access date not re-verified.
  - key: ref-2
    title: American Society of Brewing Chemists — Methods of Analysis (ASBC).
    publisher: Unattributed
    note: Migrated from the former reference list at the end of the article; access date not re-verified.
rights:
  status: allowed
  license: CC-BY-4.0
  basis: Project-authored English text verified against OIV analytical methods, university extension material, brewing analysis methods and a wine reference work; no source text is reproduced. The project owner declared project content CC BY 4.0 on 2026-10-29.
  note: Third-party texts, trademarks and images are not covered by this licence; sources are used for verification only.
verification_scope: source-verified
---

# Acidity

![Acidity image](/media/photos/term-acidity-5f4c1ad7.jpg)

Figure: Acidity. Image: Chemicalinterest, Public domain, via Wikimedia Commons ([source page](https://commons.wikimedia.org/wiki/File:Zn_reaction_with_HCl.JPG)).

## Definition and boundaries

Acidity describes how much acid a drink contains and how strong it is. It makes wine feel fresh and structured, and it affects microbial stability and ageing. Acidity is not one number: total acidity, pH and volatile acidity answer different questions, and mixing them up leads to wrong conclusions. Total acidity answers “how much titratable acid is there”, pH answers “how high is hydrogen-ion activity”, and volatile acidity answers “how much volatile acid, mainly acetic acid, is present”.

At least three boundaries need separating. Acidity is not a synonym for sourness: a high-acid wine is not necessarily the sourest, and a low-acid wine can taste sharp when it has little sugar. Nor is acidity a synonym for acid addition: the legal limits for acidification and the changes caused by malolactic fermentation belong to different layers from the acidity of the grapes themselves. Naming whether the figure is total acidity, pH or volatile acidity avoids most confusion.

## Etymology and origin

Acidity comes from Latin acidus, meaning sour or sharp, related to acere (to be sour) and acetum (vinegar). The word moved from a taste description to a chemical category and then into winemaking and tasting language. The Chinese term likewise combines a taste word with a quantity word, so a casual statement that a wine is “high in acidity” may refer to total acidity, pH or subjective sourness.

Tartaric, malic and citric acids are the acids most often named in wine. Tartaric acid comes from the grape itself, malic acid is more prominent in unripe grapes, and citric acid is present at lower levels. Acids differ in how readily they dissociate, so the same total acidity can correspond to different pH values; this is why a wine can have high total acidity without a correspondingly low pH.

## Mechanism and parameters

OIV defines total acidity as the sum of titratable acidities when wine is titrated to pH 7 against a standard alkaline solution, with carbon dioxide excluded. Results can be expressed as sulfuric or tartaric acid: the milliequivalents per litre are multiplied by 0.075 for grams of tartaric acid per litre and by 0.049 for grams of sulfuric acid per litre. That endpoint and those factors are the basis for comparability between laboratories.

PH is the negative logarithm of hydrogen-ion activity and reflects acid strength rather than acid quantity. Lower pH means stronger acid, greater sulfur dioxide effectiveness and a harsher microbial environment. Every 0.1 change in pH alters sulfur dioxide activity, microbial risk and sensory balance, so winemakers record pH separately from total acidity.

Wine total acidity is commonly 6–9 g/L as tartaric acid, with pH mostly 3.0–3.8. White wines usually have higher acidity and lower pH than reds; red wines may reach pH 3.8 or higher, depending on maceration and malolactic fermentation. Washington State University extension material targets total acidity near 6 g/L for red must and notes that finished red wine pH can be 3.3–3.8 depending on tannin content, with low-tannin wines typically at lower pH.

Malolactic fermentation converts sharp malic acid into softer lactic acid, usually lowering total acidity and raising pH. The step is carried out by lactic acid bacteria during [fermentation](ref:fermentation), and whether it happens depends on style and regulation. For high-acid white wines it can soften the palate; for wines that aim at crisp fruit, it may be deliberately avoided.

## Practical use in the drinks industry

Acidity is central to balance. Sugar and alcohol bring weight, while acidity provides freshness and cut; a wine without acidity feels loose and cloying. Acidity also affects ageing: high acidity usually means better antioxidant capacity and longer ageing potential. For [white wine](ref:white-wine), acidity largely determines how fresh the style feels; for red wine, acidity and tannin together form structure.

In the winery, acidity drives several decisions. When total acidity is too high, potassium or calcium carbonate can be used for deacidification; when it is too low, tartaric acid can be added within the legal limits. Whether to run malolactic fermentation, when to inoculate and whether to use skin contact all change final acidity and pH. Sulfur dioxide additions also depend on pH: the same free sulfur dioxide is less effective at a higher pH.

Acidity also affects pairing. High-acid wines cut through fat, balance saltiness and sit more easily with acidic dishes; low-acid wines taste flat next to acidic food. Understanding this is more useful than memorising whether a particular wine is “acidic”.

## Confusable terms

Treating total acidity and pH as the same thing is the most common confusion. Total acidity is the amount of titratable acid; pH is hydrogen-ion activity. High total acidity does not necessarily mean low pH, because acids differ in type and degree of dissociation. Volatile acidity and total acidity form another easily mixed pair. Volatile acidity is mainly acetic acid and other volatile acids; a high level brings vinegar notes and signals quality or hygiene problems, and it is only part of total acidity.

Acidity and sourness are also often treated as synonyms. Acidity is a chemical and structural measure; sourness is a sensory impression. High acidity can be balanced by sugar, alcohol or temperature and may not taste sour at all. Tartaric and malic acid, by contrast, differ in process behaviour. Tartaric acid is relatively stable and is the usual reference for total acidity; malic acid falls after malolactic fermentation while lactic acid rises, so total acidity drops and pH climbs.

## Common misuses and disputes

First, treating total acidity and pH as the same thing, and inferring a low pH from a total acidity of 7 g/L. Second, treating “acid” as a defect; insufficient acidity is the reason many wines taste dull. Third, confusing volatile acidity with total acidity and using total acidity to judge vinegar risk. Fourth, assuming all wines should be as acidic as possible: excessive acidity masks flavour and makes the palate sharp. Fifth, judging objective acidity by personal sensitivity to sourness.

The dispute centres on whether high acidity equals high quality. In high-acid varieties such as Riesling, high acidity can support sweetness and ageing and is read as structure; in low-acid varieties, the same level may seem hard. The safer judgement places acidity within variety, region, style and pairing rather than treating a single number as a quality score.

## Typical values and examples

- Common wine total acidity: 6–9 g/L as tartaric acid.
- Common wine pH: 3.0–3.8; finished red wine can be 3.3–3.8.
- OIV total-acidity titration endpoint: pH 7; tartaric conversion factor: 0.075; sulfuric conversion factor: 0.049.
- Red must total-acidity target: near 6 g/L; some varieties such as Pinot Noir can accept 7 g/L.
- Every 0.1 change in pH alters sulfur dioxide effectiveness and the microbial environment.
- [Beer](ref:beer) is mostly pH 4.0–4.6, and sour beer can be lower; [sake](ref:sake) acidity is often expressed by titration, with lactic and succinic acids giving a soft sourness.
- Typical variety: [Riesling](ref:riesling), whose high acidity supports sweetness and ageing.

These parameters form a comparable framework: acidity is not a single indicator but a system of total acidity, pH, acid types and process.

## See also

- [Wine](ref:wine): categories, vintage and appellation rules.
- [White wine](ref:white-wine): acidity and the typical fresh style.
- [Riesling](ref:riesling): how a high-acid variety supports sweetness and ageing.
- [Beer](ref:beer): pH, organic acids and sour styles.
- [Sake](ref:sake): titratable acidity and soft sourness.
- [Fermentation](ref:fermentation): malolactic fermentation and changes in acidity.
