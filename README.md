# Applied-Plotting

This repository contains projects I have worked on that demonstrate my ability to process and visualize data in Python. 

### Burnaby and Vancouver 2018 Half Marathon Top 40 Time Distributions
This project involved finding and processing some sort of sports/athletics data from publically available datasets from your hometown, stating a research question, and then creating a visual using Matplotlib that addresses the stated research question. I have chosen to look into: How do the distributions of race times for the top 40 participants compare across 4 different half-marathons (Vancouver Chilly Chase, Shamrock'n Race, Vancouver Historic Half, Fall Classic) in Burnaby and Vancouver in 2018? As well, the data visualization is truthful, functional, beautiful, insightful, and enlightening - the qualities described by Alberto Cairo in his book _The Truthful Art: Data, Charts, and Maps for Communication_. Please see the Jupyter notebook for more details on the implementation and discussion. 

![alt text](https://github.com/jeffreyboschman/Applied-Plotting/blob/main/images/Burnaby%20and%20Vancouver%202018%20Half%20Marathon%20Top%2040%20Time%20Distributions.png?raw=true)

### More confident decisions with coloured bars
This project invovled helping users make more confident decisions in regards to data with confidence intervals. For example, in a vertical bar chart where each of the x-axis categories have different y-axis values and distributions, the the confidence intervals may overlap and thus it is difficult to see which x-axis categories is representative for a given y-axis value. Therefore, one of the solutions that Ferreira, Fisher, and Konig (1) suggest is to allow users to select a y-axis value of interest, draw a horizontal line, and colour the bars based on the likelihood of that category being higher or lower than the chosen y-value. In the visualization I implemented, the bars are a dark red if they are definitely above the chosen y-value, dark blue if they are definitely below the chosen y-value, or a colour in between according to where the y-value is given the 95% confidence interval of that bar. 
![alt text](https://github.com/jeffreyboschman/Applied-Plotting/blob/main/images/More%20confident%20decisions%20with%20coloured%20bars.png?raw=true)



(1) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ferreira, N., Fisher, D., & Konig, A. C. (2014, April). [Sample-oriented task-driven visualizations: allowing users to make better, more confident decisions.](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/Ferreira_Fisher_Sample_Oriented_Tasks.pdf) 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In Proceedings of the SIGCHI Conference on Human Factors in Computing Systems (pp. 571-580). ACM. ([video](https://www.youtube.com/watch?v=BI7GAs-va-Q))
