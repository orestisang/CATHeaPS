|![ETPLogo!](Miscellaneous\ETP.jfif)|![UoGLogo!](Miscellaneous\Glasgow.jfif)|

# CATHeaPS

This library contains **CATHeaPS**, a **C**entralisation **A**nalysis **T**ool for **Hea**t **P**ump **S**ystems.

![Logo!](Miscellaneous/CATHeaPS%20Logo.JPG)

**CATHeaPS** is an open access modelling tool for the technoeconomic assessment of (a) district heating networks with a centralised WSHP, and (b) ambient networks with decentralised dwelling or plantroom level WSHP against individual ASHPs and gas boilers for a range of consumer classes. This novel open access technoeconomic tool can complete a high-level energy, hydraulic and economic analysis for any building schedule provided in seconds. This work contributes to the ongoing efforts towards heat decarbonisation by quantifying the boundaries of beneficial operation of different energy system approaches.

# Model Overview

**CATHeaPS** is developed in Excel as it offers a combination of simplicity and sufficient coding capacity (through VBA) and is also widely available. It is intended to allow multivariable comparison and a break-even analysis of the results through simulations for a range of different scenarios. It, therefore, provides a comprehensive and effective economic and environmental evaluation of alternative approaches to providing heat for a user-defined area input. 

# Structure and information

The structure of the **CATHeaPS** along with information of each of the worksheets is shown below.

|Worsheet|Description|
|---|---|
|Cover Page|Contents, project information and list of abbreviations|
|Heat Demand Input Data|Input data for key project area variables and building schedule including density, annual heat demand, consumer class mix, number of connections and number of properties|
|Peak Demand|Calculation of peak demand, sizing of units and costing for WSHP, ASHP and GB|
|Heat Demand Summary|Summary of heat demand analysis with key figures used in the project|
|AN DHW and SH|Calculation and Diversification of DHW and space heating demand for AN option|
|DH DWH and SH|Calculation and Diversification of DHW and space heating demand for DH option|
|Pipe Sizing|Hydraulic analysis and pipe sizing of both DH and AN networks|
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

**CATHeaPS** was developed by Angelidis, O., Ioannou, A., Friedrich, D., Thomson, A., Falcone, G. as part of an industrial PhD program. 

This work was partially funded by the University of Glasgow, Energy Technology Partnership (ETP) and Ramboll under grant agreement No ETP 189. The authors would like to thank the Ramboll Foundation for its financial support under grant agreement No 2020-101 and Ramboll UK Energy Systems business unit for its technical support. 
