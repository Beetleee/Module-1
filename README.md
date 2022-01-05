# Kickstarting with Excel
  By Terra Lasho
  
Overview of Project

	This project was created to help Louise visualize the goals and rates of success or failure of different theater/play type campaigns. I started with a  database of information containing many campaigns. From this, I was able to filter on data relevant to Louise’s needs, which were specifics on lunch date (month), funding goal (amount), type of campaign (plays/theater type), and overall outcome (success, failure, or canceled) of the campaign. By using functions to help analyze this, I was able to provide Louise several graphics which may help her visualize trends for the month(s) with highest launches for this type of campaign, as well as which funding level goals were most successful/failed.
	
Analysis and Challenges

	Analysis of Outcomes Based on Launch Date:
	
	I began the analysis by creating a pivot chart from our main spreadsheet which contained the filtered data for ‘theater’ campaigns (derived from a column describing parent category [for campaign]). See attached file: Theater_Outcomes_vs_Launch.png. I used a pivot table which quantifies the number of each campaign outcome (successful, failed, or canceled) in columns by the launch month displayed in rows.  In the attached figure, I used a line graph to display the information and show for each outcome, the total number of launched campaigns per each month. 
		
	Analysis of Outcomes Based on Goals:

	I began this analysis by creating the rows and columns specified by the instructions. I found that after creating the COUNTIFS formula, there was just small editing needed to continue (update just a single criteria or range). See attached file: Outcomes_vs_Goals.png) This visual shows the filtered data on ‘plays’. The table data included goal amount ranges which were listed in rows, whereas the calculated total number for each outcome was listed by column, followed by the total number overall, and finally by the fraction of the total (percentage) for each outcome. The Figure shows the trends for successful vs failed (canceled was not represented in this campaign category) for each goal range by percentage. 
 
Challenges and Difficulties Encountered

	For the launch data, I did not have any difficulties and the data analysis was very straightforward (the pivot table insert really helped). I noticed the data shows total campaigns by month, however, different years were described in the raw data and the line graph by month does not take into account if particular years affected launch numbers and/or success rates. Also, it would be good to look at percentage vs. total numbers in the final visuals so that Louise can also get a better idea of successful months (i.e. if high totals of launches occurred in successful and failed campaigns, this might mislead one into thinking that even though there were lots of successful campaigns, the rate of success may not be good.
	
	For the goals data, I initially had some trouble with the parent vs. sub-category. The instructions said to filter ‘plays’ and I filtered ‘theater/plays’ from the parent category. I did have to go back and re-read the instructions (whoops, human error) to find that the sub-category was to be filtered instead. Also, I initially had some difficulty with the COUNTIFS function. Specifically, I did not know where to how to describe the monetary ranges within the category. Eventually, I googled how to determine ranges with COUNTIFS and was able to duplicate the criteria and range and include the maximum (see in red in additional attached file: Figure_3). 
 
Results

•	What are two conclusions you can draw about the Outcomes based on Launch Date?

	1)	Successful launch dates were most populous during May-June.
	2)	It would be so valuable to also include percentage successful information in this data, because an awful lot of failed campaigns also happened in these months.
	
•	What can you conclude about the Outcomes based on Goals?

	1)	Low goal ranges were successful.
	2)	The figure (see attached file: Outcomes_vs_Goals.png) also shows that there were other goal ranges which were higher in value which were successful, so just defining a low goal range for success may not be the only consideration for a successful funded campaign.
	
•	What are some limitations of this dataset?

	Some limitations, as I described above, include taking months rather than years into account for success. Also, perhaps Louise should look at other campaign type data analysis in order to to highlight ‘play’ specific trends she hope to see.
	
•	What are some other possible tables and/or graphs that we could create?

	Maybe the data could be stratified by country. Perhaps different countries are more interested in specific campaign types? Also, as I mentioned above, we should include the percentage successful overall for the by Launch Date data.
