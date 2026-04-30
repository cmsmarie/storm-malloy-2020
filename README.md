# Storm Events 2020 - Analysis

## Introduction
I chose to analyze NOAA Storm Data in 2020, which I got from Kaggle, as I’ve always been interested in weather due to my experiences in Central Texas. In Texas, I’ve experienced winter storms, hailstorms, and tornadoes, not just in Texas, but in Kansas, where I have family. 

## Findings

### Storm Types

To start, this section will analyze storm types based on the idea of frequency vs danger, as thunderstorm wind was the most common storm event at 14,461, but it is not the most destructive weather event in 2020. The first question I put into VS Code was for the top 10 most frequent storm types, with thunderstorm wind at 14,461, hail at 6,393, and flash floods at 2,191. The second question is the total property damage by storm type, with tornadoes having the most property damage at 2,380,940,033, and high winds having the least. In terms of deadliest storm types, tornadoes topped the list at 66 deaths, followed by rip currents at 29. I predicted that tornadoes would cause the most deaths and property damage due to their destructive nature and how they can easily tear a structure apart. I thought it was interesting that the NOAA Storm data separates thunderstorm wind vs marine thunderstorm wind, as I had never heard of marine thunderstorm wind and thought that it would be grouped. 

**Question 1: What are the top 10 most frequent storm types?**
![Storm Types Frequency](images/storm_types_frequency.png)

**Question 2: What is the total property damage by storm type?**
![Storm Types Damage](images/storm_types_damage.png)

**Question 3: What are the deadliest storm events?**
![Storm Types Death](images/storm_types_death.png)

### Geography

The next section is geography, in which the overall question is to analyze where storms hit the hardest, with a further analysis on Texas, Oklahoma, and Kansas, as they’re part of Tornado Alley. The first graph shows the states with the most storm events, led by Texas at 2,843, followed by South Dakota at 1,544 and Kansas at 1,308. The next question focuses on the number of event types by state. For example, Alabama has had 806 instances of thunderstorm wind, while Arizona has had three instances of dust devils. I conducted a deeper analysis of counties in Texas, Oklahoma, and Kansas by examining event counts, total direct deaths, and total property damage, as I often spend time driving between these three states. 
 
**Question 1: Which states had the most storm events in 2020?**
![States Most Event](images/states_most_event.png)

**Question 2: What is the number of event types per state?**
![States and Events](images/states_and_events.png)

**Question 3: How many storm events, total deaths, and property damage were there in Texas counties in 2020?**
![Texas](images/texas.png)

**Question 4: How many storm events, total deaths, and property damage were there in Kansas counties in 2020?**
![Kansas](images/kansas.png)

**Question 5: How many storm events, total deaths, and property damage were there in Oklahoma counties in 2020?**
![Oklahoma](images/oklahoma.png)

### Human Impact

Moving on to the section on human impact, I wanted to measure the direct vs indirect injuries by storm type and the deadliest single storm event. Direct injuries occur during the impact of the event, while indirect injuries occur before or after the event, such as falls and lacerations. Tornadoes caused the most direct and indirect injuries, which I wasn’t surprised by. The deadliest single storm event was caused by an EF-4 tornado in Putnam County, Tennessee, and led to the deaths of 19 people. 

**Question 1: Which storm type caused the most direct vs indirect injuries?**
![Injuries](images/injuries.png)

**Question 2: What was the deadliest single storm event in 2020?**
![Deadliest Event](images/deadliest_event.png)

### Economic Damage

In terms of economic damage, I measured the states with the highest property damage and the event with the greatest property damage. Davidson County in Tennessee had the most damage, which I thought was interesting, as the tornado in Putnam County was the deadliest, and I had assumed that it would also have the most property damage.

**Question 1: Which states had the highest property damage in 2020?**
![Property Damage](images/property_damage)

**Question 2: What was the single most destructive storm event in terms of property damage?**
![Most Destructive Single Event](images/most_destructive_single_event.png)

### Flood Analysis

Next, I have flood analysis, as it’s a lesser-known event in comparison to tornadoes, but it can be just as destructive. First, I have the most common flood causes with heavy rain at 3,877, followed by snow melt at 147, and an ice jam at 16. The states that had the most instances of flood-inflicted property damage were Missouri, Illinois, and Kentucky. 

**Question 1: What are the main causes of floods in 2020?**
![Flood Causes](images/flood_causes.png)

**Question 2: Which states were most affected by flooding in 2020?**
![States Most Flooded](images/states_most_flooded.png)

