![UniLogo!](Miscellaneous/Uni_logos.jpg)

# CATHeaPS

This library contains **CATHeaPS**, a **C**entralisation **A**nalysis **T**ool for **Hea**t **P**ump **S**ystems.

**CATHeaPS** is an open access modelling tool for a complete techno-economic analysis of 5th Generation District Heating and Cooling and alternative supply options for an area. These alternative supply options include centralised 4th Generation District Heating networks with decentralised Air Conditioning units for cooling, building/flat level reversible Air Source Heat Pumps and individual Gas Boilers and Air Conditioning units. CATHeaPS includes energy demand, energy supply, hydraulic and economic analysis for each considered system. The economic analysis follows the guidelines for heat network project assessment published by the UK government. The focus is on the UK market (prices, energy projections and CO2 contents), but the overall trends and relationships established can advise projects on other markets.  

![Logo!](Miscellaneous/CATHeaPS%20Logo.JPG)

# Model Overview

**CATHeaPS** is developed in Excel as it offers a combination of simplicity and sufficient coding capacity (through VBA) and is also widely available. It is intended to allow multivariable comparison and a break-even analysis of the results through simulations for a range of different scenarios. It, therefore, provides a comprehensive and effective economic and environmental evaluation of alternative approaches to providing heat for a user-defined area input. 

# Structure and information

The structure of the **CATHeaPS** along with information of each of the worksheets is shown below.

|Worsheet|Description|
|---|---|
|Cover Page|Contents, project information and list of abbreviations|										
|Heat Demand Input Data|Input data for key project area variables and building schedule including desnity, annual energy demand, consumer class mix, number of connections, number of properties and demand type (heating/cooling/heating and cooling)|										
|Peak Demand|Calculation of peak demand, sizing of units and costing for individual supply options (AC, BHP, ASHP and GB&AC)|										
|Heat Demand Summary|Summary of heating and cooling demand analysis with key figures used in the project|				
|AN DHW, SH and SC|Calculation and Diversification of DHW, space heating and space cooling demand for 5GDHC option|
|DH DWH and SH|Calculation and Diversification of DHW and space heating demand for DH option|
|Pipe Sizing|Hydraulic analysis and pipe sizing of both DH and 5GDHC networks|
|5GDHC|Energy	Annual and hourly analysis of the 5GDHC supply option to characterise the BU share|	
|Network Info and Heat Losses|Heat loss calculation and pipe/trenching details|							
|Technical Information|Database of technical information with references of sources|
|Cost Information|Database of cost information with references of sources|					
|Cashflow|Cash flow and economic modelling calculations|						
|Sensitivity|Detailed sensitivity analysis of key factors identified|								
|Emissions|CO2 Emission calculation for all energy supply options|					
|Output|Includes the main results as references to the Cash Flow Summary tab and the Sensitivity Analysis|
|Bibliography and Methodology|Bibliography of all references used along with details on the methodology used for each design decision|

# Limitations and recommendations for future work

Furthermore, all networks studied are simplified and linear. The incorporation of the capability to solve for non-linear networks is a crucial future improvement and its results should be compared to the ones outlined in this study. The capacity for a mixed network analysis, comprising centralised and decentralised WSHPs at different levels of thermal zoning. The figures and values used are focused on the UK market but there is the capacity to change them for other market analysis.

# Requirements

**CATHeaPS** is a Macro enabled workbook developed on Excel 2019.

# Aknowledgements

**CATHeaPS** was developed by Oresstis Angelidis, Anastasia Ioannou, Daniel Friedrich, Alan Thomson, and Gioia Falcone as part of an industrial PhD program. 

This work was partially funded by the University of Glasgow, Energy Technology Partnership (ETP) and Ramboll under grant agreement No ETP 189. The authors would like to thank the Ramboll Foundation for its financial support under grant agreement No 2020-101 and Ramboll UK Energy Systems business unit for its technical support. 

![ETPLogo!](Miscellaneous/Funding_Logos.jpg)
