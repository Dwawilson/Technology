# Group 3, Project 1: Impact of AI and ML Technologies in Chicago Law Enforcement
# Summary
The main objective of this project is to explore the many ways the Chicago Police Department has used AI and ML technology to arrest criminals.
# Dependencies
* Pandas
* Prophet
* Matplotlib
* Dataset: [Arrests in the City of Chicago (2014 - 2023)](https://www.kaggle.com/datasets/mattop/arrests-in-the-city-of-chicago-2014-2023?resource=download)
# Section 1: Analysis of Predictive Technology in Larceny including Retail Theft in Chicago
Intro:

Retail theft is a significant concern for businesses across the United States. According to the 2023 National Retail Security Survey, losses soared to a staggering $112.1 billion in 2022, a concerning 19% increase from the previous year.
This rise in theft has even led to store closures, with retail giants like Walmart citing "tens of millions of dollars" in annual losses as a reason for shutting down locations in Chicago. Whole Foods also faced similar challenges, permanently closing its flagship San Francisco store due to safety concerns.
These incidents raise a crucial question: is the surge in retail theft a national trend, or are there other factors at play?
This analysis delves into this question by examining whether advancements in video recording technology, including the adoption of predictive AI by retailers and the Chicago Police Department, might be influencing these trends.

Conclusion:

While national larceny rates, which include shoplifting and retail theft, have been declining and may be plateauing, data specifically on retail theft remains limited. Cities like Chicago with extensive camera networks present a unique case study. The ongoing development of surveillance technology might influence future retail theft trends, but its effectiveness requires further investigation. 

Sources:

[Chicago among worst areas of the country for retail theft, industry group says - CWB Chicago](https://cwbchicago.com/2023/11/chicago-among-worst-areas-of-the-country-for-retail-theft-industry-group-says.html)

[Myth vs. Reality: Trends in Retail Theft | Brennan Center for Justice](https://www.brennancenter.org/our-work/research-reports/myth-vs-reality-trends-retail-theft)

[Ten Years After First Warning, Chicago’s Massive Surveillance Camera System Continues to Pose an Unregulated Threat to Privacy | ACLU of Illinois (aclu-il.org)](https://www.aclu-il.org/sites/default/files/field_documents/video_camera_surveillance_in_chicago.pdf)
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

Sources:
[20 Law Enforcement Software & Police Technology for 2024](https://10-8systems.com/20-latest-law-enforcement-software-and-police-technologies/)
[Mayor Lightfoot, CPD Launch Two New Area Technology Centers to Solve Crimes Faster and Improve Clearance Rate](https://www.chicago.gov/city/en/depts/mayor/press_room/press_releases/2019/august/AreaTechnologyCenters.html)
[Public Safety Technology in Chicago | CDS Office Technologies](https://www.cdsofficetech.com/public-safety-technology-in-chicago/)
[Chicago is the latest city rethinking disputed technology that listens for gunshots • Stateline](https://stateline.org/2024/02/27/chicago-is-the-latest-city-rethinking-disputed-technology-that-listens-for-gunshots/)
[Mobilizing First Responders with Computer-Aided Dispatch (CAD) & RMS](https://10-8systems.com/first-responders-with-CAD-and-RMS/)
[Spillman Flex™ Public Safety Software   - Motorola Solutions](https://www.motorolasolutions.com/en_us/products/command-center-software/public-safety-software/flex.html)
[Mobile CAD: Keeping Modern Officers Connected and Safe](https://insights.samsung.com/2018/12/11/mobile-cad-keeping-modern-officers-connected-and-safe/)

# Section 4: Law Enforcement's use of AI to Arrest Perpertraitors of Crimes Related to Sexual Abuse
Code:

A new DataFrame was created with the variables "Arrest Date" and "Charges Description".
The index was set and the arrest dates were sorted and verified by showing the top 5 and top bottom arrest dates/charge description in the dataset.
The dataset was further filtered to show only specific Charges that were related to sex crimes.
The results of the data analysis were displayed using a line graph to show a steady decrease in arrests due to sexually related crimes over the past 9 years.

References:

Camello, M. L., Houston-Kolnik, J. D., & Planty, M.
(2021). Chatbots in the criminal justice system.
Research Triangle Park, NC:RTI International

[ChatGPT.](https://chat.openai.com/)

[National Institute of Justice. (2021). Chatbots in the Criminal Justice System.](https://cjtec.org/files/65532ea7aa6f8)


