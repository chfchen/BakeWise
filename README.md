# BakeWise

A Simple and Practical Way to Plan Tomorrow's Baking · Prototype for Hackathon Taskforge Project · By Charles Chen

## Relevant Links
- **Live Demo:** https://bakewise-chfchen.streamlit.app/
- **Demo Video:** https://www.youtube.com/watch?v=30R3yJQzmF4

## Main Features
- Quick daily entry of produced and leftover quantities
- Next-day demand forecasts using historical sales, weekdays, holidays, and weather
- Lean, Balanced, and Safe Buffer production strategies
- Immediate production recommendations and downloadable plans
- Automated delivery of production plans to owners and staff via email or text message at scheduled times (to be implemented)
- Simple interface designed for less than five minutes of daily effort

## Development Tools
Python, pandas, scikit-learn, Streamlit, and CSV-based data storage.

## Forecasting Method

**BakeWise** uses ridge regression to estimate demand based on historical sales, weekdays, holidays, and weather conditions. Production recommendations balance estimated demand against the risks of food waste and stockouts.

The prototype uses synthetic historical data and simplified production adjustments. Forecasts have not been validated with real bakery sales.

## Future Improvements

Planned features include automated email notifications, POS integration, additional forecasting factors, a mobile app, and an optional analytics dashboard.
