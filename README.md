# Winning-Jeopardy

In this project, I used a data set about competition questions which was obtained from the TV show, Jeopardy. 
Participants answer questions and win money in this TV show. I used the data set to figure out types and frequency of subjects of questions to be successful in 
the competition.
The data has text entries. Before I started to explore the data set, I had normalized the entries by setting a function. After that, I made an exploratory 
analysis and
feature engineering on the data. I detected how often the questions repeat. I set another function to detect terms which are used in the questions. 
In this function, I cleaned questions from words which are less than 6 characters. I split questions to the words, and I counted the amount of words. 
I used chi-squared test to determine high value terms. 

## Conclusion

When I applied to chi-squared test, I did not get any significant differences between high value terms and low value terms. 
The frequencies were lower than 5. It means the chi-squared test is not valid to use on these terms.
