
📘 Project Overview (Human-Written Version)

This project explores five major types of AI agents by implementing real-world applications in Python using Jupyter Notebook.
Each agent model is supported with system design, theoretical background, implementation code, visualizations created using Matplotlib, and a discussion of results along with future scope.
The goal of the project is to clearly understand how different AI agents behave, how they make decisions, and how their complexity increases from simple reactive systems to learning-based models.

🧠 1. Simple Reflex Agent — Automatic Door System

A Simple Reflex Agent works purely on the basis of the current input.
In this model, an automatic door opens when it detects a person and closes when no one is present. The agent follows straightforward IF–THEN rules without maintaining any memory.
The simulation visually shows the door opening and closing using Matplotlib.

Key Highlights

Works only with the current sensor reading

No history or memory involved

Suitable for fully observable environments

Includes a clear open/close animation

🧠 2. Model-Based Reflex Agent — Smart Home Lighting

This agent improves on the simple reflex model by adding memory.
Each room has a motion sensor; when movement is detected, the lights turn on. Even after motion stops, the system keeps the light on for a short duration based on stored “last seen” information.
A grid-based visualization shows room occupancy and light status.

Key Highlights

Maintains internal state (timestamps)

Works in partially observable environments

Offers more realistic smart-home behavior

🧠 3. Goal-Based Agent — Self-Driving Car at Traffic Lights

A Goal-Based Agent selects actions that help achieve its goal — here, safe driving.
Depending on the traffic signal, the car reacts by stopping, slowing down, or moving forward.
The simulation animates the car moving on a road and responding to traffic light changes.

Key Highlights

Decisions are driven by the goal (safety)

Considers the meaning of actions, not just rules

Demonstrates the difference between reactive and goal-based behavior

🧠 4. Utility-Based Agent — Hospital Emergency Bed Allocation

This agent evaluates multiple options and selects the one with the highest utility value.
Patients have different severity levels, waiting times, and distances from beds. The agent assigns patients to beds by calculating utility using all these factors.
A hospital grid visualization displays bed assignments in real time.

Key Highlights

Makes rational decisions using a utility formula

Balances severity, distance, and wait time

Useful in real emergency ward scenarios

🧠 5. Learning Agent — Disease Diagnosis System

The Learning Agent improves over time using experience.
It uses a simple incremental Naive Bayes model to learn relationships between symptoms and diseases. After processing each patient case, its accuracy gradually increases.
The learning progress is plotted as an accuracy graph.

Key Highlights

Learns continuously from data

Accuracy steadily improves

Demonstrates real-world medical AI concepts

📊 Technologies Used

Python

Jupyter Notebook

Matplotlib

NumPy, Random, Time, Datetime

Core AI agent architectures
