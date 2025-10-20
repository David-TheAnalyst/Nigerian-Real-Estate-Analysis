
# **Nigerain Real Estate Analysis**

<div align="center">
  <img src="https://github.com/David-TheAnalyst/Nigerian-Real-Estate-Analysis/blob/main/Real%20Estate%20Image.png" alt="Flowpal Sales Dashboard Additional View" width="1000" height="600">
</div>

## **Introduction**

The Nigerian residential property market, while displaying robust activity, currently faces a critical challenge: a luxury concentration risk that threatens long-term sustainability and excludes the vast majority of potential homeowners. This comprehensive, data-driven audit, leveraging an analysis of over 23,000 property listings, moves beyond simple volume metrics to expose a profound structural imbalance.

The primary aim of this project is to provide a roadmap for correction. This report serves as a Strategic Blueprint to guide Developers, Financial Institutions, and Policymakers in de-risking the market. We will pinpoint key property attributes driving valuation, quantify the untapped opportunity in the mid-market segment (Terraced and Semi-Detached Duplexes), and propose strategic, actionable pathways for product diversification and innovative financing structures necessary to bridge the observed affordability gap.

The analysis seeks to solve the problem of market imbalance as the current residential real estate supply is overwhelmingly focused on the luxury segment, evidenced by a high average listing price thereby creating an unsustainable luxury concentration risk and excludes the vast majority of potential middle-class homeowners.

## **Key Datasets and Methodologies:**

The analysis utilizes a single, comprehensive dataset of individual residential property listings across Nigeria and the methodologies employed in **Microsoft Excel** include:

-	Pivot Tables for aggregating listings by state, town, house type and calculation of summary statistics such as average price.
-	Creation of custom calculated fields (e.g., Price per Bedroom) to normalize values.

## **Story of Data:**

The dataset was acquired from a publicly available repository on Kaggle, which aggregates residential property listings from major Nigerian real estate platforms. For this analysis, the raw CSV was imported directly into Microsoft Excel.

It contains a structured list of individual property listings, with rows representing single property units and columns detailing various structural attributes. Key columns include:

-	State, Town (Location)

-	House Type (e.g., Detached Duplex, Terraced Duplex)

-	Price (in Nigerian Naira, N, the key dependent variable)

-	Bedrooms, Bathrooms, Toilets (Size metrics)

-	Parking Spaces (Amenity metric)

The Price column is the dependent variable, driven by the independent variables of House Type and Location (State/Town). The combination of Bedrooms and Parking Spaces is significant as it reveals the standardized design trends of properties targeting multi-car, large family households.
However, the data only reflects the listings price, not final transaction prices because it may introduce an upward bias, from seller negotiation margins. Also, the data does not contain the land size, build quality, or age of property thereby, limiting a full regression analysis of price drivers.


## **Pre-Analysis:**

**Data Split:**

**Dependent Variable:** Price 

**Independent Variables:** State, Town, House Type

**Industry Context:** Residential Real Estate sector.

**Stakeholders:**

-	Developers: For guiding land acquisition and product development.

-	Financial Institutions/Investors: For risk assessment and capital deployment decisions.

-	Government & Policy Makers: For housing policy reform.


## **In-Analysis:**

Whilst there is a sheer volume and high average price suggestion from the pre analysis part of the project, the standardization of 4 or more Parking Spaces across 13,377 properties indicates a uniform design trend catering to the high-income target demographic and the in-analysis phase sought to validate the following hypotheses, focusing specifically on the dominant Lagos market. 

I used Pivot Tables for segmenting data by geographical location (State, Town) and Property Type to calculate their counts and averages and discovered the following highlight

1. Lagos Dominance: Lagos accounts for over 18,000 listings, vastly outstripping the activity of the next highest state, Abuja (3,524).

2. Geographical Concentration: Lekki alone holds 10,895 listings, confirming a critical concentration of market activity in a single urban corridor.

3. High Price Floor: The average listing price is N301,380,208, immediately signaling a luxury-heavy market and a potential affordability issue.

4. There is a strong positive correlation is expected between 'Detached Duplex' Property Type and Price.

5. There is also a strong positive correlation is between the 'Lekki' Town and the highest Price per Bedroom metric.


## **Data Visualizations & Charts:**
 
 <div align="center">
  <img src="https://github.com/David-TheAnalyst/Nigerian-Real-Estate-Analysis/blob/main/Real%20Estate%20Dashboard.png" alt="Flowpal Sales Dashboard Additional View" width="1300" height="auto">
</div>

Above is a single-page dynamic dashboard created in Excel.  that can be sliced by the 36 States in Nigeria.

**Key Metrics Displayed:**

-	Total Listings (Count): 23697 

-	Overall Average Price: N301,380.208 

-	Highest Listing State: Lagos

-	Highest Listing Property: Detached Duplex

**Charts and Graphs Used:**

Bar Chart: 
-	Top 5 Average Price by House Title

Pie Chart:
-	Top 4 State with Highest Listing

Column Chart: 
-	Top 5 House Title with Highest Listing
-	Top 5 Town with Highest Listing
-	Listing by Size of Parking Space

Stacked Column Chart:
-	Average Bedroom/Bathroom/Toilet by House Title


## **Recommendations and Observations:**

**Specific Recommendations:**

1.	Developers must immediately launch the Terraced/Semi-Detached Duplex as the primary mid-range product in high-growth, adjacent corridors (e.g., Ajah), marketing them as the financially savvy, land-efficient alternative to the fully detached home.

2.	Partner with Fintech platforms to introduce Rent-to-Own or other flexible financing structures seeing it is a crucial step to monetize the salaried middle-class segment currently priced out by the N301 Million average.

3.	Investors should focus on proactive land acquisition in Lekki-adjacent areas and promising Abuja corridors, positioning for future capital appreciation as demand decentralizes from the saturated core.

4.	The Government must use this data to create tax breaks or fast-track permits for projects delivering 2−3 bedroom compact units to stimulate truly affordable supply.

5.	Policymakers should commit to road expansion, power, and water infrastructure in emerging towns to unlock new, affordable land for development, relieving pressure on hyper-expensive urban centers.

## **Conclusion:**

The analysis conclusively demonstrates that the Nigerian Residential Real Estate Market faces a critical luxury concentration risk centered around the Detached Duplex in Lekki, Lagos. This imbalance is severe, but it simultaneously reveals an immense, unserved profit opportunity in the mid-market segment (Terraced/Semi-Detached Duplexes) that can be accessed through strategic product diversification and innovative financing.


## **Limitations:**

The primary limitation is the reliance on listing price data rather than final transaction prices, which could affect the precise calculation of the price premium. Furthermore, the lack of time-series data prevents any analysis of recent price appreciation rates or inventory turnover.


## **Future Research:**

Conduct a deep dive feasibility study on the Terraced Duplex product, modeling projected land-use efficiency and profit margins in Ajah and Lekki-adjacent areas.


## **References:**

-	Nigerian Residential Property Listings Dataset  [(Kaggle)](https://github.com/David-TheAnalyst/Nigerian-Real-Estate-Analysis/blob/main/nigeria_houses_data.csv)

-	Microsoft Excel (Analytical Tool)


<h3 align="left">Connect with me on Socials:</h3>
<p align="left">
<a href="https://linkedin.com/in/david-ojo-984557231/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="david ojo" height="30" width="40" /></a>
<a href="https://twitter.com/david_ojo_1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="david_ojo_1" height="30" width="40" /></a>
<a href="https://medium.com/@davidojo2214" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/medium.svg" alt="@davidojo" height="30" width="40" /></a>
<a href="https://www.youtube.com/c/davidojo-j3v" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="davidojo-j3v" height="30" width="40" /></a>
</p>


Thanks for stopping by!
