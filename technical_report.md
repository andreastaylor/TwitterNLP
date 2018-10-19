### Problem Statment
Social media is such a large landscape these days that it’s hard to get a grasp on exactly how big of a footprint it has grown into. [Twitter](https://twitter.com/) users in 2010 had a very different experience than they do today because the number of users has grown ten fold to 300 million since then. It is now a staple of promotion and marketing as well as being a social media site. There is a short list of people including Jennifer Lawerence, Emma Thompson and George Clooney that do not use Twitter but overall anyone who is anyone has an account. This includes corporations and government entities. Never before has there been so much self reported data. For this project my goal is to be able to gain insight about what people are saying and who they are saying it too using unsupervised learning and network visualizations. Topic modeling is useful when there is not an understanding of the grouping or topics of text. Twitter data is an opportunity to reveal patterns and connections the would be simply impossible to do for humans. While we may be able to relate to individual topics and themes there is a huge barrier to overall understanding posed by 300,000 short text bodies. My goal is to make the themes and interactions clearer all starting with a single user account. The commercial/promotional implications of such an analysis is not directly stated but implied. 

### Data Collection


Tweets were pulled from the [Twitter API](https://developer.twitter.com/) based on username using the [Tweepy](http://www.tweepy.org/) package. Access to the Twitter API is granted through a [developer account](https://developer.twitter.com/en/apply-for-access.html) which requires writing a 300 word statement on intended use. As a starting point I choose a journalist that I know little about other than he works [WIRED](https://www.wired.com/) magazine. After looking at ~3200 tweets I take the 100 top mentions from the individuals account and collect those tweets for a total of ~320,000 individual communications. All of the information gathered for network analysis was taken from the text body in relation to it’s author.

### Exploratory Data Analysis 

Tweets from the central user’s account were collected and a frequency chart gives us a sense of his comment distribution. His number one mention is WIRED which is his employer. The second is another wired journalist. 

![Useful stars](https://github.com/DataSnek/TwitterNLP/pics/freq1.png)

Looking at a sample of distributions from a sample of top mentions you can start to get a sense of the social network becasue almost all of them mention at least 3 of the other users.

![Useful stars](https://github.com/DataSnek/TwitterNLP/pics/freq2.png)

