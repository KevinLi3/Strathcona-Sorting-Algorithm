# Strathcona-Sorting-Algorithm
This was a high-school project to help school administration create trip groups for an outdoor adventure program, called Strathcona Park Lodge. Students could choose between a variety of trips to partake in (eg Canoeing, backpacking, rock climbing, kayaking, etc), and teachers would need to put them into groups based on a variety of factors. This process was required automation for a variety of reasons: 

1. Students could rank their top 5 favourite trip options, which the teachers had to do their best to account for when making these groups
2. It was required that students of each grade participated in each trip.
3. The gender ratio of the trip groups needed to be 1:1 (or quite close to it)
4. Each trip group needed to have a roughly equal number of people
5. There was a large amount of students to sort 
6. This sorting needed to happen every year 

In addition to satisfying the above criteria, this algorithm also uses a swap heuristic to optimize for a "score function", where points are associated with a student getting a highly ranked trip. Thus, our algorithm best tries to maximize the overall "score" while still following the above constraints. 
