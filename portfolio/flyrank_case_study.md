# FlyRank ML Capstone Case Study

## Voice Card
Direct, clear, practical, no buzzwords

## Project
FlyRank Content Refresh Ranking System

## Problem
Content teams have many pages to review, but they need to know which pages should be refreshed first. The goal was to build a ranking system that helps prioritize pages using observable content and search signals.

## What I did
I framed the problem as a ranking/scoring ML task.

I:
- Prepared a dataset of 30,000 content rows.
- Built features from available content signals.
- Created a baseline rule-based scoring system.
- Trained and compared ML models including Logistic Regression, Decision Tree, and Random Forest.
- Used a client-holdout split for validation.
- Created a ranked refresh queue with reason codes.

## What came out
The Random Forest model performed better than the baseline on Precision@50 and produced a ranked list of pages for human review.

The output supports content teams by helping them decide which pages to investigate first.

## Limitations
This model:
- Does not prove causation.
- Does not predict Google rankings.
- Only provides decision support.
- Requires human review before action.

## Before / After

### Generic AI line:
"Built an innovative AI-powered solution to optimize content performance."

### My edited version:
"Built a machine learning ranking system that helps content teams prioritize pages for review using observable search and content signals."

## Contact / CTA
View the project repository and methodology.