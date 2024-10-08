# Connecticut Population Estimates Dashboard

This dataset and documentation power the [Connecticut Population Estimates Dashboard](https://public.tableau.com/app/profile/connecticut.state.data.center/viz/ConnecticutPopulationEstimates/PEPDashboard). The interactive dashboard shows estimates of Connecticut’s total population at the state, planning region, and town levels from the Census Bureau’s [Population Estimates Program (PEP)](https://www.census.gov/programs-surveys/popest.html) and the [official population estimates for the state of Connecticut](https://portal.ct.gov/dph/health-information-systems--reporting/population/annual-town-and-county-population-for-connecticut) certified by Connecticut’s Department of Public Health (DPH). In addition, the dashboard shows estimates of the components of population change (births, deaths, and domestic and international migration) at the state and planning region levels from the PEP, and new housing units permitted annually in each town from the Census Bureau’s Building Permit Survey.

To download this dataset as a .csv, click on "popestimates_tableau_08152024.csv" from the menu above. You'll see a preview of the dataset. To download the data, click on the down arrow button at the top right of the preview pane. When you hover over the download button, text saying "Download raw file" will appear. The data dictionary can be downloaded in the same way.

### About The Census Bureau’s Population Estimates

The Population Estimates Program (PEP) by the U.S. Census Bureau generates yearly population estimates for the country, states, counties or county-equivalents (including Connecticut's planning regions), and sub-county areas (including Connecticut’s towns). The estimates are typically based on the latest decennial census counts (though since 2020, a “[blended base](https://www.census.gov/library/stories/2023/06/blended-base-methodology.html)” has been used integrating population data from multiple sources). Population estimates for each year between decennial censuses are produced by updating the decennial base population using administrative data on annual births, deaths, migration, housing unit change, and group quarters population change. See the Census Bureau’s [technical documentation](https://www.census.gov/programs-surveys/popest/technical-documentation/methodology.html) for details.

Each annual release of the postcensal population estimates is referred to as a “vintage.” Each vintage includes estimates for every year since the latest decennial census, with the year of the vintage referring to the latest year in the data series (for example, “vintage 2022” includes estimates for 2020 through 2022). The entire series of estimates is updated in each vintage, reflecting updated data inputs, geographic boundary changes, and any methodological changes made since the last vintage. Thus, different vintages can provide different population estimates for overlapping years. The Census Bureau recommends that the latest vintage of estimates be used since this will reflect the most recent data and methods.

When conducting analyses of trends over time, it is important to use the same vintage of data across all years included in the analysis. This ensures consistency in the methodology and data inputs, providing a coherent data series for longitudinal analysis. Using different vintages can lead to inconsistencies that stem from methodological changes rather than actual population trends.

### About the Official Population Estimates for the State of Connecticut Certified by the Department of Public Health

Every year, the Connecticut Department of Public Health (DPH) reviews the Census Bureau’s latest population estimates for Connecticut. After reviewing the estimates, DPH makes any necessary modifications and releases certified population estimates for the state, counties (or planning regions), and towns. These certified estimates are used by the state to determine fiscal allocations to municipalities.

It is important to note that DPH does not update past years’ certified estimates when a new estimates series is released by the Census Bureau. For instance, although the Census Bureau’s vintage 2023 estimates may include modifications to the estimates for 2020, 2021, and 2022, the DPH-certified estimates for these years remain unchanged. Thus, the DPH estimates for each year typically align with the PEP estimates from that year’s vintage (e.g., DPH estimates for 2022 align with the estimate for this year in PEP vintage 2022), but they do not align with the entire estimates series (e.g., 2020, 2021, and 2022) from any PEP vintage.

### Data Notes

Planning regions are Connecticut's new "county-equivalent" geographies. Check out our [blog post](https://www.ctdata.org/blog/geographic-resources-for-connecticuts-new-county-equivalent-geography) to learn more about planning regions to help with the transition.

The PEP vintage 2020 estimates are based on estimated population change since the 2010 Decennial Census and do not incorporate any data from the 2020 Decennial Census. These estimates are used by the Census Bureau to evaluate the accuracy of the PEP estimates over the prior decade. For this reason, CT DPH created and released its own population estimates for 2020 based on data from the 2020 Decennial Census.

In the PEP vintage 2022 estimates, a pandemic-related issue with the count of residents in group quarters facilities (e.g., college dormitories, prisons and nursing homes) resulted in an artificially high estimate of the population in certain Connecticut towns in 2021 and 2022. For more details, see our [blog post](https://www.ctdata.org/blog/known-errors-in-the-census-bureaus-vintage-2022-population-estimates) on this topic. 

The PEP vintage 2023 estimates correct for the vintage 2022 group quarters count error by reducing the 2020 population estimate to account for the pandemic-related decrease in residents of group quarters facilities that occurred between April 1st (Census Day) and the date of the annual PEP group quarters counts. This adjustment resulted in a substantial drop in the 2020 population estimate for the state and certain planning regions and towns followed by an apparent increase from 2020 to 2021 as populations residing in group quarters facilities rebounded. The 2020 estimate therefore excludes individuals who temporarily left group quarters facilities during the first year of the pandemic, even though a substantial proportion of these probably returned to homes within Connecticut, and the estimate of population change from 2020 to 2021 includes individuals who moved back into group quarters facilities from homes in Connecticut or elsewhere. For this reason, the PEP vintage 2023 estimates of total population change from 2020 should be interpreted with caution.

The adjustment to the PEP vintage 2023 estimates also impacts the net domestic migration estimate for the state and planning regions from 2020 to 2021, yielding an apparent boost in net domestic migration that is actually attributable to residents returning to group quarters facilities in 2021 from within or outside of the state. **For this reason, we have suppressed domestic migration estimates for 2021 in this dashboard.**

### Note About the PEP Vintage 2020 Estimates and CT DPH Certified Estimates for 2020

The PEP vintage 2020 estimates are based on estimated population change since the 2010 Decennial Census and do not incorporate any data from the 2020 Decennial Census. These estimates are used by the Census Bureau to evaluate the accuracy of the PEP estimates over the prior decade. For this reason, CT DPH created and released its own population estimates for 2020 based on data from the 2020 Decennial Census.

### Questions or Comments?

This will be kept up-to-date with additional explanations and notes as they become available.

If you have questions or comments about this data or the dashboard, please submit them to info@ctdata.org.
