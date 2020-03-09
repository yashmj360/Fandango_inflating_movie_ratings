Note: Refer full python notebook to understand objective, solution and conclusion.

(As per year 2015-16)

# -Fandango-inflating-movie-ratings-
(As per year 2015-16) Fandango inflating movie ratings?

In October 2015, a data journalist named Walt Hickey analyzed movie ratings data and found strong evidence to suggest that Fandango's rating system was biased and dishonest (Fandango is an online movie ratings aggregator). He published his analysis in this article.

Hickey found that there's a significant discrepancy between the number of stars displayed to users and the actual rating, which he was able to find in the HTML of the page. He was able to find that:

The actual rating was almost always rounded up to the nearest half-star. For instance, a 4.1 movie would be rounded off to 4.5 stars, not to 4 stars, as you may expect.
In the case of 8% of the ratings analyzed, the rounding up was done to the nearest whole star. For instance, a 4.5 rating would be rounded off to 5 stars.
For one movie rating, the rounding off was completely bizarre: from a rating of 4 in the HTML of the page to a displayed rating of 5 stars.
## Objective :
We'll analyze more recent movie ratings data to determine whether there has been any change in Fandango's rating system after Hickey's analysis.

## Solution:
One of the best ways to figure out whether there has been any change in Fandango's rating system after Hickey's analysis is to compare the system's characteristics previous and after the analysis. Fortunately, we have ready-made data for both these periods of time:

Walt Hickey made the data he analyzed publicly available on GitHub. We'll use the data he collected to analyze the characteristics of Fandango's rating system previous to his analysis.

We have ratings for movies released in 2016 and 2017. The data is publicly available on GitHub and we'll use it to analyze the rating system's characteristics after Hickey's analysis.

## Conclusion:
Our analysis showed that there's indeed a slight difference between Fandango's ratings for popular movies in 2015 and Fandango's ratings for popular movies in 2016. We also determined that, on average, popular movies released in 2016 were rated lower on Fandango than popular movies released in 2015.

Mode above we calculated clearly shows that in year 2015, there were more 4.5 rated movies. While in year 2016, there are more 4 rated movies. This mean, there is definitly some improvement in system of Fandango. But we can't be so much sure as we can't see the rounding technique Fandango is following now, as ratings can't be seen using HTML tag.
