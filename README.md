# Phase-1 Project

## AIRCRAFT RISK ASSESSMENT AND RECOMMENDATION FOR COMMERCIAL BUSINESS EXPANSION

Here is a snappy readme file for this project you're going to love !

**Author**: [Cindy Minyade](https://github.com/cminyade/phase-1-project.git)

# Overview
This project analyzes the data set attached in the zip folder. It invloves data cleaning, imputation, analysis and visualization to provide valuable insights for a business stakeholder to expand their business.

## Business Problem 
Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.

## Data
The [data](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) is from the National Transportation Safety Board. 
The data includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.

In my analysis I selected 8 columns that I thought woukd be relevant in this study. They include the following
 - Aircraft Make, Model, Damage, Category, Fatal Injuries, Serious Injuries, Weather Condition and Broad phase of flight. However, in the graphs presented below, my main focus drew to the fatality/seriousness of the injuries as well as the number of incident occurences. 

## Methods
This project aims to analyze the data, deal with missing values, data aggregation and visualization so as to help the organization make data driven decisions through the recommendations that we will provide.
It also aims to communicate about the data analysis process for better understanding of the analysis conducted.

## Results
Safe Models: The results below shows a list of **top 10 aircraft** models that have at most 1 incident count and 0 fatal injuries. These models appear to be the lowest risk

## safe model table
| Make                 | Model     | Aircraft.Category   | Aircraft.damage   |   Incident.Count |   Total.Fatal.Injuries |   Total.Serious.Injuries |
|:---------------------|:----------|:--------------------|:------------------|-----------------:|-----------------------:|-------------------------:|
| Airbus Industrie     | A320      | Airplane            | Minor             |                1 |                      0 |                        0 |
| Fairchild/swearingen | SA226TC   | Airplane            | Minor             |                1 |                      0 |                        0 |
| Gates Lear Jet       | 35A       | Airplane            | Minor             |                1 |                      0 |                        0 |
| Gates Learjet        | 25        | Airplane            | Minor             |                1 |                      0 |                        0 |
| Grumman              | AA-1A     | Airplane            | Minor             |                1 |                      0 |                        0 |
| Gulfstream American  | G-159     | Airplane            | Minor             |                1 |                      0 |                        0 |
| Gulfstream American  | G-159C    | Airplane            | Minor             |                1 |                      0 |                        0 |
| Lockheed             | L-1011    | Airplane            | Minor             |                1 |                      0 |                        0 |
| Mcdonnell Douglas    | DC-10-30F | Airplane            | Minor             |                1 |                      0 |                        0 |
| Nord Aviation        | 262A-12   | Airplane            | Minor             |                1 |                      0 |                        0 |

Unsafe Models: The results below shows a list of **top 10 aircraft** models that have highest fatalities and has the most number of incidents. These models appear to be the highest risk

## unsafe model table
| Make         | Model     | Aircraft.Category   | Aircraft.damage   |   Incident.Count |   Total.Fatal.Injuries |   Total.Serious.Injuries |
|:-------------|:----------|:--------------------|:------------------|-----------------:|-----------------------:|-------------------------:|
| Boeing       | 747-300   | Airplane            | Destroyed         |                1 |                    228 |                       26 |
| Cessna       | 172N      | Airplane            | Destroyed         |               22 |                     36 |                        7 |
| Piper        | PA-28-161 | Airplane            | Destroyed         |               13 |                     34 |                        4 |
| Piper        | PA-28-140 | Airplane            | Destroyed         |               21 |                     32 |                       20 |
| Fokker       | 28-4000   | Airplane            | Destroyed         |                1 |                     27 |                        9 |
| Cessna       | 172       | Airplane            | Destroyed         |               20 |                     22 |                       12 |
| Cessna       | T210M     | Airplane            | Destroyed         |               10 |                     19 |                        1 |
| Cessna       | 172M      | Airplane            | Destroyed         |               15 |                     19 |                       10 |
| Cessna       | 152       | Airplane            | Destroyed         |               26 |                     18 |                        6 |
| De Havilland | DHC-6-200 | Airplane            | Destroyed         |                2 |                     16 |                       14 |

# Recommendations
I have provided 3 recommendations to offer the business stakeholders.
- The focus should be to purchase aircraft models that have a history of zero fatalities and minimal damage and incidents such as `Airbus Industrie/A320`, and those shown in the analysis.
- Maintain proper weather monitoring to mitigate operational hazards.
- Provide proper training to the pilots to alert them on things that can affect various phase of flight and cause accidents therefore, preventing such occurences. 

# Conclusions
- The data may not have potrayed the best results because of the various missing data, which can affect the data analysis.
- The analysis conducted had the main focus on fatalities, and did not put much consideration into other factors such as the weather conditions and the phases of the flights and maintanance factors. 

### Next Steps
_What else could I do in the future to improve this project?_

- I would conduct a deeper analysis on the underlying causes of the accidents.
- Widen the data analysis factors so that a broader analysis can be done such as incorperating the weather conditions, the phases of the flights, the purpose of the flight, may come to yield a broader scope of the analysis. 
- Certain external factors such as pilot experience could also be analyzed in better detail.
