# Analyzing-Customer-Segments-Python

## Background
You are a data analyst at a crowdfunding site. For the next quarter, your company will be running a marketing campaign.
The marketing manager wants to target those segments that have donated the most in the past year. 
She turned to you to help her with her upcoming meeting with the CEO.

## Your challenge
Create a single visualization that the marketing manager can use to explore the data. Include:

What are the top three categories in terms of total donations?
What device type has historically provided the most contributions?
What age bracket should the campaign target?

# Report 
## 1. What are the top three categories in terms of total donations? 

In the dataframe the three most common categories entries are Sports with 4179, Games - 4173 and Technology - 4144, but in terms of total donations the top three are:
- **Games** with 16.54k €
- **Sports** with 16.35k €
- **Technology** with 16.27k €

In both categories Enviroment and Fashion are close in the gap (Enviroment with 4089 and 16.23k, Fashion 4073 and 15.99k) 

## 2. What device type has historically provided the most contributions? 

For the device type the user count from iOS is 13459 while android is 7199, being 0.65% from iOS and 35% from android. For android the total amount of euros donated is 283.54 k, and for iOS is 530.52k, almost the double for iOS than android. Divided by gender the amount of each part is almost equal, but appears a slightly difference about females and males with iOS and android devices respectively:
- android ( M - 132.6k € || F - 130.8k € )
- iOS     ( F -  247.9k € || M - 244.9k €)
The device with most contributions: **iOS**

## 3. What age bracket should the campaign target?

Looking about the age and gender, most of the total amount of donations are from an age bracket of [18-24], the total count for this age bracket is 10439, and if we look to the other gaps this is almost 3x. Meaning this is could be a campaing target, but we should not leave out the gaps, this because the ratio of donations is almost the same (aprox. 39 euros per user), and we could say that even if we use the age bracket of 18-24 we could influence in a certain way the range of 25-34.

Recomendation as age bracket for campaign target: **[18-24]**
