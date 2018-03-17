# Women's History Month 2018: Visualising Women's History

For Women's History Month 2018 I plan to produce some visualisations of women's/gender history datasets. I'll primarily be using R, although I'll probably experiment with other tools along the way. 

I'll blog about these experiments at [Early Modern Notes](https://earlymodernnotes.wordpress.com) and I'll post R code and underlying data here as I go along. The datavizes will be exploratory and won't necessarily be very sophisticated or original, but I'll try to highlight different kinds of graph and what they can be used for.

(All data will be in the /data/ folder and this folder structure will be assumed in the code.)

There are likely to be two types of data:
* focusing on women
* comparison of women and men's experiences

Some of the datasets are likely to be closely related to my research interests and recent projects, but I hope to find new material from various sources.

Westminster Coroner's Inquests 1760-99
----------------

I've started with this because it's data I recently created and this is my first chance to do something with it!

[Data](data/wa_coroners_inquests_v1-1.tsv)

NB that the data is fully described [here](https://github.com/sharonhoward/londonlives/tree/master/coroners_inquests)

[Blog post](https://earlymodernnotes.wordpress.com/2018/03/02/whm18-westminste…inquests-1760-99/) 

[R Notebook](whm2018_westminster_coroners_inquests.Rmd) 


World Bank World Development Indicators
-------------------------

Data:

* [dataset 1: population indicators from 1960](data/wbsp_1960_20180306.csv) (ie, includes only countries that have data from 1960 onwards)
* [dataset 2: population and education indicators, all dates](data/wbspse_alldates_20180306.csv)

[UKDS guide to the data](https://www.ukdataservice.ac.uk/use-data/guides/dataset/development-indicators)

[Blog post](https://earlymodernnotes.wordpress.com/2018/03/08/international-womens-day-2018-women-in-the-world-bank-data/)

[R Notebook](worldbank_women.Rmd)


Women's Auxiliary Army Corps
----------------------

[Source of data](http://discovery.nationalarchives.gov.uk/details/r/C15099) and [TNA search query used to obtain raw data](http://discovery.nationalarchives.gov.uk/results/r?_cr=wo398&_dss=range&_l=6%7C7&_ro=any&_hb=tna&_st=adv)

[Cleaned data used for analysis](data/tna_wo398_20180303.tsv)

[Blog post](https://earlymodernnotes.wordpress.com/2018/03/12/whm18-womens-army-auxiliary-corps/)

[R Notebook](waac.Rmd)


Women's Heights in the Digital Panopticon
------------

[Digital Panopticon website](https://www.digitalpanopticon.org)

Datasets:

* [HCR](data/hcr_heights_20180316.csv) ([full version of dataset](https://figshare.com/articles/_/5688700))
* [CIN](data/cin_heights_20180314.csv)
* [PLF](data/plf_heights_20180314.csv)
* [RHC](data/rhc_heights_20180316.csv) ([full version](https://figshare.com/articles/_/5697994))

[Blog post]()

[R Notebook](womens_heights.Rmd)

----

Unless otherwise stated, all data is shared under a Creative Commons Attribution-ShareAlike 4.0 International Licence

[![License: CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/80x15.png)](http://creativecommons.org/licenses/by-sa/4.0/)
