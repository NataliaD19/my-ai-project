# AI Productivity & Wellness Assistant
Final project for the Building AI course project

## Summary
This project aims to create an AI-powered assistant that automates daily administrative tasks while providing personalized health suggestions. It bridges the gap between professional efficiency and personal well-being by analyzing calendar data and stress levels to optimize a user's daily routine.

## Background
Modern professionals suffer from "decision fatigue" and burnout due to constant administrative overhead.
* **Problem:** People spend up to 20% of their day just scheduling and organizing.
* **Impact:** This leaves little time for physical health and mental recovery.
* **Goal:** Use AI to handle the "boring" tasks and act as a preventive health coach.

## How is it used?
The assistant works in the background of your smartphone or computer.
1. **Input:** It accesses your calendar, to-do lists, and health data (steps, heart rate).
2. **Analysis:** The AI identifies "crunch periods" where you are overbooked.
3. **Action:** It automatically blocks time for "Deep Work" and suggests short 5-minute walks or hydration when your heart rate indicates stress.

| Feature | AI Method | Benefit |
| :--- | :--- | :--- |
| Task Sorting | Natural Language Processing | Saves manual organizing time |
| Stress Prediction | Machine Learning (Classification) | Prevents burnout before it happens |
| Route Planning | Optimization Algorithms | Reduces travel time between meetings |

## Data sources and AI methods
* **Data Sources:** * Google Calendar/Outlook API for schedules.
    * Apple Health/Google Fit for activity data.
    * Anonymized datasets for stress-pattern recognition.
* **AI Methods:** * **NLP:** To understand the urgency of emails and tasks.
    * **Logistic Regression:** To predict the likelihood of a high-stress day based on your workload.

## Challenges
* **Privacy:** Health and schedule data are extremely sensitive. The system must use local encryption.
* **Medical Accuracy:** The AI should never give medical diagnoses, only general wellness tips.
* **User Control:** Users must be able to override any AI decision at any time.

## What next?
The next step is to develop a prototype as a browser extension. Eventually, it could integrate with smart home devices (like smart lights) to create a relaxing environment after a high-stress workday.

## Acknowledgments
* Inspired by the Elements of AI and Building AI courses.
* Data formats inspired by open-source health repositories.
