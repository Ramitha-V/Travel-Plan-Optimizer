# Trip Planner Program

## Overview

The Trip Planner Program is designed to simplify the process of travel planning for individuals by allowing them to create detailed itineraries. It enables users to input various destinations, allocate days and budgets, and specify activities within each destination. The program manages these inputs to ensure the plan remains within the user's budget and timeframe. It also presents the travel plan in an organized manner and provides warnings for any issues with the plan.

## Motivation

Travel planning can be complex, involving decisions about destinations, duration, budget, and activities. The motivation behind this program is to streamline the travel planning process, manage costs and time effectively, and provide customization options for users.

## Objectives

- Allow users to input destination details, including name, days, and budget.
- Enable users to add various activities within each destination.
- Maintain a structured tree-based representation of the travel plan.
- Ensure the plan remains within the specified budget and duration.
- Present the travel itinerary in an organized and readable format.
- Calculate and display the total days and costs for the entire trip.
- Provide warnings for issues such as remaining cost with no days left or remaining days with no budget left.

## Flow Chart


## Edge Cases Handled

- Invalid Input Handling
- Data Structure Size Limitations
- Remaining Budget and Days
- User Route Calculation
- Preferred Route Input
- Case Sensitivity

## Symbol Table and AVL Tree

- **Symbol Table:** Stores destination information for fast lookup by name.
- **AVL Tree:** Each node represents a destination with activities as children nodes. Allows for alphabetical sorting of destinations and activities.

## Usage

1. Clone the repository: `git clone https://github.com/your_username/trip-planner.git`
2. Navigate to the project directory: `cd trip-planner`
3. Run the program: `python trip_planner.py`
4. Follow the on-screen instructions to input destination details and activities.

