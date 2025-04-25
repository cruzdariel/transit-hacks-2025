![header](https://transit.rso.uchicago.edu/files/2025/03/Black-Gold-Luxury-Page-Border-Double-Sided-Poster-5.png)
# Transit Hacks 2025

## Location
Hacking will occur inside the Media Arts and Design Center located inside of the John Crerar Library at 5730 S Ellis Ave, Chicago, IL 60637.

There will be dedicated hacking spaces inside the Computer Science Instructional Laboratory, specifically CSIL 1 and CSIL 2. Each space contains several desktop computers for your use and monitors you may be able to plug your personal machine into.

![map](https://www.lib.uchicago.edu/media/images/Crerar_Map_Floor1_eLwXcwn.original.jpg)

Free parking is available on the street around the University and in the lot at 60th and Stony Island. Most University parking lots are free to the public all day on weekends. The parking structure at 55th and Ellis Avenue charges a fee 24 hours a day or requires a permit. Please call the Parking Office for more information at 773.702.8969.

Visit https://maps.uchicago.edu/ for a campus map.

## Internet Connectivity
Hackers are encouraged to use the *eduroam* network for the most secure and fastest internet connection at the University. Off-campus students in a participating institution, such as UIC, can enroll in *eduroam* on their device prior to arriving. For UIC/UIUC/UIS students, that information can be found at https://help.uillinois.edu/TDClient/37/uic/KB/ArticleDet?ID=898.

If you are not with an *eduroam* participating institution, please see a member of Hackathon staff to get connected. *uchicago-guest* is available, but is not secure and is slower than other networks. The login information for this network is: [TBA]

## Schedule
*Subject to change*

**12:00pm – 12:30pm**
Introduction / team formation / Lunch

**12:30pm – 6:30pm**
Free work time - SUBMISSIONS DUE 6:30 PM

**6:30pm – 7:00pm**
Dinner served

**7:00pm – 8:00pm**
Presentations and judging

**8:00pm – 8:30pm**
Awards ceremony, wrap-up

## Food and Beverage
We’ll have a snack area open by Peach’s Cafe throughout the day with an assortment of fruits, chips, and gummy snacks. Please be aware of any dietary restrictions while enjoying any snack, we don’t make any guarantee of their compliance with certain dietary needs.

You are encouraged to bring a reusable water bottle, there are bottle refill stations inside the JCL.

For Lunch, we will be ordering Pizza from Bob’s Pizza in Hyde Park.
For Dinner, we will be ordering Wings from Medici on 57th in Hyde Park with a side of fries and Mac and Cheese.

Please be advised that absolutely **no food or drink** are allowed inside the Media Arts and Design Center or the Computer Science Instructional Laboratory. If you want a snack, you’ll have to enjoy it outside the center before you head back in for hacking. (You could also 100% pick another location to hack in, just be back before judging!)

## Resources
Please join the Transit Hacks discord for all resources, including direct links to multiple APIs, Wrappers, and other Pre-built tech solutions by members of the UChicago community. Some developers are on the server as well to troubleshoot.

Some services require an API key in advance, Hackathon staff will endeavor to get keys in advance for some applications but these will be shared across teams and could be rate limited. For the most flexibility, consider requesting a key in advance (especially Metra).
### Chicago Transit Authority
#### Bus Tracker API
https://www.transitchicago.com/developers/bustracker/
#### Train Tracker API
https://www.transitchicago.com/developers/traintracker/
#### Open Data Portal
https://www.transitchicago.com/data/
#### Ridership Reports
https://www.transitchicago.com/ridership/
### Divvy
#### Live Station Information
https://gbfs.divvybikes.com/gbfs/2.3/gbfs.json
#### Trip History Data
https://divvy-tripdata.s3.amazonaws.com/index.html
### Metra
#### General Transit Feed Specification Data (GTFS)
https://metra.com/developers
### University Transportation 
#### PassioGO! API - by @swissmenace 
https://github.com/athuler/PassioGo
#### UChicagoShuttles.com API - by @swissmenace 
https://uchicagoshuttles.com/
#### UIC Ride Endpoints
These are some endpoints I discovered in the TransLoc backend:
- **GetVehiclePoints** https://uicride.transloc.com/Services/JSONPRelay.svc/GetMapVehiclePoints?apiKey=8882812681&isPublicMap=true
- **GetVehicleCapacities** https://uicride.transloc.com/Services/JSONPRelay.svc/GetVehicleCapacities
- **GetVehicleRouteStopEstimates** https://uicride.transloc.com/Services/JSONPRelay.svc/GetVehicleRouteStopEstimates?quantity=2&vehicleIdStrings=12
#### Northwestern TripShot
Inspect Element -> Network shows a ton of endpoints https://northwestern.tripshot.com/
### General Use
#### McFadden Transit Reliability API
https://brandonmcfadden.com/transit-api
#### McFadden CTA Reliability
https://github.com/brandonmcfadd/cta-reliability
#### McFadden Metra Reliability
https://brandonmcfadden.com/metra-reliability
#### City of Chicago Open Data
https://data.cityofchicago.org/
#### @kameranis's CTA API Wrapper and Scheduler
https://github.com/kameranis/cta-analysis

## Judging Criteria
Projects will be judged on the following criteria:

| Category                        | What to Look For                                                                                                                                                         |
|---------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Real-World Impact & Relevance   | Does it address a concrete pain-point for Chicago transit riders or operators? Have they identified clear stakeholders (commuters, CTA, city planners)? Evidence of research into existing services/data. |
| Technical Implementation        | Is the prototype functional and robust (no obvious bugs/crashes)? Quality of code (readability, modularity, API usage). Complexity matched to their claim—did they “hack” something non-trivial?            |
| Innovation & Creativity         | How novel is the idea compared to existing tools (Ventra app, CTA bus tracker, etc.)? Did they combine datasets or tech (ML, real-time open data, IoT) in a new way?                                |
| Data Usage & Analysis           | Effective use of Chicago-specific datasets (CTA ridership, Divvy, Metra). Depth of analysis (visualizations, insights). Proper handling of data quality and ethics.                                 |
| User Experience & Design        | Is the interface intuitive and well-designed? Accessibility (mobile-friendly, color-blind-safe, simple flows). Clear onboarding/demo for non-technical judges.                                      |
| Presentation & Storytelling     | Clarity of pitch: problem statement → demo → impact. Ability to answer judges’ questions on the fly. Good time management and slide/visual quality.                                          |

## Prizes
There will be a 1st place winner and 2nd place winner.

1st place team members will win a Transit Tees board game set, which will be arranged to be delivered to you following the competition. Every team member will get a board game of their selection from the set. Thank you Transit Tees for your support!

2nd place team members will win a Chicago “El” poster, which will be given at the competition.

## Submissions
Submissions must be in by **6:30 PM** and uploaded to the Devpost site for the Hackathon at https://transit-hacks-2025.devpost.com/. Teams should submit a public GitHub repository link containing their code, a README file explaining the project, a pdf version of your presentation slides (if used), and any supplementary materials.​

## Still need help?

Judges and mentors, when not with us in-person, will monitor the Discord for teams in need of assistance and provide support there. 

https://discord.gg/bcg7wYu7

Happy hacking!
