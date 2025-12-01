📑 Project Overview

This project demonstrates five fundamental AI agent models, each implemented using Python + Jupyter Notebook.
Every agent is connected to a real-world application and includes:

System design

Theory explanation

Python implementation

Visualization (Matplotlib)

Results

Conclusion & future scope

🧠 1. Simple Reflex Agent — Automatic Door System
📌 Description

A basic agent that takes only the current sensor input and chooses an action.

🔧 Application

Automatic door opening system:

Detects Person / NoPerson

Opens or closes the door with IF–THEN rules

📝 Key Features

No memory

Fully observable environment

Matplotlib visual animation (Open/Closed door)

🧠 2. Model-Based Reflex Agent — Smart Home Lighting
📌 Description

Uses memory to store last motion detection time.

🔧 Application

Smart home lighting:

Motion → Turn light ON

No motion → Keep ON for hold time (e.g., 60 sec)

Afterwards → Turn OFF

📝 Key Features

Internal state (last_seen timestamps)

Works in partially observable environments

Grid-based visualization of rooms

🧠 3. Goal-Based Agent — Self-Driving Car Traffic Light Navigation
📌 Description

Chooses actions based on a goal (“Safe Driving”).

🔧 Application

A simulated self-driving car:

Red light → Stop

Yellow → Slow down

Green → Go

📝 Key Features

Uses goal checking before action

Car and signal visual animation

Demonstrates decision-making based on future consequences

🧠 4. Utility-Based Agent — Hospital Emergency Bed Allocation
📌 Description

Selects best action by maximizing utility.

🔧 Application

Assigning emergency patients to available beds based on:

Severity

Distance

Waiting time

📝 Key Features

Computes utility = benefit − cost

Allocates highest-utility patient-bed pair

Hospital bed grid visualization

Realistic decision-making under constraints

🧠 5. Learning Agent — Disease Diagnosis System
📌 Description

Improves automatically using experience.
Uses an incremental Naive Bayes learning model.

🔧 Application

Predicts disease (Flu / COVID / Dengue) from symptoms:

Fever

Cough

Pain

Learns probabilities after each new patient case.

📝 Key Features

Accuracy improves over time

Learning curve plotted via Matplotlib

Real-world applicability to healthcare AI

📊 Technologies Used

Python

Jupyter Notebook

Matplotlib

NumPy / Random / Time / Datetime

Basic AI agent structures
