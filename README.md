# Group 3, Project 1: Impact of AI and ML Technologies in Chicago Law Enforcement
# Summary
The main objective of this project is to explore the many ways the Chicago Police Department has used AI and ML technology to arrest criminals.
# Dependencies
* Pandas
* Prophet
* Matplotlib
* Dataset: [Arrests in the City of Chicago (2014 - 2023)](https://www.kaggle.com/datasets/mattop/arrests-in-the-city-of-chicago-2014-2023?resource=download)
# Section 1
# Section 2: Computer Assistance in Stopping Traffic Violations
Summary:

Chicago's traffic stops primarily involve driving violations such as 'DRIVING ON SUSPENDED LICENSE', 'IVC - DRIVING UNDER INFLUENCE OF ALCOHOL', 'CRIMINAL TRESPASS TO VEHICLES', and 'DRIVING/NEVER ISSUED LICENSE'. The most frequent charge is 'DRIVING ON SUSPENDED LICENSE' with nearly 30,000 counts, followed by 'IVC - DRIVING UNDER INFLUENCE OF ALCOHOL' (15,000 counts), 'CRIMINAL TRESPASS TO VEHICLES' (9,000 counts), and 'DRIVING/NEVER ISSUED LICENSE' (4,000 counts).
These traffic stops are often facilitated by technology. 'Automatic Plate Scanners' began in 2010 and have an initial count of 4,500, while 'Biometrics' started in 1999 with an initial count of 3,500. 'Mobile Tech (Hand Gun)' has been used since 1989, starting with 2,500 counts, and 'Computer Aided Dispatch' also began in 1999 with 3,000 counts. These technologies significantly contribute to law enforcement efforts and traffic safety.

Conclusion:

Chicago's traffic enforcement focuses on driving violations, notably 'DRIVING ON SUSPENDED LICENSE'. Technology, such as automatic plate scanners, biometrics, mobile technology for gun detection, and computer-aided dispatch, has been integrated into traffic enforcement since the late 1990s and early 2000s. Addressing these common violations through targeted measures can improve overall traffic compliance and safety in the city, leveraging the advancements in technology for effective law enforcement.
# Section 3: ShotSpotter Gun Detection
According to an [article from The Guardian by Betsy Reed (2024)](https://www.theguardian.com/us-news/2024/feb/14/chicago-shotspotter-contract), ShotSpotter was used by the CPD from 2018 to the present; Mayor Brandon Johnson announced on February 13 2024 that the city of Chicago will stop using ShotSpotter because it "has been criticized for inaccuracy, racial bias and law enforcement misuse." (Para. 2) ShotSpotter has been referenced as a poor use of AI technology as "Community public safety groups argued that the system sends police officers to predominantly Black and Latino neighborhoods for often unnecessary and hostile encounters." (Reed, 2024, Para. 13)

My code creates a new dataframe which contains firearm related arrests in Chicago from 2018 to 2022. The code plots a bar graph which shows the amount of firearm arrests by race; Black people make up a large majority of firearm arrests in Chicago. The code also plots a line graph which shows the amount of firearm related charges minorities have received each year; There has been a massive increase in arrests in 2020, but has been on a sharp decline since 2020 and, The Guardian article corroborates this: "Violent crime, including homicides and shootings, has largely fallen across the country to about the same level as before the pandemic, though property crimes have risen in some places. In Chicago, the downward trend of violent crime has continued at the start of 2024 with a 30% drop in homicides. There were 39 through last week compared with 56 during the same period last year." (Reed, 2024, Para. 11)

My analysis is that it is hard to determine if ShotSpotter Gun Detection had a significant impact on the arrests of minorities based on the data. Other factors such as Chicago being a predominantly black city, racial bias amoungst law enforcement themselves, or unprecidented circumstances causing an increase in crime may explain the results. Despite ShotSpotter being discontinued in Chicago, I think a more accurate and reliable AI gunshot detector may exist in the future.
# Section 4
