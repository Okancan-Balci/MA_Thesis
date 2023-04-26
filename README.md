## Dealing with Consumer Uncertainty: Online Consumer Reviews and What makes them helpful?

**[To Read](https://raw.githubusercontent.com/Okancan-Balci/MA_Thesis/main/Paper.pdf?token=GHSAT0AAAAAACAXSBOSSDWJTRZG7PQDFZCSZCJCVYA)**

## Thesis Summary

I analyzed consumer reviews from IMDb and BestBuy in the context of Behavioral Economics and Information Economics specifically [Loss Aversion](https://en.wikipedia.org/wiki/Loss_aversion), [Negativity Bias](https://en.wikipedia.org/wiki/Negativity_bias) and [Search & Experience Goods Paradigm](https://en.wikipedia.org/wiki/SEC_classification_of_goods_and_services).

I found out that information sharing through consumer reviews is beneficial for potential buyers at least for Search Goods(Electronics). For Experience Goods(Movies) similar effect couldn't be observed.

Potential buyers find:

* Negatively and Positively rated reviews more helpful.
* Reviews with Negative sentiments more helpful.(Loss Aversion & Negativity Bias)
* Reviews with Positive sentiments less helpful.
* Moderately longer reviews more helpful.

Additionally when a review is negatively rated longer reviews are more helpful. Potential buyers may need more elaboration concerning why a certain good is bad. (Negative interaction effect between Review Rating and Review Length confirming Loss Aversion and Negativity Bias.)

## Data Collection

* I scraped the data with Selenium Webdriver from BestBuy.com and IMDb.com. 
* The scraper code can be found in [this repository](https://github.com/Okancan-Balci/Selenium_Web_Scrapers).

## Research Methodology

* Tobit Regression was used to test the hypotheses.
* [NRC Word-Emotion Association Lexicon](https://saifmohammad.com/WebPages/NRC-Emotion-Lexicon.htm) was used to get negative and positive emotion words from consumer reviews.

## Explanations of Files in the Repository

* All scripts which have `EDA` in them were part of the experimental phase of my thesis. All Data Cleaning and Data Wrangling processes were initially done within these files.
* `Report.Rmd` is the first research report concerning the research question that I sent to my thesis advisor. Initial and the lesser version of my thesis's statistical model was conducted in this report as well.
* `Paper.Rmd` includes both text and analysis code of the thesis.
* `Paper.pdf` is the rendered thesis.
* `apa.csl` configures the citation style.
* `references.bib` has all the references.
* `custom.tex` and `non-float-fig.tex` are the LaTeX configuration files that style my thesis into the appropriate format imposed by the Institute.
