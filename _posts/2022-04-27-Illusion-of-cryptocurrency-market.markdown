---
title: "Illusion of Cryptocurrency market? Bitcoin vs Crypto Index Fund"
categories:
excerpt: "Goal of this article is to investigate and compare two passive investing strategies, possibility to diversify cryptocurrency portfolio (reduce investing risk) and most importantly to see which investment strategy will lead to higher ROI (return of investment). Comparison between investing in cryptocurrency index fund vs only in BTC (Bitcoin) is given further in this article."
image:
  path: ""
  thumbnail: /images/post1/altcoins.jpg
tags: 
  - bitcoin
  - index fund
  - cryptocurrency
  - investing strategies
author:
    name: Dario
    picture: /images/author/dario.jpg
---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-SP9WHB3SPS"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-SP9WHB3SPS');
</script>

At the time of writing this article, Bitcoin dominance was around 42% . But is it “only“ 42%? Main assumption is that diversification of cryptocurrency portfolio (risk reduction) will be possible if Bitcoin dominance is not absolute. Why does investing in cryptocurrency Index Fund might have some benefits? Well, most importantly due to the elimination of unnecessary investing risk (e.g., picking wrong cryptocurrency or picking right cryptocurrency at the wrong time), this way only coin market risk remains and that risk is enough large by itself. Goal of this article is to investigate and compare two passive investing strategies, possibility to diversify cryptocurrency portfolio (reduce investing risk) and most importantly to see which investment strategy will lead to higher ROI (return of investment). Comparison between investing in cryptocurrency index fund vs only in BTC (Bitcoin) is given further in this article.

## Investing strategy – coin index fund

Buying index fund (market capitalization-weighted index) that is holding 10 of largest cryptocurrencies. Stable Coins (Tether, Dai, Binance USD, USD Coin, etc.) are not included in Cryptocurrency Index Fund. Portfolio rebalancing is made once a week. With simple words, if market cap of some cryptocurrency, currently not in an index fund is higher than of cryptocurrency currently in an index, cryptocurrency with lower market cap will be replaced by the new one with higher market cap. Any change to the cryptocurrency in the index that alters the total market value of the index while holding price constant will not lead a to change in index level (e.g., price of the coin is constant while circulating supply is changing). More on the metholodgy which this index fund is following can be read here (<a href="https://www.spglobal.com/spdji/en/documents/methodologies/methodology-sp-us-indices.pdf">S&P Global</a>). In our backtest we are investing 1000$ once per week, from 1st January 2018 to 1st May 2022. On the 1st of May 2022 everything is sold and ROI is calculated. For sake of sanity, from now on let’s call previously described index found CRYPTO10.

## Investing strategy – Bitcoin (BTC)

Buying BTC once a week for 1000$, from 1st January 2018 to 1st May 2022. On the 1st of May 2022 everything is sold and ROI is calculated.
![no-alignment]({{ 'images/post1/image1.png' | absolute_url }})

# Graph explanation 

On the graph above, two plots are presented. Orange plot is imaginary index fund holding only BTC. Blue plot represents CRYPTO10 index fund. Circle markers on plots are trading dates (when index funds were bought, once per week - without any special reason it’s always Sunday).

# Analysis
... on the 1st of May 2022 all our holdings in both index funds were sold. Amount of money that we have got from each index fund (BTC, CRYPTO10) after selling our holdings is called Return. Cumulative invested amount of money (per index fund) is called **Investment**. ROI is calculated as:

> <center>ROI =  (<sup>Return</sup>&frasl;<sub>Investment</sub> - 1) x 100% </center>

If we plug Return and Investment in ROI formula, ROI for BTC is ~286% and for CRYPTO10 ~288%. Difference in ROI between Index Funds is trivial. This is expected result, which can be easily seen just by visual inspection of plots, as correlation between index levels of BTC and CRYPTO10 is high. Reason for this high correlation is unquestionable dominance of BTC in CRYPTO10.

# Bitcoin dominance in Crypto10

![no-alignment]({{ '/images/post1/image2.png' | absolute_url }})

On the graph above, BTC dominance in index CRYPTO10 is shown. Average 5-year dominance is around ~ 61 % (based on CRYPTO10). Main force that is driving index level of CRYPTO10 is price of Bitcoin. With such high correlation between CRYPTO10 and BTC price, and with high dominance of Bitcoin over CRYPTO10, cryptocurrency portfolio diversification is close to impossible. Unfortunately, cryptocurrency market still is only Bitcoin market. Essentially Bitcoin dominance is much larger than shown on graph above, due to (as previously shown) very high correlation between Bitcoin price and prices of other top 10 altcoins.

> # Key Takeaways
* Buying cryptocurrency index funds (ETFs) will not lead to higher ROI or to portfolio diversification (risk reduction)
* Bitcoin is still dominating and driving entire “crypto” market.

# Conclusion

Team Invexed will continue to monitor correlation between BTC and CRYPTO10. Hopefully, in the future, BTC dominance and correlation between BTC and CRYPTO10 will become lower, which will lead to creative destruction of Bitcoin market and raise of the true Cryptocurrency market. Altcoin prices should not be dictated by BTC price. Fundamentals and technological innovations introduced with the coin should drive the price of the coin. This is the only way to add new value to the World which will consequently lead to growth. Bitcoin already introduced technological innovation, so it seems that other coins, for now, live on the glory of Bitcoin. In the next article comparison between Bitcoin price and S&P500 will be made. Correlation between Bitcoin price and S&P500 will be investigated. It will be shown how adding a small portion of Bitcoin in portfolio based on stock index funds can lead to a higher ROI of such portfolios.



