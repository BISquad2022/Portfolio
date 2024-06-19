# Portfolio
QLIK Sense QVF examples: 

**IQR:**

Some observations within a set of data may fall outside the general scope of the other observations. Such observations are called outliers.
We can use the IQR method of identifying outliers to set up a “fence” outside of Q1 and Q3. Any values that fall outside of this fence are considered outliers. To build this fence we take 1.5 times the IQR and then subtract this value from Q1 and add this value to Q3. This gives us the minimum and maximum fence posts that we compare each observation to. Any observations that are more than 1.5 IQR below Q1 or more than 1.5 IQR above Q3 are considered outliers. This is the method that Minitab uses to identify outliers by default. 
<img width="582" alt="image" src="https://github.com/BISquad2022/Portfolio/assets/115148983/eaf0997e-656d-40da-b69a-80796fbd399f">

Source: https://online.stat.psu.edu/stat200/book/export/html/63

Check the qvf for reference: Interquartile Method (IQR).qvf
 
**Heatmap coverage:**

Explore the benefits of using heat maps for data analysis in warehouses and distribution centers. 
Enhance inventory visibility, optimize warehouse layout, streamline order fulfillment, and improve employee performance.

<img width="479" alt="image" src="https://github.com/BISquad2022/Portfolio/assets/115148983/8b10220e-7daf-4f31-8f9b-50cb01fcaff8">

Source: https://lidd.com/warehouse-productivity-heat-maps/ https://sebastianraschka.com/Articles/heatmaps_in_r.html

Check the qvf for reference: Heatmap coverage.qvf

**Combochart showcase:**
A continious bar and line chart for Sales by year with custom color by expression
![image](https://github.com/BISquad2022/Portfolio/assets/115148983/09a0b07e-456e-4dbc-9906-529bc799170f)
Combo chart showcase.qvf


