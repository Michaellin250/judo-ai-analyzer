# judo-ai-analyzer

## Overview
A system to analyze judo videos, detect throws, and provide coaching feedback using pose estimation, ML, and an LLM for natural language insights.

## Project Structure
- `src/` : Python scripts for video reading, pose extraction, and ML
- `models/` : Saved ML models
- `data/` : Input videos and labeled datasets
- `app/` : Streamlit or React frontend
- `notebooks/` : Exploratory data analysis
- `tests/` : Unit tests

## Setup
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
