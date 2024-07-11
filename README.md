# Introduction 
By delving into the data of Data Analyst Duo's Instagram account (@dataanalystduo), the aim is to uncover valuable insights into the performance of various post types. The duo's substantial following of around 104,000 followers provides a robust dataset for analysis. Leveraging this information, we will design a comprehensive dashboard that not only captures engagement metrics but also highlights trends and patterns in post effectiveness.

This data-driven approach aligns with the growing emphasis on leveraging analytics to enhance digital presence. Given the current surge in demand for data analysts in India, which has a significant demand for data analysts, leading to 97,000 annual job vacancies. This spike is fueled by a 45% increase in data analyst positions across diverse industries. The impressive growth of data analytics in India is linked to a doubled internet penetration from 20% to 41% in 2018-19, and an expected addition of 900 million users by 2025 the project underscores the practical application of analytical skills in understanding and optimizing social media engagement. Through our analysis, we anticipate offering actionable recommendations to Data Analyst Duo, empowering them to refine their Instagram strategy for even greater impact and resonance with their audience. 

# Objective of the project

     1.To identify the media type with the highest engagement rate among the audience on Data Analyst Duo's Instagram account. 

Reason - Considering that Reels reportedly exhibit the highest reach rate among all media types on Instagram, our goal is to examine and determine which specific media format resonates most effectively with the followers of Data Analyst Duo. This analysis aims to provide actionable insights into optimizing content strategy, aligning with the goal of maximizing audience engagement on the Instagram platform.

     2.The objective is to discern which types of posts on Data Analyst Duo's Instagram account higher audience engagement across various metrics, namely likes, shares, comments, and saves. 

Reason - By delving into the specific characteristics of each post type, our aim is to understand the nuanced preferences of the audience and unravel the factors contributing to heightened engagement in each metric category. This analysis is crucial for tailoring content strategies, as it provides insights into the unique aspects that resonate with the audience, ultimately enhancing the effectiveness of the Instagram account's engagement tactics.

      3.Our objective is to analyze the trend in follower growth for Data Analyst Duo on Instagram, aiming to pinpoint the key periods of increase or decrease. 

Reason - By delving into these patterns, we seek to understand the underlying reasons behind fluctuations in follower numbers. This analysis is essential to uncover the factors driving growth and to identify potential challenges that may contribute to declines. The insights gained will facilitate informed decision-making, allowing us to capitalize on successful strategies and address areas that may require attention, ultimately optimizing the account's follower trajectory.



# DATA CLEANING AND PREPARATION 

1.Consolidating the datasets

To thoroughly examine each category and compile the report, initiated the analysis using data from December 1, 2022, as the starting point. This approach ensures a consistent timeline for both datasets. To enhance data cleanliness, we employed the text-to-column function during the processing phase.

2.Exploring the Relationship Between Reach and Profile Visits

In this analysis, our focus was on unraveling any potential direct relationship between the reach and profile visits on the Instagram account. Leveraging pivot tables for meticulous data organization, we crafted a line chart to visually represent the correlation between these two key metrics. 

3.Unveiling Demographic Patterns: Gender and Geographic Distribution of Total Followers

To gain insights into the composition of total followers, our analysis delved into two key aspects: gender distribution and geographic representation. For gender distribution, we employed bar and pie charts to visualize the proportions of followers across different genders. Simultaneously, in understanding the geographic distribution among states in India, we utilized a dynamic India map visualization. Employing the text-to-column function streamlined data processing, ensuring accuracy in portraying both gender and state-wise follower distributions. This dual approach provides a comprehensive overview of the audience demographics, aiding in targeted content strategies and audience engagement efforts.

4.Streamlining Data Integration: Utilizing VLOOKUP and XLOOKUP Functions

In the process of consolidating disparate datasets, we harnessed the power of VLOOKUP and XLOOKUP functions. These functions proved instrumental in seamlessly merging multiple datasets into a single sheet, enhancing clarity for both comprehension and calculation purposes. VLOOKUP efficiently matched and retrieved corresponding data points, while XLOOKUP, with its advanced capabilities, contributed to a more robust and dynamic consolidation process. This strategic use of functions aimed to simplify the understanding of interconnected data sets and facilitate streamlined calculations for a more comprehensive analysis.

5. Comprehensive Metrics Analysis: Retention Rate, Engagement Rate, and Growth Rate Calculations

Description:
This section delves into the meticulous calculation of three pivotal metrics—Retention Rate, Engagement Rate, and Growth Rate—each contributing unique insights into the performance and expansion of the Instagram account.

Retention Rate Calculation:
	The Retention Rate was computed by evaluating three views for each post (specifically Reels) divided by the impressions for the respective post. This formula illuminates the extent of audience retention, providing a nuanced understanding of content stickiness.

Engagement Rate Calculation:
	The Engagement Rate computation involved summing up the four key engagement metrics (likes, shares, comments, saves) and dividing the total by the reach, multiplied by 100. This metric offers a holistic measure of audience engagement, encapsulating various forms of interaction with the content.

Calculation of Total Followers:
	To determine the total followers as of December 1, 2022, we subtracted the sum of new Instagram followers from December 1, 2022, to October 26, 2023, from the total followers count on October 27, 2023. Subsequent daily total follower counts were then calculated by adding the 'New Instagram Followers' on each respective day.

Growth Rate Calculation:
	The Growth Rate was derived using the formula: (Current Rate - Previous Rate) / Previous Rate. This metric quantifies the rate of expansion or contraction, providing a dynamic indicator of the account's growth trajectory over time.

 #  Analysis and Insights

# Engagement among different types of post
 
 ![image](https://github.com/bsamirtha/Excel-Data-Analysis-for-Enhanced-Business-Decision-/assets/175279461/d094d0a1-5b14-4735-929d-93be6e991546) 


•	Engagement Insights: Unveiling Audience Attraction
   
   Observing the engagement metrics, it becomes evident that Instagram Reels exhibit the highest reach, emphasizing a substantial audience attraction. Interestingly, Instagram Carousels, particularly those with 
   25 posts, showcase the highest interaction in terms of comments, demonstrating a noteworthy level of engagement. Although Carousels may have a lower reach compared to Reels, they excel in actively engaging the 
   audience. In contrast, Instagram Images maintain a moderate engagement rate of 5%, showcasing a consistent level of interaction.

•	Content Interactions: Reels Taking the Lead

   Analyzing content interactions, it is apparent that Instagram Reels command a higher engagement metric compared to other post types.

•	Retention Rates: A Reels Exclusive Metric

   Retention rates exclusively apply to Instagram Reels, revealing a commendable rate of 9%. In summary, Reels outperform other post types, showcasing a slightly lower engagement rate than Carousels but excelling 
   in audience retention.

# Engagement Among duration bins (>30 secs & <30 secs)

   ![image](https://github.com/bsamirtha/Excel-Data-Analysis-for-Enhanced-Business-Decision-/assets/175279461/87050e81-212e-4060-bc36-eab2b866ead9)



    
   
     









