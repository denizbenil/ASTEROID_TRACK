# Apophis Asteroid Close Approach Analysis

This project analyzes the close approach of the asteroid **Apophis** to Earth, which will occur in **April 2029**. The goal is to examine the asteroid's behavior during a specific time period and visualize its movement relative to Earth, the Sun, and the Moon.

## Project Goals

1. **Examine Apophis during the period from January 01, 2029, to July 31, 2029**.
2. **Plot the distance of Apophis** from the Sun, the Moon, and Earth throughout this period.
3. **Plot the Earth-Apophis-Sun angle** as it changes over time.
4. **Show the ground track of Apophis** around the **Time of Closest Approach (TCA)**. This includes mapping the asteroid's path over Earth's surface within a total period of 12 hours (6 hours before and after TCA).

## Libraries Used

The following libraries are utilized in this project:

1. **numpy**  
   Purpose: Used for numerical calculations and data operations.
   
2. **matplotlib.pyplot**  
   Purpose: Used for creating visualizations such as graphs and charts.

3. **spiceypy**  
   Purpose: Python interface for NASA's SPICE library, used to retrieve and analyze planetary data.

4. **datetime**  
   Purpose: Used for working with dates and time-related operations, such as date manipulation.

5. **matplotlib.image**  
   Purpose: Used to read and display image files in conjunction with matplotlib for enhanced visualizations.

6. **matplotlib.dates.DateFormatter**  
   Purpose: Used for formatting time axes in matplotlib plots to ensure readable date/time labeling.

7. **os**  
   Purpose: Provides a way to interact with the operating system for file and directory management (such as checking file paths and creating directories).

## How it Works

This project will use the provided libraries and data to track the movement of Apophis and analyze the following:

- The distance of Apophis relative to the Earth, Moon, and Sun over the selected time period.
- Changes in the angle between Earth, Apophis, and the Sun during this time.
- The asteroid's ground track across Earth's surface, with a focus on the 12-hour window around the **Time of Closest Approach (TCA)**.

## Installation

Ensure you have the necessary libraries installed using pip:

```bash
pip install numpy matplotlib spiceypy
