BaristaBot: AI-Powered Cafe Ordering System
Welcome to BaristaBot, an innovative AI-driven system designed to simulate a dynamic and interactive cafe ordering experience using the LangGraph framework and the Gemini API. This project utilizes natural language processing to interact with customers, manage orders, and provide real-time menu information.

Project Overview
BaristaBot is crafted to bridge the gap between technology and everyday convenience, enabling customers to order cafe beverages using natural language. This system incorporates an AI agent that can answer inquiries about menu items, take orders, and confirm details before finalizing transactions.

Key Features
Natural Language Understanding: The bot can process and respond to customer inquiries about beverages and accept orders in a conversational manner.

Dynamic Menu Integration: BaristaBot is linked to a dynamic menu system that can adjust based on stock levels or other variables.

Error Handling and Recovery: Robust mechanisms manage miscommunications or errors in order processing.

Adaptive Learning: The system learns from each interaction to improve its accuracy and performance.

Stateful Graph-based Application: Utilizes LangGraph to define a stateful application that maintains the context of a conversation and manages state transitions.

Technologies Used
LangGraph: Used to build a stateful graph-based application structure.

Gemini API: Powers the underlying conversational AI capabilities.

Python: Primary programming language for backend logic.

Kaggle: Hosted platform for development and demonstration.

Setup Instructions
Environment Setup:

Ensure Python 3.8+ is installed on your system.

Clone the repository to your local machine or access it on Kaggle.

Install Dependencies:

bash
Copy
pip uninstall -qqy kfp jupyterlab libpysal thinc spacy fastai ydata-profiling google-cloud-bigquery google-generativeai
pip install -qU 'langgraph==0.3.21' 'langchain-google-genai==2.1.2' 'langgraph-prebuilt==0.1.7'
API Key Configuration:

Obtain an API key from AI Studio.

Store the API key in a Kaggle secret named GOOGLE_API_KEY.

Set the environment variable GOOGLE_API_KEY with your key.

Running the Project:

Open the notebook on Kaggle.

Run the cells sequentially to initiate the system.

Interact with the BaristaBot through the provided text box interface.

Project Structure
Chatbot Node: Manages conversational turns using the Gemini model.

Human Node: Simulates the human side of the conversation.

Tool Node: Handles dynamic menu queries.

Order Node: Manages the state of customer orders and integrates with backend systems for order fulfillment.

Visualizing the Graph
The LangGraph framework allows visualization of the application graph, detailing how states and nodes interact through the system's workflow.

Further Development
Potential enhancements include integrating real-time inventory updates, expanding the menu and modifier options, and deploying the system on a web-based interface for broader accessibility.

Conclusion
BaristaBot exemplifies how AI can be leveraged to enhance customer service experiences in a cafe setting. By utilizing state-of-the-art technologies like LangGraph and the Gemini API, this project pushes the boundaries of what's possible with AI in retail and service industries.
