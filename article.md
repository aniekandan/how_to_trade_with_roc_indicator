# How to trade with the ROC indicator

![featured article image trading UI with a chart, candlesticks and an indicator](https://raw.githubusercontent.com/aniekandan/how_to_trade_with_roc_indicator/main/ROC%20featured%20image.jpg)

Technical analysis is a widely embraced approach to studying trading that assists in forecasting future price movements. It examines historical market data, such as previous price fluctuations and trading volume, to deduce potential future outcomes. Practitioners of technical analysis hold the belief that analyzing past patterns and trends can provide valuable insights into future market dynamics. 

By analyzing charts and utilizing specialized tools, traders endeavor to identify favorable moments for buying and selling investments. The fundamental concept underlying technical analysis is that by comprehending and following price patterns, traders can enhance their decision-making abilities and gain a competitive edge in the market.

The **Rate Of Change (ROC) indicator** is a valuable tool in technical analysis that calculates the percentage change in price over a given time period. The purpose of the ROC indicator is to provide valuable insights into the momentum and the speed of price movements. It does this by comparing the current price to a previous price `"n"` periods ago. Armed with this information, traders can assess how quickly or slowly market prices are rising or falling.

The ROC indicator is frequently used to spot potential trend reversals, divergences, and overbought or oversold market conditions. The positive or negative values of ROC can be used by traders to find out the strength and direction of price trends, and this helps them make more informed trading decisions.

## Diving deeper into the ROC indicator.

The rate of change (ROC) indicator calculates the price change over a given period as a percentage. The ROC indicator calculates the difference in price between the current price and the price n periods ago and then expresses this difference as a percentage of the earlier price.

![ROC indicator in MT5](https://github.com/aniekandan/how_to_trade_with_roc_indicator/blob/main/roc_1.gif?raw=true)

The calculated value can either be positive or negative:

- When the ROC value is positive, it indicates that prices have increased,
- On the other hand, a negative ROC value suggests a decrease in prices.

## Formula for calculating ROC

The calculation behind the formula for ROc is rather simple. The previous price must be subtracted from the current price, and the difference must then be divided by the previous price. the final ratio must then be multiplied by 100 to make it a percent. The formula can be written as follows:

```math
ROC = \dfrac {\text{current price} - \text{previous price}}{\text{previous price}} \times 100\%
```

An example will illustrate how simple the calculation actually is:

**Example**
> The current price of a stock is $50, and the price 10 seconds ago was $40. Calculate the ROC over the 10 periods.

To calculate the ROC over these 10 periods, we would note that:

- current price is $50
- previous price is $40

If we entered these values into our previous formula, we would get the following simple calculation:

```math
ROC = \dfrac {50 - 40}{40} \times 100\%\\  
= \dfrac {10}{40} \times 100\%\\  
= 0.25 \times 100\%\\  
= 25\%
```

We first subtracted $40 from $50, resulting in a difference of $10. Then, we divided this difference by the previous price of $40 and multiplied by 100 to give an ROC value of 25%. 

This means that the price increased by 25% over the specified time frame.

**Another Example**

> Suppose the current price of a stock is $80, and the price 5 periods ago was $100. Calculate the ROC over these 5 periods

In this example, we have the following values given to us:

- current price is $80
- previous price is $100

To calculate the ROC over the 5 periods, we simply need to repeat what we did in the previous example; we will enter the values for the current and previous prices into our ROC formula:

```math
ROC = \dfrac {80 - 100}{100} \times 100\%\\  
= \dfrac {-20}{100} \times 100\%\\  
= -0.2 \times 100\%\\  
= -20\%
```

In this example, we subtracted $100 from $80, resulting in a difference of -$20. Next we divided this negative difference by the previous price of $100, and finally multipled by 100 to give us an ROC value of -20%. 

This means that the price has decreased by 20% over the specified time frame.

The ROC formula allows traders to quantify the percentage change in price, providing a standardized measure of price momentum. By comparing ROC values across different time periods or assets, traders can identify relative strengths or weaknesses in price movements and make informed trading decisions based on the observed rate of change.

## Interpreting the ROC Indicator

In order to understand the underlying market dynamics, we need to first understand how to interpret the values of the ROC indicator.

### Positive/Negative values

The positive/negative values of the ROC tell us which direction the price is moving.

When the ROC is positive, it indicates that the current price is higher than the previous price. This suggests an upward momentum in the market. A positive ROC value suggests that prices have increased during the specified period. Traders often interpret a consistently positive ROC as a bullish signal, indicating a potential buying opportunity.

Conversely, when the ROC is negative, it implies that the previous price fell to the value we now have as the current price. A negative ROC value suggests that prices have decreased during the specified period. This is usually taken as a bearish signal, indicating a possible selling opportunity.

### Size/Magnitude of the ROC values

In addition to understanding the direction of price movement, the size of the ROC value can also tell us how large the price movement was. When the ROC has a large positive or negative value, traders view this as a strong bullish or bearish price movement, and a more significant price momentum. Such large values can act as valuable overbought or oversold indicators, and can be used to inform the trader that there will soon be a reversal in the direction of the market. 

However, it's important to consider the context of the specific market and use the ROC indicator in conjunction with other technical analysis tools to confirm signals and avoid false or misleading interpretations.

Extreme positive or negative ROC values indicate substantial price movements. When the ROC reaches an extremely positive value, it suggests that the price has experienced a significant upward surge, possibly signaling an overbought condition in the market.

On the other hand, extremely negative ROC values signify a significant downward movement and may suggest an oversold condition. Traders frequently use extreme values to spot opportunities for reversal or continuation patterns and view them as potential turning points in price trends.

### Crossovers

Another important consideration when interpreting the ROC indicator is crossovers. The ROC indicator has overbouht and oversold levels that act as threshold levels on the indicator chart.

When the ROC crosses above the overbought threshold, it signals that very soon, there might be a change in momentum from bearish to bullish. Traders can use this as an opportunity to open a long position.

A bearish crossover, on the other hand, occurs when the ROC crosses below the oversold line, indicating that a potential change in momentum from bullish to bearish is imminent. This can be interpreted as a sell signal, indicating that it is time to think about going short or closing out long positions.

Traders often combine extremes and crossovers to check if their trading decisions are valid. For example, if the ROC reaches an extremely positive value and forms a bullish crossover at the same time, it reinforces the bullish signal and increases confidence in potential buying opportunities. However, it is important to consider other technical indicators, market conditions and general trend analysis to avoid relying solely on ROC signals.

## Using ROC indicator in a trading strategy

As seen in the previous section, interpreting the ROC indicator is valuable in helping the trader understand the current situation of the market. This understanding can help guide the strategy used by the trader in entering positions. We can identify trends by noting that:

**A bullish crossover can signal a buying opportunity**: When the indicator value crosses the overbought line, it suggests that there is a potential change in momentum from bearish to bullish. A trader can view this transition as a signal to exit any short positions, and enter long ones.

**A bearish crossover can indicate a selling opportunity**: Conversely, when the ROC indicator crosses below the oversold line, it creates a bearish crossover. This crossover suggests that a possible change in momentum from bullish to bearish is coming. The trader can now view this as a signal to exit any long trades, and enter short ones.

As stated earlier, these signals from the ROC indicator should not be solely relied upon to make decisions. In order to make more accurate buy/sell trade decisions, traders should use any signals from the ROC indicator in conjunction with other technical analysis tools such as support and resistance levels or chart patterns to further confirm buying opportunities and improve the effectiveness of their trading decisions.

### ROC divergence can signal a potential trend reversal

Traders can also make trading decisions using the concept of **ROC Divergence**. An **ROC Divergence** occurs when the price of an asset and the ROC indicator move in opposite directions.

For example, if the price is making **higher highs and the ROC is making lower highs**, this would indicate a **bearish bias**. Conversely, if the price is making **lower lows but the ROC is making higher low**, this indicates a **bullish bias**.

A divergence between price and ROC can serve as a **warning sign of a possible trend reversal**. Traders interpret these deviations as a change in momentum and a potential sign that the current trend may be losing steam. This can prompt traders to exercise caution, consider **resizing positions**, or even **exiting positions**.

## Applying Risk Management

Risk management is an important part of a good trading strategy.  By implementing risk management techniques, traders can protect their capital, manage potential losses and increase overall profitability.

### How can we set stop-loss orders based on ROC signals

