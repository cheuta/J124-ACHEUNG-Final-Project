# Do We Really Prefer Sugary Cereals? What 77 Cereals Reveal About Our Breakfast Choices.

Cereal is a classic breakfast option in the United States, but everyone seems to approach this meal differently. Some eat it with milk first, in different sized bowls, and prefer certain brands. Cheerios, Fruit Loops, Cocoa Puffs, Frosted Flakes--the options are endless. Each box of cereal not only comes with their unique mascots and bright colors, but also its own mix of sugar, fiber, calories, and other nutrients. Now, have you ever wondered how these nutritional attributes affect how this sugary meal is perceived and rated? Using a dataset containing 77 cereals, let's explore whether "healthier" cereals, that contain more fiber and less sugar, actually score better, and what the data reveals about trade-offs between nutrition, taste, and consumer preference.

## Where was this Dataset Obtained?
The cereal dataset originates from [StatLib](https://lib.stat.cmu.edu/datasets/1993.expo/) and is a collection of nutritional information for 77 breakfast cereals sold in US grocery stores. It includes manufacturer codes, type (hot or cold), nutrition facts, and a rating number that is derived from consumer reports. 
This dataset CSV was obtained from the [Kaggle](https://www.kaggle.com/datasets/crawford/80-cereals/data) website. 

### This dataset is not perfect and there are some potential challenges. 
- Of the 77 cereals, several are missing nutritional information. The value, -1, appears as a placeholder in the data. 
- The rating system is not fully explained. It is likely a composite score, but the lack of information about how the rating came to be limits how strongly consumer preference can be interpreted. 
- This dataset was last edited in 2016, and therefore may not match the current era of products and nutritional standards.

## Data Analysis 
This dataset can help us answer many questions:
- How are calories, sugar, and fiber distributed across cereals?
- Which cereals have the most extreme nutritional values?
- Is there a clear relationship between sugar and rating?
- Do high fiber cereals tend to have higher ratings than cereals with low fiber?
- Do manufacturers differ in average rating or nutritional profile?

## Methods and Limitations
### Methods
I imported cereal.csv into Google Sheets and cleaned it by replacing any -1 values with blanks and checking for duplicate names. To make comparison between brands easier, I converted calories, protein, fat, sodium, fiber, complex carbohydrate, sugar, and potassium into grams and made sure they were all relative to one cup. 

### Limitations
The largest limitation of this dataset is missing information. The lack of a clear definition for the rating system means I cannot claim that the ratings perfectly reflect consumer preference. The demographic context is also vague so we don’t know who rated these cereals and under what conditions. 
Additionally, the sample size is rather small with only 77 cereals. The trends observed from this dataset might not necessarily reflect the true trends of real consumers, especially since this dataset was roughly put together between 1993 to 2016. It is possible that certain ratings are higher or lower than usual because of the varying amount of people contributing to their rating. 

## Ethical Concerns 
Since this dataset is both small and historical, it is dangerous to overstate health risks as it may unfairly target certain manufacturers. There are many confounding factors when it comes to health, therefore, high fiber and low sugar may not always constitute healthy food. Some factors directly related to food include: overall diet, portion size, and added benefits like vitamins and minerals. We also have to consider socioeconomic factors and business strategies such as, income, fresh food availability, marketing, pricing, and shelf placement. 

However, there are ways to add and strengthen what the dataset already reports. 
- Consulting or interviewing a dietitian or trusted nutritionist could help us interpret cereal labels and ratings better. 
- Conducting a supplemental survey to gather information about what consumers look for when they buy cereal (e.g., taste, price, health, etc.).
- Look into how differently “healthy” and “fun” cereals are marketed.
- Comparing this dataset with more recent nutritional data so that we can analyze what has changed.
