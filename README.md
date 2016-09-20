# Final Report

In this assignment, you will be designing a small research project based on skills learned in this course. This will entail choosing a topic or research question, constructing a research design using methods learned in this course, executing the research design, and producing a report which addresses the research question. The project is due at the end of the term (December 1), and you will need to turn in the report, the code you used to produce the report, and any original data that you gathered. 

## Projects

You will have the choice of three projects, which I am associating with specific data analytic roles. These projects are examples of the kind of tasks which you will encounter in many industries, government agencies, and academic professions. 

1. **Canadian Tire social media manager**
    - *Background*: You are a social media manager for Canadian Tire. You are interested in how people are talking about Canadian Tire over time. To do that, you want to look at the volume of Twitter activity around your company and whether this talk is positive or negative. In addition, your company changed its slogan from "Canada's Store" to "Tested for life in Canada." You would like to see if there has been more positive talk of the company in light of this change. This report will help you assess what kinds of content to broadcast, which products to feature, and which sales to highlight. 
    - *Data*: You will be using a summary dataset of tweets mentioning Canadian Tire over 2013 and 2014, drawn from a 10% sample of Twitter. Each tweet will be labeled as positive or negative, and given a specific location if it exists. In order to simplify comparison, you have to choose *three months* of comparison per year. You need to justify why you chose these months instead of others. These data will be posted within a week.

<!-- These can be found [here](data/canadian-tire_cct490.csv). -->

2. **Stats Can statistician**
    - *Background*: You are a statistician at Statistics Canada (Stats Can). You want to create a report about health outcomes of Aboriginal people across Canada who are not living on a reserve. By health outcomes, we are talking about several things: self-assessments of health, diabetes, asthma, smoking, and other conditions. You need to produce a report which reports on differences in health outcomes between non-Aboriginal and Aboriginal people, and within Aboriginal people, differences between women and men, and differences between all Canadian provinces. For this purpose, you should choose *three health outcomes* on which you want to analyze. You need to justify why you chose these health outcomes instead of others.
    - *Data*: You will be using a summary dataset of the Canadian Community Health Survey (CCHS), conducted in 2005 and which surveyed over 27 million Canadians. These data report a number of health outcomes and divide them by Geography (GEO), whether the respondent was Aboriginal or not (PROFILE), Sex (SEX), and health outcome (HEALTHPROF). You will have to figure out how to navigate this dataset and produce a report from it. You can download these data from [http://open.canada.ca/data/en/dataset/5b892b96-2d1d-49f1-8a0a-e2b3f94765bd](Open Canada).

3. **Political consultant**
    - *Background*: You are a political consultant for a minor political party. You are interested in understanding which provinces and areas you could potentially pick up parliamentary seats. Based on areas of your strength, you may adjust your party platform to match the electoral profile of particular areas. You plan to do this by comparing areas of strength for *two parties* of your choice. One of them should be a major party (Liberal, NDP, Conservative), and the other should be one of the rest. Your report will report which provinces and areas in which each party seemed to have more strength. You will also compare rural areas to urban areas.  
    - *Data*: You will be using the voting totals from each of the 75,413 polling stations across the country, which can be grouped into ridings (Electoral District Number). Each polling station has vote totals for all parties which fielded a candidate in that riding. Each polling station is also divided into either urban or rural. These data will be posted within the week.

<!-- You can get the data [here](data/election-ca-2015.csv). The data are originally from [http://open.canada.ca/data/en/dataset/6a919bd5-491e-466e-a279-00cbf7a8e02c](Open Canada) and have undergone slight modifications. -->

## Report Requirements

The report has several requirements which must be met. The report must be written in Jupyter Notebook. The prose (Markdown) portion should be about 500-1000 words. The report must include at least three charts and three tables. These charts and tables should be easily readable. You must include all your code within the notebook.

The report should have four sections. First should be the *Executive Summary*. In this section, you briefly mention the question or questions you are asking, report results from the data in words, and then discuss how these results can be used to justify next steps for your organization. Then you should have an *Introduction*. In this section, you will be speaking with the voice of the role you are occupying. Why are you undertaking this data analysis? What are the variables you will use? What are the charts, tables, and statistics you will generate? Next you should have an *Analysis* section. This is the meat of the report, in which you present your code and data analysis. Lastly, you should have a *Conclusion*, which reframes the questions in the Introduction, rehashes the analysis, and then presents next steps forward. You should also discuss other kinds of analysis which can be done to support your initial conclusions.

## Timeline

- Sep 22 - Project declaration (5%)
    - The first deadline is the project declaration. You need to notify me which project you plan to do. 
- Oct 20 - Project prospectus (10%)
    - The project prospectus outlines what you plan to do on this project. You will need to make decisions for each of these: for the Canadian Tire project [UHH THERE NEEDS TO BE CHOICES HERE], for the Stats Can project, you need to decide on which health outcomes you would like to study, and for the political consultant project, you need to decide on which parties you will analyze. For the prospectus, you will have begun looking at the data for the project, and begun to engage in tentative analysis. Your final report will build directly from the prospectus, so you should start it in a Jupyter Notebook and build from there.
- Nov 17 - Midterm report
    - You will turn in a short report of what you have accomplished on the project since the prospectus deadline and what you have had trouble with. You will also report what you have left to complete on the project.
- Dec 1 - Final report (20%)
    - You will turn the final project in to me by this date.

All submissions will be done through the Learning Portal.

## Notes

*This project will take time.* This is not something which you can put off by the end of the semester. Working with data is hard and always takes more time then you think it will. Even the best data, coming directly from the government (and your instructor), can be messy and complicated. I urge you to have at least one meeting with me during my office hours. 

