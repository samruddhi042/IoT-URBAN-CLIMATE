# Comparative Literature Review: Urban Heat Island Monitoring and Mitigation

**Project context:** IoT-Based Smart Urban Heat Island Monitoring and Mitigation System  
**Purpose:** Compare the uploaded papers by research area, objective, location, methods, findings, mitigation approach, limitations, and relevance to the proposed IoT system.

> **How to read this document:** The paper-specific details below are based on the uploaded PDFs and their extracted text. “Not reported in the accessible extracted text” means an exact detail should be checked in the original paper before it is quoted. Interpretations and proposed project opportunities are marked separately from reported paper findings. Land Surface Temperature (LST) is not the same measurement as near-surface air temperature; satellite-derived LST and ground-sensor air temperature should not be treated as interchangeable.

## 1. Executive comparison

| # | Paper / study | Research area and location | Main goal | Method / data | Main reported results | Mitigation or practical implication |
|---:|---|---|---|---|---|---|
| 1 | **Assessment of Potential Temperature Increases in the UAE due to Future Global Warming** (IEEE ASET, 2022) | Climate-change projections; United Arab Emirates | Estimate future air-temperature change under alternative emissions scenarios. | Historical records from 20 weather stations; averages from three global circulation models; RCP4.5 and RCP8.5; near future 2021–2050 and far future 2051–2080. | The paper reports a near-future average air-temperature increase of **1–2.8°C** and, under RCP8.5 for the far future, **1.9–4.15°C**. The far future is projected to warm more than the near future, particularly under RCP8.5. | Supports planning for a warmer baseline and scenario-based adaptation. It is a regional climate-projection study, not a real-time city IoT deployment. |
| 2 | **Comparative Analysis of Urban Heat Island (UHI) Intensity using Remote Sensing: A Case Study of Thanjavur and Tiruchirappalli** (IEEE ICSCDS, 2025) | Comparative Indian urban climate; Tamil Nadu | Compare urban–rural UHI intensity and seasonal/temporal variation over 2012–2022. | MODIS-derived LST, urban/rural comparison, temporal and seasonal analysis, and NDVI vegetation index. | Tiruchirappalli is reported to have consistently higher UHI intensity than Thanjavur, with seasonal variation. Rural areas generally show more vegetation; Thanjavur showed improved vegetation levels. | Recommends increased green cover and reflective building materials. Demonstrates why cities/zones should be compared rather than using one city-wide temperature value. |
| 3 | **Dynamic Evolution of Surface Urban Heat Island in Beijing** (IGARSS, 2019) | Long-term urban heat dynamics; Beijing, China | Examine summer LST and the spatial expansion of the surface UHI from 2005–2015. | Remote-sensing LST; urban–rural gradient; analysis of heat-island extent and influencing factors. | Summer LST showed an increasing trend and UHI extent expanded rapidly over the study period. At township scale, building area, population and GDP had significant positive relationships with LST; those relationships were not significant at district scale. | Supports monitoring urban growth and heat patterns at more than one spatial scale. The paper identifies patterns and drivers rather than testing an IoT mitigation controller. |
| 4 | **Future Heat Risk Index: The Case of Attica Regions, Greece** (IEEE IISA, 2024) | Future heat-risk and population vulnerability; Attica, Greece | Identify future heat-risk areas under climate-change scenarios and prioritize interventions. | Future Heat Risk Index integrating climate projections/scenarios, spatial analysis, population change and current tree canopy; the paper discusses RCP8.5 for 2040. | Identifies high-risk areas and stresses that heat risk is shaped by the built environment and population vulnerability, not temperature alone. The abstract compares vegetation enhancement and cool materials; exact quantitative comparison should be taken from the paper's result tables. | Vegetation enhancement and cool/reflective materials are proposed and compared. Useful model for adding vulnerability and future climate context to a monitoring dashboard. |
| 5 | **Mitigation Strategies for a Moderate Radiative Temperature of the Land Surface: A Case Study on Local Scale Urban Heat Island in Sub-Urban Region of India** (IEEE M2GARSS, 2022) | Local-scale UHI mitigation; suburban India | Evaluate different mitigation strategies with an urban microclimate simulation. | ENVI-met urban microclimate modelling; 3D representation based on surveyed site/buildings and environmental/material inputs. | The paper evaluates mitigation options through simulation. The accessible extracted text describes the setup but does not provide a sufficiently reliable complete set of numerical outcome values for this table. Verify the result figures/tables before quoting temperature reductions. | Shows the value of testing interventions in a model before deployment. For an IoT project, use sensor readings to calibrate or evaluate simulations and compare before/after conditions. |
| 6 | **Observation Experiments and Analysis of Summer Urban Heat Island in Cold Region Based on Low-Altitude Dual-Source Remote Sensing: A Case Study of Zhengzhou University Main Campus** (IEEE JSTARS, 2025) | High-resolution UHI observation; Zhengzhou University, China | Characterize summer surface UHI across different underlying surfaces using a high-precision observation approach. | A low-altitude dual-source remote-sensing platform; synchronized thermal-infrared and hyperspectral data; retrieved LST; underlying-surface classification; SUHII and heat-field intensity index. | The authors report that fusion of thermal-infrared and hyperspectral data established relationships between surface type and temperature and enabled high-resolution SUHII calculation using vegetation as a cool reference. | Supports combining surface-type/vegetation information with thermal measurements. The method provides spatial detail, while fixed IoT sensors could add repeated local time-series readings. |
| 7 | **Optimizing Urban Heat Response with IoT-Driven Manhole Heat Detection using Recurrent Neural Networks** (IEEE I-SMAC, 2024) | IoT infrastructure monitoring and forecasting; urban manholes, India-based authors | Monitor subsurface heat dynamics and forecast heat trends to support proactive response. | IoT sensor nodes and an RNN-based forecasting approach; the abstract describes real-time monitoring and a case study in a crowded metropolitan setting. | The authors state that the case study demonstrates the potential of combining IoT with RNNs for improved urban heat response. Exact model metrics and numerical performance should be verified in the paper's evaluation section before citing. | Most directly relevant to the IoT/AI component. Its scope is subsurface/manhole heat, so it does not by itself validate a general city-wide UHI monitoring solution. |
| 8 | **Risk Assessment of Global Temperature Anomalies Using Intelligence Frameworks: Evaluating the Impact of Socioeconomic Factors and with a Case Study on Heatstroke Deaths in India** (IEEE ICAIHC, 2025) | Temperature anomalies, forecasting and public-health risk; India | Explore relationships between temperature anomalies and heatstroke and forecast future high-risk periods/regions. | Historical climate and heatstroke/fatality data; supervised regression models including linear, lasso, ridge and voting regressor; time-series analysis and Prophet are described. | The abstract reports that extreme heatwaves, humidity and urbanization factors contribute to heatstroke occurrences. It states ridge regression performed strongly in the described prediction work, but exact metrics should be checked before quoting. | Supports heat alerts that include health risk and socioeconomic context, not just a temperature threshold. It is a forecasting/public-health study rather than a physical mitigation trial. |
| 9 | **Sustainable Decision-Making in Urban Design: Softscape Solutions for Mitigating Urban Heat Island Effects in Hot-Arid Climates** (IEEE DASA, 2024) | Outdoor thermal comfort and softscape interventions; hot-arid climate | Compare three softscape treatments for urban walkways. | ENVI-met microclimate simulation comparing three treatments against an untreated baseline. | All three treatments reduced temperature relative to the untreated base case. The paper reports no statistically significant difference among the three treatment types in overall performance, while each improved conditions compared with the baseline. | Supports softscape/vegetation and climate-sensitive walkway design. Compare interventions against a baseline and report both effect size and statistical significance where available. |
| 10 | **Urban Expansion and Its Impact on Urban Heat Island Intensity: A Case Study of Chengdu City, China** (IEEE Geoinformatics, 2022) | Urban expansion and UHI dynamics; Chengdu, China | Analyze coupling between construction-land expansion and UHI expansion from 2002–2020. | WRF mesoscale weather simulation combined with remote-sensing land-cover products; mean-standard-deviation method and spatial centre-of-gravity analysis. | Urban expansion and UHI expansion were synchronized overall. Construction-land area nearly doubled (the abstract's percentage appears in the source and should be checked carefully before reuse); UHI size and intensity expanded during day and night. The relationship showed stages: strong spatial coupling in 2002–2011 and weaker construction-land influence in 2011–2020. | Supports combining land-cover/urban-growth data with temperature data. Also warns that relationships can change by time period and spatial scale. |
| 11 | **Urban Heat Island and Heat Vulnerability Assessment with Ground Validation: A Case Study for Makati City** (IEEE TENCON, 2025) | Heat mapping, social vulnerability and ground validation; Makati City, Philippines | Identify heat hotspots and communities more vulnerable to heat-related impacts, then validate maps using field devices. | Landsat 8 LST (2013–2023); NDVI/NDBI and demographic indicators; HVI maps; three planned prototype-device locations; temperature/humidity measurements over about one month. | The paper reports average city LST of **43.60°C** from its satellite-derived analysis. Forbes Park had an HVI score of **8**, while Pembo and Rizal each scored **23**. Field data reported Rizal average temperature **34.37°C** and RH **57.68%**; Pembo average temperature **31.94°C** and RH **62.56%**. The Forbes Park deployment was still pending approval in the reported results. | Strong example of combining remote sensing, demographic vulnerability and ground validation. Note that satellite LST and the prototype's air-temperature readings are different measurements and should not be directly compared as if equivalent. |
| 12 | **Urban Heat Island and Its Impact on Impervious Surfaces During Two Seasons: A Case Study of Bangalore** (IEEE InGARSS, 2021) | Seasonal UHI and land-cover relationship; Bengaluru, India | Examine how impervious/built surfaces and green spaces relate to LST in March and November 2020. | Landsat 8 band 10 for LST; NDVI and NDBI; land-use/land-cover classes: built-up, vegetation, water and bare soil. | NDVI–LST correlation was **−0.32 in March** and **−0.11 in November**. NDBI–LST correlation was **0.63 in March** and **0.28 in November**. Mean built-up LST was **36.18°C in March** and **22.40°C in November**. The authors report a stronger UHI effect in summer than winter. | Supports prioritizing built-up and low-vegetation hotspots, with season-aware analysis. It is a two-season satellite study, not continuous in-situ monitoring. |

## 2. Research-area comparison

| Research theme | Papers that contribute | What this group of papers establishes |
|---|---|---|
| Long-term urbanization and UHI expansion | Beijing; Chengdu | Urban form, construction land, population and economic activity can be associated with changing heat patterns; spatial scale and period matter. |
| India-specific city and seasonal comparisons | Thanjavur–Tiruchirappalli; Bangalore; suburban India mitigation | Vegetation, built-up surfaces and seasonality matter; local context is important and one city's results should not automatically be generalized to another. |
| Remote sensing and surface characterization | Thanjavur–Tiruchirappalli; Beijing; Zhengzhou campus; Bangalore; Makati; Chengdu | Satellite or low-altitude remote sensing gives spatial coverage and helps identify hotspots and surface types. It does not, by itself, provide continuous near-surface air-temperature data at every location. |
| Mitigation evaluation | Suburban India ENVI-met study; softscape solutions; Attica heat-risk study | Green/softscape approaches and cool materials are evaluated or recommended, but the strength of quantitative evidence differs across the papers. |
| Climate-change scenarios and future risk | UAE projections; Attica FHRI | Heat planning should account for future climate scenarios rather than assuming historical temperatures are the future baseline. |
| IoT and AI forecasting | IoT manhole/RNN paper; India heatstroke forecasting paper | Connected sensing and predictive models can support early warning. Their use cases and targets differ: subsurface infrastructure heat versus population health/temperature risk. |
| Social vulnerability and validation | Makati; Attica; India heatstroke study | Temperature alone is insufficient to describe human risk; demographics, exposure and health vulnerability can affect priority. |

## 3. Cross-paper conclusions

### A. What is already well established by these studies?

1. **Built-up and impervious surfaces are repeatedly associated with warmer surface conditions.** Bangalore, Chengdu, Beijing and the comparative Indian study connect urban form/urbanization with UHI patterns.
2. **Vegetation is a recurring cooling indicator and mitigation option.** NDVI analysis in Bangalore and the Thanjavur–Tiruchirappalli study, along with softscape work, supports incorporating vegetation into analysis.
3. **Heat is spatially and seasonally variable.** Bangalore reports stronger UHI effects in March than November; the Indian city comparison reports seasonal fluctuations; Beijing and Chengdu examine multi-year spatial evolution.
4. **Remote sensing is useful for mapping but has a different role from ground sensors.** Satellite LST supports spatial comparisons, while field sensors can provide repeated local air-temperature and humidity observations.
5. **Future climate and human vulnerability should influence priorities.** The UAE and Attica papers address climate scenarios, while Makati and the India heatstroke study add vulnerability or health context.
6. **Mitigation should be evaluated rather than merely listed.** The softscape paper compares interventions with an untreated baseline. This is a useful model for an evidence-based evaluation plan.

### B. Limitations and gaps suggested by the collection

These are cross-paper observations, not claims that every paper has every limitation.

- **Temporal sampling:** Several remote-sensing studies rely on particular satellite dates, seasons or revisit intervals; this may miss rapid daily changes and short heat events.
- **Measurement mismatch:** LST, near-surface air temperature, subsurface temperature and human heat stress are different variables. A system should label each measurement clearly.
- **Uneven ground validation:** Makati provides an example of field validation, but its reported deployment was limited to selected locations and a month-long period, with one location still pending approval.
- **Mitigation outcome evidence:** Some studies recommend actions or simulate them; this is not the same as proving long-term real-world reductions after implementation.
- **Forecast validation:** The IoT/RNN and health-forecasting studies should be checked for their exact train/test design, baselines, error metrics and deployment constraints before claiming predictive superiority.
- **Transferability:** Results from UAE, Greece, China, the Philippines and different Indian cities reflect different climates, materials, urban forms and populations. Thresholds and intervention effects should be calibrated locally.
- **Climate drivers:** The reviewed papers address global warming and climate scenarios, but the collection does not provide a consistent, dedicated comparison of El Niño periods against non-El Niño periods. That needs a separate climate-data analysis.

## 4. How the proposed IoT system can build on previous work

The following is a proposed contribution, not a result already proven by these papers.

| Proposed system feature | Research precedent | How to implement/evaluate it |
|---|---|---|
| Distributed temperature and humidity nodes | Makati prototype; IoT manhole study | Place sensor nodes in contrasting zones: dense built-up, residential, industrial/roadside and green space. Calibrate and shield air-temperature sensors appropriately. |
| Surface/land-cover context | Bangalore, Chengdu, Beijing, Zhengzhou | Combine sensor readings with satellite-derived LST, NDVI/NDBI or land-cover labels; retain the source and timestamp of each dataset. |
| Zone-level heat-risk score | Attica FHRI; Makati HVI | Combine temperature-related indicators with vegetation and vulnerability data, documenting normalization and weights rather than presenting an arbitrary score as validated. |
| Short-term forecasting | IoT/RNN manhole study; India heatstroke forecasting study | Compare a simple baseline (e.g., persistence or moving average) with a forecasting model using time-ordered test data. Report MAE/RMSE and warning lead time. |
| Action recommendations | Softscape study; suburban ENVI-met study; Attica | Recommend suitable interventions by hotspot type: irrigation only where vegetation/soil conditions justify it, shade/greening where feasible, and cool materials for exposed built surfaces. |
| Before/after intervention measurement | Softscape baseline comparison; Makati ground validation | Record a baseline, document the intervention and its timing, and compare matched periods while accounting for weather, time of day and season. Avoid claiming causation from an uncontrolled before/after comparison. |
| Heat alerts | Attica; India heatstroke study | Generate alerts from validated thresholds or a calibrated risk model, and make clear whether the alert is based on air temperature, LST, forecast values or a composite risk index. |
| Closed-loop monitoring | IoT monitoring concept | After an action, continue sensing and report whether conditions changed; do not claim the intervention worked solely because a command was sent. |

## 5. Recommended comparison metrics for the project

To make the project research-oriented, evaluate the system using measurable criteria:

- **Sensing quality:** sensor calibration error, missing-data rate and uptime.
- **Communication:** packet delivery rate, data delay and coverage.
- **Monitoring:** sampling interval, number of zones monitored and hotspot detection agreement with reference data.
- **Prediction:** MAE/RMSE against a simple baseline, evaluated on held-out time periods.
- **Alerting:** precision/recall or false-alarm rate, if labelled heat events are available; otherwise report the limitation.
- **Mitigation:** change in air temperature and/or surface temperature, measured separately, plus humidity and relevant weather context.
- **Operational performance:** energy use, maintenance needs and time between detection and alert/action.
- **Equity and relevance:** whether alerts cover vulnerable zones and whether the intervention is feasible for that location.

## 6. Important interpretation rules

1. Do not describe satellite-derived LST as air temperature.
2. Do not compare numbers across papers unless units, measurement types, dates, season, time of day and methods are comparable.
3. A correlation between NDVI/NDBI and LST does not alone prove causation.
4. A simulation result is not automatically a real-world measured outcome.
5. A proposed IoT architecture is not a validated deployment unless the paper reports an implemented and evaluated system.
6. Do not quote a model as “best” without the relevant metric, validation design and baseline.
7. Treat RCP scenarios in older papers according to the paper's own framework; do not silently relabel them as newer SSP scenarios.

## 7. Source list: uploaded papers

1. *Assessment of Potential Temperature Increases in the UAE due to Future Global Warming* (2022), IEEE ASET. DOI: `10.1109/ASET53988.2022.9734915`
2. *Comparative Analysis of Urban Heat Island (UHI) Intensity using Remote Sensing: A Case Study of Thanjavur and Tiruchirappalli* (2025), IEEE ICSCDS. DOI: `10.1109/ICSCDS65426.2025.11167379`
3. *Dynamic Evolution of Surface Urban Heat Island in Beijing* (2019), IGARSS.
4. *Future Heat Risk Index: The Case of Attica Regions, Greece* (2024), IEEE IISA. DOI: `10.1109/IISA62523.2024.10786707`
5. *Mitigation Strategies for a Moderate Radiative Temperature of the Land Surface: A Case Study on Local Scale Urban Heat Island in Sub-Urban Region of India* (2022), IEEE M2GARSS. DOI: `10.1109/M2GARSS52314.2022.9839944`
6. *Observation Experiments and Analysis of Summer Urban Heat Island in Cold Region Based on Low-Altitude Dual-Source Remote Sensing: A Case Study of Zhengzhou University Main Campus* (2025), IEEE JSTARS. DOI: `10.1109/JSTARS.2025.3610219`
7. *Optimizing Urban Heat Response with IoT-Driven Manhole Heat Detection using Recurrent Neural Networks* (2024), IEEE I-SMAC. DOI: `10.1109/I-SMAC61858.2024.10714633`
8. *Risk Assessment of Global Temperature Anomalies Using Intelligence Frameworks: Evaluating the Impact of Socioeconomic Factors and with a Case Study on Heatstroke Deaths in India* (2025), IEEE ICAIHC. DOI: `10.1109/ICAIHC64101.2025.10956697`
9. *Sustainable Decision-Making in Urban Design: Softscape Solutions for Mitigating Urban Heat Island Effects in Hot-arid Climates* (2024), IEEE DASA. DOI: `10.1109/DASA63652.2024.10836491`
10. *Urban Expansion and Its Impact on Urban Heat Island Intensity: A Case Study of Chengdu City, China* (2022), IEEE Geoinformatics. DOI: `10.1109/GEOINFORMATICS57846.2022.9963840`
11. *Urban Heat Island and Heat Vulnerability Assessment with Ground Validation: A Case Study for Makati City* (2025), IEEE TENCON. DOI: `10.1109/TENCON66050.2025.11375474`
12. *Urban Heat Island and Its Impact on Impervious Surfaces During Two Seasons: A Case Study of Bangalore* (2021), IEEE InGARSS. DOI: `10.1109/InGARSS51564.2021.9792024`

---

## 8. What to verify before final submission

- Check each paper's result tables/figures before quoting any value not explicitly stated above.
- Verify the exact construction-land percentage in the Chengdu paper; the extracted abstract's percentage should not be copied without checking the PDF.
- Verify full ENVI-met treatment names and numerical temperature changes in the suburban India mitigation paper.
- Verify exact prediction metrics and baseline comparisons in the IoT/RNN and heatstroke-forecasting papers.
- For a global warming and El Niño comparison, add separate authoritative climate sources and compare equivalent time periods; do not infer an El Niño effect from these UHI papers alone.

