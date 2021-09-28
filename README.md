# game_sales_analysis_project

We have received historical data on video games sales from the online store Ice. This data includes extensive information on popular games, including sales numbers from varios geographical regions, expert reviews, and Entertainment Software Rating Board (ESRB) ratings. Using this information, we attempt to identify patterns that determine whether a game succeeds or not; this information allows us to spot potential 'hit' games and plan advertisement campaigns accordingly. This analysis was conducted with the overall goal of planning an effective advertisement campaign for 2017. 

**Conclusion**: The overall goal of this project has been to identify patterns and trends that we can use to plan an effective game-advertisement campaign for 2017. Based on our various analyses, we've been able to conclude the following:

    Not all data included in the original data set is relevant to our task. Given that most platforms included in the dataset are long obsolete, we believe that it is most appropriate to focus on those platforms for which games were still being released in 2016. Additionally, we concluded that, to better reflect the current game market, it would be best to examine data for games released after, or near the end, of the late-2000s financial crisis.

    Based on our calculations, it takes around 6 years for a platform to become obsolete.

    Currently, the Playstation 4 and Xbox One are leading in sales. Since 2013, each platform for which games were released in 2016, other than the Playstation 4 and Xbox One, had their total yearly sales decline year over year. The Playstation 4 and Xbox One saw sales increase yearly from 2013 to 2015.

    There are significant differences in global game sales broken down by platform. For example, the median 'total_sales' values for Xbox 360 games is highest, while the value for Playstation Vita games is lowest. Between these two, we found the mean 'total_sales' value is much higher for Xbox 360 games than the Playstation Vita. We tested the hypothesis that there is no difference in the mean 'total_sales' values for games of each platform using a two-sample t-test; based on our p-value, we rejected this null hypothesis.

    While there is no correlation between user ratings and game sales, we found that there is a medium positive correlation between critic ratings and game sales.

    For cross-platform games released on the Playstation 4, which was the most popular console in 2016, the Playstation 4 version of the game tends to generate more revenue than versions for other platforms. The exception to this are for Playstation 3 and Xbox 360 versions of the same game; however, we believe this may be explained by the Playstation 4 being a newer consoles and consoles often being backwards compatible.

    In terms of mean and median 'total_sales' values for games for each genre, games of the 'shooter' genre are most profitable, followed by platform and sports games. In terms of overall revenue generated within the time-period represented in our data set, action games are the most profitable, having generated 31% of all revenue from game sales. The genre that generated the least revenue is 'puzzle'.

    Xbox and Playstation games are, by far, the most popular in North America and Europe. In Japan, games released for the Nintendo 3DS make up the largest market share (approximately half).

    In North America and Europe, games of the 'action' and 'shooter' genres are the most popular. In Japan, 'role-playing' is the most popular game genre. Along similar lines, 'mature' rated games generate, by far, more revenue than games of other genres in North America and Europe; however, in Japan such games generate the least revenue of all genres represented in our data set.

    The difference in mean user ratings between games for the Xbox One and PC is not significant enough to warrant rejecting the null hypothesis - that is, that there is no difference in mean user ratings for for each platform. That being said, the difference in mean user ratings for games of the 'shooter' and 'action' genres is substantial enough to warrant rejecting the relevant null hypothesis, which holds that there is no difference in mean user ratings between those genres.

Based on these findings, we offered several recommendations to ensure that the 2017 advertising campaign is a success. These recommendations may be summarized as follows:

1) For advertising campaigns within North America and Europe, it would be best to focus on 'mature' rated action and shooter games produced for the Playstation 4 or Xbox One. For campaigns in Japan, it would be best to focus on 'teen' rated role-playing games produced for the Nintendo 3DS.

2) Favor advertising games with high critic scores over those with low (or no) scores. If a game has not been released yet and advertisers expect it to be a 'hit', it would be in their best interest to try to get the game critially reviewed prior to releasing an advertisement. If the game doesn't receive high scores, it might be best to look towards different games that do receive higher scores.

3) If advertisers must decide which version of a cross-platform game they should advertise, they should chose the Playstation 4 version, if available.

4) With regard to games by genre, advertisers should focus on shooting and action games and steer clear of puzzle games. If the choice is between an action game or a sports game, we believe it would be more profitable to advertise the action game.

Assuming that advertisers receive a portion of the profits generated by sales of the games they advertise, we believe that taking the abovementioned points into consideration and following the recommendations when planning an advertising campaign would help advertisers chose games that may potentially become 'hits'.
