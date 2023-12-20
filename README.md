# Shift-Scheduling

**Project Overview**

This repository contains the implementation of a shift scheduling system designed for a small business context. The primary challenge addressed is to schedule a part-time employee's work hours in a manner that maximizes business value while adhering to specific constraints.

**Problem Description**
The main problem is to determine the most valuable work shifts for a new part-time employee who has a limited number of work hours per week and cannot work concurrent shifts. The value of each shift is predetermined, and the goal is to maximize the total value generated within the given constraints.

**Example Scenario**
Consider an employee who can work 20 hours a week with various shifts available each day, each offering different values. The solution involves selecting the combination of shifts that yield the highest total value without exceeding the weekly work hour limit and avoiding overlapping shifts.

**Key Features**
Shift Evaluation: Ability to assess each shift's value and duration.
Optimal Scheduling: Algorithm to find the best combination of shifts for maximum value.
Constraint Adherence: Ensures the employee does not exceed weekly work hours and does not work overlapping shifts.
Flexibility: The system can adapt to different shift lengths and values.
Implementation Details
Function: highestValueScheduleFor(const Set<Shift>& shifts, int maxHours)
Input: A set of possible shifts and the maximum number of hours the employee can work.
Output: The optimal set of shifts for maximum value generation.
Utilized Data Structures: Set<Shift>, Shift struct.
Key Functions: lengthOf(const Shift& shift), valueOf(const Shift& shift), overlapsWith(const Shift& one, const Shift& two).


**Problem Solving Approach**
Recursive Techniques: Explores combinations of shifts to find the optimal schedule.
Optimization Strategy: Focuses on generating the highest possible value within given constraints.
Considerations: Addresses the dynamic nature of scheduling and its potential impact on employees' lives.


**Ethical Consideration**
The code optimizes for business value without accounting for potential employee hardships due to unpredictable schedules. This aspect underscores the importance of considering the broader implications and stakeholder perspectives in algorithm design.
