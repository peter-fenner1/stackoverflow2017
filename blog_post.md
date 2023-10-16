# Is a career in technology right for you?

![Header image](https://github.com/peter-fenner1/stackoverflow2017/blob/main/images/technology_career.jpeg)

### Introduction

With modern technology developing at a rapid rate, ever growing numbers of people are considering a career in technology. The reasons for considering a tech career are almost as numerous as the many career paths available in the technology sector. You might be eager to be at the forefront of innovation, transforming industries and improving lives through the power of technology. Maybe you want a job which is intellectually stimulating and offers the opportunity to solve complex problems on a daily basis. Or perhaps the consistently high demand for individuals who can develop and maintain technological solutions - and the competitive salaries and job security which come as a result - is what appeals to you.

Of course, a career in technology isn't for everybody. The field of technology is constantly evolving, so those without a keen interest in the subject might find it difficult to keep up with the fast-paced nature of the industry. Tight deadlines and complex projects can be stressful for those who aren't skilled at managing their time. Large amounts of time spent working with machines might not be appealing to more people-oriented individuals.

As such, it is important for anyone considering a technology career to carefully consider whether it is a good fit for their own personality. To this end, I have used data from Stackoverflow's Annual Developer Survey to investigate the relationship between career success and personality, with the goal of helping you decide if a career in technology is for you.

### Asking the right question

My goal is to investigate the relationship between career success and personality. However there are several ways to measure career success and many different ways to gauge personality, so the first step was to decide exactly what question I am asking.

The dataset I have chosen to use comes from the results of Stackoverflow’s 2017 Annual Developer Survey. It asks participants more than 150 questions about their background, their education, their career, and their use of technology, both professionally and as a hobby.

In the survey I identified four questions which I think make good measurements of career success:

- Which of the following best describes your current employment status?
- Career satisfaction rating
- Job satisfaction rating
- What is your current annual base salary, before taxes, and excluding bonuses, grants, or other compensation?

The responses to the first question give a measure of employability. I combined the responses to the second and third questions to measure satisfaction. The third question asks for the participant's salary, which can be considered a direct measure of success.

I therefore aim to answer the three questions:

- How does personality relate to employability in a technology career?
- How does personality relate to salary in a technology career?
- How does personality relate to job satisfaction in a technology career?

Many questions in the survey described aspects of the participant's personality and asked how strongly they agree or disagree. I chose ten of these questions to use as my measurement of personality. The ten questions I chose were:

- I tend to get bored by implementation details
- Diversity in the workplace is important
- There's a right and a wrong way to do everything
- I think of myself as competing with my peers
- I want to change the world
- It's better to ship now and optimize later
- Maintaining other people's code is a form of torture
- Most project management techniques are useless
- I enjoy debugging code
- It's harder to collaborate with remote peers than those on site

### Question 1: How does personality relate to employability in a technology career?

For each of the five possible responses to each question - Strongly disagree, Disagree, Somewhat agree, Agree, Strongly agree - I measured the percentage of people giving that response who were currently employed. The results for each of the ten questions are shown in this graph:

![relationships between personality metrics and employability](https://github.com/peter-fenner1/stackoverflow2017/blob/main/images/employability_perc.png)

Out of the three questions, these are the results which were least conclusive. Many of the graphs have a hump in the middle and drop off at the extremes, suggesting that people without strong opinions on the statements are more employable. However, these hump shapes make it hard to see many clear trends.

I think the biggest correlation here is that people who disagreed with the statement "I think of myself as competing with my peers" were more likely to successfully find employment. The only other correlations which look significant to me are that people who agreed with the statments "It's better to ship now and optimize later" and "I enjoy debugging code" seemed to also have higher employability. This suggests that it is best to not be too competitive, and that it's good to know when something is "good enough for now". It's not very surprising that people who enjoy debugging code are more likely to get hired, as this is a large part of a tech job.

### Question 2: How does personality relate to salary in a technology career?

For this question I took the average salary for the participants giving each of the five responses. The results are shown in this graph:

![relationships between personality metrics and salary](https://github.com/peter-fenner1/stackoverflow2017/blob/main/images/salary.png)

These graphs show some clear trends for some of the questions. People who disagreed with the statements "There's a right and a wrong way to do everything" and "Maintaining other people's code is a form of torture" were receiving significantly higher salaries than those who agreed with the statements. To me, this suggests that openness to different methods and willingness to cooperate are important personality traits for success in a technology career.

People who agreed with the statement "It's better to ship now and optimize later" also received higher salaries, although those who strongly agreed were earning a little less than those who simply agreed.

### Question 3: How does personality relate to job satisfaction in a technology career?

Survey participants were asked to rate both their job satisfaction and career satisfaction on a scale of 1 to 10. For this question I averaged over these two responses to get an overall satisfaction. The following graph shows how satisfaction related to the responses to the personality questions:

![relationships between personality metrics and satisfaction](https://github.com/peter-fenner1/stackoverflow2017/blob/main/images/satisfaction.png)

Again there are some pretty clear trends. People who disagreed with the statements "I tend to get bored by implementation details", "Maintaining other people's code is a form of torture" and "Most project management techniques are useless" tend to be more satisfied with their jobs. This shows that it is important to be willing to cooperate, both with other coders and with project managers, and that it is also important to not bore easily.

People who agreed with the statement "Diversity in the workplace is important" were also typically more satisfied with their jobs. This suggests that technology workplaces typically have a lot of diversity, so people who appreciate the importance of this diversity with have a better experience. Unsurprisingly, people who enjoy debugging code had a high degree of job satisfaction.

### Conclusion

In this blog post I found some links between job success and personality, using data from the Stackoverflow 2017 Annual Developer Survey. I did this by finding relationships between responses to several personality-based questions and three factors of success: employability, salary, and job satisfaction.

When looking to relate survey responses to employability the results weren't very conclusive, but did suggest that it's best to not be too competitive, and that having strong opinions in either direction might harm your employability.

We found some links between personality and salary, namely that openness to different methods and willingness to compromise were good indicators of a higher salary.

We also found links with job satisfaction, which suggested that people who bore easily might have less satisfaction in a tech career, whereas those who appreciate diversity are more likely to be satisfied.

Of course, there are many other aspects of personality which could be investigated, and many more correlations to be found. If you think a career in technology might be for you, then performing your own investigation might be the perfect way to test your skills!
