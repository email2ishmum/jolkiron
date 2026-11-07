# JOLKIRON: Floating Solar and Smart Aquaculture Field Guide

Version 2.0, October 2026. English edition of the Bangla team guidebook.

Jolkiron is a proposal to put solar panels on ponds and other closed water bodies in Bangladesh, and to use the same electricity to run aerators that keep fish alive at night. This guide explains the problem, the design, the land and cost numbers, the risks, and the path to a 450 MW pilot scale by 2030.

This is a concept and planning document. It is not a site survey, an engineering design, or a bankable financial model. Section 13 lists what still needs to be verified.

## 1. Summary

Bangladesh has about 29,000 MW of installed generation capacity, but in 2026 the grid still hit a record load-shedding level of about 3,757 MW. The shortfall is worst at night, after the sun goes down and before the solar generation comes back. At the same time, fish ponds lose oxygen overnight, and in 2026 an estimated 6 million (60 lakh) pabda fish died from oxygen shortage in Jessore and Sharsha, causing losses of about 15.5 to 25 crore taka.

Bangladesh also has about 8.68 lakh hectares of closed water bodies (ponds, ditches, and similar), and almost none of it produces electricity.

Jolkiron uses a small part of that water surface. We cover no more than 30 percent of a pond with floating panels and leave the other 70 percent open for sunlight, plankton, gas exchange, fishing, and boats. The panels make electricity, the electricity runs aerators, and the aerators keep the water oxygenated. Extra daytime power goes to the grid, and a battery covers the night.

Key numbers at a glance:

- 450 MW pilot slot inside the national target: needs about 1,875 hectares of water surface (about 562.5 hectares of panels).
- Full 4,500 MW version: needs about 18,750 hectares, which is 2.16 percent of closed water bodies. No farmland or homestead land is needed.
- 0.5 MW example project: about 2.08 hectares of water, roughly 700 MWh a year, enough for about 290 homes.
- Estimated cost for 450 MW: about 4,050 crore taka (about 329 million USD), using base assumptions.

## 2. The goal and the problem

### 2.1 National target

Bangladesh's renewable energy strategy aims for about 10,450 MW of renewable capacity by 2030 under Category 1 (rooftop, ground-mounted, and other sources). Jolkiron is meant to contribute directly to that target. We see two routes:

- Route 1: a 450 MW floating solar slot inside the national target. Using the 30 percent rule, this needs about 1,875 hectares of water.
- Route 2: a 4,500 MW ground-mounted alternative built on water instead of land. This needs about 18,750 hectares of water, but no farmland.

We are not claiming that floating solar alone solves the power shortage. We are claiming that it can add real, clean capacity without taking land, and that the aquaculture benefit makes the investment easier to justify.

### 2.2 Electricity shortage in 2026

Peak demand hit a record 3,757 MW in 2026, up from 3,419 MW in 2023. On 11 August the country needed about 18,975 MW, but only about 15,833 MW was available, a shortfall of about 3,142 MW. The worst hour was 11 PM, when the forecast gap reached about 2,695 MW. Load-shedding in the south-west coastal districts reached 13 to 14 hours a day in October 2026.

The problem is not only the amount of power. The gap is largest after sunset, when solar output is zero. That is why a plan built on daytime solar alone is not enough, and why Jolkiron includes storage and automated control.

These figures come from PGCB and BPDB reporting and newspaper coverage for August to October 2026. We still need to link each one to a primary source (see Section 13).

### 2.3 Fish and the oxygen problem

Fish need dissolved oxygen (DO). For most farmed species in Bangladesh, a minimum of about 4 to 5 mg/L is needed. In ponds, DO rises during the day because of photosynthesis and falls at night, because plants and fish keep consuming oxygen while photosynthesis stops. The lowest point is usually around 6 AM, which is exactly when load-shedding is often at its height and aerators are off.

Field reports cited in the guide show DO as low as 0.14 to 0.72 mg/L in the Buriganga river. The guide also cites an estimated 6 million (60 lakh) fish deaths in Jessore and Sharsha from oxygen shortage, with losses of 15.5 to 25 crore taka. Shrimp exports from the area reportedly fell by about half over the last decade, and income by about 40 percent.

Ponds are not the only issue. The same water bodies that could make power also hold fish, and the fish are the livelihood of many families. Any solution has to protect them.

### 2.4 Water bodies and target areas

Bangladesh's closed water bodies cover about 8.68 lakh hectares. Ponds and ditches make up most of it, along with larger ponds, reservoirs, and other closed waters. Commercial fish and shrimp ponds, institutional ponds, and factory-owned ponds are the three customer groups we target first. The first priority districts are Mymensingh and Jessore, followed by Khulna, Satkhira, Bagerhat, Rajshahi, Natore, Rangpur, Comilla (Daudkandi), and Narayanganj.

## 3. What Jolkiron is

Jolkiron does three jobs on one water body:

1. It generates electricity from floating solar panels on up to 30 percent of the surface.
2. It uses that electricity to run aerators, pumps, and sensors that keep oxygen levels safe for fish.
3. It keeps the water environment friendly to fish, with shade on part of the surface and cooler water under the panels.

During the day, extra power goes to the grid through net metering or to a nearby user. At night, the batteries supply the aerators. The system is designed so the fish do not depend on the grid.

The design expects these benefits: fish production up 20 to 30 percent over baseline (this is a target to be tested, not a measured result), electricity output 5 to 15 percent higher than rooftop panels because the water keeps the panels cooler, and zero fish die-off as the goal for the pilot.

We want to be clear about the last point. Zero mortality is a goal. We have not measured it in a field trial yet.

### 3.1 The system flow

Solar panels float on the water. An inverter converts the DC power to AC. Aerators (paddle wheel or rotary blower types) run in the water. Pumps move water where needed. Batteries store power for night operation. A net meter records grid export. Underwater, the fish live in the open 70 percent of the pond.

Priority order for power use: aerators first, pumps second, export to the grid last. If power is short, aerators keep running and everything else waits.

### 3.2 How the floating structure is built

The chain from sun to grid: sunlight hits the panels, the panels sit on floats, the floats connect to mooring and anchors, cables run along the surface, a shore-side inverter converts the power, and the output goes to the grid as AC. Floats are UV-resistant HDPE. Cables and equipment are marine-rated. Inverters and batteries sit on the bank in a flood-safe location.

## 4. The AI aeration brain

The aeration system is controlled by an AI layer, and the human farmer does not need to start or stop it by hand.

The AI looks at three things: the water (DO, temperature, pH), the power situation (how much solar is being produced, how full the batteries are, whether the grid is on or off), and the weather forecast for the next 24 to 72 hours. From these it decides whether to run the aerators at full speed, at reduced speed, or to stop them and save power.

Example: at 2 AM, DO is falling (4.8 mg/L and dropping). The forecast says cloudy and rainy tomorrow, and the battery is at 80 percent. The AI runs both aerators at full power, holds grid export back to keep the battery full, and sends the farmer a short message: "Output tomorrow may drop. DO risk around 5 AM." No human had to decide that.

Safety: if the internet or AI fails, a hardware DO relay and a timer keep the aerators running on a fixed schedule. A manual override is always available.

Honesty note: in the current stage, the control logic is rule-based. The plan is to start with fixed rules, collect pilot data for about 12 months, and then test machine learning on that data. The AI aspect should be read as a design goal and a near-term build item, not a finished product.

### 4.1 What the data should decide

Basic rules come first. If DO is falling at night or in the early morning, aerators run before the risk becomes urgent. If the storm forecast is serious, the system switches to a safe mode and charges the batteries in advance. If power is short, the system prioritizes aerators over pumps. If DO is fine and solar is strong, aerators can slow down and extra power goes to the grid.

Solar-based aerator projects have been tested in lab-scale work, including a prototype with a 28V DC motor, a battery, and Bluetooth monitoring. A 2026 Mekong-delta study looked at solar-battery pond management. We are building on those ideas, not claiming they are proven at pilot scale in Bangladesh.

## 5. Why water beats roofs and land

Floating panels have three advantages over rooftop or ground-mounted panels in Bangladesh.

Temperature. Water cools the panels. Floating panels sit around 50 degrees Celsius, compared with about 65 degrees for rooftop or ground panels in the same conditions. Solar output falls about 0.35 percent for each degree above 25 degrees Celsius. Cooler panels therefore lose less output, which in our estimate means about 5 to 15 percent more energy per year.

Water use. Panels are cleaned regularly. Washing a floating panel sends the water back into the same pond, so there is no extra freshwater demand. Rooftop and ground systems that wash with fresh water add demand in dry regions, which is a real concern.

Land. Floating systems use water surface that is otherwise idle. They do not take farmland or homestead land.

The fish also benefit from shade on part of the surface, which cuts heat stress, and from continuous aeration. Rooftop systems offer none of that.

Cleaning water figures worldwide are rough. The guide cites around 1,200 crore gallons of water used each year to clean solar panels worldwide, and an estimated 1 to 5 million gallons per 100 MW for floating systems. Those numbers need a proper source before submission.

## 6. The 30 percent rule and land area

We use one simple rule: floating panels cover no more than 30 percent of a closed water body. The remaining 70 percent stays open for sunlight, plankton, gas exchange, fishing, and boats.

The reasoning is straightforward. Small closed ponds that are fully covered lose light and oxygen exchange, and fish suffer. A 30 percent cover keeps most of the benefit of the panels and most of the water's natural function.

Panel density is about 0.8 MW of peak capacity per hectare of panel area. A rough rule is that 1 hectare of water surface can hold about 0.24 MW, because only 30 percent of the water is covered. The range in real projects is wide, between about 0.37 and 1.33 MW per hectare of panel area, depending on design.

Calculations:

- 0.5 MW project: panel area 0.625 hectares, total water surface about 2.08 hectares (about 5.15 acres, roughly one standard pond). Open water is about 1.46 hectares.
- 450 MW slot: panel area 562.5 hectares, total water surface about 1,875 hectares. This equals about 927 pond-sized (5-acre) water bodies.
- 4,500 MW version: panel area 5,625 hectares, total water surface about 18,750 hectares, or about 9,266 pond-sized water bodies. This is 2.16 percent of the country's closed water bodies.

Land comparison: a ground-mounted plant of the same size would normally use roughly 1.5 to 2.5 hectares of land per MW, which means about 6,750 to 11,250 hectares of land for 4,500 MW. The floating version uses none of that land.

The percentages depend on assumptions. We are using a rough cover ratio and a rough panel density. Both must be confirmed on real sites.

## 7. Output, cost, and comparison with global projects

### 7.1 Output and cost

Using 1,300, 1,400, and 1,500 kWh per kWp per year as the low, base, and high cases, the estimated annual output is:

- 0.5 MW: about 700 MWh per year (range 650 to 750).
- 450 MW: about 630 GWh per year (range 585 to 675).
- 4,500 MW: about 6,300 GWh per year (range 5,850 to 6,750).

Construction cost (base case, rough): about 7 crore taka per MW for the 0.5 MW pilot, and about 9 crore taka per MW for large projects. That puts 450 MW at about 4,050 crore taka. The 4,500 MW version lands near 40,500 crore taka.

Converted at 1 USD = 123 taka (an assumed rate that must be updated before submission), the 450 MW project costs about 329 million USD.

### 7.2 Comparison with large floating solar projects

The guide compares Jolkiron with several real floating solar projects:

- HG14 Open-Sea project in China: 1,000 MW, about 1,223 hectares, offshore, with a reported capex around 1.2 billion USD, producing about 1.78 billion kWh per year.
- Omkareshwar Dam in India: 600 MW (planned), about 1,000 to 1,200 hectares, with reservoir coverage below 10 percent.
- Dezhou (China): 320 MW, about 400 hectares, with coverage of about 50 to 60 percent of the water body.
- Cirata (Indonesia): 192 MWp (145 MWac), about 250 hectares, with coverage around 4 percent.
- Tengeh Reservoir (Singapore): 60 MWp, about 45 hectares, roughly one third of the reservoir covered, with a 25-year agreement that pairs power generation with water treatment.
- Sirindhorn Dam (Thailand): 45 MW, about 121 hectares, hybrid with hydropower.
- Chapainawabganj (Bangladesh): about 800 kW, on about 2.2 hectares of pond area, with an estimated capex of about 1.5 million USD.

Jolkiron differs in one important way: the coverage limit. Most large projects cover less than 10 percent of their water body, though Dezhou and a few others go higher. Jolkiron sets a hard cap at 30 percent for all sites, which is the main reason our hectare numbers are larger.

Cost per MW in the comparison set ranges from about 0.52 to 0.75 million USD for large projects in China, Indonesia, and Singapore. The Bangladesh pilot is more expensive per MW because it is small. Our large-scale estimate is about 0.73 million USD per MW.

## 8. Bangladesh evidence, finance, and risk

### 8.1 Evidence so far

Bangladesh already has floating solar in some form. About 800 kW is operating at a pond in Chapainawabganj, financed by IDCOL with engineering support. A 1 MW project is reported at Walton in Gazipur, and a 10 kW pilot exists in Mohol. A 6.7 MW project at Hatirjheel is at the design or study stage. Abroad, the Tengeh reservoir in Singapore (60 MWp, operating) is the closest model in scale and context.

### 8.2 Finance

Possible sources include:

- Bangladesh Bank green refinancing: interest 3 to 5 percent, with a grace period of about one year and repayment over 3 to 10 years. Conventional lending in Bangladesh currently runs about 13 to 15 percent.
- IDCOL: soft loans at about 6 percent covering up to 50 percent of project cost, with grants of 20 to 50 percent in some cases.
- PKSF: around 6 percent through partner NGOs for solar projects.
- BKB and RAKUB: small collateral-free loans for agricultural businesses.

The Chapainawabganj project shows that a mix of IDCOL financing and technical support can work for a small pond-based system.

### 8.3 Risks and mitigation

Monsoon and flood: mooring must handle rising water, and the system must survive heavy flooding. Mitigation: flood-tested mooring design and a flood-safe electrical station.

Cyclone and storm: strong winds can damage panels and floats. Mitigation: wind-rated design and storm alert systems, with safe-mode operation.

Electrical hazards: a wet environment raises shock and fire risk. Mitigation: marine-rated cabling, proper grounding, and regular inspection.

Grid limits: export is limited if the local grid is weak. Mitigation: self-consumption first, grid studies, and battery backup.

Water quality: the pilot must monitor DO, temperature, and pH. Mitigation: continuous sensors and a limit on coverage at 30 percent.

Sensor failure: if DO sensors fail at night, fish can die. Mitigation: backup sensors and a hardware relay that runs aerators on a timer.

Cost overrun: prices for panels, batteries, and floats change. Mitigation: staged investment with go/no-go gates.

Permits and land-use: water body ownership and permits can take time. Mitigation: early engagement with owners, the Department of Fisheries, and SREDA, and a 5 to 10 year lease with the pond owner.

Stakeholder concerns: fishers who use the water for fishing or boats may object. Mitigation: keep 70 percent of the water open, and design layouts with fishing and navigation in mind.

## 9. Impact: people, carbon, and benefits

A 0.5 MW project generates about 700,000 kWh a year. At 200 kWh per month for a typical household, that is about 290 homes. At the country average of about 604 kWh per person per year, it covers roughly 1,160 people. At a typical office benchmark of 45 kWh per square meter per year, 700 MWh could run about 15,600 square meters of office space. For an air-conditioned commercial building at about 150 kWh per square meter per year, the same output covers about 4,700 square meters.

For the 450 MW slot, the annual output of about 630 GWh could power roughly 2.6 lakh homes at 200 kWh per month and cut CO2 by about 3.7 lakh tonnes per year, using a grid emission factor of about 582 grams per kWh (2025-26 average, to be verified).

For the 4,500 MW version, the figures scale to about 26 lakh homes and about 37 lakh tonnes of CO2 per year.

Fish and fishers: the design aims to raise fish production by 20 to 30 percent and to protect against oxygen-related die-off. Those are targets to be measured in the pilot.

Water savings: the design avoids the freshwater used for panel washing on land. Estimated savings are about 1.9 to 9.5 lakh liters per year for the 0.5 MW project, and 1.7 to 8.5 crore liters for 450 MW. These are estimates.

## 10. National scale: 1,500 crore taka, 450 MW, 4,500 MW

Three national scenarios were compared.

Scenario A: 1,500 crore taka invested. This buys about 167 MW of capacity, about 233 GWh per year, about 694 hectares of water surface, and about 97,000 homes.

Scenario B: the national target slot of 450 MW. This is about 630 GWh per year, about 1,875 hectares of water surface, about 4,050 crore taka in cost, and roughly 2.6 lakh homes.

Scenario C: 4,500 MW, a full grid-level version. This is about 6,300 GWh per year, about 18,750 hectares of water surface, about 40,500 crore taka, and roughly 26 lakh homes.

To cover the 2026 average load-shedding gap of about 15,700 MW, the system would need about 22,000 GWh per year and about 65,400 hectares of water surface (about 7.5 percent of closed water bodies). The cost would be about 1.4 lakh crore taka. That is possible in principle, but it is a long-term effort and needs storage, not just generation.

Average load-shedding in 2026 is about 2,509 MW. A 4,500 MW version of Jolkiron produces about 720 MW on average over the year, which is about 29 percent of the average shortfall. The rest must come from other sources and from storage.

The point is not that water alone solves the problem. The point is that water surface is a large, unused resource, and it can be used without taking land.

## 11. Investor returns compared with a bank

We compared returns for a small 0.5 MW project and a large project against a bank deposit.

Bank deposit at about 9 percent (estimated): 1 crore taka earns about 9 lakh taka a year, and roughly 8.62 crore taka after 25 years if all income is reinvested at 9 percent.

0.5 MW project, conservative case: IRR about 3.0 percent, payback about 16 years.

0.5 MW project, base case: IRR about 8.2 percent, payback about 10 years. 1 crore taka grows to about 8.08 crore taka in 25 years.

0.5 MW project, optimistic case: IRR about 15.0 percent, payback about 6.25 years.

Large project, base case: IRR about 12.3 percent, payback about 7.4 years. 1 crore taka grows to about 10.98 crore taka in 25 years.

Large project with cheap green loans (6 percent): IRR about 17.6 percent.

Returns depend heavily on assumptions: electricity price (we assume 10 to 14 taka per kWh for small projects and 8 to 11 taka per kWh for large projects), a 0.5 percent per year degradation, O&M at 2 percent of capex per year, and no tax. Inflation in August 2026 was reported at 8.26 percent, which means the real return on a 9 percent deposit is only about 0.7 percent.

The conservative case is worse than a bank deposit. That is an honest finding. It means the project only beats a bank if the scale grows, the cost falls, and the loan is cheap. Our plan depends on those three things.

## 12. Timeline to 2030

The path to 450 MW is staged, with a go or no-go decision at each stage.

Stage 0, preparation (late 2026 to 2027): identify 3 to 5 sites, sign agreements, get permits, prepare the detailed project report, and secure financing. Priority districts are Mymensingh and Jessore.

Stage 1, 0.5 MW pilot with AI control (2027 to 2028): build one pilot, run it for 12 months, and measure DO, output, and fish results. Target: about 2.1 hectares of water and about 7 crore taka.

Stage 2, 10 MW cluster (2028 to 2029): build a cluster of several sites in Mymensingh, Jessore, and Khulna. Target: about 42 hectares and about 92 crore taka.

Stage 3, 100 MW (2029): scale with large water bodies, using EPC contracting and PPP models. Target: about 417 hectares and about 900 crore taka.

Stage 4, 450 MW (2030): national deployment. Target: about 1,875 hectares and about 4,050 crore taka.

Go or no-go gates:

- Gate 0 to 1: owner agreement, government approval, and financing commitment.
- Gate 1 to 2: at least 1,300 kWh per kWp per year, DO at or above 5 mg/L, no fish die-off, and cost at or below 12 crore taka per MW.
- Gate 2 to 3: cluster is stable, customers are satisfied, and cost is within target.
- Gate 3 to 4: PPA or PPP contract signed, supply chain ready, and national approval granted.

Important: even if permits or financing are delayed, the floor is at least 100 MW by 2030. If a gate fails, the next stage waits. That is a deliberate choice. We would rather be slow and right than fast and wrong with fish.

## 13. Appendix

### 13.1 Thirty-second pitch

"Bangladesh had peak load-shedding of about 3,757 MW in 2026, and fish in ponds die at night from oxygen shortage. Our project puts solar panels on about 30 percent of a pond, uses the power to run aerators with an AI controller, and sends the rest to the grid. A 450 MW version needs about 1,875 hectares of water, which is 0.22 percent of the country's closed water bodies, and no farmland. We have not built the full system yet, so we are proposing a 0.5 MW pilot to test the numbers in the field."

### 13.2 Likely hard questions

Can 450 MW by 2030 really happen? The 2030 target is a planning goal, not a forecast. Stage gates mean the project slows down if conditions are not met. The floor is 100 MW.

If solar works on roofs, why put it on water? Roofs are limited in area and much hotter. Water cools panels, adds fish benefits, and does not take farmland.

Solar does not work at night. How does load-shedding get reduced? Batteries and AI-controlled storage, plus grid storage at larger scale. We do not claim 100 percent of night-time shortfall is covered by the pilot.

Will the panels harm the fish? The 30 percent cap leaves most of the water open. DO, temperature, and pH are monitored. The pilot will measure fish results. Zero mortality is a goal, not a proven claim.

Is the bank return better? In the base case for large projects, yes (about 12.3 percent IRR vs about 9 percent). In the conservative case for small projects, no. That is why large scale and cheap loans are central to the plan.

How does the cost compare internationally? Large projects in China, Indonesia, and Singapore cost about 0.52 to 0.75 million USD per MW. Our large-scale estimate is about 0.73 million USD per MW.

### 13.3 Key assumptions

- Panel density: 0.8 MWp per hectare of panel area (range 0.5 to 1.2).
- Cover ratio: 30 percent of closed water surface, maximum.
- Annual yield: 1,300, 1,400, and 1,500 kWh per kWp (conservative, base, optimistic).
- Degradation: 0.5 percent per year.
- O&M: 2 percent of capex per year (1.5 percent in optimistic case).
- Cost: 0.5 MW about 8, 7, and 6 crore taka per MW (conservative, base, optimistic). Large projects about 12, 9, and 7 to 8 crore taka per MW.
- Electricity price: 0.5 MW at 10, 12, and 14 taka per kWh. Large projects at 8, 10, and 11 taka per kWh.
- Household use: 200 kWh per month (range 150 to 250).
- Grid emission factor: 582 g CO2 per kWh.
- Exchange rate: 1 USD = 123 taka.
- Bank deposit: about 9 percent (estimated). Policy rate 9.5 percent (September 2026).
- Inflation: 8.26 percent (August 2026).

### 13.4 Glossary

MW: megawatt, 1,000 kW. MWp: peak megawatt of panels.
kWh, MWh, GWh: units of electricity. 1 MWh = 1,000 kWh. 1 GWh = 1 million kWh.
DO: dissolved oxygen in water, measured in mg/L. Fish need at least 4 to 5 mg/L.
Capacity factor: the share of time a plant runs at full output over a year. Solar in Bangladesh is about 16 percent.
Net metering: exporting surplus power to the grid and having it credited against the bill.
CAPEX / O&M: upfront construction cost and yearly operating and maintenance cost.
IRR: internal rate of return, the average annual return on an investment, comparable with a bank interest rate.
PPA: power purchase agreement, a long-term electricity sale contract.
IDCOL, SREDA, PBS, PGCB, BPDB: Infrastructure Development Company, Sustainable and Renewable Energy Development Authority, Palli Bidyut Samiti, Power Grid Company of Bangladesh, Bangladesh Power Development Board.

### 13.5 Scope and limits

This guide is a concept and planning document. Site surveys, environmental impact assessment, structural design, legal review, bankable financial modeling, and pilot data are still needed. Currency and power prices are assumptions. Real tender prices and pilot results should replace these numbers when they are available.
