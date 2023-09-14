# Optimal European Adventure Planning Using Mixed Integer Programming

## Context:
You've secured a week off and have a budget of €1500 to set forth on a thrilling European journey. With attraction 
scores for various cities, estimated travel times, and accommodation costs at hand, employ Mixed Integer Programming 
to ensure you extract the maximum enjoyment from your trip!


## Problem Description:
Embark on your expedition from Iceland on a Monday, and you'll also wrap up your journey there the subsequent Monday.
Your escapade spans seven days, and each day (except the last) starts with travel. Upon touching down at your 
chosen city, you dive straight into sightseeing. Remember, the seventh day has a twist! While you can sightsee till 
it's time for your flight, ensure you account for airport logistics.

## Data Acquisition:
**Travel**: You possess an Interrail ticket for one week. Costs? Your task to determine. Use dohop.com to gather flight 
quotes from Iceland. However, ensure you select cities that have direct flight connectivity with Iceland. Also, 
remember to factor in travel time from the airport to the city center (minimum 2 hours) and the time needed for 
airport procedures on your return (3 hours before takeoff).

**Accommodation**: Use platforms like hotels.com, booking.com, or any relevant source to acquire rates for 2-3* 
accommodations. Lucky for you, you're touring with a buddy, so accommodation costs are divided between the two of you.

**Attraction Scores**: Derive these scores based on ratings from Google Places, TripAdvisor, or or any other 
credible source.

## Guidelines:
### Variables:

Consider a binary variable indicating if you're stationed in a specific city on a certain day.
Another binary variable might be handy to record if you're transitioning from one city to another on any given day.

### Objective: 
What's the primary objective? Experience maximization! Integrate attraction scores, travel times, and the 
unique rule for the seventh day in your strategy.

### Constraints:

* **Budget**: Ensure your total expenses, including accommodation and other costs, don't surpass your budget.
* **Time**: Dedicate time for both traveling and sightseeing in each city.
* **City Visit Frequency**: Ponder on the frequency of your visits to each city.
* **Logical Transition**: Transitioning between cities should be sequential and logical.

### Hints:

* Dedicate each day to a single city for sightseeing.
* Travel time and the last day's schedule significantly affect a city's attraction score.
* Logic is key! Ensure your plan isn't paradoxical.
* Remember, your journey begins and concludes in Iceland.
* Ward off unnecessary detours in your plan to optimize sightseeing time.


## Collaboration and Assessment:
### Phase 1:
Work collectively to consolidate and share data. Collaboration at this stage ensures a uniform dataset for all.

### Phase 2:
Divide into two groups. Each group is tasked with crafting a concise technical report that encompasses:

* A rigorous mathematical formulation.
* Clear articulation of objectives and constraints in line with the guidelines provided.

### Software & Participation:
Use Gurobi for solving; and be certain you have secured an academic license. Since this will be too large for the 
default free-tier. 
Active participation in the modeling is paramount. Engage in constructive discussions regarding the model in the 
GitHub issues list.

### Presentation & Evaluation:
You will present your collective findings in class on September 28th 2023. Each member must make their presence felt,
as I will undertake an oral assessment to gauge their comprehension of the task. The essence of this exercise is not 
for members to fragment the work and tackle their segments. Although roles might be designated to specific members, 
comprehensive understanding is pivotal. Each one must be familiar with the team's undertakings, and no one should be 
left in the dark.

In times of ambiguity, seek clarification, or for additional insights, do not hesitate to tag me on GitHub, 
`@tungufoss` or via e-mail at `helgaingim@hi.is`. My office is located in room 254a in VR-II.

## Submission:
Your MIP formulation, presented in an articulate manner, should be submitted. This report should meticulously detail 
your optimal seven-day itinerary, conforming to the stipulated budget and time constraints. Submit your report in
PDF format to this GitHub repository, and send the URL to the file via the Canvas assignment. 
The deadline for submission is September 28th 2023.

Every team member's comprehension and contribution are essential to succeed in this endeavor. Here's wishing you an 
enlightening voyage in European adventure planning!
