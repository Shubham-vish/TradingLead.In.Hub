# Moving Average Crossover Strategy | Pine Script Indicator Tutorial (Part 3)

Welcome to Part 3 of our TradingView Pine Script series! 🎥  
In this video, we create an **Exponential Moving Average (EMA) Crossover Strategy**, which generates **Buy** and **Sell** signals based on the crossover of two moving averages. Perfect for traders looking to build their own custom indicators!

## 🔥 What You'll Learn:

- How to define short and long EMAs (14 & 50 periods).
- Using crossover and crossunder functions in Pine Script.
- Plotting Buy (Green Arrows) and Sell (Red Arrows) signals on your chart.
- Step-by-step coding tutorial with clear explanations.

## 💻 Code Example:

```pinescript
//@version5
indicator("Crossover Strategy", overlay=true)
shortMA = ta.ema(close, 14)
longMA = ta.ema(close, 50)
buySignal = ta.crossover(shortMA, longMA)
sellSignal = ta.crossunder(shortMA, longMA)
plot(shortMA, color=color.red)
plot(longMA, color=color.blue)
plotshape(buySignal, style=shape.triangleup, location=location.belowbar, color=color.green)
plotshape(sellSignal, style=shape.triangledown, location=location.abovebar, color=color.red)
```

## 🛠️ Steps in the Video:

1. Open the Pine Editor on TradingView.
2. Define the moving averages using `ta.ema`.
3. Use `ta.crossover` and `ta.crossunder` to calculate Buy and Sell signals.
4. Plot the signals and moving averages directly on your chart.
5. Save and add the indicator to your chart.

## 💡 Bonus:

Want the full code? Just comment **"Code"** on this video, and we'll share it with you! 🙌

## 🚀 Next Up:

In Part 4, we'll enhance this strategy with **trend confirmation filters** to make your signals even more accurate. Don't forget to **subscribe** and turn on notifications 🔔 so you don’t miss out!

## 📚 Other Tutorials in This Series:

- Part 1: Introduction to Pine Script.
- Part 2: Creating Indicators with Custom Alerts.

## 👍 Like, Share, and Subscribe

If you find this helpful, your support keeps us motivated to create more valuable content.

## **Follow us for more insights and strategies:**

- 🌐 Website: [tradinglead.in](https://tradinglead.in)
- 📸 Instagram: [@TradingLead](https://instagram.com/tradinglead)
- 🎥 YouTube: **Subscribe now!**

**#TradingView #PineScript #MovingAverage #TradingIndicators #LearnToTrade #TechnicalAnalysis #TradingLead**
