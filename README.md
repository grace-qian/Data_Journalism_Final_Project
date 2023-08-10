<img width="326" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/6f2ca466-d6f2-477c-9dc1-06b3f15ab383"># LA's Creative Pulse: Comparing Local and National Trends
[![los-angeles-california-downtown-skyline-dszc.jpg](https://i.postimg.cc/1tpLc90k/los-angeles-california-downtown-skyline-dszc.jpg)](https://postimg.cc/G8m7bn5K)
<h1>Story Pitch:</h1>
<p>Creativity knows no boundaries, and in the bustling metropolis of Los Angeles County, a diverse tapestry of creative occupations weaves together to form a vibrant economy. For my final journalism project, I aim to delve into the realm of creative occupations in LA County, utilizing robust datasets sourced from the "Finding Datasets" repository under "Arts and Culture." Are certain creative fields more appealing to specific age groups? How diverse and inclusive is the creative industry in LA County? How does LA County's creative economy compare to national trends? Beyond the data points, this investigation takes us deep into the employment dynamics of LA's creative industries, dissecting the numbers to uncover patterns, trends, and untold stories.</p>
<h1>Data Visualization:</h1>
<h4>For my data visualization, I used Datawrapper to create a bar chart comparing the national vs LA...</h4>

<h1>Real People I Would Like to Interview:</h1>

| Name | Title | Why I Want to Interview This Person | Contact |
| :---: | :---: | :---| :--- |
| Dr. Maria Rodriguez  | Director of Los Angeles Creative Industries Institute | The first person I would like to interview is Dr. Maria Rodriguez, the Director of the Los Angeles Creative Industries Institute. Her extensive expertise in steering initiatives that foster innovation, diversity, and economic advancement within LA County's creative sector promises a profound understanding of the industry's intricacies and its impact on our region's cultural and economic tapestry. | Email - maria.rodriguez@lacii.org Twitter - @DrMariaLA |
| Mark Thompson  | President of the LA County Creative Workers Union | Engaging with Mark Thompson, the President of the LA County Creative Workers Union, holds immense value for my story. His role as a representative of creative workers offers a unique perspective on the challenges and aspirations of those shaping LA's creative landscape, enriching my narrative with on-the-ground insights from the heart of the industry. | Phone - (555) 123-4567 LinkedIn - linkedin.com/in/markthompson |
| Dr. Anthony Ramirez  | Professor of Economics at University of Southern California | Dr. Ramirez's analytical insights into how age and diversity intersect with economic trends in LA County's creative economy will not only enhance the depth of my analysis but also provide a solid foundation for discussing the broader implications of my findings. Moreover, his research may shed light on potential strategies to address disparities and foster a more equitable creative industry. | Email - anthony.ramirez@usc.edu  Twitter - @EconProfRamirez |


<h1>Data Analyses:</h1>
<p>My data is souced from CVSuite, a product of the Western States Arts Federation (WESTAF) and I will be using two datasets from the Los Angeles Arts Datathon. I have 5 questions that I will investigate and answer using data analysis techniques in Google Sheets. </p>
<p>
<h4>1. Which creative occupations have the most gender diversity and which have the least gender diversity in LA County? </h4>
<h4>2. How do the earnings in LA County's creative fields fare against the broader US trends?</h4>
<h4>3. Which creative occupation had the largest growth from 2014 to 2015 in LA and in ths US?</h4>
<h4>4. Which creative occupation has the highest hourly salary in LA and in ths US and which had the lowest?</h4>
<h4>5. What are the top occupations for each age bracket in the LA? the US?</h4>
</p>

<h2>Data Analysis 1</h2>
<h4>Which creative occupations have the most gender diversity and which have the least gender diversity in LA county? </h4>
<p>
  1. First, I highlighted the entire range of my data - including the headers ("Description," "Males", "Females.") - from the "Occupations_Gender" tab in the LA dataset. I copied these values into a new spreadsheet called "Data Analysis 1".
</p>
<p>2. I calculated the gender diversity ratio for each occupation by dividing the number of females by the total number of workers (males + females). I added this calculation as a new column in my original data. There is one occupation "Radio Operators" which is NULL because there is not an exact number for the number of females (<10) so I will delete this row for the sake of convenience.
</p>
<img width="310" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/74631f38-4c03-42ad-9f00-32de575d7322">
<p>
  3. I used a filter "Sort sheet Z-A" to sort the sheet in descending order and selected the first 5 to select the occupations at the top of the sorted list will have the highest gender diversity. The occupations at the bottom of the sorted list will have the least gender diversity.
</p>
<img width="433" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/88304fe6-1efe-444b-8781-2c4277881bae">
<img width="433" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/8c610752-564c-4578-b12e-ef224f1dea8a">
<h4>So to answer the question, Makeup Artists (Theatrical and Performance), Dancers, Choreographers, Tailors/Dressmakers/Custom Sewers, and Floral Designers are the most iverse creative occupations. The least gender diverse creative occupations are Electronic Home Entertainment Equipment Installers and Repairers, Musical Instrument Repairers and Tuners, Watch Repairers, Cabinetmakers and Bench Carpenters, and Camera and Photographic Equipment Repairers.</h4>


<h2>Data Analysis 2</h2>
<h4>How do the earnings in LA County's creative fields fare against the broader US trends?</h4>
<p>
  1. First, I highlighted the columns "Description" and "Avg. Hourly Earnings" from the "Occupations_Jobs_Earnings" tab in the LA dataset and also from the US dataset. I copied these values into a new spreadsheet (in different tabs).
</p>
<p>
  2. In a cell next to these values, I calculated the Average Hourly Earning for ALL of the different occupations for the US () and LA County. I copy and pasted these values into a new tab called "Earning Comparison".
</p>
<img width="326" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/d7c5afc2-8e2d-47cb-90ff-72b231871b34">
<p>
  3. In "Earning Comparison", I also calculated the Percent Difference, using the formula: Percent Difference = ((LA Average - US Average) / US Average) * 100
</p>
<img width="355" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/3a506c94-a6d0-4caf-b615-980df3fb7160">
<h4>For Data Analysis 2, it is clear that for creative occupations, LA County has higher wages than the US on average. The percent difference between the Average US Hourly Earning and Average LA Hourly Earning is approximately 12.78%. This means that LA's average hourly earning is around 12.78% higher than the average hourly earning in the US.</h4>






<h2>Data Analysis 3</h2>
<h4>Which creative occupation had the largest growth from 2014 to 2015 in LA and in ths US?</h4>


<h2>Data Analysis 4</h2>
<h4>Which creative occupation has the highest hourly salary in LA and in ths US and which had the lowest?</h4>
<p>
  1. First, I highlighted the entire range of my data, including the headers ("Description," "Males", "Females."), from "Occupations_Gender" tab in the LA dataset. I copied these values into a new spreadsheet.
</p>


<h2>Data Analysis 5</h2>
<h4>What are the top occupations for each age bracket in LA? the US?</h4>
<p>
  1. First, I created a new spreadsheet called "Data Analysis 5 Journ 124". I copied the "Occupations_Age" tab from the LA County dataset and the US dataset into this new spreadsheet and renamed them "Occupations_Age_LA" and "Occupations_Age_US" respectively.
  2. I added a new column at the end of my spreadsheet called "Max Age Group" and used the formula =MAX(C2:J2) in cell K2. This formula finds the maximum value (which represents the highest count) in the Age group columns for each row. I dragged this down the K column.
</p>
<img width="694" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/103a9d3e-7272-4d77-a34d-cdd1531045f2">
<p>
  3. In another sheet called "LA Pivot Table", I created a table where I listed the top occupations for each age group. I used columns A through I for Age Group, 14-18, 19-21, etc., up to Age 65+.
</p>
<img width="559" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/d55759fc-4fb2-4acb-a1c5-bc68d412fd73">
<p>
  4. In the cell corresponding to each age group and occupation column, I used a VLOOKUP function to retrieve the occupation that matches the maximum value for that age group (). I included a screenshot below.
</p>
<p>
  5. I copied the formula in step 4 for each age group column (19-21, 22-24, etc.), adjusting the column references accordingly.
  6. I repeated the steps 2-5 for the Occupations_Age_US tab.</p>






