# Telecome_Subscriber_Personal_Offer_Generator

Telecom - Personalized Offer Generator

Overview

The Telecom Personalized Offer Generator is a Streamlit-based application that leverages OpenAI's language model to create personalized offers for telecom customers based on their purchase history.

Features

Upload and process customer purchase history.

Select a customer and view their details.

Use OpenAI's API to generate personalized telecom offers.

Enhance sales by providing upsell and cross-sell recommendations.

Installation

Prerequisites

Ensure you have Python installed and install the required dependencies:

pip install streamlit pandas langchain_openai

Clone the Repository

git clone https://github.com/yourusername/telecom-offer-generator.git
cd telecom-offer-generator

Run the Application

streamlit run app.py

Usage

Upload the customer_purchase_history_utf.csv file.

Select a customer ID from the dropdown.

Enter your OpenAI API key in the sidebar.

Click Generate Personalized Offer to get an AI-driven recommendation.

How It Works

The app loads customer purchase history and displays details for a selected customer.

OpenAI's model analyzes customer data and suggests a personalized telecom offer.

The AI-generated output includes:

The top two product categories the customer is interested in.

A customized offer based on these interests.

An explanation of why this offer suits the customer.

An upsell or cross-sell opportunity to increase revenue.

Technologies Used

Python for backend processing.

Streamlit for interactive UI.

Pandas for data manipulation.

LangChain & OpenAI for AI-powered offer generation.

Contribution

Contributions are welcome! Feel free to fork the repository and submit pull requests.


Author

Developed by : RAm SHarma
