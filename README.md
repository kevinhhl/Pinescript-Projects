## PineScript Projects

This repository contains open-source projects that I post on Tradingview. The goal is to use simple STAT101 methods and other existing PineScript libraries to systematically replicate the process of technical analysis.

For more of my projects, please visit [](http://tradingview.kevinhhl.com/)[http://tradingview.kevinhhl.com](http://tradingview.kevinhhl.com).

**Opinion**: Technical analysis on its own is a pseudoscience, similar to astrology. However, when combined with scientific methods, we can gain useful insights into market behavior and make more informed trading decisions. 

## Assumptions

The [efficient market hypothesis](https://en.wikipedia.org/wiki/Efficient-market_hypothesis) (EMH) states that all available information is already reflected in asset prices. Therefore, consistently outperforming the market without taking on additional risk is impossible. We assume that EMH holds true.

An inexperienced investor may focus solely on the percentage of their account, but this approach often leads to poor risk management as it disregards the variability of the their P/Ls. It is important to learn about statistics because chart patterns alone are insufficient for ensuring proper risk management. I encourage readers who are unfamiliar with these topics to visit [https://openstax.org/](https://openstax.org/), a nonprofit organization that provides free, peer-reviewed textbooks for university and high school courses. Basic knowledge of statistics is necessary for trading, yet this is often disregarded in blog posts that you see on top websites.

## Methodologies
As an algorithmic trader, I use the Sharpe ratio (and sometimes the Sortino ratio) to measure variability and evaluate the historical performance of a trading strategy. To ensure that my strategies perform well in different market conditions and to minimize curve fitting, I employ [walk forward analysis](https://en.wikipedia.org/wiki/Walk_forward_optimization) (WFA) to test and refine them.

Understanding the amount of variability that your strategy can cause to your account is crucial in determining the appropriate leverage to use. While the Efficient Market Hypothesis (EMH) holds true, it is possible to outperform the average investor by taking calculated risks that are necessary to achieve higher returns.

## Beyond PineScripts

As mentioned in the previous section, I heavily rely on WFA to evaluate my trading strategies.

Although this feature is currently not supported by TradingView's backtester, it is possible to create it using reports exported from TradingView.

In this repository, I have included frameworks for WFAs with exported reports from TradingView.
> [https://github.com/kevinhhl/Pinescript-Projects/tree/main/Backtesting%20frameworks](https://github.com/kevinhhl/Pinescript-Projects/tree/main/Backtesting%20frameworks)

Scripts in this folder will help users construct both in-sample (IS) and out-of-sample (OOS) datasets based on the universe of reports exported from TradingView.
