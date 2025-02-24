# INTRODUCTION 

Hello, This dataset is about laptop sales in India. This is quiet an interesting project because it's I believe m first ever real project with Python. My data Analytics journey has been very tough because, I have always had to go for interviews before realising there is a skill I should have gotten the hang on atleast but I never did but then after reading countless job posts, I realised python was something I would encounter sooner than I imagine so even though difficult, I decided to take that step and this is the result which is why I am so exceited to be putting this out here.

Enough of the intro, For this particular project, the source of my data is kaggle . The dataset contained just a sheet 5000 rows and 11 columns as shown below where Ive got the shape.

After downloading the data, I applied the step processes I normally follow. which are 

### Data Cleaning & Transformation
### Data analyzing
### Data visualization
### Recommendation.


# Data Cleaning and Transformation

In this dataset, I started of by importing my libraries, followed by my dataset. This is seen below: ![LAPTOP SALES PYTHON](https://github.com/user-attachments/assets/bb8dfe49-67bf-43d5-98e7-16fc3f67ec1b)

I then looked more at the dataset by performing certain functions like standardization, checking for datatypes, etc and cleaning before answering some business questions: ![LAPTOP PYTHON 2](https://github.com/user-attachments/assets/224aa085-9a6e-44db-8e56-e84a6826cef6) 

# Data Analysis and Visualization

After, cleaning my data, transforming and getting comfortable with my data, I moved on to answer a few business questions whiles using visuals to understand what was going on.

![LAPTOP 6](https://github.com/user-attachments/assets/fc3a9683-bdc6-4f3b-a6d2-0f35d9947b31)

#### In the above, I was looking at the number of males to females have purchase a laptop so far and we can see that, although males purchased more, females have purchased quiet a significant amount themselves with no real margin between the two genders which is great for the people of india. shows more people are really getting into tech right? lol

![LAPTOP 7](https://github.com/user-attachments/assets/ddf1b92f-d14a-4960-aeee-a490831d2a9b)

#### Well for the second Analysis we have;
So the above is showing which payment mode customers like to pay through more and the above shows that they prefer the EMI payment method more with debit ard coming in close second, credit card and UPI seeming to be on the same level here. However, we can tell that the people of india literally hate paying in cash. You ask me, that's a pretty good thing.

![LAPTOP 8](https://github.com/user-attachments/assets/4c1909ab-bbce-4714-9442-bc175e2bc0cd)

#### For the third Analysis, we have;
The Income Level by Gender who are purchasing the most laptops and we can see that people in the medium bracket overall, are purchasing more of the laptops by either genders. Well I assume those in the  high bracket already are making alot and wouldn't really chase after new careers that need you to get a laptop. People earning low pretty much arent having enough money to purchase these laptops which as a business, I think isn't fair. if business can produce slightly high level laptop at a budgeted cost, this will greatly help the business in terms of revenue and that helps either side
Above, I used functions like CASE END to change or standardize how some of the names were spelt out. I wanted to make it more readable for anyone that looks at the project, I also made use of Parsename and replace, to separate the full anme column into First_Name and Sur_Name. I also made use of delete where information of something columns are null, I didn't want that in this project and also we dropped some columns we won't be using.


# Recommendations
As stated before, I think laptop industries and sellers in India, should look at reducing the prices of laptops a little but to much performance of the laptop types to help low income earners acquire them too. However, laptops with higher performance rating should still stay the same depending on how sales is.
Again, Laptop sellers must bear in mind that since people prefer more EMI payment types, they should make accessibility of this payment mode easier at every centre and city


# Conclusion
Taking on this project has helped me gain the relevant experience in python pandas, matplotlib.pyplot and even seaborn. This was stressful but a very exiting project
I successfully cleaned a raw data , transformed and analyzed it mainly with python and even created a visual.
