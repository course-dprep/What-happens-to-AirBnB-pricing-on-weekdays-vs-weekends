
# Could shortterm Airbnb weekday stays become as expensive as weekends? 



<img width="571" alt="airbnb-678x381-1" src="https://user-images.githubusercontent.com/112823109/194286546-d71e0a28-1688-4489-a5d3-b82ec66390ab.png">

## Motivation
Shortterm weekday stays are becoming increasingly popular in the U.S (Chipkin, 2022). Demand for Tuesday night stays grew 5% from 2019 to 2021; Wednesdays came in a close second, followed by Mondays and Thursdays. In the past Airbnb hosts were quickly inclined to lower their prices for renting the Airbnb during the week, while instead, they maybe could increase prices. Currently, Airdna (2022) claims that it is an ideal time to optimize the pricing strategy for Airbnb hosts. Especially, weekday stays.

In this research, prices from 

From the top 25 most popular Airbnb cities in the U.S.(Airdna, 2019), the following cities will be analyzed: Portland, San Francisco, Denver, Los Angeles, New York. These cities are spread all over the U.S, and by gathering and analyzing data of these 5 cities, a good representation of the whole U.S. is given. There is a possibility that the roomtype (entire place, private room, hotel room or a shared room) has an impact on trend. It could appear that the pricthe trend can be confirmed in the U.S. If not, hosts can change their prices based on this research. 
The general question for this study project is as follows: 

**“*To what extent does the day of the week (weekend vs. weekday) impact pricing of Airbnb in the U.S.? And does this significantly differ per roomtype, and does this significantly differ between the 5 U.S. cities?*”**

There are no sources available for the top 5 Airbnb in Europe, which agree or disagree with the statement from the U.S. For this reason, we thought it would be interesting to find out if this trend (also) exists in Europe. The 5 most popular Airbnb countries in Europe will be analyzed: Munich, Milan, Paris, London and Dublin (**BRON**). In the end, the U.S. and Europe will be compared. 

## Method
**Variables:**
```bash
- Price
- Date 
- Location 
- Computed variable weekend or weekday
- City 
- Roomtype 
- ID
- Continent
```
**Conceptual model:**

<img width="554" alt="image" src="https://user-images.githubusercontent.com/112823109/194273826-e5bffbfb-a382-4d71-9ca3-68b32ccf30d7.png">

## Analysis results

## Repository overview
```bash
├── README.md
├── data
├── gen
│   ├── analysis
│   ├── data-preparation
│   └── paper
└── src
    ├── analysis
    ├── data-preparation
    └── paper 
```
## How to run the analyses?

### Required software / programs 
To run the file you must have installed to following programs:
- [R and R-studio](https://tilburgsciencehub.com/building-blocks/configure-your-computer/statistics-and-computation/r/)
- [Make](https://tilburgsciencehub.com/building-blocks/configure-your-computer/automation-and-workflows/make/)
- [Git Bash](https://gitforwindows.org/) (windows user) of terminal (mac user)
- [pandoc](https://tilburgsciencehub.com/building-blocks/configure-your-computer/statistics-and-computation/pandoc/) is needed to convert a markdown file to PDF

### R libraries 
In R the following packages should be installed by copying/ pasting and running the following code snippet:
- install.packages("tidyverse")
- install.packages("readr")

### Collecting the data


### Running the workflow

### Data sources for this research 
- Airbnb data use available at [Inside Airbnb](http://insideairbnb.com/get-the-data/)

### Authors
This is the repository for the course [Data Preparation and Workflow Management](https://dprep.hannesdatta.com/) at Tilburg University as part of the Master's program Marketing Analytics, used for the team project of group 2.

- Bo de Ruijter, b.deruijter@tilburguniversity.edu
- Pepijn de Vries, p.j.devries@tilburguniversity.edu
- Amber Pullens, a.pullens@tilburguniversity.edu
- Anouk Lamers, a.j.f.lamers@tilburguniversity.edu
- Caroline Bloemendaal, c.a.bloemendaal@tilburguniversity.edu

### Resources

Onderstaande bronnen moeten nog verwerkt worden, daarnaast ook nog extra bronnen zoeken: 
- *5 Airbnb Guest Trends to Watch in 2022.* (n.d.). Retrieved October 4, 2022, from https://www.airdna.co/blog/5-airbnb-guest-trends-to-watch
- *Weekday US Hotel Occupancy Hits Pandemic-Era High.* (2022, June 20). Retrieved October 4, 2022, from https://www.businesstravelexecutive.com/news/weekday-us-hotel-occupancy-hits-pandemic-era-high
