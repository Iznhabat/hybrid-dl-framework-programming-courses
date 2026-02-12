Hybrid Deep–Machine Learning Framework for Programming Courses
Overview

This repository contains the dataset and experimental pipeline used in the paper:

“A Hybrid Deep–Machine Learning Framework with Data Augmentation for Student Outcome Prediction in Programming Courses.”

The study proposes a hybrid deep–machine learning framework combining:

Leakage-controlled data augmentation (SMOTE)

Parallel deep feature extractors (ANN and 1D-CNN)

Downstream classical machine learning classifiers

Performance monitoring and long-term adaptation strategy

The framework is designed for early identification of at-risk students in programming courses under small and imbalanced dataset conditions.

Dataset Description

The dataset was collected at:

Hassan First University of Settat, Faculty of Sciences and Techniques (FSTS), Morocco

It combines two complementary types of student information:

1. Historical Academic Features

First-year university grades (e.g., mathematics, physics, general computer science)

Indicators of academic preparedness

2. Behavioral Features (Programming Courses)

Attendance

Weekly lab performance

Practical exam results

Instructor observations (encoded numerically)

Engagement indicators from programming sessions

The prediction problem is defined over three targets:

Target 1: Algorithm and Programming 1 (C language)

Target 2: Algorithm and Programming 2

Target 3: Data Structures

Each target is formulated as a binary classification problem (Pass / Fail).
