




# Global Budget Transparency
*A Data Mining Approach to Identifying Socio-Economic Correlates of Fiscal Accountability*

**Submitted By:**
- Andres, Don Elron
- Toracio, Chyna Denise Topacio
- Vilan, Miguel Anthony C.

**Submitted To:** 
Mr. Catayoc, Jacob

------

## Project Description
This project aims to apply data mining techniques taught in the DATAMIN courses on the International Budget Partnership’s (IBP) Open Budget Survey data. The primary objective is to  implement the knowledge given to derive deeper insights into the structural factors that contribute to a country’s fiscal transparency.

By analyzing the OBS scores alongside other potential regional or economic indicators, I intend to discover:
- **Trend Patterns:** How budget transparency scores have shifted globally over the last decade.
- **Clustering:** Which groups of countries share similar profiles in terms of "Public Participation" vs. "Budget Oversight."
- **Predictive Indicators:** Whether a country’s performance in one category (e.g., Transparency) can reliably predict its performance in another (e.g., Oversight).


## Dataset Background
The Open Budget Survey (OBS) is the world’s only independent, comparative, and fact-based research instrument to measure public budget transparency, participation, and oversight. The dataset provides:

- **Open Budget Index (OBI) Scores:** A 0–100 score for each country.
- **Pillars of Accountability:** Specific data points on how much information the central government provides to the public and how much opportunity the public has to participate.
- **Global Coverage:** Data spanning across multiple years and over 100 countries, making it a "large public dataset" suitable for meaningful mining.

### Dataset Link
[**World Bank Open Budget Survey Rankings**](https://data360.worldbank.org/en/indicator/IBP_OBS_RANK)

[**Full OBS 2025 Dataset**](https://internationalbudget.org/open-budget-survey/download)

## Data Mining Plan
To achieve the project goals, I plan to follow these data mining stages:

### Data Acquisition & Cleaning:
Export all the necessary data from the World Bank Data360 and standardize all values and handle missing data to be able to process the given dataset.

### Exploratory Data Analysis (EDA):
Identify outlier-countries that have seen drastic changes in their respective rankings through the use of visualization tools.

### Correlation Analysis:
Use Pearson or Spearman correlation to determine the strength of the relationship between legislative oversight and the overall OBI score.

## Tools
I plan to use [Python/Pandas/Jupyter Notebook/Google Sheets] to process and analyze the information.

## Expected Outcomes
The final output will be a report showing  rankings and characteristics that define “transparency” in order to try to understand milestones a developing country needs in order to improvise its global standing in its fiscal accountability while providing a way to apply the given knowledge in the DATAMIN class.

-----

## AI Disclosure Statement
**Tool Used**
- Gemini 3 Flash (Google)
- DeepSeek (DeepSeek)

*Date of Access: March 23, 2026*<br/>
*April 18, 2026 (DeepSeek)*

### Extent of Use
I utilized generative AI to assist in the pre-development and structural phases of this proposal. Specifically, the tool was used to:

#### Gemini
- Look for possible datasets online that can be used.
- Refine the project title and research objectives based on the World Bank Open Budget Survey dataset.
- Generate a structured outline for the proposal to ensure it met all academic requirements.
- Draft initial technical descriptions for the data mining methodology (e.g., K-Means clustering and Star Schema).
- Format academic citations in accordance with APA 7th Edition standards.

#### DeepSeek:
- Assisted during the development and analysis phases of the project
- Helped troubleshoot CSV data loading issues in Jupyter Notebook
- Provided guidance on data normalization and cleaning strategies
- Explained column meanings using the DataDictionary
- Suggested analytical approaches for trend analysis, clustering, and correlation
- Assisted in interpreting output and debugging code
- Helped refine project documentation

### Author’s Responsibility
I have critically reviewed, edited, and verified all AI-generated content. All final decisions regarding the project’s scope, technical plan, and data selection were made by me. I remain fully accountable for the accuracy and integrity of this work.

------

## Reference
**DeepSeek. (2026, April 18).** *Assistance with data mining project analysis, troubleshooting, and methodology [Generative AI chat].* DeepSeek. https://chat.deepseek.com

**Google. (2026, March 23).** *Assistance with data mining project proposal and dataset selection [Generative AI chat].* Gemini 3 Flash. https://gemini.google.com

**International Budget Partnership. (2024).** *Open Budget Survey 2023: Global report and rankings [Data file].* World Bank Data360. https://data360.worldbank.org/en/dataset/IBP_OBS

**International Budget Partnership. (2025).** *Open Budget Survey 2025: Public data statfile (Launch 2) [Data file].* https://internationalbudget.org/open-budget-survey/download

**World Bank. (n.d.).** *Open Budget Index Rank (IBP_OBS_RANK) [Data table]. Data360.* Retrieved March 23, 2026, from https://data360.worldbank.org/en/indicator/IBP_OBS_RANK