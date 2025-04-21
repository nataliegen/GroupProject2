# GroupProject2

## Team Information 
21482 Group 3 

## Team Members
1. Natalie Gen [@nataliegen](https://github.com/nataliegen/GroupProject2)
2. Anika Kaushik [@anikak-05](https://github.com/anikak-05)
3. Patrick Schutz [@pschutz13](https://github.com/pschutz13)
4. Truett Thompson [@trwthompson22](https://github.com/trwthompson22)
5. Priyanka Govani [@priyankagovani](https://github.com/priyankagovani)

## Description of Dataset
Our dataset has comprehensive records of U.S. wildfires documented by the US Forest Service. The dataset contains information on wildfire incidents across the United States, capturing fires from various years and regions, which makes it one of the largest public records on wildfire activity. It provides precise location data using latitude and longitude coordinates, along with timestamps for when the fire was discovered and, in some cases, when it was contained. It has variables related to cause, size, location, and timing. The dataset allows for geospatial mapping, trend analysis over time, and studying patterns in wildfire behavior and management strategies. 
The main columns of data include *uniquefireID*, the identifier, *fireyear* which is the year the fire occurred, *firename*, *totalacres* aka the acres burned by the fire, *statcause* which is the stated cause of the fire, *discoverydatetime* and *fireoutdatetime* which is time stamp data of when the fire was first recorded and when it was contained, *latdd83* and *longdd83* which are the geographic coordinates of the fire, *sizeclass* the classification code based on the fire size, and lastly *owneragency* and *protectionagency* which represent the agencies responsible for the land and fire response. Overall, this dataset is useful for the various fire and aviation agencies that utilize fire occurrence data for management purposes. 
https://catalog.data.gov/dataset/national-usfs-fire-occurrence-point-feature-layer-d3233

## Question 1
Question: How does the average acreage burned by wildfires vary by cause and across different regions, and where are fires the most destructive?

Importance: Through this question, we are able to identify the most dangerous causes of fires and equip agencies with the knowledge of specific behaviors and conditions that lead to larger fires. In the South and West, firearms and weapons are a major outlier, signaling the need for stricter regulation and enforcement. Natural fires cause significant damage in the South, while other natural disasters are especially large in the Midwest and the West. Furthermore, in the Midwest, equipment use is a leading cause. On average, Human-caused fires vary widely by region and require region-specific prevention measures. Lastly, lighting is a major natural cause in the West and the South, implying correlation between potential fires should be established early on in the case of these natural disasters.
![image](https://github.com/user-attachments/assets/6b5d7cff-72fd-44f5-8388-311f67566349)

### Analysis and Implications
Large wildfires also lead to billions in damages, so understanding preventable patterns is important for resource usage. This can result in policy changes if equipment use is a leading cause, or if public use is not regulated enough, along with many other causes. Using analysis like our own, they can present data behind these new laws to guide smarter, location-specific fire regulations. The data can also give agencies the evidence needed to more effectively allocate their funding and resources to target more dangerous fires. It is a measure for fire mitigation if they can develop more effective preventive measures for certain causes as well.

## Question 2
Question: Based on agency, what areas are most affected by different sizes of wildfires?

Importance: This question can help us determine which agencies need more funding and resources based on the fire acreage and severity they typically handle. It would also give insight into where the USFS and state/local agencies should put more fire stations based on the areas that tend to be affected the most. From this information, federal, state, and local fire response teams can have more effective emergency preparedness plans in certain areas and preemptively station firefighters in more high-risk regions. This would drive more aware and preventive infrastructure planning based on documented knowledge of areas more prone to fire. 
![image](https://github.com/user-attachments/assets/fa4ed3f2-72ba-4020-92e1-fadb38fed7af)
![image](https://github.com/user-attachments/assets/acf5e63e-d6dd-488e-8787-91c5830e81cb)
When looking at national fires that the USFS responds to, the area with the biggest fires is the Pacific Northwest - including states like California, Oregon, Washington, and Idaho. That tells us some of the catalysts could be climate and geographic differences that make the areas more prone to droughts or more likely to contain dry foliage that fuels large wildfires. 

![image](https://github.com/user-attachments/assets/199cc231-d3b9-44f0-b175-8b4e32f1e273)
![image](https://github.com/user-attachments/assets/997ab525-726e-4bda-a26e-4b28c2f9fb76)
Alternatively, when looking at fires across the country that the local and state agencies respond to, the area with the highest amount of fires is actually the Midwest, with states including Montana and North Dakota. Here, the landscape is grasslands and plains, where fires can grow due to open terrain and wind. 

### Analysis and Comparison
Essentially, fire management for wildfires is something that needs to be tailored to the region, and agencies tend to respond to fires with different characteristics and with different preventative and later containment methods. The USFS tends to respond to more of the large-scale, prolonged incidents on federal land, whereas state and local agencies handle the ones within their jurisdiction, including private fires, which spread faster due to different terrain. Land ownership has a very high predictability of which type of agency will respond to fire occurrences. 

## Manipulations Applied to the Data Set 
We only applied manipulations in the form of calculated fields to our first visualization in order to clean up the dataset. We used the Fire Cause calculated field for the *statcause* column to filter data that was duplicated, in the incorrect formatting, or misrepresented. The region calculated field filters outliers in the *totalacres* column and excludes certain erroneous coordinates outside the scope of our analysis. 
![image](https://github.com/user-attachments/assets/baa22ed7-ed28-4196-acdf-c7bd84965d86)
![image](https://github.com/user-attachments/assets/270a6316-a488-457f-b4e1-58fcb3028101)

## Tableau Packaged Workbook
The packaged workbooks containing the visualizations above are attached to this repository.
