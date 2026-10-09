# Urban Heat Island research notes: working literature review

These notes are an evolving reading log based on the uploaded PDFs. They distinguish reported findings from interpretation. They are not a substitute for the verbatim extractions. Some papers use satellite-derived land-surface temperature (LST), which is not the same measurement as standard near-surface air temperature.

## 1. Assessment of Potential Temperature Increases in the UAE due to Future Global Warming (IEEE ASET, 2022)
**Method/data:** Historical air-temperature records from 20 weather stations across the UAE; future projections averaged from three global-circulation climate models; periods 2021–2050 and 2051–2080; scenarios RCP 4.5 and RCP 8.5.
**Reported results:** The abstract reports average air-temperature increases of about 1–2.8 °C in the near future and 1.9–4.15 °C in the far future under RCP 8.5. The paper's conclusion says the far future has larger increases than the near future, and RCP 4.5 is the lower-warming scenario in the comparison. Jabel Jais in the far northeast is specifically mentioned for increases in minimum temperature.
**Problem/limitation relevant to our project:** Climate projections are broad-scale future scenarios, not real-time neighborhood monitoring. They help frame the background climate risk but do not locate today's street-level hotspots.
**Potential use:** Context slide on climate-change baseline and why local monitoring/adaptation matters.

## 2. Comparative Analysis of UHI Intensity using Remote Sensing: Thanjavur and Tiruchirappalli (IEEE ICSCDS, 2025)
**Method/data:** MODIS-derived LST and NDVI, comparing urban and rural areas in the two Tamil Nadu districts over 2012–2022.
**Reported results:** Tiruchirappalli showed consistently higher UHI intensity than Thanjavur, with seasonal fluctuations. Rural areas generally had higher NDVI than urban areas. The paper associates increased built-up area and reduced vegetation in Tiruchirappalli with increasing UHI; Thanjavur's more mixed urban form appeared to buffer some effects. The paper recommends more detailed spatial data and seasonal/day-night analysis in future work.
**Problem/limitation:** Satellite products offer broad coverage but can lack the spatial/temporal detail needed for individual streets and immediate operational response.
**Potential use:** Indian case-study comparison and evidence for combining remote sensing with local IoT nodes.

## 3. Dynamic Evolution of Surface Urban Heat Island in Beijing (IGARSS, 2019)
**Method/data:** Remote-sensing analysis of summer land-surface temperature and urban–rural temperature gradients in Beijing, 2005–2015; influence factors assessed at different spatial scales.
**Reported results:** Summer surface temperature showed a slight increase; temperature increased along the urban–rural gradient; the extent of the UHI expanded rapidly. Building area, population and GDP had positive relationships with surface temperature at township scale, while relationships differed at district scale.
**Problem/limitation:** Relationships vary by geographic scale, and satellite/statistical analysis describes spatial patterns rather than triggering live mitigation.
**Potential use:** Explain urban expansion and why analysis should be location-aware.

## 4. Future Heat Risk Index: The Case of Attica Regions, Greece (IEEE IISA, 2024)
**Method/data:** Future Heat Risk Index combining climate projections and spatial analysis, including an RCP 8.5 scenario for 2040; compares vegetation enhancement and cool-material interventions.
**Reported findings in abstract:** Identifies areas vulnerable to heat-related impacts and prioritizes mitigation. The paper highlights vegetation enhancement and installation of cool materials, and emphasizes proactive planning under future climate scenarios. Heat risk is particularly important for vulnerable residents such as older adults.
**Problem/limitation:** A future risk index supports planning, but it is not itself a continuous sensor network or an automatic response controller.
**Potential use:** Risk-map/dashboard design and prioritizing interventions by zone and population vulnerability.

## 5. Mitigation Strategies for a Moderate Radiative Temperature of the Land Surface: Local-scale suburban India case study (M2GARSS, 2022)
**Method/data:** Urban microclimate simulation using ENVI-met for a surveyed suburban area; compares local mitigation scenarios.
**Reported findings:** The study evaluates mitigation options by simulating local microclimate conditions. The paper's focus is that poorly planned built-up areas and paved surfaces worsen UHI, and mitigation can be assessed before deployment using a simulation model.
**Problem/limitation:** Simulation outcomes depend on site geometry, material inputs, vegetation/building data and scenario assumptions; the extracted text should be checked around the results/conclusion tables before quoting exact numerical reductions.
**Potential use:** Supports testing mitigation choices in a virtual/digital environment before applying them in the field.

## 6. Observation Experiments and Analysis of Summer UHI in a Cold Region using Low-altitude Dual-source Remote Sensing: Zhengzhou University campus (IEEE JSTARS, 2025)
**Method/data:** A low-altitude dual-source remote-sensing platform combines high-resolution thermal-infrared and hyperspectral data; estimates LST, surface classes, surface UHI intensity (SUHII) and heat-field intensity index.
**Reported findings:** Fusion of thermal and hyperspectral data was used to relate underlying surface types to temperature characteristics. The study reports prominent UHI effects in clusters of buildings and emphasizes the role of surface type and the choice of a vegetation-based cool reference when calculating SUHII.
**Problem/limitation:** High-resolution aerial/remote-sensing methods offer spatial detail but require specialized platforms and analysis; the selected reference surface affects calculated UHI intensity.
**Potential use:** Ground-truthing and validating IoT readings against spatial thermal maps; selecting representative reference zones.

## 7. Optimizing Urban Heat Response with IoT-Driven Manhole Heat Detection using Recurrent Neural Networks (I-SMAC, 2024)
**Method/data:** Proposed IoT sensor nodes for subsurface/manhole monitoring, with an RNN model to learn temporal patterns and forecast heat trends; the paper describes a case study in a dense metropolitan setting.
**Reported findings in abstract:** The authors present combining real-time IoT sensing with recurrent neural networks as a way to forecast heat trends and support proactive treatment. The application is specifically manhole/subsurface infrastructure, not a general city-wide UHI sensor network.
**Problem/limitation:** This is infrastructure-specific; do not treat it as direct evidence that an RNN accurately predicts neighborhood-level outdoor UHI unless the paper's evaluation metrics support that claim.
**Potential use:** Closest IoT + time-series forecasting precedent among the uploaded papers; useful for architecture inspiration, with clear distinction from our wider urban heat objective.

## 8. Risk Assessment of Global Temperature Anomalies Using Intelligence Frameworks: Socioeconomic Factors and Heatstroke Deaths in India (ICAIHC, 2025)
**Method/data:** Machine-learning and time-series approaches using historical temperature anomalies, meteorological variables and heatstroke-fatality data; models mentioned include linear, lasso and ridge regression, voting regressor and Prophet.
**Reported findings in abstract:** Preliminary findings associate heatstroke occurrences with extreme heatwaves, humidity and urbanization factors. The work aims to support forecasting, early warning and public-health planning.
**Problem/limitation:** The study links climate conditions with health outcomes; those predictions are not equivalent to a local physical heat measurement. Results depend on data quality, temporal coverage and model validation.
**Potential use:** Add vulnerability/health-risk alerts to a UHI dashboard, rather than reporting temperature alone.

## 9. Sustainable Decision-Making in Urban Design: Softscape Solutions for Mitigating UHI in Hot-arid Climates (IEEE DASA, 2024)
**Method/data:** ENVI-met simulations compare three softscape treatments for urban walkways in a hot-arid setting.
**Reported results:** All three treatments reduced temperature compared with an untreated baseline. Although the treatments were not statistically significantly different from one another overall, each improved thermal conditions relative to the untreated walkway. The paper highlights vegetation/soil/water and shading/evapotranspiration as cooling mechanisms.
**Problem/limitation:** Site-specific simulation results do not automatically transfer to all climates, and the abstract does not establish that one softscape treatment is universally best.
**Potential use:** Use as a mitigation comparison and argue for testing locally appropriate interventions, then measuring results with sensors.

## 10. Urban Heat Island and Heat Vulnerability Assessment with Ground Validation: Makati City (TENCON, 2025)
**Method/data:** Landsat 8 LST and satellite-derived indices plus demographic indicators; HVI combines LST, NDVI, NDBI, population density and extreme age. Three prototype devices measured ambient temperature and relative humidity in selected barangays over about one month.
**Reported results:** The paper reports average LST of 43.60 °C for the study's mapped period/data product. Barangays Pembo and Rizal had the highest HVI scores (23 each), while Forbes Park had the lowest (8); average HVI was about 17.5 per barangay. The ground devices were deployed in two high-vulnerability barangays and one low-vulnerability barangay to check map patterns.
**Problem/limitation:** Only three devices and about one month of readings are described in the abstract; this is limited ground sampling relative to city-wide mapping. The reported LST is satellite-derived surface temperature, not necessarily ambient air temperature.
**Potential use:** Strong precedent for combining satellite heat maps, ground sensors and demographic vulnerability.

## 11. Urban Heat Island and Its Impact on Impervious Surfaces During Two Seasons: Bangalore (InGARSS, 2021)
**Method/data:** Landsat 8 thermal data for March and November 2020; calculates LST, NDVI, NDBI and land-use/land-cover classes.
**Reported numerical results:** NDVI–LST correlation was −0.32 in March and −0.11 in November. Built-up index (NDBI) correlation with LST was 0.63 in March and 0.28 in November. Mean built-up LST was 36.18 °C in March and 22.40 °C in November. The paper reports stronger UHI effect in summer than winter; November showed more variation around the mean (standard deviation 3.96 versus 1.99 in March).
**Problem/limitation:** Two seasonal snapshots are not continuous monitoring; satellite LST and spectral-index correlations do not alone prove causation.
**Potential use:** Indian city evidence linking built-up surfaces to higher heat and vegetation to lower surface temperature.

## 12. Urban Expansion and Its Impact on UHI Intensity: Chengdu City, China (IEEE Geoinformatics, 2022)
**Method/data:** WRF mesoscale simulation combined with land-cover products; examines construction land and UHI changes from 2002 to 2020.
**Reported results:** Urban construction land nearly doubled over the study period and UHI extent/intensity expanded. Daytime and nighttime spatial patterns differed. The expansion relationship was strongly coupled from 2002–2011; from 2011–2020, the spatial effect of construction land on UHI weakened, showing that the relationship was not uniform over time.
**Problem/limitation:** City-scale modeling is useful for long-term planning but is not an operational real-time sensing and response system.
**Potential use:** Evidence that urban growth and heat-island expansion can co-evolve, but their relationship changes by period and time of day.

## Cross-paper synthesis so far

1. **Recurring drivers:** Built-up/impervious surfaces, dense building clusters, urban expansion and lower vegetation repeatedly coincide with higher surface temperatures or stronger UHI patterns.
2. **Promising mitigations:** Vegetation/softscape, shading, green infrastructure and cool/reflective materials are repeatedly proposed or simulated. Local performance depends on site and climate; do not claim a universal winner.
3. **Measurement gap:** Remote sensing offers broad spatial coverage and long-term comparison, while ground sensors offer local, repeated readings. Combining both can help validate maps and enable more frequent alerts.
4. **Response gap:** Most papers emphasize mapping, projections, vulnerability indices or simulated interventions. The IoT/RNN manhole paper is an infrastructure-specific exception. A city-scale loop that links local sensor data, risk assessment, targeted mitigation and post-action measurement is a defensible project opportunity, but should be presented as our proposed integration rather than a proven result of these papers.
5. **Heat risk is more than temperature:** The Makati and India heatstroke papers motivate including demographic vulnerability and health-related alerts alongside physical heat readings.
6. **Climate change vs El Niño:** The UAE and Attica papers consider future climate scenarios; the supplied paper abstracts do not establish a specific El Niño analysis. El Niño's role must be researched separately using authoritative climate sources and must not be attributed to these papers without evidence.
7. **Caution on temperature comparisons:** LST (satellite surface temperature), ambient air temperature, subsurface/manhole temperature and modeled temperature are different quantities. Keep them labelled and do not compare their numerical values as if they were the same measurement.

## Open questions for the PPT review
- Which papers report quantified before/after cooling for specific interventions, and what are the units, locations and baseline conditions?
- What exact model metrics (error, validation split, forecast horizon) are reported by the IoT/RNN and heatstroke-prediction papers?
- What are the limitations of sensor placement, sampling frequency, communication outages, calibration and maintenance?
- How should El Niño and long-term global warming be represented as distinct but potentially overlapping climate influences?
- Which mitigation action is feasible for an IoT prototype to trigger safely (for example, irrigation based on soil moisture), versus merely recommend (tree planting/cool roofs)?
