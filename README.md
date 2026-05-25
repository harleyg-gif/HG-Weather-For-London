# 🌤️ World Weather Forecast 2026

An interactive extended weather forecast for any location covering 16 days. Features detailed daily predictions, heatwave analysis, and real-time feel-like temperature calculations.

## Features

✨ **Interactive Forecast**
- 62-day extended forecast with hourly breakdowns
- 4 interactive graph views (Temperature, Rain, Humidity, Wind)
- Click any day or bar for detailed weather information

🌡️ **Advanced Temperature Metrics**
- Daily high and low temperatures
- "Feels like" calculations for both sun and shade
- Wind chill and humidity adjustments
- Record reference lines showing historical data
- Heatwaves Strengths Are Partially Estimated Based On Pressure Data

🎨 **Beautiful Visualization**
- Color-coded temperature scale from cool to extreme heat
- Dynamic color indicators for rain, humidity, and wind
- Responsive design works on mobile and desktop
- Smooth animations and interactive popups

⚡ **Storm Risk Alerts**
- Automatic detection of dangerous temperature/humidity combinations
- Special indicators for potential thunderstorm days

📊 **Data Sources**
- First 5 days: Met Office confirmed data
- Days 6-15: Near-term forecast
- Days 16+: Estimated forecast with heatwave bias adjustments

## Forecast Methodology

This forecast accounts for:
- **Jet Stream Position** - North-displaced jet stream favoring UK heat events
- **Dry Soil Effect** - England's driest spring (2025) amplifies peak temperatures by 2-4°C
- **Model Bias** - Upward adjustments for known heatwave underestimation
- **Record Risk** - Peaks reach 36°C (Jun 20) and 38°C (Jul 5), challenging London's 35.6°C June record

## Technical Stack

- **Frontend**: React 18 with JSX
- **Styling**: Inline CSS with gradient backgrounds
- **Libraries**: React DOM, Babel standalone
- **Hosting**: GitHub Pages
- **Format**: Dual HTML And json file with embedded React

## How to Use

1. Visit: https://harleyg-gif.github.io/HG-Weather-For-London/
2. Click any day card or bar chart to view detailed metrics
3. Use the tabs to switch between Temperature, Rain, Humidity, and Wind graphs
4. Hover over bars for quick tooltips
5. Check the "Forecast Rationale" section for methodology details

## Live Updates

The forecast data is static for this 2026 period but can be easily updated by modifying the `forecastData` array in `index.html`.

---

**Created**: May 2026  
**Disclaimer**: This is an extended forecast. Actual weather may vary slightly or significantly as it is impossible to gage the exact conditions for a 2 month forecast.
