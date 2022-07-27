---
title: "Forecasting market movements – do you think it's possible?"
categories:
excerpt: "In this article, we will try to explain one of many indicators which could foreshadow market movements and demonstrate a few results of our algorithm."
image:
  path: ""
  thumbnail: /images/post2/cover_photo.jpg
tags: 
  - prediction algorithm
  - index fund
  - stock market
  - investing strategies
author:
    name: Darko
    picture: /images/author/darko.jpg
---

We, from the team Invexed, tried to figure if it's possible to predict moving of the market based on some data which we could gather from different sources. 
For example, we took data from Google Trends (GT) and compared it with data from Yahoo Finance (YF), but in specific way. I will explain it further in this article. 
Let's look for example data for S&P 500 Index (^GSPC ticker from YF) and keyword „S&P 500“ (from GT) for the last 3 months. 

![no-alignment]({{ 'images/post2/picture_1.png' | absolute_url }})
-> <sub>Picture 1. Normalized graphs for S&P 500 Index and „S&P 500“ keyword.</sub> <-

Graphs on the *Picture 1*; what can we tell about them? Their coorelation is on visual level seems inverted – when one graph is in their local maximum, other graph will be at their local minumum. Math shows us that correlation between those two graphs is -32.75% which for prediction sake is not really good.
Now, what would happen if we moved all Yahoo Finance data one or more days earlier compared to Google Trends data (to simulate prediction) – this way we would „predict“ how entering some keyword could affect the way how some stock/index price will behave the next day, or the day after, and so on (basically this would mean that we would have some kind of the prediction). Let's check how the mass entering some specific keyword could show us if it's, to at least to some percentage, possible to foretell or indicate if the value of something will go up or down based on the searches for that specific keyword.
If we applied this mentioned data to our algorithm, along with more advanced filtering of the data, we would get calculations shown in the following picture.

![no-alignment]({{ 'images/post2/picture_2.png' | absolute_url }})
<center><sub>Picture 2. Coorelation graph for Picture 1 data for 7 days.</sub></center>

From the *Picuture 2* graph is visible that highest correlation for above-mentioned data is on the 5th day; 35.65%. Basically this would mean that there is 35.65% chance that S&P 500 price will follow Google Trends movement for „S&P 500“ keyword which is not blistering at all. To have a solid foundation for predicting movement, we would need at least 50.01% coorelation.

# Algorithm result examples

I will now show some other interesting results and their respective correlation graphs.

![no-alignment]({{ 'images/post2/picture_3.png' | absolute_url }})
<center><sub>Picture 3. Normalized graphs for Snapchat price stock and „snapchat stock“ keyword.</sub></center>
![no-alignment]({{ 'images/post2/picture_4.png' | absolute_url }})
<center><sub>Picture 4. Coorelation graph for Picture 3 data for 7 days.</sub></center>

![no-alignment]({{ 'images/post2/picture_5.png' | absolute_url }})
<center><sub>Picture 5. Normalized graphs for Tesla stock price and „bear market“ keyword.</sub></center>
![no-alignment]({{ 'images/post2/picture_6.png' | absolute_url }})
<center><sub>Picture 6. Coorelation graph for Picture 5 data for 7 days.</sub></center>

![no-alignment]({{ 'images/post2/picture_7.png' | absolute_url }})
<center><sub>Picture 7. Normalized graphs for Netflix stock price and „netflix accounts“ keyword.</sub></center>
![no-alignment]({{ 'images/post2/picture_8.png' | absolute_url }})
<center><sub>Picture 8. Coorelation graph for Picture 7 data for 7 days.</sub></center>

> # Key Takeaways
* It is not possible to get data scaled in 1 month, or higher timeframe, period for current day the day before.
* There is an insanely huge amount of information that could affect the price of some stock/index.

# Conclusion

Nothing free comes with a little drawback and so does this. Unfortunately, it is not possible to get data scaled to one month (or higher timeframe) from the current day or the day before from Google Trends and it's only possible to collect data from two+ past days scaled in our preferred level.
Something worth note is that we could take all kinds of data from a lot of different sources (e.g. gathering raw materials (in some country, continent, or world), production of some materials or even some macro-economic factors) and run that data through our algorithm, but we think it's up to you to investigate it for your specific needs. This can be only part of some big equation that can definitely help you on your trading path. Of course, if we assume that the market is highly effective mechanism and reflection of the information on the price is immediate, you should be aware that there is an insane huge amount of information that could affect the price of some stock/index – which is in it's purest form *system entropy*.
In the next article, I will show the results of our advanced algorithm which will filter a specific part of the gathered data (which seems to be not so important - let's call it noise) and make a comparision of those most important timeframes compared to the Google Trends data.

So, what do you think? Do you think that investing some time to find the right data would be worth it and could help you decide whether is it a good idea and the right time to invest in some particular stock/index?