# mis561-portfolio
Portfolio of projects from my Data Visualization course. This will include the completion of assignments in Excel, Tableau, PowerBI through DataCamp, Adobe Express, and various AI tools. 

1. Initial E-Commerce Profitability Analysis. The goal was to develop a basic profitability set of dashboards and explain the design choices behind them. If I were to do this again, I'd plan to start earlier and would spend more time cleaning the data. Here is the link to Tableau visuals: https://public.tableau.com/app/profile/anastasiia.semenova2944/viz/FlexAssignment3_17893676615480/ExploratoryDash

2. Account Profitability and Service Tiers. The business question: where is Southwest Office Solutions losing the most money on its accounts, and which single change, in tiering, cost to serve, or discounting, should the VP of Sales make for FY2026? If I were to do this again, I'd build the Top N filter and context filter earlier in the process instead of layering it on last, since it changed how a couple of my other filters behaved. Here is the link to Tableau visuals: https://public.tableau.com/app/profile/anastasiia.semenova2944/viz/FlexAssignment4/DesignJustification

3. Introduction to Power BI course from DataCamp, completed 9/26/2026.
In Flex Assignment 4, I built a separate "Profitability" calculated field in Tableau just to color my bars red or grey based on positive or negative net contribution. Power BI does this automatically through its formatting pane, no formula required. Next time I'd use Power BI's built-in conditional formatting for a simple case like this, since it does the same job faster and I'd only reach for a manual calculated field if the coloring logic got more complex than a simple threshold.
Link to my Tableau profile: https://public.tableau.com/app/profile/anastasiia.semenova2944/viz/PowerBITrainingCertifications_17904864317360/PowerBIStory

4. Introduction to DAX in Power BI course from DataCamp, completed 10/01/2026.
In the Excel sheet I built for Flex Assignment 4, I pulled Order Year and Order Month out into their own columns by hand just so I could summarize a four-year file by period. In DAX, once you have a real date table marked as the model's date table, time-intelligence functions handle those period comparisons automatically, without the need to pre-extract and hardcode year or month breakdowns for every new calculation. Next time I'd set up a date table and use DAX's time intelligence instead, since it adapts to any filter context automatically rather than covering only the slices I thought to pre-build.
Link to my Tableau profile: https://public.tableau.com/app/profile/anastasiia.semenova2944/viz/PowerBITrainingCertifications_17904864317360/PowerBIStory
