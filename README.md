# Y.Music
As an analyst at Y.Music Company, I test some hypothesis to compare user's preference.

Every time we conduct research, we need to formulate a hypothesis that we could test. Sometimes we accept this hypothesis, but sometimes we also reject it. To generate informed decisions, a business must be able to understand whether its assumptions are true or not.

In this project, I will compare music preferences in the cities of Springfield and Shelbyville. You will learn from the actual Y.Music data to test the following hypothesis and compare user behavior in both cities.

## Goals
Testing three hypothesis:

1. Users activity varies depending on the day and the city.
2. On Monday morning, residents of Springfield and Shelbyville listen to different genres. This also valid to Friday night.
3. Users in Springfield and Shelbyville have different preferences. In Springfield, they prefer pop music, while in Shelbyville, rap music has more fans.

## Steps
The data related to users behavior is stored in the file /datasets/music_project_en.csv. There is no information available regarding the quality of the data, therefore it is necessary to first examine it before testing any hypotheses.

Firstly, I will evaluate the data quality and determine if there any issues are significant. Then, during the data pre-processing stage, I will attempt to address the most serious problems.

This projects will consist of 3 steps:

1. Data Overview
2. Preprocessing Data
3. Testing the Hypothesis

## Conclusion

We have tested the following three hypotheses:

1. User activities in Springfield and Shelbyville depend on the day of the week, although these two cities vary in various ways.
2. On Monday morning, residents of Springfield and Shelbyville listen to different genres. This also applies to Friday night.
3. Listeners in Springfield and Shelbyville have different preferences. In both Springfield and Shelbyville, they prefer pop music.

After analyzing the available data, we can conclude that:

* User activities in Springfield and Shelbyville depend on the day, even though the cities are different. The first hypothesis can be fully accepted.

* Music preferences do not vary significantly throughout the week in Springfield and Shelbyville. We can see small differences in the order on Monday, but: In both Springfield and Shelbyville, users mostly listen to pop music. Therefore, this hypothesis cannot be accepted. It is also important to note that the obtained results may differ if we do not have missing values.

* It turns out that the music preferences of users from Springfield and Shelbyville are very similar.
The third hypothesis is rejected. If there are differences in preferences, unfortunately, we cannot determine this from this data.

## Future Work

More thorough statistical hypothesis testing would be beneficial in the future to provide more precise and quantitative results. This could lead to more refined and reliable insights about user behavior and preferences.
