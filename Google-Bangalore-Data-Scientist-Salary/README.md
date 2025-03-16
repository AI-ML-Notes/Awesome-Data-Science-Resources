#### Data is scraped Google Bangalore Data Scientist salary from Levels.fyi.
#### Duration: Sep19-Mar25
#### Data size: 122
#### Sources: [AI ML SWE](https://www.levels.fyi/t/software-engineer/locations/greater-bengaluru?search=google+ai+ml), [Data Scientist](https://www.levels.fyi/t/data-scientist/locations/greater-bengaluru?search=google)

#### Steps to scraping:
1. Take screenshots for all of the posting one-by-one, manually.
2. Prompt [Gemini](https://gemini.google.com/) <br>
   **Prompt**: `Extract the following details as keys in a json.`<br><br>
`Company`<br>
`Job Title`<br>
`Location`<br>
`Date of Posting/Information`<br>
`Level`<br>
`Years at Company`<br>
`Years of Experience`<br>
`Years at Current Level`<br>
`Employment Type`<br>
`Work Arrangement`<br>
`Average Annual Total Compensation`<br>
`Base Salary`<br>
`Average Annual Stock (RSUs)`<br>
`Average Annual Bonuses`<br>
`Demographics - Gender`<br>
`Demographics - Race`<br>
`Demographics - Qualification`<br>
3. With the outputs, create the JSONL file, [base_data_15MAR25.jsonl](https://github.com/AI-ML-Notes/Awesome-Data-Science-Resources/blob/main/Google-Bangalore-Data-Scientist-Salary/base_data_15MAR25.jsonl).
4. After data cleaning, final data, [Base Data - 15MAR25.csv](https://github.com/AI-ML-Notes/Awesome-Data-Science-Resources/blob/main/Google-Bangalore-Data-Scientist-Salary/Base%20Data%20-%2015MAR25.csv) is created. [Code](https://github.com/AI-ML-Notes/Awesome-Data-Science-Resources/blob/main/Google-Bangalore-Data-Scientist-Salary/01_Base_Data_Prep.ipynb) is here.


### Analysis is on Kaggle
