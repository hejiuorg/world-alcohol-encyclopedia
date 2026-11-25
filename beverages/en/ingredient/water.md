---
schema_version: 1
id: ingredient:water
type: ingredient
lang: en
slug: water
title: Water
summary: The most easily overlooked yet ubiquitous ingredient in brewing; its minerals, hardness and pH affect saccharification, fermentation, microbial activity and final flavour, and have long shaped where distilleries and breweries are sited.
status: reviewed
revision: 2
legacy_refs: []
translation_of: ingredient:water
source_lang: zh
translation_status: reviewed
source_revision: sha256:86560589880fb0f9f1dcaec6cc618fe0d9632216dfc0f93a1f05df3081ea27d9
source_sha256: 86560589880fb0f9f1dcaec6cc618fe0d9632216dfc0f93a1f05df3081ea27d9
aliases:
  - Brewing water
  - Process water
tags:
  - ingredient
  - water
  - brewing
related:
  - relation: about
    target_id: drink-style:beer
  - relation: about
    target_id: drink-style:whisky
  - relation: about
    target_id: drink-style:baijiu
  - relation: about
    target_id: drink-style:sake
  - relation: about
    target_id: process:fermentation
references:
  - key: beer
    target_id: drink-style:beer
  - key: whisky
    target_id: drink-style:whisky
  - key: baijiu
    target_id: drink-style:baijiu
  - key: sake
    target_id: drink-style:sake
  - key: fermentation
    target_id: process:fermentation
sources:
  - key: gbt-17204
    title: 国家标准全文公开系统 — GB/T 17204-2021 饮料酒术语和分类
    url: https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=B8F9CD37320835EEF17458CBA5962881
    publisher: 国家市场监督管理总局、国家标准化管理委员会
    published: 2021-05-21
    note: Used to check the classification of alcoholic drinks and the terminology framework for raw materials; no source text is reproduced.
    accessed: 2026-11-04
  - key: oxford-beer
    title: The Oxford Companion to Beer — Brewing water entries
    publisher: Oxford University Press
    note: Used for reference on brewing water, mineral ions and saccharification pH; no source text is reproduced.
    accessed: 2026-11-04
    url: https://global.oup.com/academic/product/the-oxford-companion-to-beer-9780195367133
  - key: who-water
    title: WHO — Guidelines for drinking-water quality
    url: https://www.who.int/publications/i/item/9789240045064
    publisher: World Health Organization
    note: Used to check the public health framework for drinking-water quality; no source text is reproduced.
    accessed: 2026-11-04
  - key: ref
    title: The Oxford Companion to Beer, entries on brewing water and mineral ions
    publisher: Oxford University Press
    note: Migrated from the former reference list at the end of the article; access date not re-verified.
rights:
  status: allowed
  license: CC-BY-4.0
  basis: Project-authored English translation of the Chinese page; no source text is reproduced. The project owner declared project content CC BY 4.0 on 2026-10-29.
  note: The lead image is a photograph from Wikimedia Commons, marked public domain; see the figure caption. Third-party standards, trademarks and quoted text are not covered by this licence.
verification_scope: source-verified
---
# Water

Water is the most easily overlooked ingredient in brewing. It makes up most of the volume of the finished drink and takes part in saccharification, fermentation, distillation and dilution, and it also affects microbial activity and equipment cleaning. Different drinks have different water requirements: beer focuses on mineral ions and saccharification pH, whisky on water source and tradition, baijiu on water added for dilution, and sake is highly sensitive to water hardness.

![Water poured into a glass](/media/photos/ingredient-water-edf289bf.jpg)

Figure: Water poured into a glass. Brewing water is also tested for hardness, alkalinity, minerals and microbiology. Image: Jorge Barrios, Public domain, via [source page](https://commons.wikimedia.org/wiki/File:Glass_of_Water.JPG).

## Definition and forms

Brewing water usually falls into two categories: water that enters the drink, such as saccharification water, fermentation water and dilution water; and water that only contacts equipment and vessels, such as cleaning water. Both must be hygienically safe, but water entering the drink also affects chemistry and flavour, so its mineral composition matters more.

Key water indicators include hardness, pH, alkalinity, calcium, magnesium, sodium, sulphate, chloride and bicarbonate. Hardness is mainly determined by calcium and magnesium; alkalinity and bicarbonate affect the pH of the saccharification mash; the ratio of sulphate to chloride affects beer bitterness and mouthfeel. The composition of natural water differs by region, which is one historical reason traditional breweries and distilleries clustered where they did.

## Main sources

Brewing water can come from surface water, groundwater, municipal supply or treated water. Surface water varies strongly with season and environment, groundwater has a relatively stable mineral composition, and municipal supply is usually disinfected and purified. Whatever the source, microbiological, heavy-metal and mineral tests are needed before brewing.

Water treatment includes filtration, softening, reverse osmosis, activated carbon adsorption and ion exchange. The goal is not to turn water into "pure water" but to make its composition suit the target drink. Fully demineralised water may lack yeast nutrients and flavour support, and over-treatment adds cost.

## Role in beer

[Beer](ref:beer) is the most sensitive to water chemistry. The pH of the saccharification mash affects amylase activity and saccharification efficiency; calcium helps enzyme action and protein flocculation; magnesium affects flavour; and too much bicarbonate makes the mash alkaline and hop bitterness coarse. Different beer styles correspond to different water compositions, and the water of traditional regions shaped local styles.

Breweries often use gypsum or calcium chloride to adjust the sulphate-to-chloride ratio. More sulphate accentuates the dry bitterness of hops, while more chloride makes the body rounder. Adjustment is not "the more the better" but a small correction according to recipe and target style.

## In whisky, baijiu and sake

[Whisky](ref:whisky) emphasises water source and tradition. Scottish distilleries often use local spring or river water as process water; its mineral composition affects saccharification and fermentation, but its flavour contribution is usually smaller than that of malt, yeast, distillation and cask ageing. Water source is also part of distillery storytelling and geographical identity, but "good water" does not automatically mean "better whisky".

In [baijiu](ref:baijiu), water is divided into brewing water and dilution water. Brewing water takes part in qu making, fermentation and distillation; dilution water is used to lower alcohol content, must meet drinking-water hygiene requirements and should introduce no off-flavours. Some distilleries emphasise local water, but baijiu flavour is mainly determined by grain, qu, fermentation pit, distillation and ageing.

[Sake](ref:sake) is especially sensitive to water hardness. Soft water usually slows fermentation and gives a softer body, while hard water may promote yeast activity and bring fuller flavour. Japanese breweries often treat local water as part of regional style, but the effect of water must still be understood together with rice, koji, yeast and temperature.

| Drink | Main use of water | Indicators of concern |
| --- | --- | --- |
| Beer | Saccharification, boiling, cleaning | pH, hardness, sulphate and chloride |
| Whisky | Saccharification, fermentation, dilution | Microbes, mineral composition, source stability |
| Baijiu | Qu making, fermentation, dilution | Hygiene, off-flavours, mineral composition |
| Sake | Steeping, steaming, fermentation | Hardness, mineral composition, temperature |

## Water and fermentation

Water is the medium of [fermentation](ref:fermentation). Sugars, amino acids, minerals and microbes all interact in water; its pH and mineral composition affect yeast metabolism and the formation of flavour compounds. When water quality is unstable, the same recipe can produce differences between batches.

Microbes and contaminants in water are a food safety issue. Brewing water must meet drinking-water hygiene requirements, and cleaning water must avoid biofilms and residues. Home brewers in particular should pay attention to water source and equipment hygiene, and should not judge suitability by taste alone.

## Buying and treatment

To choose water for brewing, first confirm hygiene and safety, then look at mineral composition. Bottled water, tap water and filtered water can all be used for home brewing, but their hardness and pH should be known. When precise control is needed, use a water report or simple test kit and verify the effect in a small batch.

Water treatment should serve the goal rather than pursue "the purer the better". Reverse osmosis removes most minerals but may also take away nutrients yeast needs, and some drinks actually benefit from retaining hardness. Treated water should be re-tested to avoid new problems from over-treatment.

## Common misconceptions

First, that water has no taste and therefore does not affect the drink. Its mineral composition affects saccharification, fermentation and mouthfeel.

Second, that purer water is always better. Full demineralisation does not suit every drink.

Third, that good water source guarantees good drink. Raw material, process, microbes and ageing matter just as much.

Fourth, that all drinks have the same water requirements. Beer, sake, baijiu and whisky focus on different things.

Fifth, that tap water can never be used for brewing. Water meeting hygiene requirements can be used after suitable treatment; testing and control are the key.

**At a glance:** The most easily overlooked yet ubiquitous ingredient in brewing; its minerals, hardness and pH affect saccharification, fermentation, microbial activity and final flavour, and have long shaped where distilleries and breweries are sited.

Begin with the form and provenance, move on to the preparation, and finish with how it behaves in the drink. That order keeps the reading of Water practical.

**Key facts.**

| Item | Detail |
| --- | --- |
| In one line | The most easily overlooked yet ubiquitous ingredient in brewing; its minerals, hardness and pH affect saccharification, fermentation, microbial activity and final flavour, and have long shaped where distilleries and brew… |
| Material | The most easily overlooked yet ubiquitous ingredient in brewing |
| Use | its minerals, hardness and pH affect saccharification, fermentation, microbial activity and final flavour, and have long shaped where distilleries and breweries are sited. |

**Sources and limits.** The key claims about Water are checked against the following sources: Industry body (Used to check the classification of alcoholic drinks and the terminology framework for raw materials), Oxford University Press (Used for reference on brewing water, mineral ions and saccharification pH; Migrated from the former reference list at the end of the article; access date not re-verified), World Health Organization (Used to check the public health framework for drinking-water quality). Prices, batches and status change; the body is project-written and does not reproduce source text.

## Further reading

- [Beer](ref:beer): the classic application of water chemistry and saccharification pH.
- [Whisky](ref:whisky): the relationship between water source, saccharification and distillation.
- [Baijiu](ref:baijiu): the distinction between brewing water and dilution water.
- [Sake](ref:sake): soft water, hard water and fermentation rhythm.
- [Fermentation](ref:fermentation): water as the medium of fermentation.
