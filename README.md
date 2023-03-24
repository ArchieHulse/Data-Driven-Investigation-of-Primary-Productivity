# Data Driven Investigation of the Negative Correlation between Sea Surface Temperature and Chlorophyll-a Concentration
*Investigation of the Negative Correlation between Sea Surface Temperature and Chlorophyll-a Concentration in the North Atlantic Ocean:*


![image](https://user-images.githubusercontent.com/122451494/217112252-eaae848a-d9e8-4831-a93a-10c7b26b3726.png)


## Introduction:

Chlorophyll-a (chl-a) concentration of the surface waters is a deciding factor of net primary production levels. For phytoplankton to bloom they require light and minerals. Therefore, the negative correlation between Sea Surface Temperature (SST) and Chl-a concentration levels can be explained;

In the summer months when the UV intesity from the sun is stronger, there exists higher water temperatures in the months from June-September. This causes an initial phytoplankton bloom and all of the nutrients in the surface waters are depleted.

Due to the increased SST, the upper surface water layers are prevented from mixing with the cooler lower water column which feeds nutrients from the deeper ocean. Whith a shortage in nutrient supply the phytoplankton levels drop and we see a reduced level of chl-a.

The vice versa occurs during the winter where a weaker temperature gradient occurs and mechanical mixing is able to happen more freely supply the phytoplankton whith regularly replenished nutrients. Thus explains the interannual seaonality of the phytoplankton bloom.


## Data and Method:

Data was collected from the E.U. Copernicus Marine Service Information data base funded by the European Eunion and available at https://data.marine.copernicus.eu/products

My methods involved first extracting the chlorophyll-a data in the form of a .csv file. Similarly, the sea surface temperature data was obtained using an api installation into the python editing environment where both data sets where cleaning and formated into tables ready for manipulation and visualisation.

<img width="1334" alt="Screenshot 2023-03-24 at 12 37 37" src="https://user-images.githubusercontent.com/122451494/227511518-a3763cf4-c3c4-44fd-b5a5-70a6f3821253.png">
<sup>(Schematic break-down of the summer and winter mixing differences and its effect on primary productivity)</sup>

---

## Findings:

- The maximum monthly mean water temperature at 17.8°C, occured in the same month as the minimum monthly mean chl-a concentration at 0.11μg/L

<img width="328" alt="Screenshot 2023-03-24 at 12 08 48" src="https://user-images.githubusercontent.com/122451494/227506665-015f14a5-832d-4bc2-8155-f40007876aad.png">
<sup>(TABLE. 1. Data frame cleaned and wrangled to summarise the results of SST and Chl-a concentration, monthly)</sup>

<img width="420" alt="Screenshot 2023-03-24 at 12 09 15" src="https://user-images.githubusercontent.com/122451494/227507372-484b9565-72b4-4973-9f10-2e4f7754c8ab.png">
<sup>(FIG. 1. Plot to show the seasonal variability in SST)</sup>

<img width="453" alt="Screenshot 2023-03-24 at 12 09 35" src="https://user-images.githubusercontent.com/122451494/227507604-87662394-258d-4b9d-af1d-3bb93cd4b7ec.png">
<sup>(FIG. 2. Plot to show the seasonal variability in Chl-a concentration. Dipicted is the Spring Bloom and Summer Depletion)</sup>

<img width="964" alt="Screenshot 2023-03-24 at 12 09 56" src="https://user-images.githubusercontent.com/122451494/227508146-9f1492c3-b276-44df-b1ca-9ffd9473c92e.png">
<sup>(FIG. 3. Multi-axis plot to summarise the relationship between temperature and Chl-a concentration and therfore the seasonal variability in the North Atlantic Sea Surface Primary Productivity)</sup>

## Further Work:

With futher time resource, more work in validadting the data such as its deviations from the mean to understand its accuracy would have been made.
Also, further time could be spent retreving differnt plots to visualise the data in a range of perspectives.


