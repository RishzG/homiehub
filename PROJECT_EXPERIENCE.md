# Most Relevant Project: HomieHub - AI-Powered Roommate Matching Platform

## Project Overview

I developed HomieHub, a cloud-native MLOps platform that uses AI to match university students with compatible roommates. The system addresses the challenge of finding suitable housing by aggregating listings from multiple sources (WhatsApp, Facebook Marketplace, Craigslist) and applying machine learning to provide personalized recommendations.

## Technical Architecture

I designed and implemented a 5-lane microservices architecture on Google Cloud Platform:

1. **Data Pipeline**: Built an automated ETL system using Apache Airflow to ingest, clean, and validate housing data from diverse sources. Integrated DVC for data versioning and implemented bias detection to ensure fairness in recommendations.

2. **AI/ML Components**: Developed a recommendation engine using Sentence Transformers for semantic embeddings and vector search. Implemented an LLM-based scoring agent using LangGraph and OpenAI API to evaluate roommate compatibility based on preferences, budget, commute, and lifestyle habits.

3. **MLOps Infrastructure**: Set up MLflow for experiment tracking and model versioning, EvidentlyAI for drift detection, and automated retraining pipelines. Configured CI/CD using GitHub Actions with Docker containerization for seamless deployment.

4. **Monitoring & Production**: Implemented comprehensive monitoring with automated email alerts for data drift and pipeline failures, ensuring system reliability and model performance.

## Tools & Technologies

Python, FastAPI, Apache Airflow, MLflow, Docker, GCP (Cloud Run, Cloud Functions, Firestore), Sentence Transformers, OpenAI API, spaCy, LangGraph, DVC, EvidentlyAI, Fairlearn

## Impact

The platform demonstrates end-to-end ML engineering capabilities, from data acquisition to production deployment. It showcases my ability to build scalable, fair, and maintainable AI systems while addressing real-world problems in the housing domain.
