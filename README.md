## Analyzing Booking Data for Splendor Hotel Groups (SHG) with the use of Microsoft Excel

Hello, I stumbled on an interesting dataset on Twitter (well, the owner calls i 'X' now but we still call it twitter here). I decided to play around the dataset to answer some questions the requirements demanded.

### Project Brief: Analyzing Booking Data for Splendor Hotel Groups (SHG)

Greetings from Splendor Hotel Groups (SHG). As a recently recruited Business Intelligence Analyst and Data Analyst, you will be essential to our efforts to solve the puzzles buried in our booking data. Renowned hospitality company SHG aims to improve visitor experiences and streamline corporate processes by utilizing data-driven insights. Your task is to thoroughly examine one of our best resorts' past booking data in order to identify trends, comprehend consumer behavior, and offer useful suggestions for tactical decision-making.

### Project Overview:

Your task involves a thorough analysis of a comprehensive dataset, featuring intricate details of bookings, guest demographics, distribution channels, and financial metrics. By applying your analytical prowess, we aim to extract meaningful insights that will not only inform operational improvements but also contribute to the overall success of SHG in delivering unparalleled hospitality.

The Project Overview and Objectives, Dataset and a dynamic dashboard prepared for dataset can be [downloaded here](https://drive.google.com/drive/u/1/folders/19nVyGpj6y2h-qMmRqqStpJ1KFA3g_-gj)

### Tools Used:

Microsoft Excel

### Data Loading, Cleaning and Preparation

The dataset was already in Excel format, opening the file was all the loading there to do. The dataset had already been cleaned. Nonetheless, I still checked the dataset to ensure that it was in a state good for use. I validated the dataset and went through each column for errors and outliers. The colum
In the "Customer Type" column, I noticed that the variable "Transient" also appeared as "Transient-Party" in some fields. This needed to be corrected in order not to distort our analysis. I employed the "Find and Replace" function as shown in the image below. 

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/69c10a15-0b33-456f-82d5-6e9063eae93e)

### Objectives of the Analysis:

### Booking Patterns:


- What is the trend in booking patterns over time, and are there specific seasons or months with increased booking activity?
- How does lead time vary across different booking channels, and is there a correlation between lead time and customer type?

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/45a2845b-6c3f-43d9-be48-0c60072b9f5c)

From the visual above, Splendor Hotel Groups (SHG) witnessed a rapid growth in bookings from 2013 to 2016. Their highest annual number of bookings was in 2016 with an approximate **59K** total bookings. There was a **55%** drop in booking in 2017. However, the data for 2017 ended in August, four months short of a full calendar year. 

Total bookings for 2017 is expected to rise by the end of the year when the months of September to December have been added to the dataset. From graph below showing the total bookings for January to August for 2015-2017, one can see that there are more bookings in 2017 than 2015 in the 8 months. However, there are 12K more bookings in 2016 than there are in 2017 in the same first 8 months.

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/0c3b4cfa-7471-450f-9203-7559ece130d4)

The months of January, February and March in the 1st quarter and October, November and December in the 4th Quarter are the most active in the year. The oddball is the month of July with a surge in bookings.

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/e3f2a2cc-a76f-478b-8089-26884b55dd61)

The months of January, February and March in the 1st quarter and October, November and December in the 4th Quarter are the most active in the year. The oddball is the month of July with a surge in bookings.

**_Recommendations:_**
_With an aggressive marketing approach and by replicating previous strategy adopted in the 4th quarters of 2015 and 2016, total bookings for 2017 can gain ground on 2016 figure. The remainder of 2017 can not be left to chance as there is a unusual downward trend in the Total Monthly Bookings for 2017 up to August. Some incentives can be introduced to reverse this trend._

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/61f7e512-135c-4c68-96ee-97ffd6647232)

Bookings through the Offline Travel Agents have the highest average lead time of 136 days. Online Travel Agents booking channel has an average leadtime of 108 days. Followed by the Direct and Corporate channels with 58 and 45 days respectively. Bookings via the Undefined channel have the least average lead time of 23 days.

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/13270a3d-89c6-4fc6-9041-85dadc31b04b)

Contract customers have an average lead time of 143 days per booking, Transient customers have an average lead time of 103 days. Group customers have a 55-day leadtime.

### Customer Behavior Analysis:

- Which distribution channels contribute the most to bookings, and how does the average daily rate (ADR) differ across these channels?
- Can we identify any patterns in the distribution of guests based on their country of origin, and how does this impact revenue?

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/d46c4ae5-78de-4dd9-9195-3cdfd5506a31)

From the summary highlighted in the chart on the left above, Online Travel Agents contribute most to total bookings with about **74K** out of the total **119K** recorded. That is **62%** of the total booking recorded.

For Average Daily Rate (ADR), Online Travel Agents has the highest with an average of **$108.57**, Direct with **$106.65**, Offline Travel Agents with **$87.15**, Corporate with **$69.33** and Undefined channel with the least ADR at **$46.24** per booking. See chart on the right above.

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/efd76f74-9124-41dc-a896-73f639e3f65e)

The graph above shows the Top 10 countries in total guests and revenue over the period. 
Portugal made a total revenue of **$9M** from **90,036 guests** in that period. The top 8 countries in total guests and revenue are from Europe (Portugal, UK, France, Spain, Germany, Italy, Ireland and Belgium). Brazil and China complete the Top 10 with **$475K** revenue from **4,867 guests**, and **$516K** from **4,669 guests** respectively.


**_Recommendations:_**
_A whooping **62%** of bookings were made from Online Travel Agents (OTA)and this channel also has the highest ADR amongst all the channels. The hotel needs to ensure that their infrastructure supporting online bookings are well maintained to avoid any downtime that can lead to booking challenges and loss of revenue. 
The hotel can also encourage the Offline Travel Agents to adopt the online channel as the OTA channel has the highest ADR and more revenue for the Hotel. Assuming half of the bookings made through Offline Travel Agents are routed through the online at the higher OTA ADR, that will translate to more revenue to the increase (even if number of bookings via offline remains constant)._

_The market approach in Portugal should be continued and similar ones tailored for each country should be encouraged for roll-out to increase revenue._

### Cancellation Analysis:

- What factors are most strongly correlated with cancellations, and can we predict potential cancellations based on certain variables?
- How does the revenue loss from cancellations compare across different customer segments and distribution channels?

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/c20d65d1-6b8a-4571-9636-64ab2eabeba8)

As shown in the scatter plot above, it can be argued that cancellation is more likely as the lead time increases. Longer lead time is correlated with cancellation rate.
Customers whose bookings with 150 days are more likely to cancel their booking than to check-in.

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/1a023f73-7ee3-4704-9f61-e4356dbd207f)

A total **$13.12** Million was the Revenue Loss over the period being analyzed. Of this amount, Transient Customers account for 98%, while Contract Customers account for **2%.**

The Distribution Channel that is responsible for the most Revenue Loss is the Online Travel Agents (**82%**). Offline Travel Agents, Direct and Corporate follow with **8%, 8%** and **2%** respectively.

**_Recommendations_**
_Revenue Loss is a direct result of booking cancellation. Revenue is lost when reservations are made while the rooms reserved are prevented from being booked by other guests, but the reservations are eventually cancelled.
Measures that will ensure minimal cancellation should be implemented. A small deposit for the bookings that are prone to cancellation (the ones with long lead time) should be demanded to get some commitment._

### Revenue Optimization:

- What is the overall revenue trend, and are there specific customer segments or countries contributing significantly to revenue?
- Can we identify optimal pricing strategies based on the Average Daily Rate (ADR) for different customer types and distribution channels?

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/a1f6f2d0-0d6d-4f1d-936d-5d79a831484f)

There has been an upward trajectory in Total Revenue from 2014 up to 2016. There is a **46%** drop in Revenue recorded in 2017. It is worthy of note that the record for 2017 is incomplete as it ends at 31st August. There are the months of September to December that are yet to be accounted. 

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/ce89d892-935f-450c-a2f4-3bba5a3c15df)

From the graph above, Transient Customer Type contributes most to Total Revenue with **$27.92M** out of the **$29M** recorded. Contract Customer Type comes a distant second with **$1.56M** in revenue.

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/da002c3f-e863-4ba3-bd08-a287616bdfd3)

The graph above shows the Top 10 countries in total guests and revenue over the period. 
Portugal made a total revenue of **$9M** from **90,036 guests** in that period. The top 8 countries in total guests and revenue are from Europe (Portugal, UK, France, Spain, Germany, Italy, Ireland and Belgium). Brazil and China complete the Top 10 with **$475K** revenue from **4,867 guests**, and $516K from **4,669 guests** respectively

**_Recommendations_**
_Transient Customers that contributed mostly to revenue can targeted in promotional programs and offers to further improve patronage and revenue._

### Geographical Analysis:

- How does the distribution of guests vary across different countries, and are there specific countries that should be targeted for marketing efforts?
- Is there a correlation between the country of origin and the likelihood of cancellations or extended stays?

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/ef26c600-e0a4-40a8-86cc-53625f3b1243)

During the period under review, Portugal contributed over **90K** to the total guests received (a whooping **38.3%**). Out of the top 20 countries in total guests, Europe accounts for 17 of them. 

The countries with the highest number of guests tend to have the most cancellations. 

**_Recommendations:_**
We need to better understand the guests in Portugal through surveys on their continuous patronage of the hotel and the areas that we need to improve upon. We can further introduce incentives, like loyalty programs and encourage them to use any of our hotels whenever they visit other cities outside of Portugal that has a Splendor Hotel._

_Brazil, Spain and a few other countries with similar cultures with Portugal can be targeted to replicate what are being done right in Portugal. Insight gathered from surveys and in-house generated data could be helpful in planning a targeted marketing strategy for the aforementioned countries._

_Based on their population sizes, the hotel group ought to be having more guests in the US, China, Russia and the UK. Efforts should be made to understand what needs to be improved upon to increase patronage._ 

### Operational Efficiency:

- What is the average length of stay for guests, and how does it differ based on booking channels or customer types?
- Are there patterns in check-out dates that can inform staffing and resource allocation strategies?

Guests to Splendor Hotel group average 3days per stay in the period under review. 
Contract Guests average 5 days per stay. Transient and Group Customers both spend an average of 3 days per stay.

By customer type, Offline Travel Agents spend more time per stay on an average at 4 days per stay.
Direct, Undefined and Online Travel Agents customer types average 3 days per stay. Corporate customers average 2 days per stay.  

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/fb06fbd8-d17a-4b03-923b-f7336d5d1cd5)

Sunday is the busiest day of the week for guests’ check-out. Followed by Thursday and Friday. 
Allocating more resources to these days to ensure business runs smoothly notwithstanding the number of guests trying to check out would be recommended. Ensuring customer satisfaction requires deliberate actions. 

Tuesday and Wednesday are the least busy days. More staff can be scheduled to have their off-days on these days as the traffic is expected to be less.

### Impact of Deposit Types:

- How does the presence or absence of a deposit impact the likelihood of cancellations and revenue generation?
- Can we identify any patterns in the use of deposit types across different customer segments?

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/c03b8be4-d811-4c90-a161-90d6bef9f42a)

Out of the **119,390** bookings recorded in the period under review, **44,224** bookings either canceled or did not show up. Late cancelations and no-shows are revenue lost by the Hotel as the rooms booked could have been booked by other guests when the bookings were yet to be cancelled. 
**104,610** bookings were made without any deposits made. About 30K bookings cancelled or did not show up. **28%** of the total bookings were made with no deposits. The cancellations and no-shows for the booking made with no deposit amount to **$13.1M** which is about **34%** of total revenue that could have been made if those cancellations never occurred. 

**_Recommenations:_**
_The Hotel group needs to discourage booking cancellation. Guests should be made to show commitment deposit (non-refundable or partial refund) while making bookings._

### Analysis of Corporate Bookings:

- What is the proportion of corporate bookings, and how does their Average Daily Rate (ADR) compare to other customer types?
- Are there specific trends or patterns related to corporate bookings that can inform business strategies?

![image](https://github.com/ahniyi01/Analyzing-Booking-Data-for-Splendor-Hotel-Groups-SHG-/assets/140920419/50ff09ff-f088-4cd0-814e-ea068e27fbf6)

Corporate Booking account for **6%** of the total booking. Average Daily Rate (ADR) for booking through corporate channel is **$69.33**. Overall ADR is **$101.83**. The ADR for bookings through corporate is **$32.50** lower than the overall ADR.
