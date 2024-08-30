# Travel-Tide
Customer segmentation of a Travel Agency "Travel Tide"

<img src="https://github.com/user-attachments/assets/64920e29-4fe6-4dfb-aabb-dc9659a0550d" alt="Customer segmentation" width="400"/>

[Here](https://colab.research.google.com/drive/1rmN6AVyNwf-so1Y2CaxPQPtrdfQoV8K0?usp=sharing) you can find the Jupyter Notebook used.

[Here](https://doc.clickup.com/9012190783/d/h/8cjp7hz-572/b8a59fd8191041f) you can find the Executive Summary.

## 🎯 Objectives                                                          
The Objective of performing a Customer Segmentation at TravelTide, a travel booking platform, is aiming for better customer engagement. The marketing team has crafted five potential perks to enhance the customer experience as follows:
Free hotel meals
Free checked bags
No cancellation fees
Exclusive discounts
One-night free hotel with a flight
Our main goal with this analysis is to identify different customer segments, each with their own preferences for particular perks based on their past behaviour. This first step is crucial in creating a personalized rewards program. However, it’s important to note that the program’s success will only be determined once these appealing perks are offered to our customers and their reactions are carefully observed and analyzed.

## 🔍 Methodology                                                     
Our first task is selecting the right group of customers for analysis. To ensure the reliability of our segmentation analysis, we consider the time customers have spent interacting with the platform.
Following guidance from the Marketing Team, our defined cohort consists of users who engaged with the platform after the New Year holiday, starting from January 4, 2023 and participated in more than seven browsing sessions during this period. This approach provides a substantial behavioural dataset, excluding recent users with limited interactions. This is how it visually looks like:

![image](https://github.com/user-attachments/assets/c4de95a9-ed2d-4efe-b34d-6d0aa9cc1b83)

We extracted raw data working on a  Jupyter Notebook hosted on Google Colab, using "SQL Alchemy" Python Library to exctract data from a PostgreSQL Database, across four key tables, generating a wide array of metrics. The data was then further processed and analyzed using several other Python Librarys. To classify customers into distinct groups we created a Decision Tree. Based on the conditions in the Decision Tree, we assigned perks that would most likely resonate with past customer behaviour.


## 💡 Key Findings                                                        
After applying the Decision Tree on the Dataset we could identify the following User Groups:

### Business
![image](https://github.com/user-attachments/assets/428cf3ca-f1ae-4166-8d6f-2391fa28b3e0)

#### Characteristics
* Users who take trips with an average stay duration of 2-3 days, typically indicative of business travel. (According to "VDR Business Travel Report 2023")
* They do not check bags but frequently book hotel rooms

#### Perk
* 1-night free hotel with flight: Provides a free hotel night when booking a flight, appealing to the typical business travel pattern.

## 

### Solo
![image](https://github.com/user-attachments/assets/1e7ebeae-5764-427a-b20a-a2b094a5b8fa)

#### Characteristics
* Users who do not check bags and typically have longer stays
* 100% of them book hotel rooms

#### Perk
* Free hotel meal: Offers a complimentary meal during their hotel stay.
## 

### Groups
![image](https://github.com/user-attachments/assets/ab18993f-65a5-43d0-b1aa-990a82ebb6e1)

#### Characteristics
* Users who often check multiple bags, book multiple hotel rooms, and travel in groups.
* Not necessarily families or couples, but rather friends or colleagues traveling together.

#### Perk
* Free checked bag: This perk reduces the cost burden on group travelers who need to check multiple bags.
## 

### Family
![image](https://github.com/user-attachments/assets/2eaae71c-930b-428b-a942-83fe44a0db12)

#### Characteristics
* Users who travel with more than one checked bag, often indicating more than one traveler.
* Typically families, identified by the presence of children in their bookings

#### Perk
* Family Discount: Offers discounts on activities that families with kids would enjoy, encouraging family travel.
## 

### Couple
![image](https://github.com/user-attachments/assets/67cb9126-aad7-45e3-98ca-b919e4ef926b)

#### Characteristics
* Users who are married but do not have children.
* Likely traveling as a couple without kids.

#### Perk
* Couple Discount: Provides discounts on couple-oriented activities to enhance their travel experience.
## 

### Dreamer
![image](https://github.com/user-attachments/assets/0ff993b1-9cc2-40c6-b8af-8af9c317e6e5)

#### Characteristics
* Users who have not booked any trips yet.
* Likely browsing and comparing offers without making a purchase

#### Perk
* First-time booking discount: This incentive encourages them to make their first booking by offering a discount.
## 

### Weekenders
![image](https://github.com/user-attachments/assets/b5a41e73-03f5-4958-a81a-172f54c9d490)

#### Characteristics
* Users who have a high proportion of bookings on weekends (>80%).
* Likely prefer short trips and quick getaways over the weekend.

#### Perk
* Weekend Discount: Provides a discount on weekend bookings to match their travel preferences.

<br>&nbsp;<br>

## 📈 Recommendations                                              
### 1. Implementation of a tailored rewards program
To enhance customer loyalty and maximize the effectiveness of our marketing efforts, we recommend the implementation of a tailored rewards program based on the insights gained from the Customer Segmentation Analysis. By aligning rewards with the specific preferences and behaviors of our identified customer segments, we can create more personalized and appealing incentives that drive engagement and repeat business.

### 2. A/B testing
Additionally, to ensure the rewards program delivers optimal results, we propose conducting A/B testing during the rollout phase. This will allow us to evaluate the effectiveness of different perks and promotional strategies in real-time, providing actionable data to fine-tune the program. By continuously monitoring customer responses, we can adapt and improve the rewards offering, ultimately leading to higher satisfaction and loyalty.

## 📄 Appendix
[Here](https://colab.research.google.com/drive/1rmN6AVyNwf-so1Y2CaxPQPtrdfQoV8K0?usp=sharing) you can find the Jupyter Notebook.
Decision Tree used in the Segmentation:

![image](https://github.com/user-attachments/assets/1681af00-9ef3-4673-9a3d-6a2d1c1b868b)


