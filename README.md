# Introduction
Working as a waiter is a very hard job. You have to always treat your guests the best. You are the face of the restaurant, while kitchen is the heart. But as we may know, hard work pays off. But how well does it pays for a waiter? Let's figure out. It is also interesting to see how generous are the people, and is there any pattern where people are more generous, than usual? Well, we are about to figure it out. Today we have data that was gathered by a waiter in some restaurant.

The data presented to us contains columns such as:

_total_bill_ - total amount spent by guest(s);

_tip_ - total tip left by guest(s);

_sex_ - gender of a guest (we assume the person who paid for the table);

_smoker_ - whether person is a smoker or no;

_day_ - day of the visit (we assume server works from Thursday to Sunday);

_time_ - time of the day (Lunch or Dinner);

_size_ - size of the group;


# Main Stages
Before analyzing and visualizing the data we had to understand the data and preprocess it. Usually, when working with duplicate data, we drop it, but if we were to look at our case from a different angle, it was not very obvious what to do with the data, and it was explained why during the analysis.

This project was utilized using Python frameworks such as Pandas, Numpy, Matplotlib, and Seaborn. By using different kinds of graphs we were able to build and look at tip distributions, average tips vs. other categories, average tips by day, and many other graphs.


# Conclusion
After exploring our data, and gaining insights, we could draw some conclusions, but an important thing to keep in mind, is that we only had 244 samples, which is not as many as we would like to have. However, based on our dataset, we conclude that during Saturday people are least generous, it is the most profitable day for waiter. On Sundays, most people come as a group of two, which is second highest tip percentage group.

Groups with only 1 person are the most generous when tipping a waiter. Also, on Fridays people are most generous as well. To be more specific, females on Fridays are the most generous.

So, if it is a Friday evening time, you see a single Female coming in to a restaurant, it will be most likely the most generous guest. But if you see, a group of 6 entering the restaurant, you can expect on average $7.02 tips.




# Future Work
By exploring our data we found some correlation between the data. We also were able to find some patterns, but more data eliminates the factor of luck, and create better statistical vision, so it would be great to collect more data. Improved data collection could also potentially lead to better analysis. For example, if we could have meal types ordered by table (e.g. soup, meat, salad, etc.) this could open whole new section for our analysis. A quick review left by guests would also help us improve our analysis (such review could consist of how good was their meal, how was the service, etc).

There is a lot of potential in exploring topic of restaurant sector and it is not limited to just tip analysis. Exploring it deep enough can benefit all: visitors, waiters, and restaurant business in general. But all of this can be done with having more data that is relevant for analysis.
