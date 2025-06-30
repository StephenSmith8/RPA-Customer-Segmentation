# RPA-Customer-Segmentation

The purpose of this project is to help the marketing department of fictional company Reputable Product Agency (RPA) segment its user base using SQL queries. By dividing users into groups based on specific criteria, such as birth year or campaign participation, the project enables personalized marketing and performance analysis. 

The project included the query requirements below:

- Start by getting a feel for the users table. What are the column names?
- The marketing department wants to send a Born in the ‘80s email to the appropriate users. Find the email addresses and birthdays of users whose birthday is between 1980-01-01 and 1989-12-31.
- We are interested in the group of users that signed up prior to May 2017.Find the emails and creation date of users whose created_at date matches this condition.
- There was an A/B test performed on users that used cute animal clipart to encourage users to sign up. We’d like to see how the group that was shown ‘bears’ is performing. Find the emails of the users who received the ‘bears’ test.
- A total of 4 advertising campaigns were run over this period. There were two sets of ad copy (set 1 and set 2) and both were run on two search engine sites (AAA and BBB).
The resulting campaign values are:
  - AAA-1
  - AAA-2
  - BBB-1
  - BBB-2
Find all the emails of all users who received a campaign on website BBB.
- Find all the emails of all users who received ad copy 2 in their campaign.
- Find the emails for all users who received both a campaign and a test. These users will have non-empty entries in the campaign and test columns.
