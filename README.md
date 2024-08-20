# Exploratory Data Analysis of Museum Website Analytics

## Executive Summary

This exploratory data analysis was completed in July 2021 as a part of my internship with the museum. Identifying information regarding the museum and team members has been omitted. 

I pulled the available Google Analytics data and put all of the data together in Google Sheets. After cleaning that data, I worked to identify and illustrate answers to the following questions:
* **Site Health**: What is the average amount of traffic? Average time spent on the site and specific pages? Average bounce rate?
* **Acquisition**: How are users finding the site? What socials are driving user traffic?
* **Behavior**: What are the most active areas of the site? Least active?
* **User Trends**: Is there a correlation between users and events?

## Business Problem

The museum has been tracking website analytics since July 18, 2020. However, no one has had the time to dive into what the data has to offer. 

After meeting with each member of the Marketing Team, the following requests were identified. 
* Team Member #1 wanted to know more about website traffic and user flow. She also wanted to see if there’s any correlation between traffic and events or trends throughout the months. With this knowledge, she would like to understand how to make the museum more innovative and come up with ways to encourage more donations and young volunteer engagement.
* Team Member #2 wanted to see a comparison of the most active and least active areas of the site. As the site administrator, she would like to potentially change a page if engagement is really low.
* Team Member #3 wanted an analysis of how people find the museum, particularly in regards to the website. For example, are visitors finding the site through organic search or through social media? If social media, which socials?
* Team Member #4 wanted to see a general indication of how the museum is doing. Specifically, the amount of traffic to the site, bounce rate, time on site/pages, social channel baseline and growth. Similar to Team Member #1, he wanted to understand how the museum performs on digital platforms in terms of driving fundraising. He also wanted insights on where to focus efforts and what the top referrals are to the site.

## Methodology

1. Extract data from Google Analytics and clean the data using Google Sheets.

2. Analyze the data, noting engagement peaks for each week and any posts to the museum’s Facebook that could drive traffic to the site that week.

3. Build visualizations and dashboards using Google Sheets to showcase acquisition types, social referrals, views per page, bounce and exit rates, average times spent on pages, and trends in overall user behavior.

## Skills

Google Sheets: calculated columns, data visualization, dashboards, data validation, filters

**At the time of this project, there was just under a year’s worth of data (~53 weeks). If I were to re-do this project in the future, there would be much more data to observe! In this case, I would use SQL queries to complete my analysis and build a dashboard using a platform such as Tableau.*

## Results & Business Recommendations

All findings were summarized in a final presentation given to the Marketing Team. 

These analytics gave the Marketing Team visibility into user behavior of the museum’s website. Using this data, the Marketing Team is now able to understand where to focus their efforts on the website.

**Site Health**

This dashboard from Google Analytics gives a summary of user behavior for our time frame. Users spent an average of 1 minute, 29 seconds on the site, and the average bounce rate was 59.96%.

<p align="center">
    <img width="1506" alt="Screenshot 2024-08-20 at 12 49 48 PM" src="https://github.com/user-attachments/assets/3e2a92ee-b734-410d-80e5-0e2d2c8a1142">
</p>

Further analysis revealed that on average, there were 3,446 page views per month. Users also spent an average of 1 minute, 28 seconds on a page. The daily number of users ranged from 21 users (December 25, 2020) to 990 (May 17, 2021) with an overall average of about 46.65 users per day

**Acquisition**

This bar chart shows that a little more than half of the site’s users got to the website through organic search. Organic search also had the lowest bounce rate.

![Acquisition Overview (% Users + Bounce Rate)](https://github.com/user-attachments/assets/15156e95-1de3-487e-b99a-9f2ee5a827ff)

Email drew the lowest number of users and also had the highest bounce rate. A link to the site is included in all monthly newsletters and in the signatures of all staff, but the data hints that these users are accidentally clicking on these links rather than purposely going to the site.

![% of total vs  Social Network](https://github.com/user-attachments/assets/0db53d77-a500-42e5-8f89-094173a7cabd)

Social media has directed 5.77% of users to the site. The museum’s top 5 social medias, ranked by the percentage of users directed to the site, are:
1. Facebook
   * This is the museum’s top social media in terms of acquisition and its most active social media. 
3. Twitter
4. Yelp
   * It appears that visitors tend to end up on the museum’s website from travel suggestion sites. Perhaps people are searching for activities to do when they come to visit the area.
6. YouTube
   * Although the museum hasn’t posted to YouTube in a while, the channel’s current content consists of oral histories. These viewers are most likely searching for additional information about the channel, whether it be for an educational project or because they’re simply curious.
8. Instagram (Stories)
   * With Instagram’s changing algorithm, perhaps it’s easier to reach viewers through stories than through a post. This is the museum’s second most active social media, but posts are usually the same as Facebook.

**Behavior**

![Pageviews vs  Page](https://github.com/user-attachments/assets/bbf172d5-3b39-45ab-b915-214210322504)

This chart shows the Top 10 Pages of the site, based on pageviews. The most active areas of the site are the Home page, followed by the Exhibitions page, and Donate and Contact are the least active. However, there are more than 10 pages on the site, so it’s worth noting that pages not included, such as the Blog, are not very active.

![Bounce Rate vs  Page](https://github.com/user-attachments/assets/a309ba03-f6a7-4ea3-b1c7-1119757d2bf2)

The Contact page has the highest bounce rate out of the most popular pages, and the Home page has the lowest. 

The museum’s overall site bounce rate is just under 60%, and for Google Analytics optimal bounce rate is typically between 26% and 40%. A high bounce rate is considered bad if the success of the site depends on users viewing more than one page. However, it’s possible for site visitors to get their desired information from a single page.

 ![Avg  Time on Page vs  Page](https://github.com/user-attachments/assets/c7e6fe76-ed99-41eb-bd80-5fd37ccbbb3b)

Users spend the most time on the Contact page, perhaps leaving the page open while they draft an email to the appropriate contact. Users spend the least amount of time on the Exhibitions page, but this page houses the links to all of the individual exhibit pages.

All times spent on a page are all relatively short, but most pages on the site do not contain a lengthy amount of information.

**User Trends**

The dates with the highest number of pageviews are:
* November 5, 2020 -- 366 pageviews
* March 22, 2021 -- 838 pageviews 
* April 9, 2021 -- 842 pageviews (Facebook post: Stop Asian Hate )
* April 10, 20201 -- 911 pageviews (Facebook post: Auction Information)
* May 17, 2021 -- 990 pageviews

Based on this analysis, it does not appear that Facebook posts hold a strong correlation with website traffic when they contain a link to the site.

**Recommendations**

To encourage more donations and young volunteer engagement, donation and volunteer information should be clearly listed on the Home page. Links to their individual pages should be included. In addition, a short little blurb about why donations and volunteer involvement are so important to the museum may help encourage participation! 

Since the museum is interested in expanding its social media presence beyond Facebook and Instagram, the most logical platforms to utilize based on this analysis are Twitter, Yelp, and YouTube. Twitter engagement can be as simple as tweeting out a relevant fact everyday. It might also be beneficial to claim the museum on Yelp and maybe keep tabs on reviews.

In order to provide more specific recommendations, the museum needs to determine what they want users to get out of the website and whether or not that aligns with what users are looking to get out of the website. To figure out what users want, the museum could have a tiny pop-up survey asking users if they are getting the information they’re looking for when visiting the website. This information can then help inform what changes need to be made to increase engagement.

## Next Steps

1. Create a dashboard with 3 key website stats that the Marketing Team should look at every month in the future.

2. Analysis of social media analytics (Facebook, Instagram, Twitter).

3. Customer data strategy analysis (looking at membership, volunteers, potential donors and sponsors, etc.).


