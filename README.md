# GENERATIVE-TEXT-MODEL

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*:CHAITANYA DODLA

*INTERN ID*: CTIS8397

*DOMAIN*: ARTIFICIAL INTELLIGENCE

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH KUMAR

This project is a Generative Text Model created using Python and the GPT-2 model. The main purpose of this project is to automatically generate text based on a topic or sentence given by the user. It uses Artificial Intelligence (AI) and Natural Language Processing (NLP) to create human-like text. This means the computer can write paragraphs, stories, articles, or content automatically after receiving a simple input from the user.

For this project, the main platform used is Google Colab. Google Colab is an online coding platform provided by Google where users can write and run Python code directly in a web browser. It is very useful for beginners because there is no need to install Python or other software on the computer. Google Colab also provides free CPU and GPU support, which helps run AI models faster.

This project also uses the Hugging Face Transformers library. The official website used is Hugging Face. Hugging Face provides ready-made AI models that can perform tasks like text generation, translation, summarization, and question answering. In this project, we use the GPT-2 model for generating text.

The required libraries for this project are:

transformers

torch


These libraries are installed using:

pip install transformers torch

The transformers library is used to load the GPT-2 AI model, and torch is used for deep learning operations. After importing the libraries, the GPT-2 model is loaded using the pipeline() function. Loading the model may take a few seconds because the model files are downloaded from the internet.

The main function in this project is generate_text(). This function takes a prompt or topic from the user and generates text automatically. For example, if the user enters “Artificial Intelligence,” the model can generate a paragraph related to AI. Parameters like max_length and temperature help control the length and creativity of the generated text.

The user enters a topic using the input function:

user_prompt = input("Enter a topic or prompt: ")

After entering the topic, the AI model processes the input and generates meaningful text. The generated text is displayed on the screen and also saved into a file named generated_text.txt.

This project is useful for beginners to understand how AI text generation works. It can be used for writing articles, stories, blog content, captions, emails, and chatbot responses. Students and content creators can use this tool to save time and generate ideas quickly.

This project shows how Artificial Intelligence can generate human-like text automatically using Python and GPT-2. By using Google Colab and Hugging Face, even beginners can easily build AI-based text generation applications without advanced programming knowledge.

