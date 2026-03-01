# AI_DeaeasePredection
## Project Description
This project is based on AICHATBOT_PRED_DES

## Project ZIP File
Download full project from Google Drive:
(https://drive.google.com/file/d/12XfAnFKnHgdj1h7EJpJcHpTcF-Dk9xrb/view?usp=sharing)

## Presentation
🩺 AICHATBOT_PRED_DES
Smart AI-Based Health Diagnosis System

Developed by: Khushmeet Singh

🔹 Slide 1 – Introduction

AI HealthVision is a smart web-based health diagnosis system that:

Collects user symptoms

Matches them with a medical dataset

Predicts possible diseases

Generates diagnostic reports

Maintains user history

The system uses both Frontend (HTML, CSS, JavaScript) and Backend (Flask – Python).

🔹 Slide 2 – Problem Statement

In today’s world:

People often rely on random internet searches for medical advice

Access to doctors is not always immediate

Self-diagnosis without logic can be risky

There is a need for a structured, dataset-driven health assistant that:

Analyzes symptoms logically

Provides percentage-based disease matching

Stores medical reports securely

🔹 Slide 3 – Project Objectives

The main objectives of this project are:

To build an AI-powered health chatbot

To integrate a medical dataset for disease prediction

To implement Flask backend for processing

To generate and store diagnostic reports

To create a professional dashboard UI

🔹 Slide 4 – Technologies Used
Frontend:

HTML5

CSS3 (Dark Purple Professional Theme)

JavaScript

Backend:

Python

Flask Framework

Data Handling:

CSV Medical Dataset

Fetch API

LocalStorage

Flask routing & API endpoints

🔹 Slide 5 – System Architecture

User → Login Page → Dashboard → AI Chatbot
→ Flask Backend → Dataset Processing →
→ Response → Report Generation → History Storage

The system follows a Client–Server Architecture:

Frontend handles UI

Flask handles dataset processing

Backend returns JSON response

🔹 Slide 6 – Flask Backend Role

Flask is used to:

Load and process CSV dataset

Handle symptom matching logic

Create API routes (e.g., /predict)

Return JSON-based disease results

Manage server-side logic

Example Flow:

User Symptoms → POST Request → Flask →
Match Algorithm → JSON Response → Display on Dashboard

🔹 Slide 7 – Login & Session Management

Features:

User login & signup system

Session ID generation

User data stored in localStorage

Redirect to dashboard after login

Logout clears session

Flask can be extended to handle authentication securely in future versions.

🔹 Slide 8 – Dashboard Features

The dashboard includes:

Sidebar navigation

New Report section

View History section

AI Chatbox

Logout option

The UI follows a professional medical dark theme.

🔹 Slide 9 – AI Chatbot Workflow

The chatbot collects information step-by-step:

Ask Name

Ask Gender

Ask Age

Ask Symptoms (comma-separated input)

Example Input:

fever, headache, nausea

The input is sent to Flask for processing.

🔹 Slide 10 – Dataset Structure

The medical dataset is stored in CSV format:

First column → Disease Name

Other columns → Symptoms (0 or 1 values)

Example:

Disease	Fever	Cough	Headache
Flu	1	1	1

Flask reads this dataset and processes matches dynamically.

🔹 Slide 11 – Matching Algorithm

The system:

Normalizes user input

Matches symptoms with dataset columns

Calculates matching percentage

Sorts results by highest match

Formula Used:

User Match % =
(Matched Symptoms / Total Entered Symptoms) × 100

Top 10 diseases are returned.

🔹 Slide 12 – Report Generation

After diagnosis:

A structured report is generated

Stored as Latest Report

On logout, moved to History

Can be viewed anytime

Reports include:

Name

Gender

Age

Symptoms

Top matching diseases

Date

🔹 Slide 13 – UI & Design Highlights

Dark Purple Medical Theme

Sidebar Navigation

Animated Chat Bubbles

Responsive Layout

Clean Dashboard Interface

The design enhances user experience and professionalism.

🔹 Slide 14 – Advantages

✔ Fast disease prediction
✔ Dataset-driven logic
✔ Flask backend processing
✔ No heavy AI model required
✔ Easy to deploy

🔹 Slide 15 – Limitations

Not a replacement for professional doctors

Accuracy depends on dataset quality

No real-time hospital integration

No advanced ML model yet

🔹 Slide 16 – Future Enhancements

Integrate Machine Learning model

Add doctor consultation system

Implement secure database (MySQL)

Generate downloadable PDF reports

Add multi-language support

Deploy on cloud server

🔹 Slide 17 – Conclusion

AI HealthVision is a smart AI-powered health assistant that:

Uses Flask backend for processing

Matches symptoms with medical dataset

Provides percentage-based diagnosis

Generates structured reports

Offers a modern dashboard interface

It is scalable, lightweight, and practical.
