---
schema_version: 1
id: term:original-gravity
type: term
lang: en
slug: original-gravity
title: Original gravity
summary: Original gravity is the concentration of soluble solids, mainly sugars and other extract, in wort before fermentation, usually expressed in °P (degrees Plato); it reflects raw-material extract and is not alcohol content.
status: reviewed
revision: 3
translation_of: term:original-gravity
source_lang: zh
source_revision: sha256:2f53fd2487694f0e9c0b3791ce2cf76bacb061a7e37dc194c2c40af9582d054f
source_sha256: 2f53fd2487694f0e9c0b3791ce2cf76bacb061a7e37dc194c2c40af9582d054f
translation_status: reviewed
legacy_refs: []
aliases:
  - original gravity
  - degrees Plato
  - OG
  - Plato
tags:
  - term
  - beer
  - measurement
related:
  - relation: about
    target_id: drink-style:beer
  - relation: about
    target_id: ingredient:barley
  - relation: about
    target_id: process:fermentation
  - relation: about
    target_id: process:saccharification
  - relation: about
    target_id: drink:czech-pilsnerurquell
references:
  - key: beer
    target_id: drink-style:beer
  - key: barley
    target_id: ingredient:barley
  - key: fermentation
    target_id: process:fermentation
  - key: saccharification
    target_id: process:saccharification
  - key: pilsner
    target_id: drink:czech-pilsnerurquell
sources:
  - key: bjcp
    title: BJCP 2021 Style Guidelines
    url: https://www.bjcp.org/style/2021/
    publisher: Beer Judge Certification Program
    note: Used to check the relationship between original gravity and alcohol in beer styles; no source text is reproduced.
    accessed: 2026-11-07
  - key: asbc
    title: American Society of Brewing Chemists — Methods of Analysis
    publisher: ASBC
    note: Used to check the measurement basis for wort gravity and extract; no method text is reproduced.
    accessed: 2026-11-07
    url: https://www.asbcnet.org/methods
  - key: brewers-association
    title: Brewers Association — Beer Style Guidelines
    url: https://www.brewersassociation.org/resources/brewers-association-beer-style-guidelines/
    publisher: Brewers Association
    note: Used for notes on style parameters and original gravity; no source text is reproduced.
    accessed: 2026-11-07
  - key: r16-ocb-og
    title: original gravity — The Oxford Companion to Beer
    url: https://www.beerandbrewing.com/dictionary/c9EBwhgZpA
    publisher: Craft Beer & Brewing / Oxford University Press
    note: Used to check how original gravity is measured and converted between units; no source text is reproduced.
    accessed: 2026-11-07
  - key: ref
    title: American Society of Brewing Chemists — Methods of Analysis (ASBC).
    publisher: Unattributed
    note: Migrated from the former reference list at the end of the article; access date not re-verified.
rights:
  status: allowed
  license: CC-BY-4.0
  basis: Project-authored English text verified against BJCP, ASBC and Brewers Association public information; no source text is reproduced. The project owner declared project content CC BY 4.0 on 2026-10-29.
  note: Third-party texts, trademarks and images are not covered by this licence; sources are used for verification only.
verification_scope: source-verified
---
# Original gravity

Original gravity (OG) is the concentration of soluble solids, mainly sugars and other extract, in wort after mashing and before pitching yeast. It answers "how much extract can this grist provide", not "how much alcohol will the finished beer contain". Breweries use OG as the starting point for recipe and process control; Chinese beer labels often print "original gravity 10°P" or "11°P", which is easily misread as alcohol content.![Original gravity thematic illustration](/media/photos/theme-wine-spirits.jpg)

Figure: thematic illustration for Original gravity. Image: AI-assisted illustration generated with Doubao Seedream 5.0 (project-owned); not a photograph of the subject.

## Definition and boundaries

OG has four boundaries. First, it is a pre-fermentation value; density measured after fermentation has begun is current gravity, not OG. Second, it includes non-fermentable extract such as protein, dextrin and minerals, so it is not the same as sugar content. Third, it says nothing about bitterness, which uses the separate IBU scale. Fourth, it is not alcohol content: alcohol depends on the gap between OG and final gravity (FG) and on attenuation. Treating OG as alcohol, or assuming "higher gravity means stronger", leads to errors. In addition, OG describes the extract load of the wort, not the share of fermentable sugar; crystal and specialty malts raise extract without necessarily raising attenuation, so recipe design cannot rely on one number alone.

## Etymology and origin

"Original gravity" literally means the original specific gravity, a term from the brewery tradition of measuring wort with a hydrometer. Here gravity means density or specific gravity, not gravitational force, which is a common source of confusion for readers outside brewing. Degrees Plato (°P) belong to the European extract-scale tradition: in the 19th century the Balling scale was applied to sugar solutions and wort, and the Plato scale later revised the relationship for sucrose solutions, becoming the common brewing scale. The Chinese label term "original wort concentration" adds the word "original" precisely to distinguish it from post-fermentation values.

## Mechanism and parameters

One degree Plato is the grams of extract in 100 grams of wort, approximately a mass percentage; specific gravity is written as 1.0xx. As a working conversion, a gravity of 1.050 corresponds to about 12.4 °P, and 1 °P corresponds roughly to 0.004 gravity units. After fermentation, alcohol is estimated from the OG–FG difference with the approximation (OG−FG)×131; for example, 1.048 falling to 1.012 gives a difference of 0.036 and an estimated 4.7% vol. Apparent attenuation is (OG−FG)÷(OG−1)×100%, so a single set of readings describes both how completely the beer fermented and how much body remains. Temperature strongly affects density readings: hydrometers are usually calibrated at 20°C and need correction when the sample deviates, while a refractometer can be used directly on plain wort but must be corrected once alcohol is present, otherwise the result reads high.

## Practical use in the industry

Recipe design fixes OG first, then malt bill, adjunct ratio and mashing temperature; a lower mash temperature or a longer mash can raise the fermentable share, so the same OG may finish drier. Mainstream Chinese beers mostly sit at 8–12 °P; pale lagers are commonly 8–12 °P, pilsners about 11–12 °P, American IPAs about 14–18 °P and stouts about 12–16 °P. Style guidelines list these ranges alongside IBU and alcohol to describe structure, not to rank quality. Understanding [saccharification](ref:saccharification), [fermentation](ref:fermentation) and [barley](ref:barley) explains why two [beers](ref:beer) both at 11 °P can taste different; [Czech Pilsner Urquell](ref:pilsner) is a reference for medium gravity and a fresh, balanced profile. In cost accounting, OG is tied directly to malt use and adjunct ratio, making it a core variable for recipe cost and yield.

## Confusable terms compared

First, OG versus FG: OG is the start, FG the end; OG sets the ceiling for potential alcohol, FG decides residual sugar and palate. Second, OG versus ABV: OG is extract concentration, ABV is ethanol by volume, and the same OG can yield different ABV at different attenuation. Third, °P versus °Brix: both approximate grams of solids per 100 grams of solution, but Brix is referenced to sucrose while Plato is corrected for wort extract, so cross-industry comparison needs conversion, not an equals sign. Fourth, OG versus the figure printed on a label: the label value is a design or legal declaration, while actual batches vary. It is also worth noting that no single conversion factor links °P and °Brix, because wort extract is not pure sucrose; laboratories often combine density and refractometer readings, while recipe software uses empirical models.

## Common misuses and disputes

First, reading 10 °P as "10 degrees of alcohol" and concluding that it is stronger than a 5% vol beer. Second, assuming a higher °P is always better, ignoring style and balance. Third, using a post-fermentation gravity as OG. Fourth, ignoring attenuation and assuming that high OG means high alcohol. Fifth, reading °Brix directly with a refractometer on an alcoholic sample without correction, which gives an inflated result. The wider dispute is whether consumers should read "original gravity" as "richness": it reflects raw-material input, but palate also depends on hops, residual sugar, carbon dioxide and bitterness.

## Typical figures and examples

Take a wort of 1.048 (about 12 °P). Fermenting to 1.012 gives about 75% apparent attenuation and an estimated 4.7% vol; fermenting only to 1.020 gives about 58% attenuation, about 3.7% vol and more residual sugar. Common ranges: pale lager 8–12 °P, pilsner 11–12 °P, American IPA 14–18 °P, stout 12–16 °P. The 8–12 °P band on Chinese labels roughly matches the "medium" end of these styles, but comparisons across styles are not meaningful.

## Measurement and recording

Breweries usually sample after mashing and sparging, once the wort is cooled, and measure at 20°C with a hydrometer, density meter or refractometer, recording batch number, grist and mashing curve. Laboratory methods follow ASBC extract and gravity procedures. For craft brewers, recording OG, FG, attenuation and yeast generation is more useful for reproducibility than a single "target OG". Temperature offsets shift readings directly, and carbon dioxide or particles interfere, so samples should be degassed, filtered or settled before measurement. When sampling at several points in one batch, record the time and the end of sparging so that the last, denser runnings are not mistaken for the overall OG.

## See also

- [Beer](ref:beer): raw materials, fermentation and the style framework.
- [Barley](ref:barley): the source of malt and extract.
- [Saccharification](ref:saccharification): the conversion of starch into fermentable sugar.
- [Fermentation](ref:fermentation): sugar converted into alcohol and carbon dioxide.
- [Czech Pilsner Urquell](ref:pilsner): a typical medium-gravity sample.

**Short definition:** Original gravity is the concentration of soluble solids, mainly sugars and other extract, in wort before fermentation, usually expressed in °P (degrees Plato); it reflects raw-material extract and is not alcohol content.

Original gravity is best approached through where the term is used, then what it is contrasted with, and then whether the source is a standard. One check alone will not settle it.
