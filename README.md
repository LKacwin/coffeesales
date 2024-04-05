# Sales-Analysis-Dashboard

## Problem Statement
An analysis of the coffee sales in order to determine the most profile clients, countries and type of coffee for future approaches.

## Dataset Used
A data with 1000 rows and 3 years of orders. 
## Analyses derived from the dataset
- Analysis of orders shipped within seven days, within one month, and after 30 days of placing the order.

<p align="center"><img width="300" alt="orderanalysis" src![Cleaning coffe type name](https://github.com/LKacwin/coffeesales/assets/161726319/83be2fb6-a6c0-4bd9-9775-4237c5a3d14a)
=></p>

- Linked transaction, order, COGS, revenue, and net profit options buttons to the charts. If an option is selected on a chart, the selected option is displayed on all charts except those with shipping intervals.

<p align="center"><img width="262" alt="toggleoptionbuttons" src="https://user-images.githubusercontent.com/71536311/192081379-3573aef2-3a80-4a09-b114-2c58a961a156.png"></p>   
<p align="center"><img width="405" alt="profitmonquart" src="https://user-images.githubusercontent.com/71536311/192081388-68e4e70c-b8a3-4fe6-9e1c-84000ad8031f.png"> </p>     
  
<p align="center"><img width="371" alt="profitsaleschannel" src="https://user-images.githubusercontent.com/71536311/192081392-66d58382-98e2-4966-8438-ce91aa03abbb.png"> </p>     
  
<p align="center"><img width="365" alt="profititemtypes" src="https://user-images.githubusercontent.com/71536311/192081397-1718cac7-4655-4a7a-9cb2-5a9ca4458681.png"></p>     
  
<p align="center"><img width="400" alt="profitsalesregions" src="https://user-images.githubusercontent.com/71536311/192081402-dbb355b9-2125-45ba-aca8-9fb0e932b257.png"></p>

- Easy-to-read cards visualize important KPIs for rapid decision-making.

<p align="center"><img width="811" alt="kpis" src="https://user-images.githubusercontent.com/71536311/192081558-a958c702-3901-494b-a04a-321f600b2a63.png"></p>

### Active filters needed to interact with the data and the dashboard 
Country, years, and quarters

<img width="130" height="155" alt="countryslicer" src="https://user-images.githubusercontent.com/71536311/191996934-3fefa752-2aca-4285-b51b-d2f5bda2671e.png">  <img width="130" height="120" alt="yearslicer" src="https://user-images.githubusercontent.com/71536311/191996968-115a04a3-7280-4e1e-b447-ec7f1c014492.png">  <img width="120" height="85" alt="quarterslicer" src="https://user-images.githubusercontent.com/71536311/191996992-fc2f9fef-1b51-4676-9aab-59e10625f756.png">

## Tools Used
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

- Utilized **Power Query** to extract and transform the data, then transferred the data to **Power Pivot** for further analysis.
- **Power Pivot** is used to store the data for further exploration in the future, if the number of rows increases into the millions.
- Implemented **OFFSET** and **COUNTA** functions to prepare reports that interpret transaction, order, COGS, revenue, and net profit on a monthly and quarterly basis, by sales channel, by sales regions and by item types sold over time.
