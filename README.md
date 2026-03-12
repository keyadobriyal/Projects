# Welcome to my Repository of Projects I have completed as a part of my Bachelor's Degree in Computer Science (Honors in Data Science)

## 01. Malware Detection using Machine Learning 

Machine Learning (ML) is replacing traditional, signature-based antivirus systems to combat modern, evolving malware. I utilized various machine learning algorithm to detect malware.

**Key Highlights:**

The Problem: Traditional security fails against "zero-day" and polymorphic malware because it relies on predefined patterns.

The Solution: The author uses the Malimg dataset, converting binary malware files into grayscale images to allow ML models to detect structural patterns visually.

Top Performer: After testing multiple algorithms (including ANN and Decision Trees), Random Forest proved the most accurate at identifying obfuscated threats.

Future Outlook: The study advocates for Explainable AI (XAI) and real-time deep learning integration to move from reactive defense to proactive threat anticipation.

## 02. Content Based Recommendation System 

This project targeted Development of a Content-Based Restaurant Recommendation System designed to help users navigate the overwhelming number of dining options.

**Key Highlights:**

The Problem: "Decision fatigue" and the time-consuming process of manually searching for restaurants that match specific tastes.

The Approach: A content-based filtering system that uses Cosine Similarity and Count Vectorization. Unlike collaborative filtering, this model doesn't need data from other users; it makes suggestions based on the attributes (cuisine, location, cost, rating) of restaurants the user already likes.

**Tech Stack:** 

Data: A "Dineout" dataset from Kaggle containing thousands of Indian restaurants.

Libraries: Python (Pandas, NumPy, Scikit-learn) for data processing and modeling; Pickle for saving the model.

Frontend: An interactive web application built with Streamlit that allows users to select a restaurant and get instant recommendations.

Results: The system successfully identifies similar dining spots by merging key features (Cuisine + Locality + City) into a single profile for each restaurant.

Future Scope: The authors plan to evolve the project into a hybrid system by adding collaborative filtering and real-time user feedback.

Bottom Line: The project provides an efficient, privacy-respecting way to discover new restaurants based purely on individual preferences.

## 03. ECOPOOL - A smart Car Pooling Application

EcoPool, a conceptual car-pooling application designed to address urban traffic congestion and reduce carbon emissions.

**Key Highlights:**

The Problem: Increasing pollution, rising fuel costs, and traffic congestion caused by the high volume of single-occupancy vehicles in urban areas.

The Concept: A platform that connects commuters traveling along similar routes, allowing them to share rides. This not only splits fuel costs but also lowers the overall environmental footprint per passenger.

**Core Features:**

Route Matching: Algorithms to pair drivers and riders with compatible destinations.

Safety & Trust: Features such as verified user profiles and ratings to build a secure community.

Sustainability Tracking: Monitoring individual and collective carbon emission savings to encourage eco-friendly habits.

Tech Strategy: The author discusses using modern development frameworks (such as Flutter or React Native) and cloud-based databases to ensure a seamless, real-time user experience.

Bottom Line: EcoPool aims to transform daily commuting into a shared, cost-effective, and environmentally sustainable practice through a technology-driven community platform.
