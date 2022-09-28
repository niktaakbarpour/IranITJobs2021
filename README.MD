# IranITJobs2021
This is a dataset containing 1300 Iranian IT job advertisements in English from August 2019 to January 2021 and collected by using a new crowdsourcing-based dataset gathering process. These ads are collected from Iranian online job search websites. These websites are as follows: 

 - https://quera.ir
 - https://jobinja.ir
 - https://karboom.io
 - https://cheragh.com
 - https://jobvision.ir
 - https://e-estekhdam.com
 - https://iranestekhdam.ir
 - https://karinsoo.com
 - https://computerjobs.ir
 - https://javacup.ir
 - https://daneshkar.net
 
 Each record in the IranITJobs2021 dataset incorporates 13 fields.

## Fields of The Dataset
| Column name         | Data type | Description                                                                                                       |
|---------------------|-----------|-------------------------------------------------------------------------------------------------------------------|
| Company name        | String    | -                                                                                                                 |
|Company type         |Nominal    |Type of company: governmental, non-governmental, or non-company                                                    |
|Ad date              | Date      |The date that the job advertisement is posted                                                                      |
|Ad title             |String     |Example: hiring a senior Android programmer                                                                        |
|Remote work          |Boolean    |Yes, if the company allows remote work, otherwise, No                                                              |
|Location             |String     |The city/distinct where the job seeker is supposed to work                                                         |
|Knowledge enterprise |Boolean    |Yes, if the company is knowledge-based, otherwise, No                                                              |
|Part-time            |Boolean    |Yes, if the company supports part-time recruitment, otherwise, No                                                  |
|Gender               |Nominal    |Requested gender: Female, Male, or Both                                                                            |
|Military service     |Boolean    |Yes, if the job seeker has an option to work in a company in exchange for doing his military service, otherwise, No|
|Project-based        |Boolean    |Yes, if the company supports project-based recruitment, otherwise, No                                              |
|Ad text              |String     |The whole text of the advertisement                                                                                |
|Keywords             |String     |List of technologies and skills required for a job                                                                 |

## Related Paper
This dataset was collected by using a new crowdsourcing-based dataset gathering process. This process is published in a paper named "IranITJobs2021: a Dataset for Analyzing Iranian Online IT Job Advertisements Collected Using a New Crowdsourcing-based Dataset Gathering Process". This paper can be accessed [here](https://github.com/mrezasaeidi/IranITJobs2021/blob/main/IranITJobs2021.xlsx?raw=true).
