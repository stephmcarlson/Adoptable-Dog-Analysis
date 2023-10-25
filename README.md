# project1

## Resources


Title: Local Pets in your Area

Team Members:
-Alyssa Cullinan
-Valeria Briones
-Luke Payne
-Shubhangi Bidkar
-Stephanie Carlson


Project Outline:
Pull Petfinder API
Breakdown to find local dogs in Chicago, Illinois
Summarize dogs available by breed, age, size, color and gender
Analyze data for "Black Dog Syndrome" and see if they are on the site longer

Findings:
Overall while black dogs are available most frequently, black dogs don't seem to be online longer than other dogs. We did find that breed tended to influence the days online more than color.

-Black dogs are the most frequent color dog available in our sample of Chicago area data making this a great dataset to analyze for black dogs
-In both adoptable and adopted dogs, Black dogs are not listed substantially longer than other colors
--In the findings of the ttest, the pvalue is .11 which is over .05 showing us that in the distribution of colors in adoptable vs. already adopted dogs, these populations are statistically different
-In both our adoptable and already adopted dog populations, Pitbulls take the longest to find a home
-While Pitbulls are the most frequently available dogs for adoption, the Labrador Retriever is the most frequently adopted dog, highlighting the difference in breed preferences
-We are getting mixed results for the correlation between age and days online prior to adoption with the adoptable dog population having a positive correlation of .24 and adopted dogs having a negative   correlation of -.32. This looks to be due to more senior dogs getting adopted faster in the adopted population
-For size of the dogs, we are seeing a slight positive correlation of larger size dogs being available longer prior to adoption. The correlation coefficients are .07 in the adoptable population and .04 in the population that has already been adopted.
-As we analyze by coat, the majority of the data is more closely distributed with a relatively small number of outliers

Challenges and Limitations:
-Calculating the number of days on petfinder/adoptable days online 
-There is no defined specification for age or breed size. 
-Inconsistency of breed identification by the  shelter.  
-Analyzing categorical data vs. numerical


Resources:
-Petfinder API (https://api.petfinder.com/)

-Petpy Wrapper (https://petpy.readthedocs.io/en/latest/api.html)

-Geoapify API (https://api.geoapify.com)

