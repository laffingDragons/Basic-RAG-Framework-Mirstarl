
# RAG (Retrieval-Augmented Generation) Model

This repository contains a basic implementation of the Retrieval-Augmented Generation (RAG) model using Python. The goal of the RAG model is to retrieve relevant information from a knowledge base and use it to generate more accurate and contextually rich responses.

## Features

- Implements the RAG model using [Hugging Face Transformers](https://huggingface.co/).
- Integrates with Mistral API for enhanced capabilities in natural language understanding.
- Includes a simple example of how to use the model for document retrieval and generation.

## Requirements

Before running the code, ensure you have the following dependencies installed:

```bash
pip install -r requirements.txt
```

## Setup Mistral API

To use Mistral in your project, you’ll need to obtain an API key from Mistral’s Console.

### How to Generate an API Key:

1. **Sign Up / Log In:**
   - Go to the Mistral Console: [https://console.mistral.ai](https://console.mistral.ai).
   - Sign up or log in with your credentials.

2. **Create an API Key:**
   - After logging in, navigate to the **API Keys** section of the dashboard.
   - Click **Create New API Key** and give it a name (e.g., “RAG Model API Key”).
   - Once created, copy the key that is generated.

3. **Store the API Key:**
   - For security, store the API key in an environment variable or in a `.env` file.
   - Example:
     ```bash
     export MISTRAL_API_KEY="your_api_key_here"
     ```

## Example Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/rag-model.git
   cd rag-model
   ```

2. Create a Python virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scriptsctivate`
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the example:
   ```bash
   python example.py
   ```

## Contributing

Feel free to fork the repository, create a branch, and make pull requests. If you encounter any issues or have suggestions, please open an issue in the issue tracker.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
