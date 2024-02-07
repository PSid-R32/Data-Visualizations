## Historical Assessment Dashboard
This is a dashboard which displays the number of assessment conducted from the previous year within the selected date range from the top. The bar graph to the right displays that same date range within the last 30 days. This dashboard allows for the analysis of the overall progress of a clinic's patient base and their progress. The grid at the bottom is compiled of the data points that make up the bar graph displaying the last 30 days of assessments. The bar graphs are dynamic, and clicking on a specific assessment, would yield filtered results of all other visualizations with dependencies on one another.
In this example, we see the GAD-7 asssessment and a snapshot of who it was administered to (redacted), when it was administered, the score, as well as the interpretation of the score.
For clients that administer multiple assessments across various office locations, this is a great report to help take a "zoomed out" look at the effectiveness of assessments throughout the facility.

![Assessments](https://github.com/PSid-R32/Data-Visualizations/assets/55320989/59a4e427-f956-45df-98ed-0a55343ead94)

### Takeaways
This dataset is particularly interesting to me as this serves as a perfect contender for applying Machine Learning to. In this instance, I would start by using a scatter plot instead of a bar graph, and focus on the data showing assessment scores throughout the year. From there I would sculpt a test and train dataset, and use linear regression to plot a line of where clients can expect their patients to be in the future based on historical data.

## Insurance Payment Report
This report allows the client to view which insurances claims are being cut out to. In the top grid, there is a summation of all insurance payors categorized into their respective category (Commercial, Medicaid, Medicare, respectively) shown. The arrows to the left of each of the categories expands each row and shows the breakdown of each specific payor and the total dollar amount they were billed for. 
Underneath is another grid that is linked to the top grid, and this actively filters the category that is being viewed. So when the top grid shows the **total dollar amount**, the bottom grid shows the individual dollar amount transactions that summate to the total. We also see more detailed information in addition to the payment amount regarding the invoice number, how the payment was made, date of the service, patient name and account, and even the date and user that are tied to the transaction. 

![Financial2](https://github.com/PSid-R32/Data-Visualizations/assets/55320989/7c14a66b-52aa-4c6c-bacf-d08cbec22f8d)

### Takeaways
Working with all data requires a surgical level of precision, and that statement could never be more true when creating reports revolving around a facility's money. This specific client relied on this report to keep track of over $680,000 for the 2023 calendar year.
For this report, I'd like to revisit it and add some more visualizations just to see where every cent falls categorically within the different insurance payors.

## Dose History Report 
One of the most stringent reports revolves around tracking the inventory of controlled substances. This report is typically ran for a single date, where the start and end date are the same. Here, we see the prescription order that the physician wrote, where each order has its own unique ID. The report goes on to show when these orders were written and by which physician, when the order takes effect, and when the order expires. The dispense date column is the main focus of this report as it shows any medication that was dispensed out of the facility within that date range, and by which nurse. 
This report is ran every day by nurses since it is part of their end-of-day workflow to keep a record as to where each milligram of medication went.

![Dosing](https://github.com/PSid-R32/Data-Visualizations/assets/55320989/48fb35b5-404f-4913-a81d-ca83d8b84e5b)

## Takeaway
We had just discussed the severity of reporting accurate financial reports for clients. Here, we are multiplying the severity as a clinic can be shut down, on the spot, if a DEA auditor suspects that there are unaccounted for discrepencies in the medication inventory and history. One instance, I was on the phone with a client as they exclaimed they have an auditor from the DEA sitting next to them and they want to see data point X in the report, and an explaination as to how data point Y was derived.

## Demographics Across a Facility
This report is a great one that I use often when talking to non-techincal stakeholders that want an interactive dashboard. Each one of the graphs display information as you hover over each piece of the pie, as well as the ability to dril down into each "slice" to see what makes up that slice. Right above the graphs we also see two filters that allow the user to filter their results based on parameters they requested. So while there is a location filter at the top, this specific client also wanted to be able to filter by program, as well as a specific counselor.

![Dashboard](https://github.com/PSid-R32/Data-Visualizations/assets/55320989/dfb3892b-5ee7-45d8-8b3b-c43dba6db230)

### Takeaways
I'd like to pull in more patient demographic columns focusing on cities, and towns. From there, I'd locate a rough estimate of the latitude and longitude of those cities/towns and then map that data onto a dashboard that uses geolocation as a visualization. I have yet to leverage that feature and this would be a great dataset to do so.
A big aspect of working with data is being able to make it easy to read, much like this forum (at least I hope.) Without being a data storyteller, the end user really cannot get the information that they're looking for, even if it is right in front of them. Everyone interprets information differently, and being able to adapt to each individual's learning style is pivitol when creating data visualizations.


## Overall Conclusion
While reports are only as good as the data that they are fed, there is still a slew of data validation that need to be done on the backend before it is made client-facing to ensure that the data being presented is one hundred percent accurate.

Within healthcare, there are a lot of reporting agencies within the private sector, as well as public; on a state and federal level. Being able to customize reports on a moments notice, confidently is a skill that I value immensely.




