# Coin Stock

## Overview

Market Visualizer is tool to help pull and visualize market data from not only from the US Stock Market but also pricing for cryptocurrencies.

With the rise of blockchain and cryptocurrencies becoming a viable vehicle for investing, it is good to have the ability to compare stock prices and indices such as the S&P 500 with cryptocurrencies like Bitcoin and Ethereum.

## Functionality and MVP

Users will be able to:
- [ ] Select single entity to analyze from either the stock market or crypto currency
- [ ] Select the date range
- [ ] Enter mock investment value at start date to calculate end profit
- [ ] Compare two entities through a given date range

## Wireframes

This app will be on a single screen with the main element being a price over time char generated by D3.

All controls will be on the left side of the chart which gives the user options to select which type of financial instrument to analyze within a selected date range.

Users will also have the option to put in a mock investment value to calculate resulting changes and potential profits or losses.

![wireframes](https://github.com/addriv/market_visualizer/blob/master/docs/wireframes/main.png)

## Technologies

* D3.js for price charting
* Vanilla Javascript
* Alpha Vantage API to pull historical stock prices
* Coin Bin API to pull historical crypto currency prices

## Implementation Timeline

**Over the weekend**:
- [X] Find and test APIs to source historical price data
- [X] Go through D3 tutorials

**Day 1**: Learning D3, testing and setting up stock market price charting
- [X] Install stock market type selection
- [X] Setup ajax request functions to Alpha Vantage
- [X] Build basic line chart on prices with D3
- [X] Add volume data bar chart

**Day 2**: Setup crypto currency price charting
- [ ] Install date pickers for date range
- [X] Setup ajax request functions to Coin Bin
- [X] Build basic line chart on prices with D3
- [X] Install investment functionality

**Day 3**: Setup comparison between two entities and polish chart
- [ ] Normalize data into percent gain
- [X] Install controls for comparison
- [X] Add hover effects on chart to display data points and statistics
- [X] Add loading spinner while data is being loaded

**Day 4**: Styling and polishing up chart visualization
- [X] Style controls
- [] Add icons for links to Github and LinkedIn

### Bonus Features
- [ ] Intraday, weekly, monthly charting for stock market prices
- [ ] Add basic analysis like SMA and EMA to chart
- [ ] User customization of chart colors
