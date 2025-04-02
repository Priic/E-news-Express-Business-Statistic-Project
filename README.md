# E-news-Express-Business-Statistic-Project

![AbTesting](https://github.com/user-attachments/assets/c9bcddbf-22b7-4741-ac40-a8d0ca6eda18)
Image by Freepik

## Business Context

The advent of e-news, or electronic news, portals has offered us a great opportunity to quickly get updates on the day-to-day events occurring globally. The information on these portals is retrieved electronically from online databases, processed using a variety of software, and then transmitted to the users. There are multiple advantages of transmitting new electronically, like faster access to the content and the ability to utilize different technologies such as audio, graphics, video, and other interactive elements that are either not being used or aren’t common yet in traditional newspapers.

**`E-news Express is an online news portal`**, aims to expand its business by acquiring new subscribers. They provide faster access to the high-quality engaging content utilizing different technologies such as audio, graphics, video, and other interactive elements.
The dataset we have analyzed here consists of **`100 randomly selected users`** containg informations about `user id`, `two groups (control and treatment)` ,`time spent on page (in minutes)` on `landing page (old/new)` by `different language users (English,French and Spanish)` and their `conversion status(Yes/No)`. The users are divided equally into 2 groups. The **`existing landing page`** was introduced to `first group (control)` while  `second group (treatment)` served the **`new landing page`**. 

[Companies often analyze user responses to two variants of a product to decide which of the two variants is more effective. This experimental technique, known as A/B testing, is used to determine whether a new feature attracts users based on a chosen metric.]

## Objective

The design team of the company has researched and created a new landing page that has a new outline & more relevant content shown compared to the old page. In order to test the effectiveness of the new landing page in gathering new subscribers, the Data Science team conducted an experiment by randomly selecting 100 users and dividing them equally into two groups. The existing landing page was served to the first group (control group) and the new landing page to the second group (treatment group). Data regarding the interaction of users in both groups with the two versions of the landing page was collected. 
The main idea of this analysis is to explore the data and perform a **`statistical analysis (at a significance level of 5%)`** to determine the effectiveness of the new landing page in gathering new subscribers for the news portal by answering the following questions:

1. Do the users spend more time on the new landing page than on the existing landing page?
2. Is the conversion rate (the proportion of users who visit the landing page and get converted) for the new page greater than the conversion rate for the old page?
3. Does the converted status depend on the preferred language? 
4. Is the time spent on the new page the same for the different language users?
   
## Analysis Approach

As a Data Scientist, 
1. I explored the dataset to understand its **`shape, size, data types, missing values, duplicates, and statistical summary`**.
2. Conducted **`Exploratory Data Analysis (EDA)`** to understand the interaction of users in both the groups with the two versions of the landing page.
3. Performed  **`Statistical analysis(Hypothesis testing)`** where I defined `null and alternative hypotheses`, applied statistical tests like **`Chi-Square, ANOVA, and Two-Proportion Z-test`** to validate 
   differences in user engagement and conversion rates and finally used **`p-value analysis`** to determine statistical significance, ensuring results were not due to chance.

## Data Dictionary

The data contains information regarding the interaction of users in both groups with the two versions of the landing page.

1. `user_id `- Unique user ID of the person visiting the website

2. `group `- Whether the user belongs to the first group (control) or the second group (treatment)

3. `landing_page` - Whether the landing page is new or old

4. `time_spent_on_the_page `- Time (in minutes) spent by the user on the landing page

5. `converted` - Whether the user gets converted to a subscriber of the news portal or not

6. `language_preferred` - Language chosen by the user to view the landing page
   
