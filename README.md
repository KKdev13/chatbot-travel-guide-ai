# Paris Travel Guide AI Chatbot

An AI-powered virtual Parisian travel guide built with OpenAI's API. This chatbot provides intelligent responses to common questions about Paris landmarks, helping users plan their visit to the City of Light. Paris is just an example here!

## Features

* Answers questions about Paris attractions and landmarks
* Provides accurate information about distances, locations, and must-see artworks
* Uses OpenAI's GPT-4o-mini model for intelligent responses
* Structured conversation format for easy integration
* A list of dictionaries called conversation was created that lists the 'role' and 'content' for each question and response. Starting the conversation with a 'system' message to set the model's behavior, a temperature of 0.0, and maximum number of tokens of 100:

&#x20;  \[ {"role": "system", "content": ...}, {"role": "user",    
   "content": ...}, ... ]

## Prerequisites

* Python 3.7+
* OpenAI API key

## Installation

Clone the repository:

```bash
git clone https://github.com/KKdev13/chatbot-travel-guide-ai.git
cd chatbot-travel-guide-ai

