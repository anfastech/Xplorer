# Chatbot-using-Gemini-Pro

## Overview

This project is a simple chat bot application that utilizes the Gemini Pro API and Tkinter for the graphical user interface (GUI). The chat bot allows users to interact with Gemini Pro's language model through a user-friendly interface.

## Features

- **Gemini Pro API Integration:** Utilize the Gemini Pro API for powerful natural language processing capabilities.
- **Tkinter GUI:** The graphical user interface is built using Tkinter, providing an intuitive and interactive experience.
- **User Input and Responses:** Users can input text queries, and the chat bot responds with generated text based on the Gemini Pro API's language models.
- **Speech Recognition:** Users can input text by voice and listen to the response using the speech recognition module.

## Prerequisites

Before running the application, ensure you have the following dependencies installed:

- Python 3.x
- Tkinter library
- Gemini Pro API key from the [Gemini AI Studio](https://makersuite.google.com/app/apikey)

## Getting Started
1. Create a Virtual Environment
   ```bash
   $ pip install virtualenv
   $ virtualenv chatbot
   
2. Activate environment
   ```bash
   $ cd chatbot
   $ Scripts\activate 
   
3. Install the Python SDK:

   ```bash
   $ pip install -q -U google-generativeai

4. Import packages
   ```python
   import google.generativeai as genai

5. Setup your API key
   ```python
   GOOGLE_API_KEY='GOOGLE_API_KEY'

   genai.configure(api_key=GOOGLE_API_KEY)

## Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or create a pull request.

<hr>

**Thank You**

   
