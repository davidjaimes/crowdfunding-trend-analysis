### Background
Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome. Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success.

### Given the provided data, what are three conclusions we can draw about Kickstarter campaigns?

![figure1](images/parent-category.png)

From the first plot, based on Parent Category and including all Countries, we can clearly see the Top Three Categories with the highest rates of success as a percentage are Music (77%), Film & Video (58%), and Theater (60%). On contrast, the Worst Three Categories belong to Journalism (0%), Food (17%), and Publishing (34%). Digging a little deeper and using the same analysis, if we filter by Country and pick out the Top Three with the highest number of campaigns, we can produce the following table:

Country | No. of Campaigns | Top Three | Worst Three
--- | --- | --- | ---
US | 3038 | Music (77%), Film and Video (62%), and Theater (58%). | Journalism (0%), Food (20%), and Games (35%).
GB | 604 | Music (74%), Theater (72%), and Games (48%). | Food (0%), Publishing (35%), and Film and Video (40%).
CA | 146 | Music (83%), Theater (64%), and Photography (46%). | Food (0%), Technology (26%), and Publishing (33%).

Therefore, if you want the highest probability of success, then start a Kickstarter campaign either in Music or Theater and keep away from things related to Journalism and Food! Note to reader, even though Great Britain and Canada did not have a Journalism category, I assume they would suffer the same fate as those in the United States.

![figure2](images/sub-category.png)

Let us continue down this road of analysis and say you decide to start a campaign in the Music category. What genre will you choose? Lucky for us, we can filter the Music into Sub-Categories and see which genres of music are most successful. To my surprise, we do have a few to choose from. We can go with Rock, Indie, Metal, Pop, Classical, and even Electronic music. However, if you do decide to go with Jazz, keep in mind it does have a 100% failure rate. Now, what if you are not the Music type but the Food-skilled, type of person? You are determined to make it in the food industry even if the odds are stacked against you. If we look the Food sub-categories, then we see that your best bet would be with small batches of food rather than a food truck or restaurant. The differences are night and day (90% vs 0%).

![figure3](images/date-conversion.png)

Okay, great. You’re all set to go. Now, when should you start this Kickstarter campaign? Using our third plot and filtering by the Music category we can see a time series curve for the for the months out of the year. Diving a little more reveals a general trend for 2012 and 2015—the years with the most numbers of campaigns in the Music category. This trend has a negative, linear slope that starts in January and ends in December. This trend, more or less, remains the same when we filter by all years. This suggests it is better to start a Kickstarter campaign early in the year rather than later.

In summary (tldr), the three conclusions I draw from three plots produced are: (1.) Music Category has the greatest rates of success, (2.) Rock is the most popular/successful genre under the Music category, and (3.) the months between January and May have the greatest number of successful Kickstarter campaigns.

### What are some limitations of this dataset?

List of Limitations:
   - The background portion of this homework states more than 300,000 projects have been launched on Kickstarter but we only analyze roughly 4,000 projects. We are only analyzing about 1% percent of the total projects launched.
   - The data we used does not take into account whether each project was Staff Picked and/or Spotlighted. Projects may be more successful if they are labeled as a Favorite by Kickstarter.
   - Other markers not listed in our data such as:
      - Video showcasing project.
      - Available reward by making a pledge.
      - Estimated delivery date.
      - Updates on projects between campaigner and their pledgers.

### What are some other possible tables and/or graphs that we could create?

List of possible table and/or graphs:
   - Compare the average goal amount between successful and failed projects filtered by Categories. Important to get a sense of much money should be requested.
   - Compare the average donation per backer between successful and failed projects. Some projects may have many backers and others might have few backers; but based on Category, some projects may raise more per backer.
   - Success rate vs Failure rate for each Category and Sub-Category. Similar to graph 1 but turn number of successful and failed to percentages.

![figure4](images/goal-bins.png)
