# Connecticut Population Estimates Dashboard

This dataset and documentation power the [Connecticut Population Estimates Dashboard](https://public.tableau.com/app/profile/connecticut.state.data.center/viz/ConnecticutPopulationEstimates/PEPDashboard). The interactive dashboard shows estimates of Connecticut’s total population at the state, planning region, and town levels from the Census Bureau’s [Population Estimates Program (PEP)](https://www.census.gov/programs-surveys/popest.html) and the [official population estimates for the state of Connecticut](https://portal.ct.gov/dph/health-information-systems--reporting/population/annual-town-and-county-population-for-connecticut) certified by Connecticut’s Department of Public Health (DPH). In addition, the dashboard shows estimates of the components of population change (births, deaths, and domestic and international migration) at the state and planning region levels from the PEP, and new housing units permitted annually in each town from the Census Bureau’s Building Permit Survey. 

The Census Bureau releases new population estimates for different geographic levels over the course of the year, beginning with state-level estimates, then planning regions, and finally towns. This dashboard will be updated as new estimates are released for each geographic level. For more information, see the Census Bureau’s Population Estimates Release Schedule and Building Permits Survey Release Schedule. 

See notes below for more details on data definitions and limitations.

To download this dataset as a .csv, click on "popestimates_tableau_03-2025.csv" from the menu above. You'll see a preview of the dataset. To download the data, click on the down arrow button at the top right of the preview pane. When you hover over the download button, text saying "Download raw file" will appear. The data dictionary can be downloaded in the same way.

## About The Census Bureau’s Population Estimates

The Population Estimates Program (PEP) by the U.S. Census Bureau generates yearly population estimates for the country, states, counties or county-equivalents (including Connecticut's planning regions), and sub-county areas (including Connecticut’s towns). The estimates are typically based on the latest decennial census counts (though since 2020, a “[blended base](https://www.census.gov/library/stories/2023/06/blended-base-methodology.html)” has been used integrating population data from multiple sources). Population estimates for each year between decennial censuses are produced by updating the decennial base population using administrative data on annual births, deaths, migration, housing unit change, and group quarters population change. See the Census Bureau’s [technical documentation](https://www.census.gov/programs-surveys/popest/technical-documentation/methodology.html) for details.

Each annual release of the postcensal population estimates is referred to as a “vintage.” Each vintage includes estimates for every year since the latest decennial census, with the year of the vintage referring to the latest year in the data series (for example, “vintage 2022” includes estimates for 2020 through 2022). The entire series of estimates is updated in each vintage, reflecting updated data inputs, geographic boundary changes, and any methodological changes made since the last vintage. Thus, different vintages can provide different population estimates for overlapping years. The Census Bureau recommends that the latest vintage of estimates be used since this will reflect the most recent data and methods.

Once a decade, the Census Bureau releases “intercensal” estimates for the 10 years between the most recent decennial census and the prior decennial census. In November 2024, the Census Bureau released intercensal estimates for the years from 2010 to 2020. These estimates revise the prior decade’s estimates to align with the most current census and are the recommended data series for that decade. 

When conducting analyses of trends over time, it is important to use the same vintage of data across all years included in the analysis. This ensures consistency in the methodology and data inputs, providing a coherent data series for longitudinal analysis. Using different vintages can lead to inconsistencies that stem from methodological changes rather than actual population trends.

## About the Official Population Estimates for the State of Connecticut Certified by the Department of Public Health

Every year, the Connecticut Department of Public Health (DPH) reviews the Census Bureau’s latest population estimates for Connecticut. After reviewing the estimates, DPH makes any necessary modifications and releases certified population estimates for the state, counties (or planning regions), and towns. These certified estimates are used by the state to determine fiscal allocations to municipalities.

It is important to note that DPH does not update past years’ certified estimates when a new estimates series is released by the Census Bureau, as DPH estimates are used for funding allocations. For instance, although the Census Bureau’s Vintage 2023 estimates may include modifications to the estimates for 2020, 2021, and 2022, the DPH-certified estimates for these years remain unchanged. Thus, the DPH estimates for each year typically align with the PEP estimates from that year’s vintage (e.g., DPH estimates for 2022 align with the estimate for this year in PEP Vintage 2022), but they do not align with the entire estimates series (e.g., 2020, 2021, and 2022) from any PEP vintage. 

## Data Notes, Errors, and Corrections

Planning regions are Connecticut's new "county-equivalent" geographies. Check out our [blog post](https://www.ctdata.org/blog/geographic-resources-for-connecticuts-new-county-equivalent-geography) to learn more about planning regions to help with the transition.

In the PEP Vintage 2022 estimates, a pandemic-related issue with the count of residents in group quarters facilities (e.g., college dormitories, prisons and nursing homes) resulted in an artificially high estimate of the population in certain Connecticut towns in 2021 and 2022. For more details, see our [blog post] (https://www.ctdata.org/blog/known-errors-in-the-census-bureaus-vintage-2022-population-estimates) on this topic. 

The PEP Vintage 2023 and later estimates correct for this error by subtracting residents who left group quarters facilities between April 1st, 2020 (Census Day) and the fall of 2020 from the 2020 population estimate. This resulted in a drop in the 2020 population estimate for certain towns, followed by an increase from 2020 to 2021 as populations residing in group quarters facilities rebounded. However, it is unknown whether residents who left group quarters facilities actually moved out of the state, planning region, or town where their facility was located. For this reason, estimates of total population change from 2020 in PEP Vintage 2023 and later estimates series should be interpreted with caution. For more details, please see our [blog post] (https://www.ctdata.org/blog/vintage-2023-population-estimates-for-connecticut) on this topic. 

### Changes to the Estimation of International Migration in PEP Vintage 2024 

The PEP Vintage 2024 estimates incorporate a methodological change to how the Census Bureau estimated net international migration, resulting in higher estimates of net international migration in 2022 through 2024 in Connecticut and nationwide. This change also yielded higher estimates of Connecticut’s total population in these years. For more information, see our [blog post] (https://www.ctdata.org/blog/vintage-2024-state-population-estimates) on this topic. 

### Calculation of Implied Net Household Domestic Migration  

PEP’s net domestic migration estimates incorporate both household domestic migration and group quarters change (see PEP’s [methodology] (https://www2.census.gov/programs-surveys/popest/technical-documentation/methodology/2020-2024/methods-statement-v2024.pdf) for details). Given the large pandemic-related shifts in the population residing in group quarters facilities, we calculate the implied net household domestic migration by subtracting group quarters change from PEP’s net domestic migration estimate. This approach has been used previously by the Census Bureau in their [analysis of domestic migration trends during the pandemic] (https://www.census.gov/library/stories/2023/03/domestic-migration-trends-shifted.html).  

### Note About the CT DPH Certified Estimates for 2020 

CT DPH created and released its own population estimates for 2020 based on data from the 2020 Decennial Census. They did not use the PEP estimates for that year because these were based on estimated population change since the 2010 Decennial Census and did not incorporate any data from the 2020 Decennial Census.  

### New Housing Units

Data on new housing units are from the 2020-2023 Building Permit Survey, which is conducted by the Census Bureau to gather statistics on residential construction projects across the country. This survey requests the number of new housing units covered by residential building permits issued from all permit-issuing entities (including Connecticut’s towns). The Census Bureau uses these data to estimate the annual change in housing units in each town in Connecticut, which is in turn used in the estimation of the annual population change in each town. The counts shown here are for new permitted residential housing units in each calendar year (January – December). 

### Questions or Comments?

This will be kept up-to-date with additional explanations and notes as they become available.

If you have questions or comments about this data or the dashboard, please submit them to info@ctdata.org.
