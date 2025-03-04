# 🍳 AI Cooking Assistant

## Project Overview
The AI Cooking Assistant is a powerful tool designed for culinary enthusiasts who want to explore AI-powered recipe suggestions. By leveraging advanced natural language processing capabilities from OpenAI's GPT-4o model, this application helps users discover exciting recipes based on the ingredients they have on hand.

### Purpose
The primary purpose of this project is to simplify meal planning and inspire creativity in the kitchen, especially for those who prefer cooking with available resources rather than making trips to the grocery store. It is ideal for home cooks, culinary students, and anyone interested in exploring new recipes effortlessly.

## Key Features
- 🔑 **API Configuration**: Securely input and validate your OpenAI API key within the application.
- 🥕 **Ingredient Input**: Easily enter a list of ingredients you have at home.
- 🍽️ **Recipe Suggestions**: Get personalized recipe suggestions powered by GPT-4o.
- 👨‍🍳 **Interactive UI**: User-friendly interface built with Streamlit, designed for a seamless user experience.
- ⚡ **Real-time Processing**: Instantaneous response for recipe ideas based on selected ingredients.

## Installation & Setup Guide

### Pre-requisites
- Python 3.7 or above
- OpenAI account and API key

### Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/ai-cooking-assistant.git
   ```
2. **Navigate to Directory**
   ```bash
   cd ai-cooking-assistant
   ```
3. **Set Up Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
4. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## Usage Instructions

1. **Run the Streamlit App**
   ```bash
   streamlit run app.py
   ```
   
2. **Interacting with the App**
   - Navigate to the web interface opened in your browser.
   - In the sidebar, enter your OpenAI API key.
   - Input your available ingredients in the provided text area.
   - Click on "🍽️ Get Recipe Suggestions" to receive AI-generated recipes.
   - Browse the personalized recipes and enjoy cooking.

## Technology Stack

- **Languages**: Python
- **Frameworks**: Streamlit for building the web-based UI
- **APIs**: OpenAI GPT-4o for AI-driven recipe generation

## Additional Notes

- **Configuration**: Ensure you have a valid OpenAI API key to leverage the proposal's capabilities.
- **Limitations**: Currently, the system requires internet connectivity to access OpenAI services.
- **Future Improvements**: We plan to integrate inventory tracking and more granular recipe filtering options.

Explore new culinary dimensions with the AI Cooking Assistant and transform your cooking experience! Enjoy the convenience of AI at your fingertips while discovering delicious recipes tailored just for you.
```
