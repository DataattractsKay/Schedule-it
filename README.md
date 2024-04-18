# Schedule It

![Banner](Banner.png)

Schedule It is a Python program built using the Qt Library for creating timetables for a summer camp. It aims to assist in generating schedules for groups of campers based on various constraints.

## Running The Program

To run the program, simply execute the script `ui.py`

## Program Information

### Purpose
This scheduling software was developed to facilitate the creation of group schedules for campers at a summer camp. It automates the process of generating schedules based on specific constraints provided

### Schedule Layout
Each schedule consists of 6 periods: 2 in the morning and 4 in the afternoon. The morning includes 2 sports activities, while the afternoon comprises lunch, swimming, and 2 sports activities. Lunch and swimming always occur during the same period every day.

### Schedule Rules
1. No group may have the same activity more than 3 times a week (2 if possible).
2. No group may have the same activity on the same day
3. No two groups can have the same activity at the same time
4. If an activity exists twice in a week it should be at least one day apart from the last time it occurred
5. If an activity exists more than twice in a week it should be in the opposite part of the day. Meaning if, for example, soccer occurs in the morning, then if it occurs again it will be in the afternoon
6. Group 2 will never place tennis

### Details
Each week, the office staff manually create a schedule for each group of campers expected in the following week. The goal when creating this schedule is to keep each one as diverse as possible, ensuring that each group participates in as many activities as possible. However, this process can be tedious and challenging, especially when dealing with multiple groups and complex constraints. It can be likened to solving a more advanced version of sudoku.

### Limitations
Sometimes, the constraints selected in the program interface may result in impossible scenarios for generating a schedule. For example, if there are more groups than available activities in a certain time slot, the schedule may be impossible to generate.

### This is the max Permutation Combination that I can apply in a lifetime! 🤯

