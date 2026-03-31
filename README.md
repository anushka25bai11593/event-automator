# event-automator

 # Intelligent Event Automator (IEA)
 
A Python & AI-powered workflow tool for student leaders and club organizers.

 # Project Overview
The Intelligent Event Automator (IEA) is a productivity solution designed to eliminate the administrative friction of organizing campus events. Whether you are in the Fashion Club, ACM, or any student chapter, this tool automates the "starter kit" for any event—from formal permissions to creative social media assets.

 # Why this exists?

-Student organizers spend hours on repetitive tasks:

-Drafting formal emails to proctors.

-Ideating themes and Canva design prompts.

-Writing platform-specific social media copy.
IEA handles this in seconds using the Google Gemini 2.0 Flash LLM.

 # Key Features
 
1.Proctor Email Generator: Automatically generates a formal, formatted permission request for faculty and proctors.

2.AI Creative Suite: Powered by Gemini AI to provide:

-Canva Design Briefs: Suggested Hex color palettes and typography pairings.

-AI Image Prompts: Detailed descriptions for Midjourney or Canva AI generators.

3.Social Media Planner: Generates high-energy Instagram captions and professional LinkedIn announcements.

4.Event Logic: Suggests creative sub-events/rounds based on your specific theme.

 # Technical Stack

-Language: Python 3.10+

-AI Engine: Google Generative AI (Gemini 2.0 Flash)

-Environment: CLI (Command Line Interface)

-Core Libraries: google-genai

 # Getting Started

1. Prerequisites
   
You need a Google Gemini API Key.

-Get one for free at: Google AI Studio

2. Installation
   
Bash

# Clone this repository
git clone https://github.com/YOUR_USERNAME/event-automator.git

# Enter the project folder
cd event-automator

# Install the required AI library
pip install -r requirements.txt

3. Running the App

1. Open ai_engine.py and paste your API Key in the api_key variable.
  
2. Run the main script:

Bash

python main.py
 
#  Project Structure
 
Plaintext

├── main.py            # Main entry point & User Interface
├── ai_engine.py       # Gemini API integration & Prompt Engineering logic
├── generators.py      # Python logic for emails and templates
└── requirements.txt   # Project dependencies

# Reflection & Course Relevance

 This project fulfills the BYOP Capstone requirements by applying:

1. AI Integration: Real-world application of LLMs using the Google GenAI SDK.

2. Prompt Engineering: Implementing "Role-Task-Constraint" frameworks to ensure high-quality AI outputs.

3. Modular Programming: Demonstrating clean code organization and separation of concerns.

