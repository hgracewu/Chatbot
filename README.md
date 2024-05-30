# Magical Conversations: Creating a Role-Playing GenAI Chatbot for the Harry Potter Universe

### Introduction
Enter the enchanting world of Hogwarts with the Harry Potter Universe Chatbot. This innovative project leverages advanced NLP tools and techniques to create a magical experience, allowing users to interact directly with their favorite characters from the Harry Potter series. Engage in captivating conversations and explore the rich lore of the wizarding world through a fully interactive chatbot.

### Environment Setup
Before you dive into the magical conversations, you'll need to set up your environment. Ensure you have Python installed and then install the necessary libraries using the following commands:

pip install langchain

pip install langchain_community

pip install langchain_text_splitters

pip install sentence-transformers

pip install cohere

pip install faiss-cpu

pip install PyPDF2

pip install gradio

### Project Structure

chatbot.py: Main script to run the chatbot application.

HP.pdf: Text data sourced from the Harry Potter series for training the model.

requirements.txt: Contains all necessary Python libraries.

### How It Works

1. Importing External Text Data
The chatbot is trained on textual data extracted from a provided PDF of the Harry Potter series. Text extraction and processing are handled to prepare the data for embedding and retrieval.

2. Creating Embeddings
We use sentence transformers to create embeddings of the text data. These embeddings help in retrieving the most relevant text passages in response to user queries.

3. Prompt Engineering and LLM Response Generation
The chatbot uses specifically engineered prompts to generate responses. It includes a role-playing element where the bot adopts a character's persona from the Harry Potter series.

4. Building a Web Application with Gradio
The chatbot is hosted on a web interface using Gradio, allowing users to interact through a friendly GUI. Users can choose different characters and ask questions related to the Harry Potter universe.

### Running the Project

To run the project locally, execute the following command:

python chatbot.py

This will start a local server, and you can interact with the chatbot by navigating to the displayed URL.

### Contributing

Contributions to this project are welcome! Whether it's adding new features, improving the conversation logic, or documenting, feel free to fork the repository and submit a pull request.

### License

This project is licensed under the MIT License - see the LICENSE file for details.
