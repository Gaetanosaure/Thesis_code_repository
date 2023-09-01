# Thesis_code_repository

This repository contains the Jupyter notebook used to code the models and obtain the results presented in my master thesis: "Emissions from a hydrogen-fuel-cell-powered aircraft characterization, environmental impact, and mitigation study".

The abstract of this work is presented below: 

ABSTRACT: 

Aviation accounts for 3.5 % of anthropogenic radiative forcing, the two main contributions being contrail cirrus and carbon dioxide emissions. To meet the Paris Agreement’s goals, hydrogen aviation will play a significant role by 2050. As hydrogen aviation releases more water than kerosene aviation, and since hydrogen is a perturbing agent of the methane cycle, it is relevant to investigate the environmental impact of hydrogen aircrafts. The cleaner form of hydrogen aviation - fuel cells - is investigated in this report. A literature review evaluates the current and projected capabilities of fuel cells for aviation to elect the ATR 72-600 as an impactful but also realistic aircraft and object of study. It is found that an ATR 72-600 would emit 299 g.s-1 of water during take-off and 192 g.s-1 during cruise and landing and that it would emit between 1.03 % and 5.63 % of its full tank in terms of mass of hydrogen during a typical flight. The environmental impact of these emissions is considered. If research has been conducted to reduce hydrogen emissions below their admittable threshold, no work seems to have been produced to mitigate the impact of contrail cirrus for hydrogen-fuel-cell-powered aircrafts. Their impact lies between 82 % and 100 % of that of conventional aviation – lower than today’s but still higher than EU goals to reduce non-CO2 effects radiative forcing by at least 30 % by 2035, and contrail cirrus by 90 % by 2050. Three contrail cirrus mitigation strategies are devised and analysed in this work: water storage, water storage coupled with water release, and water expulsion at high speed. The three strategies are compared in terms of their physics, their energy requirements, and their costs. This comparison is led over two of the most frequented domestic routes in the world to study the impact of latitude, and at the two solstices and the two equinoxes to study the impact of the time of the year. It is found that the most influential parameters are latitude for the first and second strategies, and droplet release radius and temperature for the third strategy. The simple storage strategy can mitigate only up to 35 % of long-lasting contrails and cannot meet EU goals. Water storage coupled with release is found to reasonably be able to abate at least 80 % of long-lasting contrails with a water tank of a capacity equal to the mass of the fuel tank before take-off, with an energy consumption of less than 0.33 % of the initial fuel tank’s energy. High-speed ejection is found to be able to mitigate 100 % of contrail formation with an energy use of less than 0.05 % of the initial fuel tank’s energy. It is likely to be the most effective solution of the three studied in this work, however, water-cooling energy requirements must be investigated further in order to assess the accessibility of its best results at a reasonable energy cost. EU goals mentioned above are found to be within reach for 2035 and likely achievable for 2050. Overall, hydrogen fuel cell-powered aircraft like an ATR 72-600 can be subject to a dramatic reduction in environmental impact with an increase in energy requirements less than 1.13 % of their initial fuel tank energy. 

END OF ABSTRACT

This Jupyter notebook is divided into 6 main parts: 
I: General functions definition
    Some functions used in every other sections are defined here.
II: Mitigation scenario 1 study
    Physical analysis of scenario 1
III: Mitigation scenario 2 study
    Physical analysis of scenario 2
IV: Mitigation scenario 3 study
    Physical analysis of scenario 3
V: Scenarii comparison
    Comparisons of the differents scenarii in terms of energy requirements, additional fuel consumption and passenger displacement.
VI: Case studies
    Use of all the functions defined above on the data from the three case studies chosen.

More details are written in sections' headline in the notebook itself.

The code has been commented as often as possible to be clearer, and it can be run using exclusively the basic modules NumPy, SciPy and Matplotlib. 

The graph results generated in section 6 are automatically saved in the folder "Graph results". The graphs used in the thesis have been saved on the date they were generated, in the folder "Graph results - 22082023".

