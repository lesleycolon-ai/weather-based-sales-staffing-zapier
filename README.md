\# Weather-Based Sales and Staffing Automation



A TripleTen AI Automation portfolio project that uses Zapier, the OpenWeather API, Gemini AI, Gmail, and conditional logic to generate daily sales, staffing, and promotion recommendations.



\## Business Problem



A weather-sensitive kiosk manager spends time each morning checking the forecast and making manual decisions about staffing, inventory, and promotions. This process can be inconsistent and may delay operational planning before the business opens.



\## Solution



This automation runs each morning at 7:00 AM and:



1\. Uses a Zapier Schedule trigger to start the workflow.

2\. Retrieves live weather data from the OpenWeather API through Webhooks by Zapier.

3\. Sends weather conditions to Gemini AI using a structured prompt.

4\. Generates a recommended product focus across hot drinks, cold drinks, gelato, and pastries.

5\. Generates a staffing recommendation to add, reduce, or maintain current staffing.

6\. Creates two weather-specific promotional messages of fewer than 120 characters.

7\. Sends a formatted daily plan to the manager through Gmail.

8\. Triggers a separate severe-weather alert when the temperature is above 91°F or the forecast contains “storm” or “rain.”



\## Tech Stack



\- Zapier

\- Zapier Schedule

\- Webhooks by Zapier

\- Zapier Filters

\- OpenWeather API

\- Gemini AI

\- Gmail

\- Prompt engineering

\- Conditional logic



\## Testing and Validation



\- Tested the scheduled trigger, OpenWeather API request, Gemini AI prompt, and manager email output.

\- Verified that weather data flowed from the API through Gemini AI to a formatted Gmail message.

\- Tested severe-weather filter logic for temperatures above 91°F and weather descriptions containing “storm” or “rain.”

\- Identified future opportunities to add error alerts, API fallback data, monitoring, sales tracking, inventory integration, and multi-location support.



## Screenshots and Documentation



[View the weather-based sales and staffing case study](docs/weather-based-sales-staffing-case-study.pdf)



\## Future Improvements



\- Add error monitoring and alerts when a Zap step or API request fails.

\- Use cached or prior-day weather data as a fallback if the API is unavailable.

\- Log weather data, AI recommendations, and sales results to measure performance over time.

\- Integrate inventory data and dashboards to evaluate product recommendations.

\- Expand the workflow to support multiple locations.



\## Note



This is a TripleTen portfolio project built with hypothetical business data for demonstration and learning purposes.



\## Author



Lesley Colon  

AI Automation Specialist  

\[LinkedIn](https://www.linkedin.com/in/lesleycolon)

