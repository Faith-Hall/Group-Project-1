# An Analysis of The Impact of Energy on Life Expectancy Around the World  
<font size="3">**Group-Project-1: Team 6**  
**Contributors:** Kyle Dalton, Faith Hall, Thomas Keene, Cassia Yoon  
**Github link:** https://github.com/Faith-Hall/Group-Project-1</font>

## Project Overview  
The aim of our project was to determine if there is a correlation between energy consumption and life expectancy. We have examined consumption of energy per capita, type of energy source and life expectancy around the world and in each continent. The goal of these analyses are to provide the reader with an overall picture of the impact of energy consumption on life expectancy. 

## Project Questions:  
1. What is the correlation of global life expectancy to overall per capita energy consumption?
2. Does higher energy consumption affect life expectancy (broken down by continents)?
3. Is global life expectancy affected by type of energy consumption (renewable vs fossil fuels)?
4. Is the life expectancy affected by type of energy consumption (renewable vs fossil fuels) in each continent?

Folder Structure:  

---
### Analysis 1: What is the correlation of global life expectancy to overall per capita energy consumption?
![Analysis 1 graph](/Readme_imgs/A1.png)
> [!NOTE]
> This analysis was also done by generation. See additional graphs in the folder "analysis_1_figs"  

<font size="3">**Analysis 1 Conclusions:**</font>  
write conclusion here  

---
### Analysis 2: Does higher energy consumption affect life expectancy (broken down by continents)?
![Analysis 2 graph 1](/Readme_imgs/A2_1.png)
![Analysis 2 graph 2](/Readme_imgs/A2_2.png)  

<font size="3">**Analysis 2 Conclusions:**</font>  
We found a strong correlation between per capita energy use and Life expectancy at birth. 
- In 1965, energy consumption of 2-3kWh correlated with LEx of 43- 50 years. While energy consumption at 30kWh correlated with LEx of 65 years. 
- Similarly, in 2021 energy consumption of 4000kWh correlated  LEx of 61 years. 16 - 19,000kWh correlated to LEx of 72.5=73 years, while consumption of 40, 000 kWh and above correlated with LEx of of 77 years.  
- Energy consumption above 30kWh in 1965 and 40kWh in 2021 did not seem to significantly increase LEx

What does this mean?  
- Could more energy use make life easier? Appliances, less hard labor, fewer accidents?
- Could it mean better medical care? More modern equipment.
- Could it simply be a correlation of wealthy economies with all of the above?
---
### Analysis 3: Is global life expectancy affected by type of energy consumption (renewable vs fossil fuels)?  
![Analysis 3 graph 1](/Readme_imgs/A3_1.png)
![Analysis 3 graph 2](/Readme_imgs/A3_2.png)

<font size="3">**Analysis 3 Conclusions:**</font>  
- Global trends showed a marked increase in the use of fossil fuels (the dominant fuel source of the time) during the mid 1980’s. This is likely due to the growth of emerging nations as they ramped up development to compete with previously established industrialized nations.
- Life expectancy shows a steady increase over time regardless of energy type. This is likely due to the dependence of life expectancy on other factors such as nutrition and advancements in healthcare.
- Albeit slow, growth in the use of renewables over fossil fuels can clearly be seen when examined over the time period of 1965 - 2022.
---
### Analysis 4: Is the life expectancy affected by type of energy consumption (renewable vs fossil fuels) in each continent?
![Analysis 4 graphs](/Readme_imgs/A4.png)
> [!NOTE]
> To view each individual graph see folder "analysis_4_figs"

<font size="3">**Analysis 4 Conclusions:**</font>  
- Over the years, life expectancy at birth has increased over time in every continent from 1965 to 2022, similar to trends seen globally.
- The use of renewable energy has increased gradually over the years in most continents (except Africa).
- The use of fossil fuels has decreased over the years in Oceania, North America and Europe but this has not changed life expectancy trends.
- Life expectancy does not appear to correlate with type of fuel consumed based on the graphs, even at the continents level.

# Project Conclusions:  
We acknowledge the limits of analyzing life expectancy against energy consumption alone. Life Expectancy is affected by many factors. According to an article, “Significant factors in life expectancy include gender, genetics, access to health care, hygiene, diet and nutrition, exercise, lifestyle, and crime rates.”<sup>[^1]</sup> However, transitioning to using more renewable energy can offer many health and environmental benefits, which may in turn improve our life expectancy. For future analysis considerations, we could also analyze life expectancy with additional factors (such as advances in healthcare over time, poverty, and air quality).  

# Resources  
Datasets used:
- Energy dataset: https://github.com/owid/energy-data
- Life Expectancy dataset: https://web.archive.org/web/20230728063248/https://population.un.org/wpp/Download/Standard/CSV/

For coding work:
- Plots with 2 different scales:  https://matplotlib.org/stable/gallery/subplots_axes_and_figures/two_scales.html
- legend for two axes:  https://stackoverflow.com/questions/5484922/secondary-axis-with-twinx-how-to-add-to-legend
- Matplotlib list of marker shapes:  https://matplotlib.org/stable/api/markers_api.html#module-matplotlib.markers
- savefig cutting off title at the top:  https://stackoverflow.com/questions/35992492/savefig-cuts-off-title
- legend location codes: https://www.geeksforgeeks.org/change-the-legend-position-in-matplotlib/

Some articles we looked at for inspiration:
- https://www.climatecouncil.org.au/11-countries-leading-the-charge-on-renewable-energy/
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10002415/
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9631790/
- https://www.econstor.eu/bitstream/10419/233768/1/1757035656.pdf
- Research article on relationship of life expectancy to energy: https://www.iaea.org/sites/default/files/publications/magazines/bulletin/bull26-3/26304044950.pdf
- Another article, but with more of a focus on renewable energy vs life expectancy: https://www.emerald.com/insight/content/doi/10.1108/IJESM-11-2022-0001/full/html


[^1]: https://www.disabled-world.com/fitness/longevity/#:~:text=Significant%20factors%20in%20life%20expectancy,%2C%20genetics%2C%20and%20lifestyle%20choices. 

# Acknowledgements
We wish to thank our teaching staff:
- Hunter Hollis
- Sam Espe
- Randy Sendek
- Kourt Bailey
