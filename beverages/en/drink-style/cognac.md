---
schema_version: 1
id: drink-style:cognac
type: drink-style
lang: en
slug: cognac
title: Cognac
summary: "A grape brandy from the Cognac region of France, protected by appellation rules since 1936: Ugni Blanc dominates, the Charentais pot still distils twice, and VS, VSOP, XO and XXO carry legal minimum ages."
status: reviewed
revision: 2
translation_of: drink-style:cognac
source_lang: zh
translation_status: reviewed
source_revision: sha256:7e966bc3654f13e6ced8e639c4e3a529e0b48b3419c6aada33173005891496ee
source_sha256: 7e966bc3654f13e6ced8e639c4e3a529e0b48b3419c6aada33173005891496ee
legacy_refs: []
parent_style_id: drink-style:brandy
aroma_family: fruit/floral/oak
aliases:
  - Cognac
tags:
  - curated
  - source-verified
  - style-guide
  - brandy
related:
  - relation: about
    target_id: drink-style:brandy
  - relation: about
    target_id: process:distillation
  - relation: about
    target_id: process:oak-ageing
  - relation: about
    target_id: variety:trebbiano
  - relation: about
    target_id: region:cognac
  - relation: about
    target_id: term:appellation
references:
  - key: brandy
    target_id: drink-style:brandy
  - key: distillation
    target_id: process:distillation
  - key: oak-ageing
    target_id: process:oak-ageing
  - key: trebbiano
    target_id: variety:trebbiano
  - key: cognac
    target_id: region:cognac
  - key: appellation
    target_id: term:appellation
sources:
  - key: bnic
    title: Bureau National Interprofessionnel du Cognac — Cognac Production Rules
    url: https://www.cognac.fr/en/
    publisher: BNIC
    note: Used to verify the appellation area, permitted varieties, Charentais distillation, maturation and grade rules; no original text is reproduced.
    accessed: 2026-11-08
  - key: eu-spirits
    title: EU Regulation 2019/787 — Spirit Drinks
    url: https://eur-lex.europa.eu/eli/reg/2019/787/oj
    publisher: European Union
    note: Used to verify the framework for grape brandy and geographical indications for spirits; no original text is reproduced.
    accessed: 2026-11-08
  - key: oxford-spirits
    title: The Oxford Companion to Spirits and Cocktails
    url: https://global.oup.com/academic/product/the-oxford-companion-to-spirits-and-cocktails-9780199311132
    publisher: Oxford University Press
    note: Consulted for entries on Cognac, the Charentais still and age designations; no original text is reproduced.
    accessed: 2026-11-08
  - key: c-ref-4
    title: BJCP — Beer Style Guidelines
    url: https://www.bjcp.org/
    publisher: BJCP
    accessed: 2026-11-21
    note: Used to verify the entry's background, terminology and regulatory context; no source text is reproduced.
rights:
  status: allowed
  license: CC-BY-4.0
  basis: Original project writing verified against BNIC material, EU spirit-drink law and a reference work; no original text is reproduced. The project owner declared on 2026-10-29 that project content is licensed CC BY 4.0.
  note: Third-party standards, trademarks, images and quoted text are outside this licence; sources are cited for verification only. This style uses no third-party images.
verification_scope: source-verified
---
# Cognac

Cognac is not simply "premium brandy". It is a set of checks that can be performed one by one: which villages the grapes grew in, which varieties were used, when distillation happened, what shape the still had, how long the spirit sat in which barrel, and how old the youngest eau-de-vie in the blend is. Fail any one and the bottle may not carry the name. Read as a geographical indication rather than a brand, the picture gets much clearer.

![Cognac image](/media/photos/drink-style-cognac-b2c89cad.jpg)

Figure: Cognac. Image: Didier Descouens, CC BY-SA 3.0, via Wikimedia Commons ([source page](https://commons.wikimedia.org/wiki/File:Cognac_glass.jpg)).

## Starting from the 1936 AOC

Cognac was among the first French spirits to win appellation control, formally established in 1936. Today it is protected both by the French appellation system and by EU spirit-drink law, placing it inside the wider family of [brandy](ref:brandy) under an [appellation](ref:appellation) regime.

Protection covers more than the word Cognac: it also covers a series of place terms and grade terms. A common misunderstanding is that bottling in the town of Cognac makes a spirit into Cognac. In fact the grapes, the distillation and the maturation must all happen inside the delimited area; bottling is only the final step.

## Six gates

The first gate is the region. Grapes must come from the delimited communes centred on Charente and Charente-Maritime. The second is variety: Ugni Blanc leads, with Folle Blanche, Colombard, Montils, Sémillon and Folignan also permitted.

The third gate covers pressing and fermentation. Grapes are pressed soon after harvest to give an acidic, low-alcohol white juice, fermented with little or no sulphur dioxide. The fourth is distillation, which must be finished by 31 March after the harvest and uses the Charentais pot still twice.

The fifth gate is maturation: the spirit enters French oak in supervised cellars. The sixth is bottling, at no less than 40% ABV. Only the whole chain earns the name.

## The Charentais pot still

The defining feature is a preheater, the chauffe-vin. Wine on its way to the still passes through it and is warmed by alcohol vapour leaving the still head, which condenses in the process. Heat is reused and the wine arrives already warm, making the run more efficient than a plain pot still.

Distillation happens twice. The first run gives a cloudy low wine of roughly 27% to 30% ABV (brouillis); the second takes the middle cut to produce clear spirit of no more than 72.5% ABV (bonne chauffe). The distiller judges the cut by experience: heads are recycled, tails return to the next charge, and only the heart goes to barrel. For the general principle, see [distillation](ref:distillation).

## The six crus

Cognac is divided into six growing areas, called crus. Grande Champagne, with its chalk soils, gives fine, high-acid spirit with long ageing potential; Petite Champagne is similar but matures a little faster; Borderies is the smallest and often shows nut and violet; Fins Bois is fruit-forward and matures quickly; Bons Bois and Bois Ordinaires feel the ocean more strongly and give plainer styles.

The term "Fine Champagne" on a label is regulated: at least half the blend must come from Grande Champagne and the rest from Petite Champagne. It has nothing to do with Champagne wine, and "fine" is not a quality adjective but a historical place combination. Treating the crus as a quality ranking ignores blending and barrel ageing.

## Grades are a timeline

The grade is set by the youngest eau-de-vie in the blend, not by an average. VS requires at least 2 years, VSOP at least 4, XO at least 10 and XXO at least 14. In 2018 the minimum for XO rose from 6 to 10 years, the most important rule change in decades.

"Napoleon" appears widely on labels but is not a separate legal grade; such bottles usually sit above VSOP, and the producer's own statement is the guide. Read grade, region, bottler and vintage information separately. The label guarantees "not less than", never "exactly".

## Barrel wood: Limousin and Tronçais

French oak for Cognac comes mainly from two forests. Limousin oak has a wide grain and more tannin and lignin, giving firmer structure with vanilla and toast; Tronçais oak has a finer grain and gentler aromatics, often considered better for long maturation. New barrels add wood and spice, while older ones let fruit and rancio come forward.

During [oak ageing](ref:oak-ageing), alcohol and water evaporate slowly, colour deepens and tannin softens. Cellar humidity and temperature, barrel size and position all change the pace. Colour alone is therefore not evidence of age.

## Blending: hiding the years inside a style

Cognac is almost always a blend. The blender samples eaux-de-vie of different crus, years and barrel types, combining them for aroma, body and finish so that each brand stays consistent from batch to batch. Grande Champagne supplies backbone and ageing potential, Borderies adds flower and nut, the Bois add fruit and volume.

Vintage Cognac exists but is not the mainstream product; most houses build a stable, non-vintage style. That contrasts with Armagnac's habit of bottling single vintages as a normal line. Both approaches have their logic, and neither is superior.

## Tasting and serving

Start with the production rule. From there, consider the strength, then the usual serving. That is how a practical judgment about Cognac is built.

VS and VSOP work over ice or in cocktails; the Sidecar and the French Connection are both Cognac-based. XO and older bottles are better neat, with chocolate, dried fruit and cheese. Ice suppresses aroma, so whether to use it depends on age and preference. Excessive drinking is harmful to health, and minors should not drink.

## Common misconceptions

- Cognac means brandy: it is one protected regional name inside brandy.
- XO is a vintage: it is a minimum-age threshold set by the youngest spirit.
- Darker colour means older: colour depends on barrel, toast, cellar and caramel.
- Cognac uses only Ugni Blanc: it dominates, but other varieties are permitted.
- Fine Champagne is Champagne: it is a combination of two Cognac crus.
- Bottles keep ageing: spirits do not meaningfully mature in glass.

Read [Brandy](ref:brandy) for the legal definition side of Cognac, and [Oak ageing](ref:oak-ageing) for the materials and process side. Together they locate it.

**In brief:** A grape brandy from the Cognac region of France, protected by appellation rules since 1936: Ugni Blanc dominates, the Charentais pot still distils twice, and VS, VSOP, XO and XXO carry legal minimum ages.

## Further reading

- [Brandy](ref:brandy): the wider distilled family.
- [Distillation](ref:distillation): the Charentais still and the double run.
- [Oak ageing](ref:oak-ageing): where colour, aroma and texture come from.
- [Ugni Blanc](ref:trebbiano): the dominant grape of Cognac.
- [Cognac region](ref:cognac): boundaries, climate and soils.
- [Appellation](ref:appellation): the entry point to AOC and GI systems.
