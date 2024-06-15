# Great Recession News Corpus

## Overview

Reconstructed  "Great Recession News" Corpus, described in "Building the Great Recession News Corpus (GRNC): A contemporary diachronic corpus of economy news in English" (Research in Corpus Linguistics, 2020).

The authors don't share the source data neither the list of articles. The corpus can be only interacted through paid plans of Sketch Engine.

This repository offers an alternative by publishing digital identifiers (urls) of the documents used in the corpus. The content can be further retrieved for non-commerical purposes through APIs for developers or scrappers.

## Data Description

SketchEngine processed [18,915 articles from "The Guardian"](./data/links_guardian.csv) and [13,069 articles from "New York Times"](./data/links_nytimes.csv).
There are some redundancies in the data, not mentioned in the original paper. The urls retrieved in this repo perfectly match what is available at SketchEngine.

| source         |   unique urls |   total urls |
|:---------------|--------------:|-------------:|
| New York Times |         12556 |        13069 |
| The Guardian   |         18161 |        18915 |

## Methodology

I developed a [Selenium Bot](src/SketchEngineScrapper.ipynb) to extract article identifiers that were available from SketchEngine. 
