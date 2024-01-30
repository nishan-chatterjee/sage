# sage

**Social And Global Economy (SAGE):** Enhancing happiness prediction by integrating social surveys and global economic data

####**Objective:**

The objective is to enhance the dataset from [TheGlobalEconomy.com data](https://www.theglobaleconomy.com/download-data.php) by incorporating correlations from news reports sourced from the [European Social Survey (ESS)](https://www.europeansocialsurvey.org/data). This augmentation aims to facilitate experiments in predicting target values, such as the happiness index classification/prediction, by leveraging various attributes and sentiments from the ESS data. The analysis also plans to explore whether external factors, such as economic indicators or sentiment from news reports, can improve the prediction accuracy of happiness levels or other metrics, and if so, by how much.

**Examples from TheGlobalEconomy.com data:**

-**Country:** Name of the country.

-**Code:** Country code.

-**ContinentCode**

-**Year:** The specific year corresponding to the data.

-**GDP per capita current U.S. dollars:** Gross Domestic Product (GDP) per capita, measured in current U.S. dollars.

-**Gini income inequality index:** Measure of income inequality within a population (0 represents perfect equality, while an index of 100 implies perfect inequality).

-**Happiness Index 0-10:** Scale representing happiness level, ranging from 0 (unhappy) to 10 (happy).

**Fields in the ESS data:**

-**pubdate:** Publication date of the article.

-**guid:** Globally Unique Identifier, providing a unique reference for the article.

-**link:** URL link to the source or publication of the article.

-**source_country:** Country where the information source is located.

-**main_country_x:** Primary country mentioned in the context of the article.

-**main_country_y:** Another country mentioned prominently in the article.

-**other_country_x, other_country_y, other_country_z:** Additional countries referenced in the article.

-**tonality:** The overall tone or style of the article, categorized as positive, negative, or neutral.

-**sentiment:** The emotional tone or attitude expressed in the article, classified as positive, negative, or neutral.

-**title:** The headline or title of the article.

Since access to the complete dataset is unavailable at this moment, a proxy dataset [Madhurima Panja. (2023). Happiness Index.](https://www.kaggle.com/competitions/happiness-index) will be utilized. Although the feature variables are similarly defined, the dataset from [TheGlobalEconomy.com data](https://www.theglobaleconomy.com/download-data.php) will offer a broader scope, covering multiple years and more economical factors.

---

---
