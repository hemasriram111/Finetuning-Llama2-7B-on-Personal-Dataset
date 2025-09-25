
# Fine-Tuning LLMs with Ollama

This project demonstrates how to fine-tune Large Language Models (LLMs) in Python and use them seamlessly with **Ollama**.
The notebook walks you step by step through the process of preparing your dataset, training the model, and running it locally with Ollama.

## 🚀 Features

* Fine-tune an LLM on your **custom dataset**
* Use Python scripts & Jupyter notebooks for training
* Deploy and run your fine-tuned model with **Ollama**
* Easy-to-follow, beginner-friendly workflow

## 📂 Project Structure

```
├── finetuning_personal_dataset.ipynb   # Jupyter notebook with step-by-step code
├── dataset/                            # Your training dataset (JSONL, CSV, etc.)
├── models/                             # Trained models (after fine-tuning)
├── requirements.txt                    # Python dependencies
└── README.md                           # Project documentation
```

## 🛠️ Installation

Clone the repository and set up the environment:

```bash
git clone https://github.com/your-username/finetuning-ollama.git
cd finetuning-ollama
```

Create a virtual environment and install dependencies:

```bash
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows

pip install -r requirements.txt
```

Make sure you have [Ollama](https://ollama.ai) installed on your system.

## 📊 Usage

1. Open the Jupyter notebook:

   ```bash
   jupyter notebook finetuning_personal_dataset.ipynb
   ```

2. Follow the notebook cells step by step to:

   * Load and preprocess your dataset
   * Train/fine-tune your model
   * Export and run it with Ollama

3. Run your fine-tuned model with Ollama:

   ```bash
   ollama run your-model-name
   ```

## 📌 Example

Here’s a quick example after fine-tuning:

```bash
> ollama run your-model-name
User: What is this project about?
Model: This project is a hands-on guide to fine-tuning LLMs and running them locally with Ollama.
```

## 📚 Requirements

* Python 3.8+
* Jupyter Notebook
* Ollama installed locally
* Libraries listed in `requirements.txt`

## 🤝 Contributing

Contributions are welcome! If you’d like to improve the notebook, fix bugs, or add new features, feel free to fork the repo and submit a pull request.

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for details.

---
