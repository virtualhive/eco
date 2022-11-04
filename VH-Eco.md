# Eco

Since Virtual Hive is a future oriented company, we are not only focusing on innovation in technology and business but also seriously considering our company and actions within the developments of the **global ecological system and its current trajectory**.

## Background

The Intergovernmental Panel on Climate Change (IPCC) is currently finishing the Sixth Assessment Report: 2022 “about the state of scientific, technical and socio-economic knowledge on climate change, its impacts and future risks, and options for reducing the rate at which climate change is taking place.” [1] Since we think a scientific based approach on climate change is the best way to find suitable countermeasures, Virtual Hive will take the works of the IPCC and other institutes as the foundation for our decisions regarding our impact and possible mitigations on climate change.

The observed **impacts** on ecosystems and human systems **today** which are attributed to climate change are already occurring earlier, more widespread and with more far-reaching consequences than anticipated [2]. The IPCC report on “Climate Change 2022: Impacts, Adaptation and Vulnerability“ states [2]:

> "Climate change has already altered terrestrial, freshwater and ocean ecosystems at global scale, with multiple impacts evident at regional and local scales where there is sufficient literature to make an assessment. Impacts are evident on ecosystem structure, species geographic ranges and timing of seasonal life cycles"

> “Climate change has already had diverse adverse impacts on human systems, including on water security and food production, health and well-being, and cities, settlements and infrastructure.“

 

However, looking into the future the **risk and impact** on ecosystems are tightly and directly proportionally bound to the **further increase of the global surface temperature** [3]. There is a very clear tipping point for these risks and impacts to become severe if global warming overshoots an increase of **1.5°C**. There is a  special report about this topic from the IPCC called “Global Warming of 1.5 ºC“ [4] and the already mentioned “Climate Change 2022: Impacts, Adaptation and Vulnerability“ report underlines the findings with more recent data.

The “Global Warming of 1.5 ºC“ special report states that an estimated 1.0°C increase of global surface temperatures is caused by **human activities** (with a likely range between 0.8°C and 1.2°C) and with high confidence global warming will reach 1.5°C above pre-industrial levels between 2030 and 2052 if the increase continues at the current rate [4 p. 4]. New estimates are even higher with ranges of 0.8°C to 1.3°C and assume an overshoot of 1.5°C rather early (2030) than late [5]. A news post on the IPCC website from August 9, 2021 [6] sums up the findings of the then newly released IPCC Working Group I report “Climate Change 2021: the Physical Science Basis” with the words:

> The report provides new estimates of the chances of crossing the global warming level of 1.5°C in the next decades, and finds that unless there are immediate, rapid and large-scale reductions in greenhouse gas emissions, limiting warming to close to 1.5°C or even 2°C will be beyond reach.
>
> […]
>
> The report also shows that human actions still have the potential to determine the future course of climate. The evidence is clear that carbon dioxide (CO2) is the main driver of climate change, even as other greenhouse gases and air pollutants also affect the climate.

 

Taking all this information into account, it is clear every sector (energy, AFOLU, buildings, transport, industry and others) has the obligation to reduce greenhouse gases (GHGs) as soon and as effective as possible. Virtual Hive will follow this call and the first step towards this is to identify the emissions and potential for reduction.

## GHG Emission Identification

Our inventory approach to determine carbon dioxide equivalent (CO2e) emissions of Virtual Hive is based on the 3 scopes defined by the GHG Protocol [7],[8].

### Green Energy and CO2 eq.

Currently all our servers are powered by 100% renewables but against the common believe this does not equal 0 g CO2 eq. per Watt since the manufacturing and building processes of renewable energy technologies as well as transportation and possible other scope 3 emissions, in short the lifecycle needs to be accounted for. There is a report published by the United Nations Economic Commission for Europe which investigates the topic of lifecycle impacts of electricity generation also for renewables [11]. The report shows how difficult it is to estimate the actual impact. However, we want to account for these emissions and hence have to derive a single value for renewable CO2 eq./kWh. The energy mix of renewables in the EU is as follows [12]:

- 36% Wind
- 33% Hydro
- 14% Solar
- 8% Solid Biofuels
- 8% other

Based on the report of the UNECE [11] Table 14 “LCIA results for region EUR (Europe EU 28), in 2020 […]“ the following CO2 eq./kWh can be used to calculate an average CO2 eq./kWh for the renewable mix:

- Wind: ~13 g CO2 eq./kWh (average for onshore/ offshore, concrete foundation/ offshore, steel foundation
- Hydro: ~11 g CO2 eq./kWh (based on a 360 MW facility as it is most representative)
- Solar: ~21 g CO2 eq./kWh (average of all PV variants)
- Solid Biofuels: N/A
- Other: N/A

For solid biofuels and others we will assume a CO2 eq. of natural gas with a conservative 281 g CO2 eq./kWh (based on the average of natural gas CO2 eq. in [11] Table 14).

#### Average Renewable Mix CO2 eq./kWh

0.36 * 13 g CO2 eq./kWh + 0.33 * 11 g CO2 eq./kWh + 0.14 * 21 g CO2 eq./kWh + (0.08 + 0.08) * 281 g CO2 eq./kWh = 56.21 g CO2 eq./kWh = **~56 g CO2 eq./kWh**



### Scope 1

*Direct emissions (manufacturing combustion, vehicles etc.)*

Virtual Hive has one small car in its inventory which is leased until April 2023. Even though it is not used to travel to work since we all work remote, it is still accounted for.

#### Company vehicles

1 small car, built 2019, average of 2000 km per year

Average of 122.3 g CO2 eq./km [9]

2000 km/year * 0.1223 kg CO2/km = **244.6 kg CO2 eq./year**



### Scope 2

*Indirect emissions (purchased electricity)*

Since Virtual Hive does neither own nor rent any office space or buildings due to full remote work, the scope 2 emissions include only the electricity which is directly accountable to the company by the use of laptops, desktop PCs and servers.

#### Laptops/desktop PCs

5 laptops and 3 desktop PCs are used. The average usage is estimated with 12 hours per day 365 days a year.

Per laptop/desktop PC\*:

~90W * 12h/day * 365 days/year = 394.2 kWh/year

0.056 kg CO2 eq./kWh * 394.2 kWh/year = ~22.1 kg CO2 eq./year

5 * 22.1 kg CO2 eq./year = **110.5 kg CO2 eq./year**

\**90W is based on the average power supplies of laptops and measured consumption by desktop PCs - it is at the upper boundary.*



#### Servers

The amount of servers is changing frequently so we will use an upper boundary of 70 servers which will not be exceeded in 2022. Based on an average workload of 50% idle and 50% full load a power consumption of 216 W per hour can be assumed [10]. All servers are running 24 hours on 365 days per year.

0.216 kW * 24 h/day * 365 days/year = 1892.16 kWh/year

0.056 kg CO2 eq./kWh * 1892.16 kWh/year/server = 105.96 kg CO2 eq./year/server

70 servers * 105.96 kg CO2 eq./year/server = **7417.2 kg CO2 eq./year**



### Scope 3

*Work in progress*



## Mitigations

*Work in progress*





## Sources

[1] https://www.ipcc.ch/ 

[2] Climate Change 2022: Impacts, Adaptation and Vulnerability. Contribution of Working Group II to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change p. 45-46 (https://www.ipcc.ch/report/ar6/wg2/downloads/report/IPCC_AR6_WGII_TechnicalSummary.pdf)

Pörtner, H.-O., D.C. Roberts, H. Adams, I. Adelekan, C. Adler, R. Adrian, P. Aldunce, E. Ali, R. Ara Begum, B. Bednar-Friedl, R. Bezner Kerr, R. Biesbroek, J. Birkmann, K. Bowen, M.A. Caretta, J. Carnicer, E. Castellanos, T.S. Cheong, W. Chow, G. Cissé, S. Clayton, A. Constable, S.R. Cooley, M.J. Costello, M. Craig, W. Cramer, R. Dawson, D. Dodman, J. Efitre, M. Garschagen, E.A. Gilmore, B.C. Glavovic, D. Gutzler, M. Haasnoot, S. Harper, T. Hasegawa, B. Hayward, J.A. Hicke, Y. Hirabayashi, C. Huang, K. Kalaba, W. Kiessling, A. Kitoh, R. Lasco, J. Lawrence, M.F. Lemos, R. Lempert, C. Lennard, D. Ley, T. Lissner, Q. Liu, E. Liwenga, S. Lluch-Cota, S. Löschke, S. Lucatello, Y. Luo, B. Mackey, K. Mintenbeck, A. Mirzabaev, V. Möller, M. Moncassim Vale, M.D. Morecroft, L. Mortsch, A. Mukherji, T. Mustonen, M. Mycoo, J. Nalau, M. New, A. Okem, J.P. Ometto, B. O’Neill, R. Pandey, C. Parmesan, M. Pelling, P.F. Pinho, J. Pinnegar, E.S. Poloczanska, A. Prakash, B. Preston, M.-F. Racault, D. Reckien, A. Revi, S.K. Rose, E.L.F. Schipper, D.N. Schmidt, D. Schoeman, R. Shaw, N.P. Simpson, C. Singh, W. Solecki, L. Stringer, E. Totin, C.H. Trisos, Y. Trisurat, M. van Aalst, D. Viner, M.Wairiu, R.Warren, P.Wester, D.Wrathall, and Z. Zaiton Ibrahim, 2022: Technical Summary. [H.-O. Pörtner, D.C. Roberts, E.S. Poloczanska, K. Mintenbeck, M. Tignor, A. Alegría, M. Craig, S. Langsdorf, S. Löschke, V. Möller, A. Okem (eds.)]. In: Climate Change 2022: Impacts, Adaptation and Vulnerability. Contribution of Working Group II to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change [H.-O. Pörtner, D.C. Roberts, M. Tignor, E.S. Poloczanska, K. Mintenbeck, A. Alegría, M. Craig, S. Langsdorf, S. Löschke, V. Möller, A. Okem, B. Rama (eds.)]. Cambridge University Press, Cambridge, UK and New York, NY, USA, pp. 37–118, doi:10.1017/9781009325844.002.

[3] Climate Change 2022: Impacts, Adaptation and Vulnerability. Contribution of Working Group II to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change p. 55-70 (https://www.ipcc.ch/report/ar6/wg2/downloads/report/IPCC_AR6_WGII_TechnicalSummary.pdf)

Pörtner, H.-O., D.C. Roberts, H. Adams, I. Adelekan, C. Adler, R. Adrian, P. Aldunce, E. Ali, R. Ara Begum, B. Bednar-Friedl, R. Bezner Kerr, R. Biesbroek, J. Birkmann, K. Bowen, M.A. Caretta, J. Carnicer, E. Castellanos, T.S. Cheong, W. Chow, G. Cissé, S. Clayton, A. Constable, S.R. Cooley, M.J. Costello, M. Craig, W. Cramer, R. Dawson, D. Dodman, J. Efitre, M. Garschagen, E.A. Gilmore, B.C. Glavovic, D. Gutzler, M. Haasnoot, S. Harper, T. Hasegawa, B. Hayward, J.A. Hicke, Y. Hirabayashi, C. Huang, K. Kalaba, W. Kiessling, A. Kitoh, R. Lasco, J. Lawrence, M.F. Lemos, R. Lempert, C. Lennard, D. Ley, T. Lissner, Q. Liu, E. Liwenga, S. Lluch-Cota, S. Löschke, S. Lucatello, Y. Luo, B. Mackey, K. Mintenbeck, A. Mirzabaev, V. Möller, M. Moncassim Vale, M.D. Morecroft, L. Mortsch, A. Mukherji, T. Mustonen, M. Mycoo, J. Nalau, M. New, A. Okem, J.P. Ometto, B. O’Neill, R. Pandey, C. Parmesan, M. Pelling, P.F. Pinho, J. Pinnegar, E.S. Poloczanska, A. Prakash, B. Preston, M.-F. Racault, D. Reckien, A. Revi, S.K. Rose, E.L.F. Schipper, D.N. Schmidt, D. Schoeman, R. Shaw, N.P. Simpson, C. Singh, W. Solecki, L. Stringer, E. Totin, C.H. Trisos, Y. Trisurat, M. van Aalst, D. Viner, M.Wairiu, R.Warren, P.Wester, D.Wrathall, and Z. Zaiton Ibrahim, 2022: Technical Summary. [H.-O. Pörtner, D.C. Roberts, E.S. Poloczanska, K. Mintenbeck, M. Tignor, A. Alegría, M. Craig, S. Langsdorf, S. Löschke, V. Möller, A. Okem (eds.)]. In: Climate Change 2022: Impacts, Adaptation and Vulnerability. Contribution of Working Group II to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change [H.-O. Pörtner, D.C. Roberts, M. Tignor, E.S. Poloczanska, K. Mintenbeck, A. Alegría, M. Craig, S. Langsdorf, S. Löschke, V. Möller, A. Okem, B. Rama (eds.)]. Cambridge University Press, Cambridge, UK and New York, NY, USA, pp. 37–118, doi:10.1017/9781009325844.002.

[4] IPCC, 2018: Global Warming of 1.5°C. An IPCC Special Report on the impacts of global warming of 1.5°C above pre-industrial levels and related global greenhouse gas emission pathways, in the context of strengthening the global response to the threat of climate change, sustainable development, and efforts to eradicate poverty [Masson-Delmotte, V., P. Zhai, H.-O. Pörtner, D. Roberts, J. Skea, P.R. Shukla, A. Pirani, W. Moufouma-Okia, C. Péan, R. Pidcock, S. Connors, J.B.R. Matthews, Y. Chen, X. Zhou, M.I. Gomis, E. Lonnoy, T. Maycock, M. Tignor, and T. Waterfield (eds.)]. Cambridge University Press, Cambridge, UK and New York, NY, USA, 616 pp. https://doi.org/ 10.1017/9781009157940. (https://www.ipcc.ch/sr15/)

[5] Technical Summary. In Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change p. 59

https://www.ipcc.ch/report/ar6/wg1/downloads/report/IPCC_AR6_WGI_TS.pdf

Arias, P.A., N. Bellouin, E. Coppola, R.G. Jones, G. Krinner, J. Marotzke, V. Naik, M.D. Palmer, G.-K. Plattner, J. Rogelj, M. Rojas, J. Sillmann, T. Storelvmo, P.W. Thorne, B. Trewin, K. Achuta Rao, B. Adhikary, R.P. Allan, K. Armour, G. Bala, R. Barimalala, S. Berger, J.G. Canadell, C. Cassou, A. Cherchi, W. Collins, W.D. Collins, S.L. Connors, S. Corti, F. Cruz, F.J. Dentener, C. Dereczynski, A. Di Luca, A. Diongue Niang, F.J. Doblas-Reyes, A. Dosio, H. Douville, F. Engelbrecht, V. Eyring, E. Fischer, P. Forster, B. Fox-Kemper, J.S. Fuglestvedt, J.C. Fyfe, N.P. Gillett, L. Goldfarb, I. Gorodetskaya, J.M. Gutierrez, R. Hamdi, E. Hawkins, H.T. Hewitt, P. Hope, A.S. Islam, C. Jones, D.S. Kaufman, R.E. Kopp, Y. Kosaka, J. Kossin, S. Krakovska, J.-Y. Lee, J. Li, T. Mauritsen, T.K. Maycock, M. Meinshausen, S.-K. Min, P.M.S. Monteiro, T. Ngo-Duc, F. Otto, I. Pinto, A. Pirani, K. Raghavan, R. Ranasinghe, A.C. Ruane, L. Ruiz, J.-B. Sallée, B.H. Samset, S. Sathyendranath, S.I. Seneviratne, A.A. Sörensson, S. Szopa, I. Takayabu, A.-M. Tréguier, B. van den Hurk, R. Vautard, K. von Schuckmann, S. Zaehle, X. Zhang, and K. Zickfeld, 2021: Technical Summary. In Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change [Masson-Delmotte, V., P. Zhai, A. Pirani, S.L. Connors, C. Péan, S. Berger, N. Caud, Y. Chen, L. Goldfarb, M.I. Gomis, M. Huang, K. Leitzell, E. Lonnoy, J.B.R. Matthews, T.K. Maycock, T. Waterfield, O. Yelekçi, R. Yu, and B. Zhou (eds.)]. Cambridge University Press, Cambridge, United Kingdom and New York, NY, USA, pp. 33−144. doi:10.1017/9781009157896.002.

[6] https://www.ipcc.ch/2021/08/09/ar6-wg1-20210809-pr/ 

[7] https://www.epa.gov/climateleadership/ghg-inventory-guidance-low-emitters  

[8] https://www.wri.org/initiatives/greenhouse-gas-protocol 

[9] https://www.eea.europa.eu/ims/co2-performance-of-new-passenger  

[10] https://i.dell.com/sites/content/corporate/corp-comm/en/Documents/dell-server-carbon-footprint-whitepaper.pdf

[11] UNECE: Life Cycle Assessment of Electricity Generation Options, 2021 https://unece.org/sed/documents/2021/10/reports/life-cycle-assessment-electricity-generation-options 

[12] https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Renewable_energy_statistics#Wind_and_water_provide_most_renewable_electricity.3B_solar_is_the_fastest-growing_energy_source

