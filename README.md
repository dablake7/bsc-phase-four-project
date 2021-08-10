# Movie Recommendations Analysis

## Authors:
Daniel Blake, Qiwen Ou, Gabriel Warner

# Overview 

In this project we will create a system that recommend movies to users based on inputed movies.

# Business Problem

A client has no idea what to watch but knows what kind of movie he wants to watch. So, he decided to create a recommendation system that gives users movie recommendations based on user input.

# Data

For this project, we used multiple datasets in order to make our database. We found data from Kaggle which gave us more information on the movies that were present in our original dataset.

# Methods

This project uses surprise model to make recommendation system. We went on Kaggle and Statista to find information on the streaming service industry and movie theratre trends. We then went through the data and cleaned and organized it and then decided on how we wanted to display the information. This approach was taken because in order for us to look at multiple datasets and come up with a decision for Microsoft, we needed to be able to see multiple trends over multiple years.

# Results

The number of tickets sold hit its peak in 2002. After 2002, there is a slight decline in the number of tickets sold. Starting in 2018, there is a rapid decline and we can see that COVID impacted the number of ticket sales greatly, due to the huge decline in 2020. With as large of an impact that COVID had, it is unlikely that ticket sales will ever get as high as they used to be.
![example](images/tickets_sold_year.png)


On average, movies that are found on streaming services make a higher gross profit than movies that are not on streaming platforms. Movies that are making a lot of money are more likely to be on streaming services.
![example](images/streaming_vs_not.png)

The number of people subscribing to streaming services have been and still are increasing, including Hulu, HBO, and Netflix.
![example](images/platform_subscribers.png)

The revenue that streaming services are making from the increase in subscribers has been steadily increasing since 2011 and is still increasing.
![example](images/subscription_revenue.png)

Successful platforms have both movies and tv shows available for streaming.
![example](images/moviesandtvshows.png)

# Conclusions
After analyzing all of this data, we have come up with three recommendations for Microsoft:

1. Do not create a movie studio.
2. Create a streaming platform.
3. Have both movies and tv shows on the streaming platform to get the most subscribers.

We make these recommendations because there has been a decline in the amount of people going to the movies but an increase in the number of streaming service subscriptions and revenue. We also found that these platforms are the most successful if they have both movies and tv shows.

# For More Information

Please review our full analysis in our [Jupyter Notebook](./CQM_Phase1_Project.ipynb) or our [presentation](./Phase_1_PPT.pdf). For any additional questions please contact Mallory Wilson at mallorye1103@gmail.com, CeCe Lacey at cecelacey@gmail.com, Qiwen Ou at qwin.ou0721@gmail.com.

# Repository Structure
```
├── README.md                           <- The top-level README for reviewers of this project
├── CQM_Phase1_Project.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images   