---
schema_version: 1
id: process:lagering
type: process
lang: en
slug: lagering
title: Lagering
summary: The cold-storage stage after primary fermentation, in which yeast takes up diacetyl, suspended solids settle, sulfur compounds disperse and natural carbonation settles; the temperature curve, time and dissolved oxygen decide the cleanliness and shelf life of lager.
status: reviewed
revision: 3
translation_of: process:lagering
source_lang: zh
source_revision: sha256:d37a9dc88f85b7b3e241c8b9cae388bd6572c9c29c8ece1fd878cd1bdedc27d9
source_sha256: d37a9dc88f85b7b3e241c8b9cae388bd6572c9c29c8ece1fd878cd1bdedc27d9
translation_status: reviewed
legacy_refs: []
aliases:
  - Cold storage
  - Cold conditioning
tags:
  - curated
  - source-verified
  - process
  - beer
related:
  - relation: about
    target_id: drink-style:beer
  - relation: about
    target_id: process:fermentation
  - relation: about
    target_id: process:malting
references:
  - key: beer
    target_id: drink-style:beer
  - key: fermentation
    target_id: process:fermentation
  - key: malting
    target_id: process:malting
  - key: c-extra-1
    target_id: process:blending
sources:
  - key: oxford-beer
    title: The Oxford Companion to Beer — Lagering entries
    publisher: Oxford University Press
    note: Used for reference on lager yeast, cold storage and diacetyl reduction; no source text is reproduced.
    accessed: 2026-11-05
    url: https://global.oup.com/academic/product/the-oxford-companion-to-beer-9780195367133
  - key: britannica-brewing
    title: Encyclopaedia Britannica — Brewing
    url: https://www.britannica.com/technology/brewing
    publisher: Encyclopaedia Britannica
    note: Used for reference on bottom fermentation and cold storage; no source text is reproduced.
    accessed: 2026-11-05
  - key: brewers-association
    title: Brewers Association — Brewing resources
    url: https://www.brewersassociation.org/
    publisher: Brewers Association
    note: Used to check industry descriptions of lager fermentation, diacetyl reduction and cold storage; no source text is reproduced.
    accessed: 2026-11-07
  - key: ref
    title: The Oxford Companion to Beer — Lagering entries (Oxford University Press).
    publisher: Unattributed
    note: Migrated from the former reference list at the end of the article; access date not re-verified.
rights:
  status: allowed
  license: CC-BY-4.0
  basis: Project-authored English text checked against brewing reference works and an encyclopaedia, with no source text reproduced. The project owner declared project content CC BY 4.0 on 2026-10-29.
  note: Third-party texts, trademarks and images are not covered by this licence; sources are used for verification only.
verification_scope: source-verified
applies_to_refs:
  - drink-style:beer
---
# Lagering

Lagering sits after primary [fermentation](ref:fermentation) and before filtration and filling. The German verb lagern means "to store", and the stage places the beer in conditions close to freezing so that yeast metabolism, colloidal settling and carbonation can finish slowly. It is neither simple chilling nor a synonym for ageing: it is a process window with defined end points.

![Lagering image](/media/photos/process-lagering-7d0e4091.jpg)

Figure: Lagering. Image: Lars Curfs ( Grashoofd ), CC BY-SA 3.0 nl, via Wikimedia Commons ([source page](https://commons.wikimedia.org/wiki/File:Bitburger_Glass.JPG)).

## Place in the process

In lager brewing, primary fermentation converts wort sugar into ethanol and carbon dioxide, while lagering deals with the intermediates left behind: diacetyl, acetaldehyde, sulfur compounds, and suspended yeast and protein-polyphenol complexes. The stage usually begins when sugar attenuation is nearly complete and the yeast starts to flocculate. Its end is judged from diacetyl concentration, clarity and carbonation together. Treating it as the same thing as warm conditioning of ale misreads how temperature and time are chosen.

## Steps and parameters

A typical schedule runs primary fermentation at 8–12 °C for about 7–14 days, a rise to 12–18 °C for 1–3 days of diacetyl reduction, known as a diacetyl rest, then cooling to −1 to 4 °C for 2–6 weeks of lagering. High-gravity or dark products may extend this to 8–12 weeks. These ranges follow the common descriptions in the brewing reference works and association material listed on this page; individual breweries still adjust them to yeast strain and tank heat transfer. A vessel pressure of 0.8–1.2 bar keeps carbon dioxide in solution, and dissolved oxygen during transfer should ideally stay below 50 μg/L. pH at this stage normally falls between 4.0 and 4.6, with ethanol at 4–6% by volume.

## Mechanism: yeast uptake and settling

Diacetyl comes from the valine biosynthesis pathway. Yeast secretes α-acetolactate, which leaves the cell and decarboxylates non-enzymatically into diacetyl; yeast reductases then convert diacetyl into acetoin and 2,3-butanediol, both with much higher flavour thresholds. Cold slows that reduction, so beer held too cold for too short a time keeps a buttery note. Settling follows Stokes' law: larger particles, lower viscosity and weaker convection settle faster. Cold raises viscosity yet makes flocculation more complete, and the two effects offset each other, so time remains the decisive factor.

## Equipment and variants

Traditional cellars used horizontal wooden or aluminium tanks cooled by natural ice; modern plants mostly use vertical conical tanks with cooling jackets, completing primary fermentation and lagering in one vessel and collecting yeast at the cone. Variants include single-tank and two-tank methods, filtered versus unfiltered or centrifuged beer, PVPP or silica gel treatment for polyphenols, and the German route of cold storage with natural carbonation. Equipment differences show up mainly in temperature gradients, yeast settling paths and oxygen pickup: taller tanks settle yeast more easily through hydrostatic pressure but also develop a larger top-to-bottom temperature difference.

## Failure modes and diagnosis

Four failures are common. First, residual diacetyl, smelling of butter or popcorn, with a sensory threshold around 0.02–0.1 mg/L that varies between tasters. Second, sulfur compounds: hydrogen sulfide resembles rotten eggs and dimethyl sulfide cooked corn, often linked to poor yeast nutrition or copper deficiency. Third, oxidation: the cardboard note comes from trans-2-nonenal, usually through aeration during transfer or high dissolved oxygen at filling. Fourth, poor clarity, shown by rising filter differential pressure or turbidity above 1 EBC. Diagnosis should combine sensory checks, turbidity and dissolved oxygen rather than assuming that "long enough" is enough.

## Effect on flavour

Lagering moves the aroma from "fermenting" to "finished". As diacetyl falls, grain sweetness and the herbal or citrus side of hops read more clearly; as sulfur compounds disperse, green apple and vegetable notes fade; settled yeast makes bitterness cleaner and the finish crisper. Too short a rest leaves creamy viscosity, while excessive storage with poor oxygen control dims hop aroma and brings cardboard and sherry-like oxidation. In dark lagers, mild oxidation can add nutty and caramel layers, but that is a style choice rather than a general virtue.

## Effect on stability

Cold reduces the solubility of potassium bitartrate and calcium oxalate, so some crystals form in the tank and fewer appear as chill haze in bottle. Protein-polyphenol complexes continue to aggregate at low temperature, and silica gel or tannin treatment can extend shelf life. Ethanol and low pH suppress most spoilage organisms, yet lactic acid bacteria and wild yeast can still act when residual sugar is present, so lagering does not replace filtration or pasteurisation. Carbonation stability depends on the balance of pressure and temperature; a sudden pressure drop before filling gives coarse foam and weaker carbonic bite.

## Common misconceptions

First, that colder is always better. Below the freezing point the beer can ice up, damage yeast and alter its colloidal state. Second, that long cold storage alone will remove diacetyl, ignoring the need for a warm rest. Third, that every lager must be stored for months, when light-bodied pale lagers may need only weeks. Fourth, that unfiltered means more natural, ignoring the trade-off between clarity and microbial stability. Fifth, treating a lagering tank as ordinary storage and neglecting pressure control and oxygen pickup.

## See also

- [Beer](ref:beer): the drink category and style framework that lagering belongs to.
- [Fermentation](ref:fermentation): the upstream metabolism that produces ethanol and by-products.
- [Malting](ref:malting): how the malt sugar profile and fermentability constrain the lagering result.

Further reading: [Blending](ref:c-extra-1).

For Lagering, begin with the inputs. Then look at the sequence of steps, and finally ask what changes at the end. The answers point to different choices, not to a single score.

Read [Beer](ref:beer) for the purpose side of Lagering, and [Malting](ref:malting) for the control point side. Together they locate it.

**Short definition:** The cold-storage stage after primary fermentation, in which yeast takes up diacetyl, suspended solids settle, sulfur compounds disperse and natural carbonation settles; the temperature curve, time and dissolved oxygen decide the cleanliness and shelf life of lager.

Lagering is cold storage after primary fermentation, usually near 0–4 °C for weeks, which settles yeast and softens sulphur notes.

The cold storage also allows the beer to carbonate naturally and clarifies it without filtration.

**Key facts.**

| Item | Detail |
| --- | --- |
| In one line | The cold-storage stage after primary fermentation, in which yeast takes up diacetyl, suspended solids settle, sulfur compounds disperse and natural carbonation settles; the temperature curve, time and dissolved oxygen de… |
| Applies to | Beer |

**Sources and limits.** The key claims about Lagering are checked against the following sources: Oxford University Press (Used for reference on lager yeast, cold storage and diacetyl reduction), Encyclopaedia Britannica (Used for reference on bottom fermentation and cold storage), Brewers Association (Used to check industry descriptions of lager fermentation, diacetyl reduction and cold storage) and 4 sources in total. Prices, batches and status change; the body is project-written and does not reproduce source text.
