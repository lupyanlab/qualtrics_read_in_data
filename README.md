# qualtrics_read_in_data_updated
These codes are for importing qualtrics data directly from website and organize data to a long format data-frame that we would use in an analysis.

Make sure following packages are installed in R:

tidyverse
yaml
qualtRics
readr

1. Clone this repository to the local folder where you will analyze your data.
2. Open download_survey_data.R, set your working directory on line 2.
3. Enter your survey name under variable "survey_name"
4. Run download_survey_data.R. There will be three files created in your folder. "qualtrics.csv" will be your raw data in wide format. "responses.csv" will be your raw data in long format. "questions.csv" will be comments to your survey as well as some demographic information of the participants.

