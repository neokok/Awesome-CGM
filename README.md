# Awesome-CGM

This is a collection of links to publicly available continuous glucose monitoring (CGM) data.

CGMs are small wearable devices that allow to measure glucose levels continuously throughout the day, with some meters taking measurements as often as every 5 min. For the head start on CGM data analyses, check out our R package [iglu](https://github.com/irinagain/iglu).

This collection follows the style of Mike Love's [awesome-multi-omics](https://github.com/mikelove/awesome-multi-omics) and Sean Davis' [awesome-single-cell](https://github.com/seandavi/awesome-single-cell) repos, although the latter are collections of methods rather than dataset links.


## Citation and contributions

The new list was updated in October 2024 and assembled by Xinran (Charlotte) Xu, Neo Kok, and Junyan (Samuel) Tan, under the supervision of Dr. Irina Gaynanova. [Contributions are welcome](https://github.com/irinagain/Awesome-CGM/blob/master/CONTRIBUTING.md).

To cite current version 1.2.0, use

[New Zenodo Citation]

The original list was assembled by Mary Martin, Elizabeth Chun, David Buchanan, Eric Wang, and Sangaman Senthil as part of their [Aggie Research Project](https://aggieresearch.tamu.edu) under the supervision of Dr. Irina Gaynanova. 

To cite current version 1.1.0, use 

Mary Martin, Elizabeth Chun, David Buchanan, Rucha Bhat, Shaun Cass, Eric Wang, Sangaman Senthil & Irina Gaynanova. (2021, April 27). irinagain/Awesome-CGM: List of public CGM datasets (Version v1.1.0). Zenodo. [![DOI](https://zenodo.org/badge/267687517.svg)](https://zenodo.org/badge/latestdoi/267687517)


## Datasets

Below is a list overview of all datasets with the links, the same list in a table format can be seen [here](https://github.com/irinagain/Awesome-CGM/wiki). Click the name of a data set for a link to download the CGM data, pre-processing scripts, and covariate information, as well as any additional dataset-specific use agreements.

### Type 1

* [Aleppo (2017)](https://github.com/irinagain/Awesome-CGM/wiki/Aleppo-(2017))
  * The purpose of this study was to determine whether the use of continuous glucose monitoring (CGM) without blood glucose monitoring (BGM) measurements is as safe and effective as using CGM with BGM in adults (25-40) with type 1 diabetes. The total sample size was 225 participants. The Dexcom G4 was used to continuously monitor glucose levels for a span of 6 months.
  * Found by Mary Martin. CGM Processor by David Buchanan, Elizabeth Chun. Updated R processor by Shaun Cass. Uploaded by Mary Martin, Elizabeth Chun.
  
* [Anderson (2016)](https://github.com/irinagain/Awesome-CGM/wiki/Anderson-(2016))
  * This study was designed to test a closed-loop control-to-range artificial pancreas (AP) system. There are two phases to this study. Within Phase 1, there were various stages of this study starting with 0-3 weeks of practice with CGM. This was followed by 2 weeks using the study pump together with CGM known as sensor augmented pump (SAP) therapy. This was used as a baseline and followed by 2 weeks of overnight only closed loop control (CLC) and 2 weeks of 24/7 CLC. During the CLC weeks, insulin was administered by the AP system. Phase 2 continued with only 14 patients - physician’s choice. These 14 patients used the CLC system 24/7 for five additional months.
  * Found by Elizabeth Chun. CGM Processor by David Buchanan, Elizabeth Chun. Uploaded by Elizabeth Chun, Mary Martin.

* [Brown (2019)](https://github.com/irinagain/Awesome-CGM/wiki/Brown-(2019))
  * This study examined the use of the Dexcom G6 CGM and t:Slim X2 with Control-IQ Technology among children and adults (ages 14+). The study duration was 6 months with a sample size of 168 participants.
  * Found by Junyan (Samuel) Tan. Updated R processor by Junyan (Samuel) Tan. Uploaded by Junyan (Samuel) Tan.

* [Buckingham (2007)](https://github.com/irinagain/Awesome-CGM/wiki/Buckingham-(2007))
  * This study was designed as a pilot study to analyze use of a CGM for children with diabetes. The subjects first established a baseline during a week blinded use, followed by at home use for 3 months.
  * Found by Eric Wang. CGM Processor by David Buchanan, Elizabeth Chun. Enhanced CGM processing by Rucha Bhat. Uploaded by Elizabeth Chun, Mary Martin.

* [Chase (2005)](https://github.com/irinagain/Awesome-CGM/wiki/Chase-(2005))
  * This study focused on the use of the GlucoWatch G2 Biographer as a tool to help in diabetes care. The 200 subjects were randomly assigned to test (CGM) or control (self-monitoring blood glucose). At the end of the study duration, A1c measurements were used to compare the two groups.
  * Found by Eric Wang. Uploaded by Elizabeth Chun, Mary Martin.

* [Dubosson (2018)](https://github.com/irinagain/Awesome-CGM/wiki/Dubosson-(2018))
  * This study focused on the use of wearable devices in a non clinical setting. There are nine type 1 diabetes patients. A large variety of data other than CGM data was collected for this study, designed for research on correlations between glucose levels and physiological measures such as ECG.
  * Found by Elizabeth Chun. CGM Processor by David Buchanan, Elizabeth Chun. Uploaded by Elizabeth Chun, Mary Martin.

* [Lynch (2022)](https://github.com/irinagain/Awesome-CGM/wiki/Lynch-(2022))
  * The study aims to evaluate the transition of Type 1 diabetes management from a hybrid closed-loop system using an insulin pump and CGM to a biotic pancreas. The Dexcom G6 CGM was used across a population group aged between 6 and 71 years over a 13-week period, with a sample size of 90 participants.
  * Found by Xinran (Charlotte) Xu. Updated R processor by  Neo Kok. Uploaded by Junyan (Samuel) Tan.

* [Marling (2019)](https://github.com/irinagain/Awesome-CGM/wiki/Marling-(2019))
  * This study has 12 type 1 diabetes patients. 
  * Found by Irina Gaynanova. CGM Processor by Elizabeth Chun. Uploaded by Elizabeth Chun.


* [Tamborlane (2008)](https://github.com/irinagain/Awesome-CGM/wiki/Tamborlane-(2008))
  * This study was designed to test CGM as a technology to assist in diabetes care. The randomized trial was intended to determine if CGM usage had a positive effect on diabetes management. The total subjects were split into two cohorts based on A1c results, with one cohort having initial A1c measurements from 7-10% and the second cohort of those with A1c levels <7%. Within each cohort, subjects were randomly assigned to a test (CGM) or control group.
  * Found by David Buchanan. CGM Processor by David Buchanan, Elizabeth Chun. Uploaded by Elizabeth Chun, Mary Martin.

* [Tsalikian (2005)](https://github.com/irinagain/Awesome-CGM/wiki/Tsalikian-(2005)) 
  * The purpose of this study was to find out how often low blood sugar (hypoglycemia) occurs during the night after exercise in late afternoon for children aged 10 to 18 with type 1 diabetes. The total sample size was 50 participants. The OneTouch Ultra Meter was used to continuously monitor glucose levels during two seperate 24 hours periods.
  * Found by Eric Wang. CGM Processor by David Buchanan, Elizabeth Chun. Uploaded by Mary Martin, Elizabeth Chun.

* [Wadwa (2023)](https://github.com/irinagain/Awesome-CGM/wiki/Wadwa-(2023))
  * The purpose of this study was to improve glycemic outcomes in young children (ages 2-6) with Type 1 diabetes using the t:slim X2 insulin pump with Control-IQ Technology and Dexcom G6 CGM. The study spanned 13 weeks with a total sample size of 102 participants.
  * Found by Xinran (Charlotte) Xu. Updated R processor by Junyan (Samuel) Tan. Uploaded by Junyan (Samuel) Tan.

* [Weinstock (2016)](https://github.com/irinagain/Awesome-CGM/wiki/Weinstock-(2016))
  * The purpose of this study was to identify factors associated with severe hypoglycemia in older adults (60+) with type 1 diabetes. The total sample size was 200 participants: 100 cases, 100 control. The Dexcom SEVEN PLUS was used to continuously monitor glucose levels for a span of 2 weeks.
  * Found by Mary Martin. CGM Processor by Sangaman Senthil, Elizabeth Chun. Uploaded by Mary Martin, Elizabeth Chun.
  
### Type 2
* [Broll (2021)](https://github.com/Charlotte1031/Awesome-CGM/wiki/Broll-(2021))
   * The study involved Type 2 diabetic individuals using the Dexcom G4 CGM. Data from 5 subjects is provided as an example dataset for the development of the [‘iglu’ package](https://github.com/irinagain/iglu). 
  * Found by Irina Gaynanova. Uploaded by Xinran (Charlotte) Xu.
  
### Other
* [Colas (2019)](https://github.com/irinagain/Awesome-CGM/wiki/Colas-(2019))
  * This study has 208 subjects, all healthy at study start and 17 developed type 2 diabetes by study end. 
  * Found by Elizabeth Chun. CGM Processor by Elizabeth Chun. Uploaded by Elizabeth Chun. Updated Processor by Neo Kok.

* [Hall (2018)](https://github.com/irinagain/Awesome-CGM/wiki/Hall-(2018))
  * This study analyzes how blood glucose fluctuates in healthy individuals by using a CGM to monitor glucose. Standardized meals (breakfast only) were given to a subset of patients in order to monitor the effect of meals on the glucose readings of healthy individuals. The 57 subjects in this study had no prior diabetes diagnosis but 5 were diagnosed with Type 2 on study screening and a further 14 with pre-diabetes.
  * Found by Elizabeth Chun. CGM Processor by David Buchanan, Sangaman Senthil, Elizabeth Chun. Uploaded by Elizabeth Chun, Mary Martin.
  
* [Åm (2018)](https://github.com/irinagain/Awesome-CGM/wiki/%C3%85m-(2018))
  * This study was done on an **animal** model, specifically **pigs**, in order to study sensor placement and the corresponding effects on CGM data. In order to simulate meals, glucose infusions were given to non-diabetic, anesthetized pigs through IV.
  * Found by Elizabeth Chun. Uploaded by Elizabeth Chun, Mary Martin.
  
* [Shah (2019)](https://github.com/irinagain/Awesome-CGM/wiki/Shah-(2019)) 
  * The purpose of this study was to evaluate glucose control in a mixed population (ages 6 and older) and  to establish reference sensor glucose ranges in healthy, non-diabetic individuals using the Dexcom G6 CGM. The sample size was 153 participants, with varying study duration. 
 * Found by Xinran (Charlotte) Xu. Updated R processor by Xinran (Charlotte) Xu. Uploaded by Xinran (Charlotte) Xu.

  
### Simulators

* [Xie (2018)](https://github.com/irinagain/Awesome-CGM/wiki/Xie-(2018))
  * This repo is a python implementation of the FDA-approved UVa/Padova Simulator for research purposes. It is "reinforcement-learning-ready", with a simulation enviroment which follows OpenAI gym and rllab APIs.
  * Found by David Buchanan.

* [Lehmann (2011)](https://github.com/irinagain/Awesome-CGM/wiki/Lehman-(2011))
  * The AIDA simulator is intended for simulating the effects on the blood glucose profile of changes in insulin and diet for a typical insulin-dependent (type 1) diabetic patient. 
  * Found by David Buchanan


 ## Validation Dataset and additional processing

The Awesome-CGM public datasets have been updated with processing scripts designed for advanced integrative validation. These datasets serve as standardized test cases for software evaluation. The following datasets have been integrated with additional patient-level statistics such as 'Sex', 'Insulin Modality', 'Diabetes Type', and 'Device Used' from each raw data source:

- **[Colas2019](https://github.com/IrinaStatsLab/Awesome-CGM/wiki/Colas-(2019))** (Healthy: n=191, Type 2 Diabetic: n=17)
- **[Broll2021](https://github.com/IrinaStatsLab/Awesome-CGM/wiki/Broll-(2021))** (Type 2 Diabetic: n=5)
- **[Brown2019](https://github.com/IrinaStatsLab/Awesome-CGM/wiki/Brown-(2019))** (Type 1 Diabetic: n=168)
- **[Hall2018](https://github.com/IrinaStatsLab/Awesome-CGM/wiki/Hall-(2018))** (Healthy: n=38, Pre-Diabetic: n=14, Type 2 Diabetic: n=5)
- **[Shah2019](https://github.com/IrinaStatsLab/Awesome-CGM/wiki/Shah-(2019))** (Healthy: n=168)
- **[Buckingham2007](https://github.com/IrinaStatsLab/Awesome-CGM/wiki/Buckingham-(2007))** (Type 1 Diabetic: n=47)
- **[Lynch2022](https://github.com/IrinaStatsLab/Awesome-CGM/wiki/Lynch-(2022))** (Type 1 Diabetic: n=440)
- **[Wadwa2023](https://github.com/IrinaStatsLab/Awesome-CGM/wiki/Wadwa-(2023))** (Type 1 Diabetic: n=102)

Each subject is uniquely identified using a pseudo-ordered ID format, with the first digit representing the dataset (e.g., the first subject in the updated Colas2019 dataset is assigned ID 3001, and in the Lynch2022 dataset, ID 1401).

This combined dataset encompasses a population of:
- **Type 1 Diabetic**: n=820
- **Type 2 Diabetic**: n=27
- **Pre-Diabetic**: n=14
- **Healthy**: n=398

The dataset has an average study duration of 18 weeks, with a mean age of 32 years. Approximately 74% of the cohort used an insulin pump rather than injections during their study period.

### Data Quality Checks

Minimal exclusion criteria have been implemented for users performing data quality checks. A missing data/cleaning check [R script](https://github.com/IrinaStatsLab/Awesome-CGM/blob/master/R/filter_missing_data.R) is provided with the following inclusion criteria:
- 90% non-missing data for 1-day records
- 70% non-missing data for records spanning 2–14 days
- 70% non-missing data for records covering periods from 14 days to 3 months

An optional visual quality check [R script](https://github.com/IrinaStatsLab/Awesome-CGM/blob/master/R/plot_check_csv.R) is also available, using the `plot_glu()` function from the iglu R package ([GitHub link](https://github.com/charlotte1031/iglu)).

A code reproduction demo can be followed using this README file: [Processing Demo](https://github.com/IrinaStatsLab/Awesome-CGM/blob/master/R/Processing_Demo.md).

### Data Processing R Shiny App

This release includes a **ShinyGUI** app designed to assist users in navigating, downloading, and processing raw CGM datasets.
The app will navigate users to download raw datasets directly from their original sources and process them using their respective AwesomeCGM processing scripts. Users can process and execute datasets either individually or multiple datasets at once. An optional missing data exclusion filter can be applied during processing, enabling more tailored dataset outputs. Processed datasets can then be downloaded in their final form.

You can access the deployed Shiny at [Awesome-CGM Validation Dataset GUI](https://xxchar.shinyapps.io/Awesome-CGM-GUI/).

**Steps to Use the App:**
1. Open [Awesome-CGM Validation Dataset GUI](https://xxchar.shinyapps.io/Awesome-CGM-GUI/) in you browser.
2. Browse the dropdown menu to view a list of preloaded **dataset** sources. Select one or multiple datasets to work with. For each selected dataset, upload the required raw data files by downloading them from their original data sources, as indicated by the on-screen message prompts.
3. Once all the necessary raw data files are uploaded (bulk uploads are supported), click **Process Dataset** to begin processing. If desired, toggle the **Apply Missing Data Filter** checkbox to exclude rows with missing data during processing.
4. After processing is complete, click the **Download Processed** Data button to download all processed datasets as a single compressed .zip file.

---
**Important Note:** The deployed Shiny link may be **unusable for datasets exceeding ~500MB** (e.g., the Brown and Lynch datasets). Due to server capacity limitations, unzipping these large datasets may cause the app to time out or fail. Users are encouraged to host the shiny locally when processing that two datasets for optimal performance. 

**Follow these steps to set up and use the Shiny app on your local machine:**

1. Clone the Repository
   
Download the repository to your local machine:
```bash
git clone https://github.com/Charlotte1031/Awesome-CGM.git
```
2. Open the Project File

Navigate to the folder where the repository was cloned and open the ShinyGUI.Rproj file in RStudio. This ensures that the correct working directory and project environment are loaded.

3. Run the Shiny App with:
- Open the server.R or ui.R file in RStudio, then click the **“Run App”** button in the top-right corner of the editor panel.
- Alternatively, run the following command in the R console:
```r
shiny::runApp("GUI")
```

4. Process Datasets Locally

Once the app launches in your browser or a new window, use the Shiny interface to navigate, select, validate, and process your datasets. For larger datasets, such as Brown and Lynch, running the app locally ensures sufficient capacity for processing. Please note that processing these larger datasets may still take a few minutes.
 
---


