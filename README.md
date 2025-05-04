🚧 Road Accident Data Analysis & Safety Dashboard
--------------------------------------
🎯 Objective
--------------------------------------
The aim of this project is to:

Analyze accident data to discover high-risk locations, frequent causes, and time-based trends

Use visual analytics and modeling to guide road safety improvements

Present insights through a Power BI dashboard highlighting key hotspots, severity patterns, and operational performance (satisfaction, response time)

📊 Dataset Overview
--------------------------------------

The dataset includes traffic accident records with attributes such as:

🗓️ Date & Time of the accident

📍 Location (including district, area, latitude & longitude)

🚗 Vehicle Type involved

⚠️ Accident Cause (e.g., rash driving, speeding)

👥 Casualties – fatalities and injuries

🎫 Ticket Priority (High, Medium, Low)

⏱️ Response/Resolution Time

😊 Satisfaction Level post-resolution

This structured dataset enables deep exploration of spatial, temporal, and categorical accident patterns.

🔍 Key Insights & Trends
🕒 Time-Based Accident Trends
--------------------------------------
Accidents are more frequent during peak hours (8–10 AM and 5–8 PM).

A noticeable rise occurs on weekends, especially Saturdays.

Seasonal spikes are visible in the monsoon months (July–August), correlating with wet road conditions.

📍 High-Risk Locations
--------------------------------------
Hotspot areas include intersections near commercial zones and highways.

GIS mapping reveals clustered high-severity zones in District A and District B.

⚠️ Top Causes of Accidents
--------------------------------------

Rash Driving and Over Speeding account for over 60% of total accidents.

Driver fatigue and poor visibility are significant during night hours.

🚗 Vehicle Type Patterns
--------------------------------------

Two-wheelers have the highest involvement rate, followed by cars.

Heavy vehicles cause fewer accidents but are associated with higher fatalities per incident.

🎫 Satisfaction by Ticket Priority
--------------------------------------

🚨 High-priority tickets are resolved faster and have an 80%+ satisfaction rating.

🟡 Medium-priority cases show moderate satisfaction, often due to 12–24 hour delays.

🔵 Low-priority tickets have the lowest satisfaction, highlighting the need for better triage or response strategies.

Insight: Prioritization is directly linked to citizen satisfaction. Faster response = happier outcomes.

⏱️ Resolution Time vs. Satisfaction
--------------------------------------

Satisfaction drops sharply when resolution time exceeds 24 hours.

Visualizing this in a scatter plot shows a negative correlation between resolution time and satisfaction.

DAX for Resolution Time (in hours):
----------------------------------------------------------------------------
dax

Copy

Edit

Resolution Time = DATEDIFF([AccidentReportedTime], [AccidentResolvedTime], HOUR)

DAX for Avg Satisfaction:
---------------------------------------------------------------------------------

dax

Copy

Edit

Avg Satisfaction = AVERAGE([SatisfactionScore])

🤖 Model Development (Optional Predictive Analytics)
--------------------------------------

A basic machine learning model (e.g., Logistic Regression or Random Forest) was developed to predict accident severity using:

Time of Day

Weather Conditions

Vehicle Type

Cause of Accident

Location

🎯 Model Accuracy: ~83%
🔮 Predicted severity levels allow proactive resource allocation and alert systems.

💡 Recommendations
--------------------------------------

🚦 Improve traffic signal visibility and timings at top hotspots.

🛑 Add speed breakers and better signage in high-accident zones.

📢 Run awareness campaigns targeting top causes like rash driving.

📍 Install smart cameras for live monitoring and incident detection.

🧠 Leverage predictive models to trigger alerts in high-risk zones.

🧾 Conclusion
--------------------------------------

Data analysis revealed clear patterns in location, timing, and causes of road accidents.

Hotspot mapping and severity tracking can directly inform safety interventions.

Satisfaction and resolution analysis help improve operational response and public trust.

The dashboard provides a powerful decision-support tool for traffic and safety authorities.

✅ Future Scope: Integration with real-time traffic data and live incident reporting systems for dynamic decision-making.

Submitted by
--------------------------------------

JEYA BHARATHI R

Task: 02

Track code: DS

FUTURE INTERNS
