# LingoLift
The LingoLift is an AI-powered tool designed to rephrase sentences while preserving their original meaning. This project leverages the T5 model from the Hugging Face Transformers library, enabling users to input text and receive high-quality paraphrased results. It is ideal for content writers, students, and professionals looking for diverse ways to express ideas.

# Features
High-quality paraphrasing using state-of-the-art Transformer-based models.
Simple and intuitive interface for user interaction.
Scalable design for integration into larger systems.
# Tech Stack
1. **Backend:** Python, Flask
2. **AI Model:** T5 model (Hugging Face Transformers)
3. **Environment:** VsCode
4. **Frontend:** HTML, CSS
5. **Dependencies:**
* Transformers
* Torch
* Flask

# Installation
Follow these steps to set up the project on your local machine:

**Clone the Repository:**
```
git clone <https://github.com/Jyotirmoyee18/LingoLift.git>
cd LingoLift
```

**Set Up a Virtual Environment:**
```
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

**Install Dependencies:**
```
from transformers import T5ForConditionalGeneration, T5Tokenizer

model = T5ForConditionalGeneration.from_pretrained("t5-small")
tokenizer = T5Tokenizer.from_pretrained("t5-small")

model.save_pretrained("t5_model")
tokenizer.save_pretrained("t5_model")
```
### Usage
Run the Application:
```
python app.py
```
**Access the Application: Open your browser and navigate to:**
```
http://127.0.0.1:5000
```
**Input and Paraphrase:**

* Enter a sentence in the input field.
* Click the "Paraphrase" button to get a rephrased version of the text.
# Example
**Input**
Artificial intelligence is transforming industries around the world.
**Output:**
AI is revolutionizing global industries.
# Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a Pull Request.
# Contact
For inquiries, feature requests, or bug reports:

* Email: Jyotirmoyeemandal63@gmail.com
* Linkedin: www.linkedin.com/in/jyotirmoyee-mandal-1111j222
