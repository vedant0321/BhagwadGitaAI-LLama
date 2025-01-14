# BhagwadGitaAI-LLaMA: Bhagavad Gita Analysis and Interpretation

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Python](https://img.shields.io/badge/python-3.8%2B-brightgreen)

## 📋 Description
 BhagwadGitaAI-LLaMA is an AI-powered tool designed to fine-tune the LLaMA language model on the Bhagavad Gita dataset. It provides users with an interactive Gradio-based interface to input quotes from the Bhagavad Gita and receive precise interpretations and meanings. This project combines the power of advanced language models with sacred texts to deliver insightful analyses.

## 🚀 Features
- Fine-tune the LLaMA model on a Bhagavad Gita dataset.
- Interactive Gradio interface for quote analysis.
- Generate contextual meanings for Gita verses.
- Easy-to-use architecture for researchers and enthusiasts.

## 🛠️ Tech Stack
- **Languages:** Python
- **Frameworks:** PyTorch, Gradio
- **Libraries:** Transformers, Hugging Face
- **Dataset:** Bhagavad Gita

## 📂 Project Structure
```
BhagwadGitaAI-LLaMA/
├── Bhagwad_Gita.csv             # Dataset file
├── gita_llama.ipynb             # LLaMA fine-tuning notebook
├── gita_gradio.ipynb            # Gradio interface notebook
├── README.md                    # Project documentation
└── requirements.txt             # Required Python packages
```
## 📊 Workflow
Below is the flowchart representing the workflow of the Gita-LLaMA project:

![Workflow](https://github.com/vedant0321/BhagwadGitaAI-LLama/blob/main/Flowchart.png)


## 📦 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/vedant0321/BhagwadGitaAI-LLama.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Gita-LLaMA
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🧠 Model Fine-Tuning
The `gita_llama.ipynb` notebook provides a complete pipeline for fine-tuning the LLaMA model on the Bhagavad Gita dataset.

### Steps:
1. **Dataset Preparation:**
   - Load and preprocess the Bhagavad Gita dataset from `data/Bhagwad_Gita.csv`.
2. **Model Initialization:**
   - Set up the LLaMA model using Hugging Face Transformers.
3. **Fine-Tuning:**
   - Use the dataset to train the LLaMA model with hyperparameter tuning.
4. **Saving the Model:**
   - Export the fine-tuned model for integration with the Gradio interface.

## 🌐 Interactive Interface
The `gita_gradio.ipynb` notebook provides an intuitive Gradio application for users to input quotes from the Bhagavad Gita and receive contextual meanings.

### Steps:
1. **Load the Model:**
   - Import the fine-tuned LLaMA model.
2. **Set up Gradio:**
   - Build a user-friendly interface with input fields and output sections.
3. **Run the Interface:**
   - Launch the Gradio app locally using:
     ```bash
     gradio app.py
     ```
4. **Usage:**
   - Enter a quote from the Bhagavad Gita in the input box.
   - View the generated meaning in the output section.

## 📖 Example
| Input Quote                   | Interpretation                                  |
|-------------------------------|-----------------------------------------------|
| "Karmanye vadhikaraste ..."  | Focus on your actions without attachment ... |


## 🛡️ License
This project is licensed under the [MIT License](LICENSE).

## 📫 Contact
- **Author:** Vedant Birewar
- **Email:** vedantbirewar8@gmail.com
- **LinkedIn:** [Vedant Birewar](https://www.linkedin.com/in/vedant-birewar-85438724b/)

## 🌟 Acknowledgements
- Hugging Face for their powerful Transformers library.
- Gradio for providing an easy-to-use interface framework.
- The teachings of the Bhagavad Gita for inspiration.

---

*Made with ❤️ by Vedant Birewar.*

