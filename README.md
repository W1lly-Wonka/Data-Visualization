# __Data Visualization__

HR Analytics Data Visualization

## __Background__

Good data visualization can help us understand what kind of information is contained in a dataset, can extract information from it, help in identifying patterns. Data visualization can also help if there is a lack of understanding of a field of study or a lack of domain knowledge, or simply wants to check the data for further steps such as data pre-processing. On this occasion, I will try to do data visualization of the hr case. 

## __Context and Content__

A company which is active in Big Data and Data Science wants to hire data scientists among people who successfully pass some courses which conduct by the company. Many people signup for their training. Company wants to know which of these candidates are really wants to work for the company after training or looking for a new employment because it helps to reduce the cost and time as well as the quality of training or planning the courses and categorization of candidates. Information related to demographics, education, experience are in hands from candidates signup and enrollment.

## __Objective__

Find any patterns related to the dataset, preferably for business purposes.

## __Findings and Discussions__

<img src='/Visualizations/candidate percentage.png'>

It can be seen that our data has an imbalanced amount of data, between classes that will not change jobs and those that will change. So, when we are going to visualize this data, be careful not to jump to conclusions directly, as it will cause bias

<img src='/Visualizations/city vs cdi.png'>

In general, candidates come from pretty decent cities. This is indicated by the index of cities that are classified as decent, where most of them are above 0.7 .

<img src='/Visualizations/gender vs cdi.png'>

For those who come from a city that is pretty decent, most of them are men. 

<img src='/Visualizations/relevant experience vs experience.png'>

This is interesting, because it turns out that most of the participants that have relevant experience with what the company needs, many of whom already have more than 20 years of working experience. This begs for questionable reason behind their participation in the training session. 

<img src='/Visualizations/edu level vs relevant exp.png'>

Graduates hold the most for being having relevant experience regarding the field. 

<img src='/Visualizations/com size vs rel exp.png'>

As for the trend among candidates with relevant experience, it can be seen in the graph above that, most of those with relevant experience, comes from small companies, which only have 50 - 99 employees.

<img src='/Visualizations/com size vs com type.png'>

And, most of them, come from a private limited company.

<img src='/Visualizations/enrollment courses vs ed level.png'>

Where, most of them, when applying for jobs and training in this company, is not taking other courses from some university. Therefore, they can be focused on the training the company provided.

<img src='/Visualizations/ed level vs training hours.png'>

However, in terms of the number of hours of training completed, there was almost no significant difference among all levels of education. Where the number of hours ranges from 60 - 70 hours

<img src='/Visualizations/major dis vs ed level.png'>

Most graduates and masters, come from STEM. This is in line with the needs of the company that engaged in data science.

<img src='/Visualizations/major dis vs exp.png'>

Where the experience they have varies, but those who have the most work experience come from STEM.

<img src='/Visualizations/Last new job vs Major dis.png'>

Surprisingly, most of the workers, only have a 1-year difference between their previous job and current job.

## __Conclusions__

These visualizations are just a preliminary action, before we're going to take a deeper understanding of the data, there's still a lot of room for improvement. Because there are some of the questions that need further investigation. Such as the reason behind their participation in the training session, even though they have more than 20 years of experience.
