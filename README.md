# Group project proposal

**Spring 2026**

Directions:

- Use your work plan from class to fill in the information below.
- Practice pulling, making changes, staging/committing/pulling/pushing to the same repo.
- **Communicate about who is doing what throughout the entire process.**

What you will submit on Friday the 15th:

- proposal: a link to your forked repository with the completed proposal in the README
- work plan: your paper plan that you completed in class on Monday the 4th

Use your project proposal to:

- refer back to the original plan while you are working
- keep track of high-level changes in structure (e.g. role switching, elective modifications)

Note:

- your project proposal is subject to change after you learn more about your datasets and what is possible - allow yourselves the flexibility to make adjustments as needed
- the more detail you can provide in your proposal, the more thorough your feedback will be

## Group members

Sofia Favela, Nina Cutner, Kelsey Hammond

## Group name (optional): 

The Geese 

## Topic information and question

**Topic: Bird abundance and precipitation patterns at North Campus Open Space (NCOS)

**Question(s):**  

- What are the effects of precipitation on bird abundance?
- How does precipitation influence waterfowl abundance through time at NCOS?
- Are there seasonal patterns between precipitation and waterfowl abundance?.

**Response variable(s)**

- Waterfowl abundance
- Species abundance counts
- Seasonal abundance trends

## Datasets

- birds.csv
- NOAA_daily_summaries.csv

## Figures

**Potential figure 1:**

Monthly precipitation through time.

![Monthly precipitation](figures/monthly-precipitation.png)

**Potential figure 2:**

Monthly waterfowl abundance through time by species.

![Waterfowl abundance](figures/waterfowl-abundance.png)

**Potential figure 3:**

Relationship between previous month's precipitation and total monthly waterfowl abundance.

![Precipitation abundance relationship](figures/precipitation-abundance.png)

**Potential figure 4**

Faceted seasonal line plots comparing average seasonal precipitation and average seasonal waterfowl abundance across all study years.

![Seasonal abundance and precipitation trends](figures/seasonal-abundance-trends.png)

## Data cleaning/wrangling/summarizing plan

### Bird data (`birds.csv`)

- Convert observation dates using `lubridate`
- Filter data to only include observations classified as `"Waterfowl"`
- Remove repeat observations
- Filter observations to water years 2020–2025
- Aggregate abundance counts by month and species
- Create summarized monthly and seasonal abundance data sets

### Weather data (`NOAA_daily_summaries.csv`)

- Convert weather observation dates using `lubridate`
- Filter observations to water years 2020–2025
- Calculate total monthly precipitation values
- Create seasonal precipitation summaries

### Combined analysis

- Join summarized precipitation and abundance data by month
- Create lagged precipitation variables to compare previous-month precipitation with current-month bird abundance
- Create seasonal summaries to compare long-term seasonal trends in abundance and precipitation

## Project roles

**Natural history/framing director:**

Kelsey Hammond

**Stats and visualization director**

Nina Cutner

**GitHub/code director**

Sofia Favela 

## Elective (not required for all groups or group members)

**Group members completing elective:**

Kelsey, Nina, and Sofia

**Elective idea:**

Create a digital interpretive trail sign/informational pamphlet on Canva to display to potential trail visitors when the best time of year would be to see waterfowl.

**Elective timeline (what you will have completed each week):**

Week 7: enter your own text here

Week 8 (timeline check in): enter your own text here

Week 9: enter your own text here

Week 10: enter your own text here

<<<<<<< HEAD
Finals week: Submit elective.    


=======

Finals week: Submit elective.    
>>>>>>> 463d009007619117d0aae3a82dd7cd96e456986a






