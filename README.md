# LA's Creative Pulse: Comparing Local and National Trends
## by Grace Qian
<h1>Story Pitch:</h1>
<p>Creativity knows no boundaries, and in the bustling metropolis of Los Angeles County, a diverse tapestry of creative occupations weaves together to form a vibrant economy. For my final journalism project, I aim to delve into the realm of creative occupations in LA County, utilizing robust datasets sourced from the "Finding Datasets" repository under "Arts and Culture." Are certain creative fields more appealing to specific age groups? How diverse and inclusive is the creative industry in LA County? How does LA County's creative economy compare to national trends? Beyond the data points, this investigation takes us deep into the employment dynamics of LA's creative industries, dissecting the numbers to uncover patterns, trends, and untold stories.</p>

<h1>Data Visualization:</h1>
<p>For my data visualization, I used Datawrapper to create two bar charts. </p>

[![CWXlk-average-hourly-wages-for-us-s-creative-occupations.png](https://i.postimg.cc/QM38QB3J/CWXlk-average-hourly-wages-for-us-s-creative-occupations.png)](https://postimg.cc/gxgbd2rx)




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
<h4>3. Which creative occupation had the largest growth from 2014 to 2015 in LA and in the US?</h4>
<h4>4. Which creative occupation has the highest hourly salary in LA and in ths US and which had the lowest?</h4>
<h4>5. Which occupation is the largest (has the maximum number of people working in it) for each age bracket in LA? the US?</h4>
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
<img width="275" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/2fa22bc1-c026-4415-9029-3d308e30b7d3">
<p>
  3. In "Earning Comparison", I also calculated the Percent Difference, using the formula: Percent Difference = ((LA Average - US Average) / US Average) * 100. However, since I formatted this value to "Percent" in Format --> Numbers --> Percent, so I did not multiply by 100 (shown in screenshot).
</p>
<img width="355" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/3a506c94-a6d0-4caf-b615-980df3fb7160">
<h4>For Data Analysis 2, it is clear that for creative occupations, LA County has higher wages than the US on average. The percent difference between the Average US Hourly Earning and Average LA Hourly Earning is approximately 12.78%. This means that LA's average hourly earning is around 12.78% higher than the average hourly earning in the US.</h4>

<h2>Data Analysis 3</h2>
<h4>Which creative occupation had the largest growth from 2014 to 2015 in LA and in the US?</h4>
<p>
  1. First, I highlighted the columns "Description", "2015 Jobs",	"2014 Jobs", "2014 - 2015 % Change", "2014 - 2015 Change" from the "Occupations_Jobs_Earnings" tab in the LA dataset and also from the US dataset. I copied these values into a new spreadsheet (in different tabs).
</p>
<img width="418" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/26bf7343-f45a-4119-8654-9190d9202645">
<p>
  2. Because I want to find growth, I will filter for the occupations in which the number of jobs in 2014 is less than 2015. I created a helper column called 'Growth - Y/N?' that evaluates to 'Y' if the number of jobs in 2015 is greater than 2014, and I used this to filter the tab.
</p>
<img width="446" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/278d9e33-f539-48f5-8b6f-9d399d569696">
<p>
  3. Next, I sorted the data in descending order by "2014 - 2015 % Change". I highlighted the occupation in the first row. I repeated this for both the "LA" tab and the "US" tab (final results shown below).
</p>
<img width="433" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/df5a75c6-b902-4cea-86d6-ac8595e27a45">
<img width="429" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/b0b2f258-bab3-438e-b108-cd9983ac52a1">
<h4>From Data Analysis 3, it is clear that for Theatrical and Performance Makeup Artists had the largest growth from 2014 to 2015 in both LA County and in the US as a whole. What is interesting to note though is that in the US, Actors, Multimedia Artists and Animators, Photographers, and Film and Video Editors experienced the most growth from 2014 to 2015 (after the makeup artists); meanwhile, Photographers, Film and Video Editors, Multimedia Artists and Animators, and Writers and Authors had the most growth from 2014 to 2015 (after the makeup artists).</h4>



<h2>Data Analysis 4</h2>
<h4>Which creative occupation has the highest hourly salary in LA and in the US and which had the lowest?</h4>
<p>
  1. I first created a new spreadsheet called "Data Analysis 4". I copied the "Occupations_Jobs_Earnings" tabs from the US and LA datasets to this new spreadsheet and renamed the two tabs accordinglyl.
</p>
<p>
  2. Next I used "Sort Sheet Z to A" on the Avg. Hourly Earnings column to find the highest paying creative occupation (highlighted in the screenshots).
</p>
<img width="727" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/33c5e233-2384-4986-92fe-202503893baf">
<img width="733" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/ca5bad6c-fff4-4855-a806-75aa14d3f112">
<h4>From the screenshots, I can conclude that Marketing Managers seem to be the highest paying creative occupation in BOTH the US as a whole and in LA County. </h4>

<h2>Data Analysis 5</h2>
<h4>Which occupation is the largest (has the maximum number of people working in it) for each age bracket in LA? the US?</h4>
<p>
  1. The first step I did was to copy the columns Description, Age 14-18,	Age 19-21,	Age 22-24,	Age 25-34,	Age 35-44,	Age 45-54,	Age 55-64, and Age 65+ from the tab "Occupations_Age" from the US table. I copy and pasted these into my new spreadsheet called "Data Analysis 5".
</p>
<img width="688" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/fc1bcc28-09af-45c4-8b7b-9d9623c3e9c2">
<p>
  2. On the right side of this tab, I created a new table. I copied and pasted the "Description" column and then created a new column on the right called "Age Group with Max" which contains the age group in which the corresponding occupation has the largest number of people. I used the formula =INDEX($B$1:$I$1, 1, MATCH(MAX(B2:I2), B2:I2, 0)) and then dragged down the column. (in screenshot below)
</p>
<img width="883" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/fa78df90-0350-42bb-9c77-88139c17c4c6">
<p>
  3. My new table displays each creative occupation along with the corresponding age group that has the maximum number of people working in it. I repeated steps 1 and 2 for the "Occupations_Age" tab from the LA County Table.
</p>
<img width="72" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/9519e5f5-34a9-4168-8855-35628337fe1b">
<img width="78" alt="image" src="https://github.com/grace-qian/Data_Journalism_Final_Project/assets/108700172/211da091-7fec-4282-a7a0-35ae0e594268">
<h4>From the two tables I made, it seems that most creative workers are in the age ranges 25-34 and Age 35-44. Some interesting standouts in LA are that most Radio Operators were in the 14-18 age range and most Costume Attendants were 65+. Nationally, however, age ranges 25-34 and Age 35-44 were the only ranges that had the max number of workers (there were no age ranges that were standouts nationally).</h4>

<h1>Additional Sources:</h1>
<h2>Creative Economy Research - National Endowment for the Arts (NEA):</h2>
<h4>Link: https://www.arts.gov/</h4>
<p>This source accesses research and reports on the creative economy at a national level, offering a broader context for understanding creative art trends across the US. NEA compiles and publishes comprehensive data on various aspects of the creative economy, including employment, earnings, and contributions to GDP. Also, NEA's research often delves into regional nuances and variations within the creative economy. </p>
<h2>Art Industry Reports - Los Angeles County Economic Development Corporation (LAEDC):</h2>
<h4>Link: https://laedc.org/reports/entertainment-arts/</h4>
<p>These reports provide a localized lens through which I can analyze creative art trends by delving into the intricate web of employment, economic impact, and contributions of the art and creative sector within the county. The LAEDC's expertise in economic research, particularly in relation to the arts, ensures that the insights derived from their reports are both current and well-informed. </p>



