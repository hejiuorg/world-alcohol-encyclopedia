---
schema_version: 1
id: drink-style:other
type: drink-style
lang: en
slug: other
title: Other Drinks (Category Note)
summary: An explanatory container for marginal drinks that do not fit neatly under wine, beer, distilled spirits or compounded drinks; not a specific style and not a new legal category.
status: draft
revision: 3
aliases:
  - Other drinks
  - Other beverages
tags:
  - curated
  - taxonomy-note
related:
  - relation: about
    target_id: drink-style:nigori-sake
  - relation: about
    target_id: drink-style:ice-cider
  - relation: about
    target_id: drink-style:melomel
  - relation: about
    target_id: drink-style:fruit-beer
  - relation: about
    target_id: drink-style:airag
references:
  - key: sake
    target_id: drink-style:nigori-sake
  - key: cider
    target_id: drink-style:ice-cider
  - key: mead
    target_id: drink-style:melomel
  - key: fruit-beer
    target_id: drink-style:fruit-beer
  - key: airag
    target_id: drink-style:airag
sources:
  - key: who-alcohol
    title: WHO — Alcohol and health
    url: https://www.who.int/health-topics/alcohol
    publisher: World Health Organization
    note: Used to verify health definitions, risk framing and public-policy background for alcoholic drinks; no source text is reproduced.
    accessed: 2026-11-22
  - key: bjcp
    title: BJCP — Beer Style Guidelines
    url: https://www.bjcp.org/
    publisher: BJCP
    accessed: 2026-11-21
    note: Used to verify style boundaries between beer, fruit beer and mead; no source text is reproduced.
  - key: codex
    title: Codex Alimentarius
    url: https://www.fao.org/fao-who-codexalimentarius/
    publisher: FAO / WHO
    note: Used to verify food classification and the definitional boundaries of alcoholic drinks; no source text is reproduced.
    accessed: 2026-11-22
  - key: ttb
    title: TTB — Alcohol and Tobacco Tax and Trade Bureau
    url: https://www.ttb.gov/
    publisher: TTB
    accessed: 2026-11-21
    note: Used to verify the labelling classification framework for distilled spirits and compounded spirits; no source text is reproduced.
rights:
  status: allowed
  basis: Project-authored; classification boundaries were checked against public material from OIV, BJCP, FAO and TTB, with no source text reproduced. The project owner declared project content CC BY 4.0 on 2026-10-29.
  license: CC-BY-4.0
  note: Third-party trademarks, promotional copy, images and quoted text are not covered by this licence; sources are cited for verification only. The image is the project's own AI-assisted illustration.
translation_of: drink-style:other
source_lang: zh
translation_status: reviewed
verification_scope: source-verified
source_revision: sha256:f504af0f415486914a839c00f777cf3d1842fba53ba44c0834c2319773b33f7c
source_sha256: f504af0f415486914a839c00f777cf3d1842fba53ba44c0834c2319773b33f7c
---

# Other Drinks (Category Note)

“Other drinks” is not a strict legal category. It is a mapping container retained from the old site for entries that did not fit neatly under wine, beer, distilled spirits or compounded drinks. It is not a specific drink, a quality grade, or a way of saying that a subject matters less. A better reading is that when a drink crosses several craft families, or when a local name does not match the mainstream taxonomy, this page explains the boundary and points to the specific style entry.

![Thematic illustration for other drinks](/media/photos/theme-asian.jpg)

Figure: thematic illustration for the category note. Image: AI-assisted illustration generated with Doubao Seedream 5.0 (project-owned); not a photograph.

## Definition and boundaries

The first layer of classification is raw material and process, not the name. A drink made by fermenting grain or fruit, then distilling the result, usually belongs with distilled spirits. A drink made from malted grain, boiled with hops and fermented with brewers’ yeast belongs with beer. A drink made by fermenting grapes or other fruit and keeping the juice character belongs with wine or fruit wine. Some drinks combine fermentation with infusion, blending or the addition of honey, and do not fit a single box. In that case “other” means “needs a separate explanation”, not one shared flavour or grade.

This page therefore does not offer a single alcohol level, ingredient list or serving temperature for “other drinks”. Each drink should be checked against its own entry: what sugar source it uses, which microorganism ferments it, whether it is distilled, whether sugar or flavouring is added, and how it is stabilised and packaged.

## Why the container exists

The old site’s taxonomy needed a fallback node; without it, marginal entries could not be given a parent-child relation. Keeping “other” helps preserve historical links and search migration, but it also creates a risk: readers may assume that everything listed here shares one process, or that “other” is an official category. The remedy is to make the container an explanatory page rather than a list page, to return specific drinks to their own entries, and to express real parentage through aliases and parent relations.

For editors, the container also has a technical function. When a style’s parent is temporarily missing, a relation field can point here instead of leaving a dangling reference. Once a better parent is created, the child entry should be moved there rather than left under a fallback category.

## Fermented drinks

Fermented drinks are defined by the conversion of sugar into alcohol by microorganisms. Alcohol levels are usually lower, and flavour comes from the raw material, the microorganism and the fermentation conditions. Sake uses rice as its sugar source, with koji mould saccharification and yeast fermentation, followed by milling, steaming, koji-making, fermentation and pressing. Cider ferments apple juice and highlights fruit aroma and acidity. Perry, cherry wine and other fruit wines use their own juices. All may be called fermented drinks, but their materials and processes differ greatly and are not interchangeable.

Labels for this family usually stress raw material, fermentation method, sweetness, carbonation and origin. Calling them all “fruit wine” or “rice wine” hides process differences. In sake, for example, “junmai” and “honjozo” refer to ingredients and permitted additions, not to a sweetness grade. A reader should first confirm the sugar source and the starter culture, then look at pasteurisation, filtration and water addition.

## Honey and mixed fermentation

Mead is made by fermenting a honey-water solution with yeast. Fruit, spice or grain can be added, creating a family of honey drinks. Because honey sugar concentration, pollen source and finishing point vary, a drink with the same name can range from bone-dry to very sweet, with a wide alcohol range. Treating mead as a “sweet drink” is inaccurate, since dry mead is common.

Mixed-fermentation drinks may contain both grain and fruit, or may be fermented and then infused. Classification should follow the main sugar source and the key process, and the label should state the additions. If the main alcohol comes from infusion rather than fermentation, the product is closer to a compounded drink. If it is distilled, it belongs with distilled spirits. The purpose of classification is not to erect borders but to tell the reader which standards to consult.

## Fruit drinks other than wine

Apples, pears, cherries and plums can all be fermented into alcohol. Cider is often treated as its own category in English-speaking markets, with subdivisions by sweetness, acidity, carbonation and apple variety. Perry has a long tradition in some regions. Cherry drinks may be made by fermentation or by infusion. They share the basic logic of fermented fruit juice with wine, but their raw-material chemistry, tannin structure and regulatory systems differ.

Calling all fruit drinks “wine” creates confusion, especially on labels, duty codes and alcohol licensing. A safer description states the main fruit first, then fermentation or infusion, then sweetness and carbonation. For blended juice products, check the juice proportion and added sugar rather than relying on the fruit picture on the package.

## Grain drinks other than beer

Using grain does not make a drink beer. Beer usually means malted grain that is mashed, boiled with hops and fermented with yeast. Drinks based on rice, corn, sorghum or other grains, saccharified with koji or enzymes and not boiled with hops, often belong to a different tradition. Sake, rice wine, huangjiu and some local fermented drinks all follow paths unlike beer.

The common point is that grain starch must first be converted into fermentable sugar. The difference lies in the saccharifying agent: malt relies on its own enzymes, koji moulds rely on mould enzymes, and some processes use external enzymes. The saccharification route shapes flavour and production time, and it determines what the label should declare. Equating “grain brewing” with beer ignores these differences.

## Distillation and compounding

Distilled drinks should be treated as spirits or one of their subclasses: grape-marc spirit, grain whisky, molasses rum and so on. If the distillate is later infused, sweetened, flavoured or blended, it may move into the compounded or liqueur family. The key questions are the main alcohol source and whether distillation occurred, not simply what was added at the end.

Compounded drinks cover a wide field, including products made from alcohol, water, sugar and flavouring. They need not be fermented or distilled. Alcohol level, sugar and additives are the main label information. Treating compounded drinks as “inferior spirits” is a value judgment, not a process classification. The two can share a base spirit while following different production and labelling rules.

## Classification and retrieval

In this site’s structure, “other drinks” is only an explanatory and fallback node. Specific entries should sit under a more precise parent wherever possible: sake under the sake family, cider under cider, mead under mead, marc under marc. Only when a drink genuinely crosses families, or has no suitable parent yet, should this container be used, and the body should explain why.

Readers can approach retrieval through four dimensions: raw material, process, origin and alias. Raw material points to the broad family, process to the subclass, origin to the style variant, and aliases help with local names. Writing all four clearly is more useful than arguing over which box a word belongs in. Classification is a reading aid, not a ranking of drinks.

## Common misreadings

First, “other” is not a drink or a legal grade; it is an explanatory container. Second, grain fermentation is not beer: beer has malt, hops and a specific process, while sake and rice wine follow different paths. Third, mead is not necessarily sweet; it can range from dry to sweet and across a wide alcohol band. Fourth, fruit wine is not wine; apples, pears and cherries differ in raw-material chemistry and regulation. Fifth, compounded drinks are not simply low-quality spirits; they may share a base spirit but follow different process and label rules. Sixth, do not infer process from a single name. Look at raw material, saccharification, fermentation, distillation and additions before the name.

Related entries: [sake](ref:sake), [ice cider](ref:cider), [mead](ref:mead), [fruit beer](ref:fruit-beer) and [airag](ref:airag).

**In brief:** An explanatory container for marginal drinks that do not fit neatly under wine, beer, distilled spirits or compounded drinks; not a specific style and not a new legal category.
