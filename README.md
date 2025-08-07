🌐 Multi-language Translator

This project implements a multi-language translation tool using the Hugging Face Transformers library and an interactive web interface built with Gradio. It leverages the facebook/nllb-200-distilled-600M model, capable of translating across 200+ languages with high accuracy.

🚀 Features
English to Multiple Languages: Translate English text into various languages supported by the NLLB-200 model.

Gradio Interface: Clean and interactive web UI for easy input, language selection, and output display.

High-Quality Translations: Uses the facebook/nllb-200-distilled-600M model from Hugging Face Transformers.

Easy Deployment: Quickly launch and share your translation tool with Gradio.

🧰 Technologies Used
Python: Core programming language.

Transformers (Hugging Face): For loading and using the NLLB-200 model.

Torch: Backend deep learning framework.

Gradio: For building the web-based interface.

JSON: Used for loading language code mappings from a file.

🛠️ Setup and Installation
Follow these steps to run the project locally:

1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/Ayush0135/multi-language-translator.git
cd multi-language-translator
2. (Optional) Create a Virtual Environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
3. Install Required Packages
nginx
Copy
Edit
pip install -r requirements.txt
If requirements.txt is not available, install manually:

nginx
Copy
Edit
pip install transformers torch gradio
4. Run the Application
nginx
Copy
Edit
python app.py
This will launch the Gradio interface in your browser or give you a link.

📁 Project Structure
bash
Copy
Edit
multi-language-translator/
├── app.py               # Main application script
├── language.json        # Contains language names and FLORES-200 codes
├── requirements.txt     # List of Python dependencies
└── README.md            # Project documentation
🤖 Model Details
Model Name: facebook/nllb-200-distilled-600M

Architecture: Transformer-based multilingual model

Languages Supported: 200+ (FLORES-200 codes)

Purpose: Translate text from English to other languages

Benefits: Fast, accurate, and lightweight version of the full NLLB-200 model

🧪 Example Usage
Open the app in your browser.

Type a sentence in English.

Choose your target language.

Click Translate.

View the translated text instantly.

📄 License
This project is licensed under the MIT License.

🙏 Acknowledgments
Meta AI - NLLB

Hugging Face

Gradio


