Multi-language Translator


This project implements a multi-language translation tool leveraging the power of the Hugging Face transformers library and a user-friendly web interface built with Gradio. It utilizes the NLLB-200 distilled model, known for its capabilities in translating across a wide range of languages.

Features
English to Multiple Languages Translation: Translate text input in English to several other languages supported by the NLLB-200 model.
Intuitive Gradio Interface: Provides a simple and interactive web interface for seamless text input, language selection, and viewing translated output.
Utilizes State-of-the-Art Model: Employs the facebook/nllb-200-distilled-600M model from the Hugging Face transformers library for high-quality translations.
Easy to Deploy: The Gradio interface makes it straightforward to share and deploy the translator.
Technologies Used
Python: The core programming language for the project.
transformers (Hugging Face): A powerful library for working with pre-trained models, including the NLLB-200 translation model.
torch: A deep learning framework used by the transformers library.
gradio: A library for quickly creating customizable UI components for machine learning models.
json: Used for loading language code data from a JSON file.
Setup and Installation
To set up and run this project locally, follow these steps:

Clone the repository:
