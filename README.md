# SCL System Customer Service Chatbot Capstone Project (Prototype)

## Introduction
Welcome to the SCL System Customer Service Chatbot (Prototype) repository! This project is a Streamlit-based chatbot prototype designed to assist users with inquiries regarding products and services offered by SCL System Enterprise Pte Ltd. Developed in collaboration with a team from the Institute of Technical Education (ITE) at ITE College Central in Singapore. This chatbot serves as a capstone project for students pursuing a Higher Nitec in AI Application.

## Features
- **Terms and Conditions:** Users must agree to the Terms and Conditions before accessing the chatbot.
- **Product Information:** Provides detailed specifications and models for Enclosure Boxes.
- **Contact Us:** Displays contact details for SCL System Enterprise Pte Ltd.
- **Chat History:** Allows users to view, clear, and save chat history for future reference.
- **Feedback Form:** Enables users to submit their thoughts on the chatbot through a feedback form.
- **Save Chat Log:** Implemented feature to store chat logs for future reference.
- **Chat Input & Assistant Responses:** Facilitates text-based conversations between users and the chatbot.
- **Clear Chat History:** Allows users to clear their chat history.
- **Chat Functionality:** Offers a user-friendly interface for customers to interact with.
- **Encryption and Decryption:** Includes functionalities for securing and accessing encrypted data files.

## Getting Started
To run the chatbot locally, follow these simple steps:

1. **Clone the Repository**: Download the project files to your local machine.
2. **Navigate to the Project Directory**: Access the project folder using your terminal or command prompt.
3. **Install Dependencies**: Install necessary libraries by running `pip install -r requirements.txt`.
4. **Set Up OpenAI API Key**: Create a `.env` file and add your OpenAI API key: `OPENAI_API_KEY=your_api_key_here`.
5. **Run the Application**: Start the chatbot application by executing `streamlit run app.py`.
6. **Access the Chatbot Interface**: Open your web browser and go to the provided address.

## Usage
- Upon launching the application, users must agree to the Terms and Conditions.
- Once agreed, users can interact with the chatbot by entering queries into the input field.
- The chatbot generates responses based on user input and relevant information from its knowledge base.
- Users can manage their chat history, including viewing, clearing, and saving it for future reference.
- A feedback form is available for users to provide valuable insights on the chatbot's performance.

## Encryption and Decryption
- The chatbot application includes functionalities for encrypting and decrypting chat log files to ensure data security.
- Users are required to agree to the Terms and Conditions before accessing the chatbot, which includes information about data usage and privacy.
- If any issues arise with decryption in the app.py, users can utilize the provided `decryption.py` script to ensure proper file decryption.

**Note:** 
- This chatbot is a prototype version, and further development and testing may be necessary for deployment in a production environment.
- Please refrain from modifying or tampering with the `encryption_key.key` file as it is crucial for encryption and decryption processes.
- DO NOT CHANGE THE DATA OR MESS UP ONCE IT ENCYPTYED
- If the Data Encryption did mess up or cannot decrypt back to Text file, use the 'Industial data draft.zip' file.