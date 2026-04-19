# Constraints & Patterns: Advanced Scheduling and Search

## The Project
This lab tackles two distinct "heavy-lifting" areas of computer science: solving NP-hard constraint satisfaction problems through intelligent search and optimizing text pattern recognition.

## Core Features
* **Crew Scheduling**: A backtracking-based engine that assigns airline flights to crew members while strictly adhering to safety overlaps and mandatory rest periods.
* **Search Optimization**: A deep dive into string matching, comparing the "brute-force" Naive approach against the Knuth-Morris-Pratt (KMP) algorithm to see how pre-processing saves time.

## Performance Insights
Because backtracking can be computationally expensive, I implemented Branch and Bound logic to "prune" the search space, ensuring the algorithm focuses only on viable solutions.
