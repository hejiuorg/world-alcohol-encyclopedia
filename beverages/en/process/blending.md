---
schema_version: 1
id: process:blending
type: process
lang: en
slug: blending
title: Blending
summary: Combining liquids from different batches, vintages, varieties or cask types in set proportions to stabilise quality, balance structure or build a fixed style; wine, Champagne, whisky, brandy and baijiu follow different rules and logics.
status: reviewed
revision: 3
translation_of: process:blending
source_lang: zh
source_revision: sha256:f981b6e5eb1248db6158349bd962fedfa78a55de56dfbc6b6a9c32a1c9526e60
source_sha256: f981b6e5eb1248db6158349bd962fedfa78a55de56dfbc6b6a9c32a1c9526e60
translation_status: reviewed
legacy_refs: []
aliases:
  - Assemblage
  - Blending process
tags:
  - curated
  - source-verified
  - process
  - wine
  - whisky
related:
  - relation: about
    target_id: drink-style:wine
  - relation: about
    target_id: drink-style:sparkling-wine
  - relation: about
    target_id: drink-style:whisky
  - relation: about
    target_id: drink-style:brandy
  - relation: about
    target_id: process:oak-ageing
references:
  - key: wine
    target_id: drink-style:wine
  - key: sparkling
    target_id: drink-style:sparkling-wine
  - key: whisky
    target_id: drink-style:whisky
  - key: brandy
    target_id: drink-style:brandy
  - key: oak-ageing
    target_id: process:oak-ageing
sources:
  - key: eu-wine
    title: EU Regulation 1308/2013 — Common Market Organisation for Wine
    url: https://eur-lex.europa.eu/eli/reg/2013/1308/oj
    publisher: European Union
    note: Used to check the EU framework for wine categories, blending and labelling; no source text is reproduced.
    accessed: 2026-11-04
  - key: swa
    title: Story of Scotch — Scotch Whisky Association
    url: https://scotch-whisky.org.uk/discover-scotch/story-of-scotch/
    publisher: Scotch Whisky Association (SWA)
    note: Used to check the blended categories and labelling rules for Scotch whisky; no source text is reproduced.
    accessed: 2026-11-04
  - key: gbt-15109
    title: GB/T 15109-2021 Terminology of Baijiu Industry
    url: https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=D2F1ED3F0BAA0EBE99AEE34293C0BC43
    publisher: State Administration for Market Regulation, Standardisation Administration of China
    published: 2021-05-21
    note: Used to check baijiu blending and base-liquor terminology; no source text is reproduced.
    accessed: 2026-11-04
  - key: oxford-wine
    title: The Oxford Companion to Wine
    publisher: Oxford University Press
    note: Used for reference on wine blending, mixed varieties and Champagne assemblage; no source text is reproduced.
    accessed: 2026-11-04
    url: https://global.oup.com/academic/product/the-oxford-companion-to-wine-9780198871316
  - key: ref
    title: The Oxford Companion to Wine (Oxford University Press).
    publisher: Unattributed
    note: Migrated from the former reference list at the end of the article; access date not re-verified.
rights:
  status: allowed
  license: CC-BY-4.0
  basis: Project-authored; checked against EU regulations, industry association material and public national standard information, with no source text reproduced. The project owner declared project content CC BY 4.0 on 2026-11-04.
  note: Third-party standards, trademarks, photographs and quoted texts are not covered by this licence; sources are used for verification only.
verification_scope: source-verified
applies_to_refs:
  - drink-style:wine
  - drink-style:sparkling-wine
  - drink-style:whisky
  - drink-style:brandy
  - drink-style:baijiu
---
# Blending

Blending is the process of combining liquids from different batches, vintages, varieties, regions or cask types in set proportions. It can be a technical tool for consistency or the core of style design. Wine, Champagne, whisky, brandy and baijiu all blend, but the permitted scope, terminology and goals differ. Reading blending as simply "mixing things together" ignores proportional design, sensory calibration and the settling that follows.

![Editorial illustration of a wine blending trial](/media/photos/editorial-blending-q2.jpg)

Figure: Editorial illustration of a wine blending trial: base wines compared in beakers, with a pipette for bench trials; AI-assisted illustration, not a photograph. Image: Hejiu editorial team, project-owned.

## Place in the process

Blending sits after each component has finished fermentation or ageing and before stabilisation and bottling. It may happen several times: blending base wines, blending between barrels, and a final blend before bottling. In Champagne, assemblage happens before the in-bottle second fermentation; in whisky, blending happens before bottling, but the liquids involved have already spent different periods in [oak](ref:oak-ageing). In baijiu, blending combines base spirits from different rounds and pits and is part of finished-product design.

## Steps and parameters

The usual sequence is component assessment, bench trials, fixing proportions, vat blending, resting, stabilisation and filtration. Bench trials record alcohol, titratable acidity, pH, residual sugar, colour, tannin and aroma intensity; after vat blending the liquid rests for 2–4 weeks so colloids and aromas can rebalance. These ranges follow the common descriptions in the regulations, industry material and reference works listed on this process. Temperature, stirring and oxygen during mixing change how quickly components marry; when alcohol levels differ widely, a compatibility trial should come first to avoid protein or tartrate precipitation.

## Mechanism: colloids, colour and volatility

Blending is not simple addition. When liquids are mixed, potassium bitartrate and proteins can cross their solubility limits and precipitate; tannins and pigments undergo co-pigmentation, making colour deeper and more stable; tannin molecules aggregate, so astringency shifts from sharp to round. Ethanol concentration changes the volatility of aroma compounds, so a component with slightly more alcohol can push aromas forward and also mask delicate floral notes. Acid and sugar interact in perception: high acidity suppresses sweetness, while high alcohol amplifies acidity.

## Equipment and variants

Equipment includes blending tanks with agitation and temperature control, flow meters, in-line mixers, nitrogen blanketing and sampling systems. Traditional cellars blend in wood with manual measurement; modern plants use automatic dosing and batch traceability. Variants include single-vintage blending, multi-vintage blending, single-variety and mixed-variety wines, single-cask and cask-to-cask spirits, and vertical or horizontal assemblage in Champagne. Equipment precision affects how repeatable a ratio is, but sensory calibration still depends on a tasting panel, and instruments cannot replace the palate.

## Failure modes and diagnosis

Four problems are common. First, imbalance: acidity or alcohol stands out and aroma is suppressed, usually visible at bench-trial stage. Second, stability failure: tartrate crystals, protein haze or pigment deposit after bottling, often because cold and protein stabilisation were not repeated after blending. Third, microbial risk: a component carrying residual sugar or an infection contaminates the whole tank. Fourth, label or regulatory breach: variety, vintage or category claims fall outside what is permitted. Diagnosis should combine bench re-tasting, stability trials and a regulatory check rather than the taste of the vat alone.

## Effect on flavour

Moderate blending improves completeness: a high-acid component lifts a flabby batch, old wine brings dried fruit, spice and softer tannin, young wine brings fresh fruit and energy; new oak adds vanilla and toast while old oak adds neutral texture. In [wine](ref:wine), blending can happen at variety, parcel or vintage level; in [Champagne](ref:sparkling), assemblage is style design; in [whisky](ref:whisky), blended and single-cask products represent two product logics; in [brandy](ref:brandy), the mix of ages sets roundness and complexity. Excessive blending flattens character.

## Effect on stability

Blending disturbs the existing colloidal balance, so cold, protein and microbial stability must be re-established afterwards. Potassium bitartrate precipitates at low temperature and can be prevented by cold treatment and contact seeding; protein instability comes from differences in protein composition between batches and should be checked with a bentonite trial; changes in residual sugar and alcohol affect the effectiveness of sulfur dioxide, so free and molecular fractions must be recalculated. Filtration after blending changes texture, and over-filtration can strip aroma and body.

## Regulation and labels

Blending is not unlimited. EU wine rules govern categories, variety labelling and permitted blending; Scotch whisky has specific requirements for names such as blended Scotch whisky and blended malt; Chinese baijiu blending and age statements are also constrained by standards. Terms such as single cask, single vintage and blended on a label describe the scope of blending. The Chinese term for blending is often misunderstood as adulteration, but in the baijiu industry it is a normal step in combining base spirits; the real problems are false age claims, illegal additions and label fraud.

## Common misconceptions

First, equating blending with dilution or adulteration. Second, assuming every drink suits cross-batch mixing and ignoring the value of a single vintage or single cask. Third, copying a recipe by proportion while ignoring differences between base years. Fourth, bottling after blending without repeating stability trials. Fifth, treating "original spirit" as a guarantee of quality, when it too must be assessed and designed.

## See also

- [Wine](ref:wine) and [Champagne](ref:sparkling): still-wine blending and assemblage.
- [Whisky](ref:whisky) and [brandy](ref:brandy): the product logic of blended spirits.
- [Oak ageing](ref:oak-ageing): the maturation step that shapes how blends integrate.

Start with the inputs. From there, consider the sequence of steps, then what changes at the end. That is how a practical judgment about Blending is built.

[Wine](ref:wine) and [Whisky](ref:whisky) are the nearest useful comparisons: one clarifies purpose, the other tests control point.

**Short definition:** Combining liquids from different batches, vintages, varieties or cask types in set proportions to stabilise quality, balance structure or build a fixed style; wine, Champagne, whisky, brandy and baijiu follow different rules and logics.

A common mistake is to treat Blending as a brand. Start with what it is, then check where it belongs. If they conflict, trust the more specific source.

**Key facts.**

| Item | Detail |
| --- | --- |
| In one line | Combining liquids from different batches, vintages, varieties or cask types in set proportions to stabilise quality, balance structure or build a fixed style; wine, Champagne, whisky, brandy and baijiu follow different r… |
| Applies to | Wine、Sparkling wine、Whisky |

**Sources and limits.** The key claims about Blending are checked against the following sources: European Union (Used to check the EU framework for wine categories, blending and labelling), Scotch Whisky Association (SWA) (Used to check the blended categories and labelling rules for Scotch whisky), State Administration for Market Regulation, Standardisation Administration of China (Used to check baijiu blending and base-liquor terminology) and 5 sources in total. Prices, batches and status change; the body is project-written and does not reproduce source text.
