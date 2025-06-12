# Electric-Vehicles-Data-Analysis

Interactive dashboard created for **EcoDrive Analytics Inc.** to analyze EV adoption trends across the U.S.

![EV Dashboard](https://github.com/user-attachments/assets/7d1dc408-27cf-4589-a692-11cbdea3f11e)



## Project Overview
EcoDrive Analytics Inc. is a data-driven organization focused on transforming the electric vehicle (EV) ecosystem through advanced analytics. 
Founded in response to the rapid acceleration of clean energy initiatives and sustainable transportation goals, the company provides cutting-edge data products, 
dashboards, and consulting services to stakeholders across the EV landscape.

EcoDrive partners with government bodies, automakers, environmental think tanks, and smart city projects to offer visibility into EV adoption trends, 
regional infrastructure needs, and vehicle performance metrics. By aggregating and analyzing registration and performance datasets, the firm empowers clients 
to make decisions that accelerate EV penetration and support long-term sustainability targets.

With a team of data scientists, transportation analysts, and environmental experts, EcoDrive Analytics stands at the forefront of the green mobility revolution, 
bridging the gap between raw data and strategic action.


## Data Structure Overview
This dashboard is powered by a rich dataset comprising detailed electric vehicle registration records across the United States. 
The data has been collated from multiple Department of Motor Vehicles (DMV) databases, as well as from clean fuel and transportation initiatives.

Each record in the dataset provides insights into the following fields:

- Model Year: The year in which the vehicle was manufactured.
- Make: The company or manufacturer of the vehicle (e.g., Tesla, Nissan, Chevrolet).
- Model: The specific model of the vehicle (e.g., Model Y, Leaf).
- EV Type: Classification of the vehicle as a BEV (Battery Electric Vehicle) or PHEV (Plug-in Hybrid Electric Vehicle).
- CAFV Eligibility: Indicates whether a vehicle qualifies for Clean Alternative Fuel Vehicle programs.
- State: The U.S. state where the vehicle is registered.
- Electric Range: The average distance (in miles) the vehicle can travel on a single electric charge.

This structured data forms the backbone of the interactive visualizations and summaries within the dashboard.


## Executive Summary
This dashboard presents a high-level overview of electric vehicle registrations in the U.S., highlighting trends, adoption rates, and eligibility insights.

Key Highlights:
- Total Vehicles Analyzed: 1,50,413
- Battery Electric Vehicles (BEV): 1,16,745 (77.6% of total)
- Plug-in Hybrid Electric Vehicles (PHEV): 33,668 (22.4% of total)
- Average Electric Range: 67.83 miles
- Top Manufacturer: Tesla (52.7% share)

This report offers an essential tool for decision-makers looking to understand and act on current EV market dynamics.


## Insights Deep Dive
### Vehicle Registrations Over Time:
From 2011 to 2023, EV registrations show a consistent upward trend, with a dramatic rise between 2020 and 2023. The peak occurred in 2023 with over 37,000 new vehicles. 
A sharp drop in 2024 may be due to incomplete data or lag in reporting.

![Screenshot 2025-06-12 200559](https://github.com/user-attachments/assets/0fd34df0-0735-4147-b02f-0b3c4e9ae8f9)

### Geographic Distribution:
Washington State accounts for the overwhelming majority of EV registrations (1,50,082), far surpassing any other state. 
This highlights a strong concentration of EV-friendly policies and infrastructure in the region.

![image](https://github.com/user-attachments/assets/ae3fdea7-df83-4003-9859-2a7e0bad723e)

### Top Vehicle Makes:
Tesla leads by a wide margin, making up more than half of all EVs in the dataset. Nissan, Chevrolet, and Ford also show strong participation, 
but trail significantly behind Tesla.

![Screenshot 2025-06-12 200839](https://github.com/user-attachments/assets/658e811f-2480-49ce-a35e-100d85b93ec7)

### CAFV Eligibility Insights:
A surprising 46.34% of vehicles have unknown CAFV eligibility, suggesting a data gap or lack of program clarity. Only 41.81% are confirmed eligible, 
highlighting a need for better tracking or communication.

![Screenshot 2025-06-12 201019](https://github.com/user-attachments/assets/7f0acced-2d55-4793-a929-16010f4bdec1)

### Model Trends:
Tesla’s Model Y and Model 3 are the top-performing models, collectively comprising over 37% of all EVs. 
Models from Nissan (Leaf) and Chevrolet (Bolt EV, Volt) also appear in the top 10, showing widespread manufacturer participation.


## Recommendations
1. **Capitalize on High-Adoption States:** Washington’s market dominance presents a lucrative opportunity for launching new models, services, and charging infrastructure.

2. **Enhance Data Collection Processes:** Collaborate with DMV agencies to reduce the high rate of unknown CAFV eligibility data, which hinders clean fuel policy analysis.

3. **Diversify Model Promotion:** While Tesla dominates, there’s significant room to grow the market share of emerging or underrepresented models like Volkswagen ID.4 or KIA Niro.

4. **Address 2024 Data Drop:** Validate the 2024 data for completeness. If accurate, conduct root cause analysis on potential market, regulatory, or supply chain issues.

5. **Promote EV Awareness Nationwide:** Launch initiatives and awareness campaigns in low-adoption states to promote benefits of EV ownership and infrastructure support.


## Dashboard Usage Tips
Use filters on the left to narrow down data by CAFV eligibility, EV type, make, model, and state.
- Hover over charts and map visuals for deeper insights into trends and figures.
- Switch between top-N views to analyze market concentration across brands and models.
- Track time series trends to evaluate policy or manufacturer impact on EV adoption.





















