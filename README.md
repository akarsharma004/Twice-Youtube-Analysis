# Twice Youtube Analysis

## Project Overview:
**Background:**
    TWICE, a popular K-Pop music group, has seen a significant rise in global popularity. To maintain this momentum and cater to their expanding fanbase, it's crucial to understand their audience's preferences and content consumption habits on YouTube.

**Objective:** 
    This data analysis project aims to leverage insights from TWICE's official YouTube channel to optimize their content strategy and maximize engagement with their global audience.

## Data Sources and tool use:
* All analysis is conducted using python. Twice youtube data is exttracted using the Youtube API. pandas, numpy for basic inspection , feature engineering and eda and matplotlib, seaborn for data visualization are use to analyse the data.
* twice_vid dataset comprises unique video IDs and corresponding video types.

## Data Extraction and cleaning:
* YouTube data was extracted from three channels: JYP Entertainment, TWICE Official, and TWICE Japan Official. Collected information included video title, publish date, duration, view, like, and comment counts, as well as the originating channel.
* An initial analysis identified 2241 videos across all channels.
* Features were assigned appropriate data types.
* The twice_vid dataset was used to categorize videos into eras (albums), special types, and video types, creating three new features.
* Missing values for views, likes, and comments were imputed using the mode.

## Exploratory Data Analysis
* TWICE's content is spread across 3 YouTube channels, with the official channel hosting the majority of its 1,500+ video library.
* Over 330 videos belong to top-performing eras, while 'Twice TV' and 'Time To Twice' together comprise over 280 videos.
* Challenge, Preview, Behind-the-Scenes, and Activity videos collectively account for nearly 1,800 videos. Jihyo and Nayeon have over 150 associated videos each, significantly more than Jeongyeon and Tzuyu.
* 2023 was the peak year for uploads (likely due to growing popularity), with Fridays as the busiest day and weekends as the slowest.
* Average video garners 7.5 million views and 1.8 million likes/comments, though outliers reach 798 million views and 7 million likes/comments.
* A shift towards shorter videos (average under 2000 seconds) is evident, likely influenced by YouTube Shorts.
* Music and performance videos excel in views and duration, while highlights and previews underperform. Era and special performance also vary widely.

## Conclusion:
TWICE's YouTube channel is a powerhouse of content, characterized by high viewership and engagement. The group's strategic content distribution and consistent output have contributed to its substantial online following. However, there's significant variation in video performance across different categories, eras, and specials. Identifying factors driving this variation is crucial for optimizing future content strategy.

## Suggestion:
To further enhance TWICE's YouTube presence, a deep dive into the performance metrics of specific eras, video categories, and member-focused content is recommended. Understanding the audience preferences and trends can inform content creation and scheduling. Additionally, leveraging the success of high-performing content formats and exploring new short-form video opportunities can help maintain and grow the fanbase.
