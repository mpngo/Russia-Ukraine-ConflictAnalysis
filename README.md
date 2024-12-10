# Russo-Ukraine War Analysis

## Overview
This project provides a comprehensive data-driven analysis of the Russo-Ukraine War. Using data on armed conflict events, weapons transfers, and media coverage, we explore the geopolitical, strategic, and narrative aspects of the war. Our findings reveal critical insights into the types of weapons used, key supplier nations, conflict trends, and differences in media framing by CNN and Fox News.

## Objectives
1. **Analyze conflict events:** Examine the geographic patterns and intensity of conflict events using ACLED data.
2. **Evaluate arms transfers:** Assess the weapon types and supplier nations to Ukraine and Russia using SIPRI data.
3. **Explore media coverage:** Investigate keyword trends in reporting by CNN and Fox News to analyze narrative shifts.

## Data Sources
1. **ACLED:** Armed conflict event data.
2. **SIPRI:** Stockholm International Peace Research Institute arms transfer data.
3. **CNN & Fox News:** Web-scraped articles related to the Ukraine conflict.

## Methodology
### Data Acquisition
- **ACLED API:** Extracted over 160,000 conflict event records via API integration.
- **SIPRI:** Downloaded CSV files for weapons transfer data, focusing on Russia and Ukraine.
- **Web Scraping:** Used Selenium and BeautifulSoup to collect over 3,700 articles from CNN and Fox News.

### Data Processing
- Cleaned and standardized data from all sources.
- Integrated datasets for consistent analysis.
- Preprocessed text data with tokenization, lemmatization, and stopword removal for keyword analysis.

### Exploratory Analysis
- **Conflict Data:** Mapped event types like battles, protests, and drone strikes over time and geography.
- **Arms Transfers:** Assessed key weapon types, import volumes, and top supplier nations.
- **Media Analysis:** Tracked keyword mentions over time to compare narrative focus between CNN and Fox News.

## Results
- **Conflict Trends:** Increased battles and drone strikes highlight evolving strategies.
- **Arms Transfers:** The U.S. dominates as Ukraine's top supplier, while Russia relies on pre-war agreements and Iranian imports.
- **Media Insights:** CNN emphasizes detailed reporting on advanced weaponry, while Fox News adopts a more general approach with reactionary peaks.

## Challenges
- **SIPRI Limitations:** Manual data downloads due to the lack of an API.
- **Dynamic Websites:** JavaScript-heavy pages required advanced scraping techniques with Selenium.
- **Keyword Bias:** Focus on selected terms may exclude nuanced reporting.

## Repository Contents
- **`141B_project.ipynb`:** Jupyter Notebook with all code for data acquisition, preprocessing, and analysis.
- **`data/`:** Contains cleaned and raw datasets used in the analysis.
- **`visualizations/`:** Includes figures and charts generated during the project.
- **`interactive_map/`:** Interactive map visualizing conflict events by type and location.
- **`README.md`:** This file documenting project details and instructions.
