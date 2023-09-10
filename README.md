
# NIGERIAN GRADUATES SURVEY RESPONSE ANALYSIS


![Logo](https://github.com/Brymahh/Nigerian-Graduates-Survey/blob/main/Graduate.png?raw=true)


-----
## INTRODUCTION


Employability is the ability of an individual to secure and maintain gainful employment in the labor market. The employability of Nigerian graduates has been a source of concern for policymakers, stakeholders, and employers, given the high rate of unemployment in the country. 

The Nigerian higher education system comprises public and private tertiary institutions, which offer various courses across different fields. The quality of education, skills, and work experience of graduates from these institutions varies, and this may impact their employability. In addition to the type of institution attended and the course of study, the National Youth Service Corps (NYSC) program is another factor that affects the employability of Nigerian graduates. This study aims to explore the factors that affect the employability of Nigerian graduates, including the type of institution attended, the course of study, and the NYSC program.

---------
## BACKGROUND:
The Nigerian higher education system has undergone significant expansion in recent years, with the establishment of more public and private tertiary institutions offering a diverse range of courses across different disciplines. While this growth is laudable, the employability of Nigerian graduates is a source of concern for policymakers, stakeholders, and employers. The high rate of unemployment in the country, coupled with the mismatch between the skills possessed by graduates and the demands of the labor market, has led to a situation where many graduates struggle to secure gainful employment.


The quality of education, skills, and work experience of graduates from public and private institutions vary. Public institutions are primarily funded by the government, while private institutions are funded by private individuals or organizations. The differences in funding and resources may lead to disparities in the quality of education and exposure to practical work experience between public and private institutions, which may impact the employability of graduates from these institutions. Graduates from private institutions may have an advantage in the labor market, as they are perceived to have received a higher quality of education, exposure to better resources, and practical work experience.
Furthermore, the relevance of courses to the needs of the labor market is a critical factor that affects the employability of Nigerian graduates. 

The Nigerian higher education system offers a wide range of courses across different fields, such as engineering, medicine, law, social sciences, humanities, and education. However, the relevance of these courses to the needs of the labor market varies, and this may impact the employability of graduates. Graduates with skills that are in high demand in the labor market are more likely to secure employment than those with skills that are not in demand. Graduates from fields such as engineering, medicine, and law are generally in high demand in the labor market, as these fields are considered critical for national development. In contrast, graduates from fields such as social sciences, humanities, and education may face difficulties in securing employment, as the demand for graduates from these fields is relatively low.
    In addition to the type of institution attended and the course of study, the National Youth Service Corps (NYSC) program is another factor that may impact the employability of Nigerian graduates. The NYSC program is a mandatory one-year national service for Nigerian graduates, aimed at fostering unity and promoting the development of the country. The program provides graduates with an opportunity to gain practical work experience and develop skills that are in demand in the labor market. The program also exposes graduates to different parts of the country, thereby broadening their perspective and enhancing their cultural awareness. However, the impact of the NYSC program on the employability of Nigerian graduates is still a subject of debate. Some argue that the program provides graduates with relevant work experience and exposure to diverse cultures, making them more attractive to employers. Others, however, argue that the program is poorly managed, and the skills gained are not always relevant to the needs of the labor market.

In conclusion, the employability of Nigerian graduates is a multifaceted issue influenced by various factors such as the type of institution attended, the course of study, and the NYSC program. While the Nigerian higher education system has undergone significant expansion, there is a need for policymakers and stakeholders to address the quality of education, skills, and work experience of graduates from public and private institutions. Additionally, there is a need for more relevant courses that align with the demands of the labor market to enhance the employability of Nigerian graduates. 

`The study aims to investigate the factors influencing the employability of Nigerian graduates detailed above and thus strive to seek answers to these questions.`
1. Can the employability of graduates from Nigerian universities be correlated with the academic programs they pursued during their undergraduate studies?
3. Assessing Influence of a type of tertiary institutions on employability for Nigerian graduates. (That is Private or Public Universities.)
4. Evaluating the importance of (NYSC) program to Nigerian graduates. (If it enhances their chances of employment after graduation).


---------
## METHODOLOGY
The study employed a mixed-methods research design, which involved the use of both quantitative and qualitative data. The study population comprised Nigerian graduates who had completed their NYSC program within the last five years from the year 2018. A total of 5219 graduates from both public and private tertiary institutions across different fields of study participated in this survey. Data was collected using a survey questionnaire, which was designed to elicit responses on questions regarding their employability as Nigerian graduates; including the institution attended, the course of study, and the NYSC program. 

---------
## DATA COLLECTION:
The data for this analysis involves a survey response collated by Stutern; a platform designed to facilitate skills development and job placement for young African talents by offering training programs and establishing connections with potential employers, ultimately enabling them to secure long-term employment prospects.

---------
## DATA ANALYSIS:
Statistical tools such as Python and PowerBi will be utilized to analyze the collected data. The survey responses were stored in an Excel spreadsheet containing 36 features (column names) and 5219 observations (responses). Due to the manual nature of data entry by the graduates through Google Forms, the data contained discrepancies and required cleaning to remove errors and inconsistencies.

In this data analysis, Jupyter Notebook was used as the Python development environment to perform data wrangling, which involves cleaning, transforming, and restructuring raw data to prepare it for analysis. The NumPy, Pandas, and Matplotlib libraries were imported and utilized to explore the survey responses.

After loading the dataset, we conducted a preliminary analysis to identify any issues such as missing, inconsistent, or incorrect data, including typos and duplicates. Based on this analysis, we determined the necessary steps to be taken for data wrangling.
1. The column names were modified by shortening the original lengthy sentences and a data dictionary was provided to explain the new names and their corresponding meanings.
2. A subset of the initial dataset consisting of only 11 columns relevant to the current analysis was extracted.
3. The existence of duplicated values across all columns was checked. Given that it is highly unlikely for the same individual to provide identical information across all fields and submit them at the same time (exact time stamps), this was considered a result of internet connection errors.
4. The percentage of missing values was calculated and features with over 50% missing values were evaluated for their significance before being eliminated from the dataset.
5. Each column was individually assessed and cleaned through appropriate techniques.
During evaluation, the column titled “Was Qualification Relevant to Your First Job” contained 68% missing values.

------------
## RECOMMENDATIONS:
Based on the analysis conducted, we can make several recommendations for stakeholders involved in the Nigerian education sector:
1.	Improve employability skills of Nigerian graduates: As the analysis showed a significant correlation between employability and the course studied during undergraduate years, it is recommended that tertiary institutions in Nigeria focus on courses that are in demand in the labor market. This can be achieved through curriculum redesign and partnerships with industry players to provide practical training and mentorship programs.
2.	Promote National Youth Service Corps Completion: As the analysis showed that graduates who completed their NYSC had a higher employment rate compared to those who did not, it is recommended that the Nigerian government and relevant stakeholders promote the importance of completing the program to all graduates.
3.	Improve the quality of education in publicly funded institutions: As graduates from private institutions showed a higher employment rate and lower unemployment rate compared to graduates from publicly funded institutions, it is recommended that the Nigerian government improve the quality of education in publicly funded institutions. This can be done through increased funding, improving infrastructure, and hiring qualified lecturers.
4.	Encourage data-driven decision making in the Nigerian education sector: As demonstrated by this analysis, data can provide valuable insights for improving the Nigerian education system. It is recommended that stakeholders in the education sector prioritize data collection and analysis to inform decision making.


`The recommendations provided above aim to improve the employability of Nigerian graduates and reduce the unemployment rate in the country.`

----------
## LIMITATIONS
Based on our analysis, some limitations to this study/analysis are:
1.	Sample size: The analysis is based on a survey with 5219 responses, which may not be representative of the entire population of Nigerian graduates. This may limit the generalizability of the findings.
2.	Data quality: The data involved manual responses of graduates via Google Forms, which may lead to discrepancies and errors in the data. While efforts were made to clean the data, there may still be some inaccuracies or missing data that could impact the results.
3.	Scope of analysis: The analysis focuses on the relationship between employability, course of study, and completion of the National Youth Service Corps program. Other factors that may impact employability, such as skills and work experience, are not considered.
4.	Timeframe: The study is limited to a particular timeframe and may not reflect the current situation. The results may be impacted by changes in the labor market or educational system over time.

## Acknowledgements

This project was accomplished through joint effort with Asemota Precious.