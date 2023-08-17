# An Analysis of The Impact of Energy on Life Expectancy Around the World  
<font size="3">**Group-Project-1: Team 6**  
**Contributors:** Kyle Dalton, Faith Hall, Thomas Keene, Cassia Yoon  
**Github link:** https://github.com/Faith-Hall/Group-Project-1</font>
---
**Slide link:** https://docs.google.com/presentation/d/1DSr3_O2OVHAVpbSOfo72kpphd2Cr3JQx/edit?usp=sharing&ouid=112791377453488755006&rtpof=true&sd=true </font>
## Project Overview  
The aim of our project was to determine if there is a correlation between energy consumption and life expectancy. We have examined consumption of energy per capita, type of energy source and life expectancy around the world and in each continent. The goal of these analyses are to provide the reader with an overall picture of the impact of energy consumption on life expectancy. 

## Project Questions:  
1. What is the correlation of global life expectancy to overall per capita energy consumption?
2. Does higher energy consumption affect life expectancy (broken down by continents)?
3. Is global life expectancy affected by type of energy consumption (renewable vs fossil fuels)?
4. Is the life expectancy affected by type of energy consumption (renewable vs fossil fuels) in each continent?
---
### Analysis 1: What is the correlation of global life expectancy to overall per capita energy consumption?
![Analysis 1 graph](/Readme_imgs/A1.png)
> [!NOTE]
> This analysis was also done by generation. See additional graphs in the folder "analysis_1_figs"  

<font size="3">**Analysis 1 Conclusions:**</font>  
- The correlation between energy consumption and life expectancy at birth and at age 15 have a logarithmic correlation.
- Energy consumption past 35,000 kwh in the larger sample size, across all of the years in the dataset, has no correlation to life expectancy.
- The correlation between energy consumption and life expectancy is nearly nonexistant for the age groups of 65 and 80. 

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
![Analysis 4 linegraphs](/Readme_imgs/A4.png)
![Analysis 4 linear regression graphs](/Readme_imgs/A4_2.png)
> [!NOTE]
> To view each individual graph see folder "analysis_4_figs"

<font size="3">**Analysis 4 Conclusions:**</font>  

- Similar to trends seen globally, life expectancy at birth and use of renewable energy has increased over time in most continents.
- The use of fossil fuels has decreased over the years in Oceania, North America and Europe but this does not appear to affect life expectancy.
- There is a strong, positive correlation between life expectancy and overall energy consumption in South America.
- There is a strong, positive correlation between life expectancy and fossil fuel consumption in Asia.
- There is a strong, positive correlation between life expectancy and renewable fuel consumption in Europe.

# Project Conclusions:  
The analyses suggest that there is a correlation between energy consumption and life expectancy in some parts of the world. We acknowledge the limits of analyzing life expectancy against energy consumption alone. Life Expectancy is affected by many factors. According to an article, “Significant factors in life expectancy include gender, genetics, access to health care, hygiene, diet and nutrition, exercise, lifestyle, and crime rates.”<sup>[^1]</sup> However, transitioning to using more renewable energy can offer many health and environmental benefits, which may in turn improve our life expectancy. For future analysis considerations, we could also analyze life expectancy with additional factors (such as advances in healthcare over time, poverty, and air quality).  

# Resources  
Datasets used:
- Energy dataset: https://github.com/owid/energy-data
- Life Expectancy dataset: https://web.archive.org/web/20230728063248/https://population.un.org/wpp/Download/Standard/CSV/

For coding work:
- How to replace column values:  https://sparkbyexamples.com/pandas/pandas-replace-by-examples/
- Plots with 2 different scales:  https://matplotlib.org/stable/gallery/subplots_axes_and_figures/two_scales.html
- legend for two axes:  https://stackoverflow.com/questions/5484922/secondary-axis-with-twinx-how-to-add-to-legend
- Matplotlib list of marker shapes:  https://matplotlib.org/stable/api/markers_api.html#module-matplotlib.markers
- savefig cutting off title at the top:  https://stackoverflow.com/questions/35992492/savefig-cuts-off-title
- legend location codes: https://www.geeksforgeeks.org/change-the-legend-position-in-matplotlib/
- GH006 git push error solution:  https://stackoverflow.com/questions/52589285/cannot-push-on-github-suddently
- list of git branches commands:  https://www.nobledesktop.com/learn/git/git-branches
- clearing git commits:  https://stackoverflow.com/questions/1146973/how-do-i-revert-all-local-changes-in-git-managed-project-to-previous-state
- Readme formatting:  https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
- how to insert folder structure to readme: https://medium.com/@shradhaagarwal01/how-to-represent-folder-directory-tree-with-links-in-github-readme-in-less-than-5-minutes-84230fdcb1

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
---
### Folder Structure:  
* [analysis_1_figs/](/analysis_1_figs)
  * [analysis_1_fig_1965-2022.png](/analysis_1_figs/analysis_1_fig_1965-2022.png)
  * [analysis_1_fig_2021.png](/analysis_1_figs/analysis_1_fig_2021.png)
  * [analysis_1_fig_GenAlpha.png](/analysis_1_figs/analysis_1_fig_GenAlpha.png)
  * [analysis_1_fig_GenX.png](/analysis_1_figs/analysis_1_fig_GenX.png)
  * [analysis_1_fig_GenZ.png](/analysis_1_figs/analysis_1_fig_GenZ.png)
  * [analysis_1_fig_Millennials.png](/analysis_1_figs/analysis_1_fig_Millennials.png)
* [analysis_4_figs/](/analysis_4_figs)
  * [analysis_4_fig_Africa.png](/analysis_4_figs/analysis_4_fig_Africa.png)
  * [analysis_4_fig_Asia.png](/analysis_4_figs/analysis_4_fig_Asia.png)
  * [analysis_4_fig_Europe.png](/analysis_4_figs/analysis_4_fig_Europe.png)
  * [analysis_4_fig_North_America.png](/analysis_4_figs/analysis_4_fig_North_America.png)
  * [analysis_4_fig_Oceania.png](/analysis_4_figs/analysis_4_fig_Oceania.png)
  * [analysis_4_fig_South_America.png](/analysis_4_figs/analysis_4_fig_South_America.png)
  * [analysis_4-2_fig_Africa.png](/analysis_4_figs/analysis_4-2_fig_Africa.png)
  * [analysis_4-2_fig_Asia.png](/analysis_4_figs/analysis_4-2_fig_Asia.png)
  * [analysis_4-2_fig_Europe.png](/analysis_4_figs/analysis_4-2_fig_Europe.png)
  * [analysis_4-2_fig_North_America.png](/analysis_4_figs/analysis_4-2_fig_North_America.png)
  * [analysis_4-2_fig_Oceania.png](/analysis_4_figs/analysis_4-2_fig_Oceania.png)
  * [analysis_4-2_fig_South_America.png](/analysis_4_figs/analysis_4-2_fig_South_America.png)
* [Readme_imgs/](/Readme_imgs)
  * [A1.png](/Readme_imgs/A1.png)
  * [A2_1.png](/Readme_imgs/A2_1.png)
  * [A2_2.png](/Readme_imgs/A2_2.png)
  * [A3_1.png](/Readme_imgs/A3_1.png)
  * [A3_2.png](/Readme_imgs/A3_2.png)
  * [A4_2.png](/Readme_imgs/A4_2.png)
  * [A4.png](/Readme_imgs/A4.png)
* [Resources/](/Resources)
  * [owid-energy-data.csv](/Resources/owid-energy-data.csv)
  * [WPP2022_Demographic_Indicators_Medium.csv](/Resources/WPP2022_Demographic_Indicators_Medium.csv)
* [.gitignore](/.gitignore)
* [analysis_1.ipynb](/analysis_1.ipynb)
* [analysis_2.ipynb](/analysis_2.ipynb)
* [analysis_3.ipynb](/analysis_3.ipynb)
* [analysis_4.ipynb](/analysis_4.ipynb)
* [dataset_cleanup.ipynb](/dataset_cleanup.ipynb)
* [energyLEclean_NA.csv](/energyLEclean_NA.csv)
* [energyLEclean_NA_continents.csv](/energyLEclean_NA_continents.csv)
* [energyLEclean_NA_energy_sources.csv](/energyLEclean_NA_energy_sources.csv)
* [README.md](/README.md)
