# Transjakarta April 2023 Dataset - Data Analysis

## Background of the Study

Transjakarta is a bus rapid transit (BRT) system operating in the Special Capital Region of Jakarta, Indonesia. Officially launched on January 15, 2004, it was the first BRT system in Southeast Asia, established to provide a fast, reliable, and affordable mode of transportation for the residents of Jakarta.

The system is operated by PT Transportasi Jakarta, a regional-owned enterprise responsible for managing and developing the Transjakarta services. It operates a wide range of fleets including standard buses, articulated buses, low-entry buses, electric buses, and smaller feeder buses to accommodate various routes and passenger needs.

With its dedicated lanes and integrated system, Transjakarta has become one of the largest BRT systems in the world in terms of route length and daily ridership. The establishment of Transjakarta aimed to reduce traffic congestion, improve air quality, and enhance the overall public transportation system in Jakarta. By offering a more efficient and environmentally friendly alternative to private vehicles, Transjakarta plays a crucial role in promoting sustainable urban mobility and addressing transportation challenges in one of the world’s most densely populated cities.

## Business Problem

**Addressing Underage Students Riding Motorcycles Without Licenses**

As Indonesia experiences a demographic bonus, several challenges arise, especially in urban areas like Jakarta. One prominent issue is the significant number of underage students commuting to school using motorcycles without the legally required driver's license (SIM). This behavior violates traffic laws and poses serious safety risks.

According to data from the Korps Lalu Lintas Polri, approximately 80% of traffic accident fatalities annually involve individuals from the student or adolescent demographic. High-profile incidents, such as a 16-year-old high school student driving a BMW without a license and causing an accident in Tangerang, highlight the urgency of this issue.

## Objective

Transjakarta aims to reduce the use of private vehicles among underage students who do not yet possess a valid driver's license (SIM) by offering a safe, comfortable, and reliable public transportation alternative. By improving services tailored to students and conducting targeted outreach through its Public Relations team, Transjakarta seeks to encourage students to shift from private vehicles to public transit.

This initiative is expected to minimize instances of unlicensed driving and reduce the risk of traffic accidents involving school-aged individuals.

## Stakeholders

**Transjakarta Public Relations Team**  
- Responsible for external communications  
- Develops the core campaign messages (e.g., safety, comfort, legality)

**Transjakarta Social Media Team**  
- Translates insights into engaging content for platforms such as TikTok, Instagram, Twitter  
- Collaborates with designers and content creators

**Digital Marketing Team**  
- Manages marketing collaborations with external parties  
- Aims to increase youth interest in using Transjakarta

## Data Understanding

The dataset contains **37,900 rows and 22 columns**, categorized into several groups:

### Transaction Information
- `transID`: Unique transaction ID  
- `payAmount`: Amount paid by the customer (some transactions are free)

### Customer Information
- `payCardID`: Unique identifier of the customer card  
- `payCardBank`: Issuing bank of the card  
- `payCardName`: Name on the card  
- `payCardSex`: Sex/gender on the card  
- `payCardBirthDate`: Birth year of the customer

### Route Information
- `corridorID`: Route or corridor ID  
- `corridorName`: Name of the route  
- `direction`: 0 for outbound, 1 for inbound

### Tap-In Information
- `tapInStops`: Stop ID where the customer tapped in  
- `tapInStopsName`: Name of the tap-in stop  
- `tapInStopsLat`: Latitude of tap-in stop  
- `tapInStopsLon`: Longitude of tap-in stop  
- `stopStartSeq`: Sequence order of the stop  
- `tapInTime`: Time the customer tapped in

### Tap-Out Information
- `tapOutStops`: Stop ID where the customer tapped out  
- `tapOutStopsName`: Name of the tap-out stop  
- `tapOutStopsLat`: Latitude of tap-out stop  
- `tapOutStopsLon`: Longitude of tap-out stop  
- `stopEndSeq`: Sequence order of the stop  
- `tapOutTime`: Time the customer tapped out

## Data Preparation

### Data Cleaning
- Handling null values, invalid times, and incorrect data types

### Removing Duplicates
- Ensured each transaction is unique

### Handling Anomalies
- Removed outliers and suspicious entries (e.g., unrealistically long durations or tap-in/out gaps)

## Analysis & Insights

- Passengers traveling early morning (05:00–07:00) are mostly adults (83.9%), followed by teenagers (13.7%) and elderly (2.4%).
- Among teenagers, female riders dominate most age groups, except at age 17.
- A significant drop in male teenage users occurs at age 16, likely due to an increased tendency to use private vehicles at that age.
- Transjakarta shows consistent performance during morning hours (05:00–06:00), with most trips finishing before 07:00.
- Peak ridership occurs during 07:00 AM and 06:00 PM, aligning with student and worker commuting hours, increasing potential for overcrowding.
- Bank DKI is the most used bank across both male and female students, likely due to their issuance of JakCard and Jaklingko cards, which are main payment methods for Transjakarta.

## Conclusion

- Transjakarta is heavily used by adult commuters in the early morning, with teens making up a smaller but significant portion.
- Female students dominate teen ridership, with the exception of male students around age 17.
- There's a sharp decline in Transjakarta use by male teens at age 16, possibly reflecting a cultural shift toward private vehicle usage.
- Transjakarta maintains good performance and on-time departures in the early hours, making it a viable alternative to private transportation.
- Peak hours overlap with both school and work commuting schedules, potentially causing overcrowding.

## Recommendation

**For Transjakarta Public Relations Team:**
- **Leverage Social Media for Awareness Campaigns**  
  Target Gen Z on social media with messages promoting Transjakarta as a reliable and legal commuting method for school.

- **Use Male Students in Visual Campaigns**  
  Highlight male high school students using Transjakarta to break the stigma that public transport isn't "cool" or masculine.

- **Promote Safety for Female Passengers**  
  Since more female teens use Transjakarta, ensure safety campaigns are visible, and provide encouragement to report harassment, both online and on physical signage.

- **Improve and Promote Complaint Mechanisms**  
  Enhance the in-app complaint process for faster, more intuitive reporting, benchmarking against systems in developed countries.

**For Transjakarta Marketing Team:**
- **Revamp JakCard/Jaklingko Appeal**  
  Introduce branding or limited-edition collaborations with influencers, artists, or brands popular with youth to make the cards more desirable.

- **Focus on Non-Premium Routes**  
  Since student ridership is concentrated in non-premium corridors, campaigns should be localized to these routes.

## References

- Transjakarta internal dataset (April 2023)
- Korps Lalu Lintas POLRI accident statistics
- News reports regarding underage driving incidents in Jakarta
