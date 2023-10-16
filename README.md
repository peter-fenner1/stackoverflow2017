# stackoverflow2017
This repository is for Project 1 of the Undacity Data Science for Scientists nanodegree.

## Project Aim
The goal of the project is to ask questions with business or real-world applications, and analyse a publically available dataset to find insights to answer these questions. I decided to analyse the results of the 2017 Stack Overflow Annual Developer Survey for insights to help people answer the question "Is a career in technology right for me?" I decided to do this by searching for relationships between personality and career success in order to answer the following three questions:

- How does personality relate to employability?
- How does personality relate to salary?
- How does personality relate to job satisfaction?

As a measurement of personality, I analysed the responses to several "agree/disagree" type questions.

## Analysis
I started by plotting the distribution of responses for 20 "agree/disagree" type questions, as shown in the following bar charts:

![Distrubution of responses to 20 "agree/disagree" type questions](https://github.com/peter-fenner1/stackoverflow2017/blob/main/images/response_distribution.png)

For my analysis I wanted to use questions with a fairly even distribution of responses, to give me a better distribution of data to use for finding correlations. As such, I decided to use the following 10 questions:

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

## Results

After processing and cleaning the data, the results for the question "How does personality relate to employability?" are as follows:

![relationships between personality metrics and employability](https://github.com/peter-fenner1/stackoverflow2017/blob/main/images/employability.png)

This suggests that there is perhaps a positive correlation with ShipIt and EnjoyDebugging, and a negative correlation with CompetePeers. However, none of the graphs are strictly increasing or decreasing (although CompetePeers comes close), so I don't think we can be confident that any of these factors have a significant effect on employability.

The results for the question "How does personality relate to salary?" are as follows:

![relationships between personality metrics and salary](https://github.com/peter-fenner1/stackoverflow2017/blob/main/images/salary.png)

This shows a pretty clear negative correlation with RightWrongWay and OtherPeoplesCode. The data also suggests, although less strongly, a negative correlation with BoringDetails and a positive correlation with ShipIt.

Finally, the results for the question "How does personality relate to job satisfaction?" are as follows:

![relationships between personality metrics and job_satisfaction](https://github.com/peter-fenner1/stackoverflow2017/blob/main/images/satisfaction.png)

This data shows a pretty clear negative correlation with BoringDetails, OtherPeoplesCode and ProjectManagement, and it also suggests a positive correlation with DiversityImportant and EnjoyDebugging.
