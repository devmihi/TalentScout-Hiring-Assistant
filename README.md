# TalentScout Hiring Assistant

## Project Overview
This project implements an intelligent hiring assistant chatbot for TalentScout,
a fictional recruitment agency specializing in technology roles.

The chatbot performs initial candidate screening by collecting basic information
and generating technical interview questions based on the candidate’s tech stack.

## Features
- Step-by-step candidate information collection
- Tech stack-based technical question generation using LLM
- Context-aware conversation flow
- Graceful conversation termination
- Secure API key handling

## Technologies Used
- Python
- OpenAI API
- Google Colab

## Prompt Design
Prompts were carefully designed to:
- Gather candidate information in a structured manner
- Generate relevant and practical technical interview questions
- Maintain a professional hiring-focused conversation

## Data Privacy
No real candidate data is stored.
All information is handled temporarily during runtime using simulated inputs.

## How to Run
1. Open the notebook in Google Colab
2. Add your OpenAI API key using Colab Secrets
3. Run cells sequentially
4. Interact with the chatbot via input prompts

## Future Improvements
- Streamlit-based UI
- Multilingual support
- Sentiment analysis during conversation
