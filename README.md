# TripOpt+ : Travel Planner (C Project)

TripOpt+ is a simple C-based travel planning application that helps users choose the best set of places to visit within a given budget and time limit.

The project combines **Dynamic Programming** and a **Greedy Algorithm** to:
- Select the most valuable places under constraints
- Decide the best visiting order for maximum enjoyment

---

## Features

- Accepts user input for multiple places
- Each place includes:
  - Name
  - Cost
  - Time required
  - Enjoyment score
- Uses **Dynamic Programming (DP)** to:
  - Select optimal places within budget and time
- Uses **Greedy Algorithm** to:
  - Sort selected places by enjoyment-to-time ratio
- Displays:
  - Selected places
  - Visit order
  - Total cost, time, and enjoyment

---

## Algorithms Used

### 1. Dynamic Programming (DP)
- Solves a variation of the **Knapsack Problem**
- Maximizes total enjoyment while staying within:
  - Budget constraint
  - Time constraint

### 2. Greedy Algorithm
- Sorts selected places based on:
