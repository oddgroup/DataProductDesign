# DataProductDesign
*A method to design data products*

A data product is a solution that, without data, would not exist. You may argue that everything is data, but let’s not get into that right now. The point is: we now have a lot of data (and metadata) available. In fact, we have more than we can consume and we have produced more data in the past 5 years than we have ever produced in our entire existential lifes. At some point, this Big Data world we live in became our new normal. 

Normality here, is the fact that we cannot stay offline anymore, and everything we use to stay connected runs an algorithm that determines what kind of content we should receive in order to boost engagement rates, what route we should take to get to our destination faster, and what else people that are similar to us have been buying lately - and that perhaps you will like and buy too.

But what we don’t realize is that we don't even notice they are there. If you are not from a technical area or have an interest in data science, you probably won’t realize how many data products are around you. But could you say the same for sloppy dashboards, bad data visualization reports, or systems that require too much interaction to get to the results? Probably not. You probably either complain about them all the time, or don't know how to improve them in the first place. And that is the whole point: every solution based on data should be thought of as a product. And there are many types of data products, as well, with different types of users, formats, technologies, purposes… and so on.

**But where to start?**

Say no more, we are here for you: we have come up with Odd.DPD, a canvas to deliver better data products, and we are building a guide to get you through it. Everything is open source and you can use it whenever you want (as long as you keep it open and attribute us as your source ;)! This is the first draft of this tool, but we have been applying and refining the method for a while, testing it in various situations, organizations and individuals.
Feel free to comment and help us improve it.

### So let’s get to it.


## It is a 10 step canvas: each step helps you answer the next one.


## 1. Challenge 

Every problem starts with a good challenge and this is where you state it - what are you trying to achieve and what is the answer you are looking for?
A good challenge in data science doesn’t give you the solution right away, but rather looks at the problem at hand. We are not looking for the data science solution, we are trying to put everyone on the same page and give the team something to focus on, an objective. 
Write it down and go around the table - is everyone on your team on board with the challenge at hand and agree that it is a priority? If you don’t all agree, I suggest you write two or three down and have everyone comment on why they have different views on it. Maybe you are looking at more than one problem and more than one product. 

**This is how good challenges would look like:** 

* Develop a solution that defines which client should be attributed to which salesman
* Determine if there are relationships between socioeconomic variables and neonatal mortality in my country/state
* Inform the board of the investments and returns  in marketing regularly
* Develop a process that recommends news to our customers based on their profile

**This is not what you are looking for:**

* Create an algorithm that will tell me the best day to invest money
* Find correlations between neonatal mortality and hospital’s infrastructure
* Show the board the work we have been doing


## 2. Analytical Solution

It is very common in data science to try out different approaches before you decide on the best solution. So the idea here is not to define the best one, but to get to the same understanding on how to tackle  it with your team, considering time, resources, knowledge and technology available. Also, it is a good moment to align expectations between technical and non-technical teams: what is a viable solution that could be tested, and how long would it take? Are we looking at an algorithm that has a clear in and out, or are we going to be testing many different analysis methods and go more for an exploratory approach? Is it something that will be constantly developed, as in updated weekly, or is it a one time thing? You don’t need to answer all questions here, you can come back once other steps have been completed.

**This is how a good solution would look like:**
* A visualization of the main results and investments of the last month
* A predictive algorithm for the value of the month
* Linear regression models and correlation analysis in general
* A decision tree based on the least amount of risk

**This is not what you are looking for:**
* An app
* A dashboard that determines the best answer


## 3. User

Everything you produce is going to be consumed by someone. Even if you are planning something for yourself. And if you say “everyone in the office should use it”, or “society” then I’m sorry to be the one to inform you, but you are dead wrong. Knowing your user gives you insight on what is relevant and what is not. Consider detailing 3 main users, by asking these questions:

* Is the output of my product going to be consumed by a human or will it feed a machine?
* Is it going to be used by an individual or by a group of people?
* Is it going to guide decision making or is it going to make decisions?

>Try going outside your comfort zone and knowing more about your users by talking to them. It will make your job easier when you need to define your challenges on step 1.  Consider having them participate in this process as well! 

**This is how a good user description would look like:**
* Board members and Head Directors
* Ministry of health technicians, focused on mother and child’s health
* Participants in the selective process of projects
* General society, but mainly interested in data science and data visualization
* Marketing department, focused on analysts and day-to-day operations

**This is not what you are looking for:**
* Everyone at the office
* Leaders of the company
* General population
  
  
## 4. Format 

We are used to specific formats when we talk about data science projects - they are usually an algorithm, a dashboard or a report - but many other formats can also deliver qualified information while engaging your user in that process. Here are some examples of possible formats of deliverables to inspire you:

* A workshop to present and analyse the information in group;
* A video or an audio explaining the results sent via text message for easy access;
* A physical installation to collect information on people’s behaviour and visualize it at the same time;
* An executive report explaining your main discoveries in 10 grand headlines;
* An infographic showing the main visuals to your discovery, send in a link to everyone at the company;
* An app that runs a simulator and lets you play with the inputs and outputs.


*And here are some questions to guide you through it:*

* How much time does that user usually have to consume it?
* How often do they need to use it?
* Is it something that needs to be visible for everyone consuming it in a space (ex.: a dashboard on a wall), or available online, or in more than one type of screen?
* How sensitive is the information of the product?
* Do you need to use a technology that is already available, or do you have the budget to consider a new one?
* Will they access it while at work or is it something they need to be doing remotely?
* Will you need to record any of the decisions for improvement or to monitor how it is being used?
* Does the situation change constantly, so they have to input new information and filters or is it more constant, so you can * plan less interaction?

**This is how a good format description would look like:**
* An online dashboard that allows period and user filters, acessed on a desktop, updated monthly
* A predictive algorithm for the price of manganese for the next 3 months, if possible, 6
* A montlhy report containing the main discoveries generated by the analytics team about our consumers

**This is not what you are looking for:**
* An app that tells us the best day to invest
* A dashboard containing everything we need to know


## 5. Decisions

Every data product should give insights or support someone into making a decision. And these decisions should guide the data (inputs and outputs), as well as the information you are using to create it. You should be able to list at least five questions or decisions that should help you in that process. Remember that you are not setting objectives  or rules yet, but rather guiding your product through the decisions that your user will make when consuming it. This is a moment to also align expectations with your team, by understanding what you are able to answer with the data available. Sometimes, you cannot answer all their questions through only one product, and that has to be clear to everyone involved in that process.

Also it is important to control the expectations of what you can achieve: if the decisions outlined are not clear, the output is less likely to be useful as well. Make sure you highlight what you can answer, and decide, otherwise, your user may think you can deliver it all, when we know that is not always the case. You can separate your questions into - things we will test and things we will deliver.

*Here are some questions to guide you through it:*
* When the user consumes this information, does it usually ask more questions about it, or is it a straightforward decision?
* Is this an exploratory type of solution that helps you sort through data or does it have standart questions/answers?
* Is the information being analysed known to the user or is it completely new?
* How often are these decisions made?


**This is how a good list of decisions would look like (you can write them in sentence or question, your choice):**

* The information will be used to generate insight on how much to invest in different types of campaign, what formats of media are working, what content is engaging our audience and to adjust investment for the following month
* The information will guide which actions will be most effective to reduce child mortality in each region of our country, defining the calendar of actions for the next year
* The information will help guide which collaborators have been performing above average for the past 6 months and should be considered for a raise, which should remain as they are, and which should be closely monitored due to a bad performance

**This is not what you are looking for:**

* Decide on the best employee of the month
* Give ideas to our team on content for our website
* Determine the investments to be made for the country in health


## 6. Inputs and Outputs

Every data product has data that comes in, and processed data that comes out. There’s usually a data transformation process that goes into making dashboards, algorithms and data visualizations. So make sure you understand what is expected of your team to deliver, and how complex is the information that you need to import to do the work. 
This step is fundamental to understand the viability or limitations of your data product. If you cannot process data in that way, you probably have to go back to your solution.

*Here are some questions to guide you through it:*
* Where is it located, is it easy to process or do you need to build scripts, linking or cleaning algorithms to be able to process it?
* Is the output a number, a visualization, a list, an index, a vector?

> You don’t need to be 100% specific at this point, but again, aligning expectations never hurt nobody.

**This is how a good list of inputs and outputs would look like:**
* Inputs:
** number of children that were born per month for the last 10 years 
** number of children that died in the first 28 days of life per month for the last 10 years

* Output: 
** rate of mortality 3 months from now

* Inputs: 
** number of likes per post 
** number of people that follow the instagram page
** number of comments per post
* number of clicks on links per post

* Outputs: 
** engagement per post;
** engagement growth or decrease per post

**This is not what you are looking for:**
* Inputs: database xls
* Output: best post of the month

> You will see at the canvas that there are dots to connect inputs and outputs, that is a simple way for you to determine which inputs form which outputs.

## 7. Threats & Barriers

Change can be difficult, and implementing something to guide someone else’s decision making process is a challenge by itself, so it is crucial for you to consider all the difficulties along the way. It can be the access to data - maybe your area is not the owner of the information and you depend on someone’s approval of it everytime, or it can be a culture centered on opinions instead of facts, or even factors on the data input that can lead to errors. As soon as you make them clear to everyone, it is easier for you to think of actions that can prevent them from becoming an issue or from putting your project and effort to waste.  Again, this is the perfect opportunity to make your problems visible for everyone involved or even for you to become aware of someone else's needs.

*Here are some questions to guide you through it:*
* Is there anyone standing between you and the access of the data you need?
* Is the area/company/team/user used to consuming that type of information?
* Are there any technical issues or limits that your team has to be considered during this process?

**This is how a good list of threats and barriers would look like:**
* Cultural acceptance - teams are not used to consuming information from Software x, and still use MSExcel to analyse information
* Input error: data is collected manually and may present errors
* Data dependant: team depends on sales team sending file containing data every month

**This is not what you are looking for:**
* Data has no quality
* User is very difficult
* Database not available


## 8. Actions and rules

After you have completed your threats and barriers it is time to engage your team into understanding how you will prevent them from happening or adapt to them. These are the actions that you should list. It is a perfect opportunity to develop a sense of ownership of that product within your team and your user’s team as well. You shouldn’t be left alone deciding on what to do once those barriers come your way.

Also, it is a good moment to highlight the rules to be applied. You can include data related rules, such as filters, databases you have to clean and how to do it, or they can even be a list of the people you have to talk to in order to understand all these rules better.

*Here are some questions to guide you through it:*
* What are the actions your group and the users can program to prevent it from not being used?
* Which are the criteria that should be considered to analyse data correctly?
* Did the software/datasource ever change, and if so, did it generate any changes in the quality of the data?

**This is how a good list of actions and rules would look like:**

* Actions:
** Ask for automatic access of data from department x or leader y
** Do a workshop on the benefits of using this data product for the main users
** Talk to leadership to provide incentives for the product to be disseminated and used
** Validate missing data with the users

* Rules:
** Only consider data from 2005 to 2015
** Give more than one option for the output if there is more than one result above 95% confidence
** Validate used variables so they are in accordance with data protection laws

**This is not what you are looking for:**
* Actions:
** Ask for more time
** Reduce scope to fit schedule

* Rules:
** Define which variables to use


## 9. Answer

The answer is the business/objective solution you are trying to achieve with your product. *It is the most difficult element to explain, but one of the most crucial ones in the entire canvas.* Depending on the product you have, the output and the answer will be the same. For example, if it is an analysis or a dashboard, both the output and the answer will be a list of the amount of visits you have to make to achieve your revenue at the end of the year, or the percentage of tasks the development team has completed and which projects are in risk of being delayed. But if you are delivering an algorithm, they are probably different - the output is the exact data format in which the input has to be transformed, but the answer is what you are trying to achieve by developing that product, more or less, the information.

**Some examples to help you understand:**
* Your solution is an exploratory analysis on the relationship  between low birth weight in newborns and socioeconomic variables. The inputs are low birth weight of children, characteristics of the mother, characteristics of the environment and so on. The output is the p value (or how significant that analysis is) of those analyses. Your answer is if that variable is positively or negatively related to low birth weight in newborns.
* Your solution is a visualization comparing the performance of employees in your company for the last 6 months. Your input is the number of tasks executed, the evaluation from peers and deliveries executed on time. Your output is the number of the calculated index of those inputs, combining all those variables. The answer is the rank of the employees from best to worst (who performed best), considering the index value.
* Your solution is a predictive algorithm to help the acquisition team define if they should buy 3 or 6 months of goods. The outputs are the percentage of increase or decrease on a certain commodity for the next 6 months. The answer is a quadrant that compares the value of the commodity, market demand and suppliers limits, determining the best composition to be bought among suppliers. They are extremely different: one is an LTSM model, and the other is just a logistic regression with that output. 

> This is a good moment to ask our users to draw what they need on a piece of paper. It is the best way to be on the same page and to know you will deliver something that has meaning to it.

*Here are some questions to guide you through it:*
* How would you describe your deliverable to someone outside your area of expertise?
* What is the main business/organization/individual objective we are trying to achieve?
* What does your user repeat throughout the process that makes it stand out?

**This is how a good answer would look like:**
* A list of books recommended for the user that is likely for them to continue navigating in our website
* The difference between the amount sold and our year goal in currency and percentage
* The amount of money we have to invest to reach the audience we desire monthly

**This is not what you are looking for:**
* The best recommendations for our user
* The effort we have to put in to achieve our goal
* The return on our investment


## 10. Success 

Now that you have the concept of your product, you have to consider how you will measure its success. This also gives you a good understanding of the rules applied, for example, when developing a predictive algorithm to recommend news on a website, do you wish to increase access, even though you may jeopardize diversity and create content bubbles, or do you want to be remembered for diversity, but may decrease access in the process? Determining what is success is very important for your product to be useful.

*Here are some questions to guide you through it:*
* Does the success of your data product depend on the success of the organisation’s or the area you’ve built it for?
* Can you measure it automatically or will you have to ask for 
* What does your user repeat throughout the process that makes it stand out?

**This is how a good success measurement would look like:**
* Amount of people that used it in the last month
* Amount of ideas/decisions it helped answer
* Increase/decrease in the main answer after using the product

**This is not what you are looking for:**
* Anything that is not dependant on your product - there is usually a person deciding at the end of the line



# Well, if you read it all through, please leave your comment below, feel free to help us improve it, and if you want to send us your canvas or tag us on Instagram please do using @odd_group!





  
-----------------------------------------
Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
