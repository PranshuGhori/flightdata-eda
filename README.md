# ✈️ Flight Delay and Cancellation Analysis (2019–2023)

Exploratory Data Analysis of **~3 million U.S. flights** between 2019 and 2023.

Dataset:  
https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023

---

# Dataset Description

The dataset contains information about:

- Airlines
- Departure and arrival airports
- Flight delays
- Cancellation status
- Delay causes
- Distance and scheduling information

---

## Key Columns

| Column | Description |
|------|-------------|
| AIRLINE | Airline operating the flight |
| ORIGIN | Departure airport |
| DEST | Arrival airport |
| DEP_DELAY | Departure delay (minutes) |
| ARR_DELAY | Arrival delay (minutes) |
| CANCELLED | Flight cancellation indicator |
| DIVERTED | Flight diversion indicator |

---

# Total Flights

The dataset contains approximately:

**3,000,000 flight records**

Each observation corresponds to a scheduled commercial flight.

---

# Average Delay

Average delays across all flights:

| Type | Average Delay |
|-----|---------------|
| Departure Delay | ~10 minutes |
| Arrival Delay | ~4 minutes |

Flights often recover time in the air because airlines build buffer time into schedules.

---

# Airline Performance

Airlines with the highest delays:

- JetBlue Airways
- Frontier Airlines

Airlines with the best punctuality:

- Alaska Airlines
- Horizon Air
- Hawaiian Airlines

---

# Delay Causes

Average delay contribution by cause:

| Cause | Avg Delay (minutes) |
|------|--------------------|
| Late Aircraft | 4.53 |
| Carrier Issues | 4.41 |
| NAS (ATC) | 2.3 |
| Weather | 0.7 |
| Security | 0.03 |

Late aircraft arrivals and airline operational issues are the primary drivers of delays.

---

# Seasonal Delay Patterns

| Season | Avg Departure Delay |
|------|---------------------|
| Summer | ~13.8 min |
| Winter | ~10.2 min |
| Spring | Moderate |
| Fall | Lowest delays |

Summer delays are mainly driven by increased traffic and weather disruptions.

---

# Key Insights

Major findings from the analysis:

• Late aircraft turnover and airline operations cause most delays  
• Morning flights are significantly more punctual  
• Evening flights accumulate delays during the day  
• Major hubs maintain better reliability than regional airports  
• Short-haul flights experience higher delay rates  

---
##
# Conclusion

Flight delays are primarily caused by **operational scheduling and aircraft turnaround**, rather than weather.

Improving aircraft scheduling, airport coordination, and turnaround efficiency could significantly improve airline punctuality.
