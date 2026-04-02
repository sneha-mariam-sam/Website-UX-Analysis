# Improving Navigation & User Flow on a University Website

## Overview
This project analyzes and redesigns the user experience of a recently launched university thesis platform for current and prospective students. The goal was to identify usability issues that hinder users from accessing key features and to propose structured, data-informed design improvements that enhance navigation and clarity.

## Problem
The newly launched platform had several usability challenges, particularly around navigation and discoverability of essential features:

- Students struggled to find the login page quickly.
- Post-login access to resources was buried in menus.
- The seminar calendar's date highlighting caused confusion.

These issues increased friction in the user journey and risked reducing engagement with the platform.

## User Goals
The primary users of the platform are students. Key user goals included:

- Accessing the student login quickly
- Understanding the thesis process if they had no account
- Accessing thesis resources and seminar schedules efficiently
- Distinguishing between past, current, and upcoming seminars at a glance
  
## Identified Issues

**1. Navigation**

Issue: Login access was buried in a multi-step menu.
Solution: Added a “Student Login” item to the main navigation to reduce clicks and improve discoverability.

**2. Login Page**

Issue: New students lacked clear guidance in case of clicking login.
Solution: Added a line: “No account? Read about us here,” linking to the Bachelor/Master Thesis page to help students understand the process.

**3. Post-Login Navigation**

Issue: Key resources were not easily accessible.
Solution: Provided quick access to “Thesis Resources” and the “Seminar Calendar” from the main menu, reducing steps to find important information.

**4. Seminar Calendar**

Issue: Date highlighting caused confusion about past and upcoming seminars.
Solution: Redesigned date styling:

- Greyed-out past dates
- Reduced opacity for past seminars
- Subtle blue line for current day
- Standard black text and full opacity for upcoming dates

## Data & Metrics

To evaluate usability and measure improvements, the following metrics were defined:

- Task Success Rate: Can students complete key tasks (login, find resources)?
- Time to Task Completion: How long it takes to access login or seminar information
- Click Depth: Number of steps required to reach key pages

Example
| Metric                      | Before | After (Expected) |
| --------------------------- | ------ | ---------------- |
| Clicks to login             | 3-4    | 1                |
| Time to access login        | ~20s   | ~5s              |
| Visibility of key resources | Medium | High             |
| Seminar date clarity        | Low    | High             |

## Redesign (with images)

Redesigns were implemented in Figma for four key pages:

- Navigation: Added “Student Login” to main menu
- Login Page: Added guidance for new students
- Post-Login Navigation: Quick access to key resources
- Seminar Calendar: Clearer date highlighting to reduce confusion

Figma Prototype: https://www.figma.com/proto/H7vPuUuYcpuq4Nnyw9T6tR/Thesis-Website?node-id=1-78&t=jMyuDduMIXbzi3rR-1

## Impact & Insights

The redesigned interface is expected to:

- Reduce friction in user navigation
- Improve task completion rates
- Decrease time required to access essential features
- Enhance overall user satisfaction

This project highlights how small structural changes can significantly improve usability and efficiency.

## Validation Plan

To measure the effectiveness of these improvements:

1. Conduct usability testing with 5-10 students
2. Track task success rate and time to completion for key actions
3. Collect feedback on clarity of seminar calendar
4. Run A/B tests with old vs redesigned pages

<img width="1743" height="869" alt="image" src="https://github.com/user-attachments/assets/c1958938-e757-4073-a273-df0df30f5456" />
<img width="1588" height="843" alt="image" src="https://github.com/user-attachments/assets/c0e0ed5d-129c-463b-9ec2-50a737a1d01c" />
<img width="1652" height="861" alt="image" src="https://github.com/user-attachments/assets/77334a02-2469-4e9d-b863-499e089cae8a" />
<img width="1722" height="866" alt="image" src="https://github.com/user-attachments/assets/a98c98b4-f331-4431-90a8-79d0468d7003" />

## Tools Used

- Figma (UI/UX design and prototyping)
- Excel/Python (for structuring and analyzing metrics)
- GitHub (project documentation)

## Key Takeaway
This project demonstrates how combining UX analysis, data-informed thinking, and product understanding can improve digital experiences. By identifying key usability issues, redesigning critical pages, and defining measurable success metrics, this work bridges the gap between design and actionable product insights.
