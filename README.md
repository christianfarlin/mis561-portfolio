# mis561-portfolio
Portfolio of projects from my Data Visualization course. This will include the completion of assignments in Excel, Tableau, PowerBI through DataCamp, Adobe Express, and various AI tools.

Initial E-Commerce Profitability Analysis, develop a basic profitability set of dashboards and explain your design, [a link to your published Tableau workbook](https://public.tableau.com/views/AdvancinginExcelandTableau-Pt_1_17893492268790/ExploratoryDash?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link), if I were doing this again, I'd further refine the dashboards by cleaning up the exploratory tooltips to remove unnecessary calculated-field information, adjusting the scatterplot axis and allowing label overlap so more subcategory labels are visible, and increasing the information panel's contrast with a darker background and white text. For the explanatory dashboard, I'd reorder the bars so the negative subcategories appear first, more prominently emphasize Tables' -8.46% profit margin in the title by highlighting the value in red, and strengthen the recommendation by highlighting that Tables has both the lowest profit margin and the lowest total profit.

Account Profitability and Service Tiers, determine which FY2026 account service policy change Southwest Office Solutions should prioritize to improve account profitability, [a link to your published Tableau workbook](https://public.tableau.com/views/AdvancinginExcelandTableau-Pt_2_17899784803710/AccountPortfolioDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link), if I were doing this again, I'd further refine the Account Portfolio dashboard by cleaning up the individual visuals, centering and emphasizing the chart titles, and increasing text contrast to better distinguish key information from the background. For the Inside Sales analysis, I'd divide accounts into smaller revenue bands, such as $1,000 increments, to compare Gross Profit and Cost to Serve within different portions of the tier. This would help determine whether the negative Net Contribution is consistent throughout Inside Sales or driven primarily by particular revenue ranges.

Introduction to Power BI, Completed September 25, 2026

https://public.tableau.com/views/PowerBITrainingCertifications_17903801267200/PowerBIStory?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Power BI Automates Data Relationships and Reduces Manual Setup

Power BI automatically detects relationships between related tables based on common fields or columns, whereas in Excel I previously had to manually match records and use lookup formulas such as VLOOKUP or XLOOKUP to bring related data together. Tableau made relationships more explicit, but I still had to identify the common fields and define how the datasets should be connected myself. For this type of task, I would choose Power BI because its automatic relationship detection reduces the manual work required to connect multiple tables while also reducing the opportunity for human error during the relationship-building process. This makes data preparation more efficient and helps avoid incorrectly connecting tables, which could affect the accuracy of the resulting analysis. However, I would still review Power BI’s automatically detected relationships to verify that it selected the appropriate fields and relationship structure, and manually modify or add relationships when necessary.

Introduction to DAX in Power BI, Completed October 5, 2026

https://public.tableau.com/views/PowerBITrainingCertifications_17903801267200/PowerBIStory?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Power BI Profit Margin Measure Enables Dynamic, Granular Profitability Analysis

In Flex 3, I calculated Profit Margin (%) in Tableau by dividing the sum of Profit by the sum of Revenue, which I used to compare profitability across product subcategories and identify Tables as having the lowest overall margin. In Power BI, I would build Profit Margin (%) as a measure rather than a calculated column because profit margin is not a fixed value that belongs to each individual row; it should be recalculated based on the data included in the reader’s current filter context. As a measure, Profit Margin (%) could dynamically respond as Anita filters by individual products, subcategories, regions, sales representatives, customer segments, or time periods, allowing her to determine where profitability problems are actually concentrated. For example, she could investigate whether Tables performs poorly throughout Southwest Office Solutions or whether particular products, regions, or other parts of the business are driving its negative margin. By placing the Profit Margin (%) measure in the Power BI model, Anita gains a reusable, self-service profitability metric that she can slice during a meeting to answer more granular business questions without waiting for an analyst to build another calculation or view.

Advancing in Power BI for Data Visualization, Completed October 12, 2026

https://public.tableau.com/views/PowerBITrainingCertifications_17903801267200/PowerBIStory?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Applying Power BI Visualization Techniques to Improve Business Intelligence and Decision-Making

Ms. Chen,

My coursework has prepared me to contribute to business intelligence at Southwest Office Solutions through data preparation, visualization, and decision-focused analysis. In Flex 3, my Tableau profitability dashboard identified Tables as the least profitable product subcategory, with a -8.46% margin. I would enhance this analysis in Power BI with a reusable DAX measure dividing total profit by total revenue within the current filter context. This would help Anita Reyes, Vice President of Merchandising, investigate margins by region or customer segment; conditional formatting would highlight negative margins without adding clutter. In Flex 4, my Tableau account analysis identified Inside Sales’ negative $16,822 net contribution. I would use Power BI drill-down through a service-tier-to-account hierarchy and drill-through to an account-filtered detail page, helping Marcus Reyes, Vice President of Sales, investigate individual accounts and target service-policy decisions. These are proposed improvements to existing Tableau analyses; Tableau also supports interactive exploration.
I would choose Excel for smaller datasets, quick calculations, and manual validation; Tableau for exploratory visual analysis and focused executive dashboards; and Power BI for related datasets, reusable calculations, and operational reports requiring repeated exploration. Across platforms, I would prioritize purposeful design and visual clarity. My Power BI experience is primarily guided training, and I have not published reports to the Power BI Service. To improve, I would independently clean and model realistic data, validate calculations and relationship keys and cardinality, practice publishing reports, and test usability with stakeholders.

**OpenAI Citation & How It Was Used**

OpenAI. (2026). *ChatGPT (GPT-6.1 Sol Light)* [Large Language Model].  
https://chatgpt.com/share/6acdcebd-ac60-83e8-adfa-d4b3a7ea1d88

I used ChatGPT on October 12, 2026, to refine and condense my independently developed business intelligence analysis into a 238-word statement while preserving my original examples, technical reasoning, and recommendations. I also used it to verify alignment with the assignment requirements.
