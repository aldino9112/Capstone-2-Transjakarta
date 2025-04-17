## Transjakarta 2023 April Dataset - Data Analysis

# Background of the Study
Transjakarta is a bus rapid transit (BRT) system operating in the Special Capital Region of Jakarta, Indonesia. Officially launched on January 15, 2004, it was the first BRT system in Southeast Asia, established to provide a fast, reliable, and affordable mode of transportation for the residents of Jakarta. The system is operated by PT Transportasi Jakarta, a regional-owned enterprise responsible for managing and developing the Transjakarta services.
Transjakarta operates a wide range of fleets including standard buses, articulated buses, low-entry buses, electric buses, and smaller feeder buses to accommodate various routes and passenger needs. With its dedicated lanes and integrated system, Transjakarta has become one of the largest BRT systems in the world in terms of route length and daily ridership.
The establishment of Transjakarta aimed to reduce traffic congestion, improve air quality, and enhance the overall public transportation system in Jakarta. By offering a more efficient and environmentally friendly alternative to private vehicles, Transjakarta plays a crucial role in promoting sustainable urban mobility and addressing the transportation challenges in one of the world’s most densely populated cities.

# Business Problem
Addressing Underage Students Riding Motorcycles Without Licenses
As a country experiencing a demographic bonus there are several issues that need to be addressed. One of these challenges is the issue faced by the capital city. In Jakarta, a significant number of underage students commute to school using motorcycles without possessing the legally required Surat Izin Mengemudi (SIM), or driver's license. This practice not only contravenes traffic regulations but also poses substantial safety risks. Data from the Korps Lalu Lintas Polri indicates that annually, approximately 80% of traffic accident fatalities involve individuals from the student or adolescent demographic. Furthermore, specific incidents, such as the case of a 16-year-old high school student operating a BMW without a license and colliding with a motorcyclist in Tangerang, underscore the gravity of the situation .​

# Objective
Transjakarta aims to reduce the use of private vehicles among underage students who do not yet possess a valid driver’s license (SIM), by offering a safe, comfortable, and reliable public transportation option. Through service improvements tailored to the needs of students and strategic outreach conducted by the Transjakarta Public Relations team, the initiative seeks to encourage students to choose Transjakarta as their alternative to private transportation. This effort is expected to help minimize instances of unlicensed driving and reduce the risk of traffic accidents involving school-aged individuals.

# Stakeholder
Transjakarta Public Relations Team:
Responsible for external communications.
Develops the core messages of the campaign (e.g., safety, comfort, legality).
Transjakarta Social Media Team:
Transforms insights into engaging content for platforms such as TikTok, Instagram, Twitter, etc.
Collaborates with designers and content creators.
Digital Marketing Team:
Handles marketing collaborations with external parties to increase youth interest in using TransJakarta.

# Data Understanding
The dataset consists of 37,900 rows and 22 columns. The dataset contains multiple attributes grouped into the following categories:

Transaction Information :
	transID: Unique transaction id for every transaction  
	payAmount: The number of what customers pay. Some are free. Some not.

Customer Information :
	payCardID: Customers main identifier. The card customers use as a ticket for entrance and exit.  
	payCardBank: Customers card bank issuer name  
	payCardName: Customers name that is embedded in the card.  
	payCardSex: Customers sex that is embedded in the card  
	payCardBirthDate: Customers birth year

Route Information :
	corridorID: Corridor ID / Route ID as key for route grouping.  
	corridorName: Corridor Name / Route Name contains Start and Finish for each route.  
	direction: 0 for Go, 1 for Back. Direction of the route.

Tap In Information :
	tapInStops: Tap In (entrance) Stops ID for identifying stops name  
	tapInStopsName: Tap In (entrance) Stops Name where customers tap in.  
	tapInStopsLat: Latitude of Tap In Stops  
	tapInStopsLon: Longitude of Tap In Stops  
	stopStartSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.  
	tapInTime: Time of tap in. Date and time

Tap Out Information :
	tapOutStops: Tap Out (Exit) Stops ID for identifying stops name  
	tapOutStopsName: Tap out (exit) Stops Name where customers tap out.  
	tapOutStopsLat: Latitude of Tap Out Stops  
	tapOutStopsLon: Longitude of Tap Out Stops  
	stopEndSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.  
	tapOutTime: Time of tap out. Date and time

Data Preparation

Data Cleaning

Data Duplicate

Data Anomaly

Data Preparation

Analysis/Insight

# Conclusion and Recommendation

# Conclusion

Based on demographic data, passengers traveling in the early morning (05:00–07:00 AM) are predominantly adults (83.9%), followed by teenagers (13.7%) and a small portion of elderly passengers (2.4%).
Among teenagers, the majority of riders are female. Across the 11–18 age range, females dominate in most age groups, except at age 17. This may be due to the higher popularity of private vehicles among male teenagers.
Here is a significant decrease in the number of male Transjakarta users at the age of 16. This may be due to the behavior of teenage boys at that age, who tend to prefer using private vehicles.
As for departure performance, Transjakarta appears to maintain a consistent schedule, especially between 05:00–06:00 AM, with most trips completing before 07:00 AM. This indicates good on-time performance during early hours.
Transjakarta experiences peak occupancy during rush hours at 07:00 AM and 06:00 PM. Unfortunately, this overlaps with the travel times of both students and workers, increasing the likelihood of overcrowding.
Bank DKI is the most frequently used bank, with relatively equal distribution between male and female users. This is likely due to the fact that Bank DKI issues JakCard and Jaklingko card, the primary payment card for TransJakarta rides.

# Recommendation

With the goal of encouraging students—especially those underage and without a driver's license—to choose Transjakarta over private vehicles (which is not only illegal but also contributes to congestion and pollution in Jakarta),This recommendation should be more targeted toward the non-premium routes, as only a small number of students use premium routes.
The following actionable recommendations are proposed for Transjakarta’s public relations and marketing teams:

For TransJakarta Public Relations:

Leverage Social Media for Awareness Campaigns
Targeting Gen Z—who are highly active on social media and rely on it as a primary source of information, Transjakarta can run informative campaigns highlighting that it is a reliable and timely alternative for commuting to school.
Use Male Students in Visual Campaigns
To counter the perception that riding a private vehicle is a status symbol for "boys", to be specific is highschool boys since a massive declining of teenage boys at 16 years old from using Transjakarta. Visual content featuring male students commuting with Transjakarta can help normalize male students to use public transit as a practical, flexible, and efficient option.
Promote a Safe Environment for Female Passengers
Demographic data also shows that a higher female number of Teenager that using Transjakarta, which highlights the importance of ensuring a sense of safety for them.

According to this report, cases of sexual harassment involving women, including underage girls, are often unreported due to various reasons. Therefore, further education and awareness efforts are needed. These can be carried out through social media campaigns and also through visible signs inside TransJakarta buses, encouraging passengers to speak up if they witness or experience sexual harassment.

Improve and Promote Complaint Mechanisms
While TransJakarta already has a complaint system via its app, it remains inefficient according to user feedback. The app needs significant improvement to provide fast, intuitive reporting—similar to those implemented in other developed countries.
For Transjakarta’s marketing team:
The JakCard or Jaklingko Card, which is the most widely used payment method among teenagers, should be made more appealing. One approach is to create collaborations with brands or public figures that are popular among the youth. This strategy has already been implemented by competing banks, showing its effectiveness in attracting the younger demographic.
Here is the comparison between Bank DKI against competitors.

References

