
# LLM-Powered W&B

A package that automates the extraction of experimental conditions from Jupyter Notebooks, sends them to OpenAI, and logs the results using Weights & Biases (W&B).

## Features

- Automatically extracts code from Jupyter Notebook files.
- Sends extracted code to OpenAI for processing.
- Logs responses to Weights & Biases (W&B) for easy tracking and analysis.
- Simplifies the workflow for researchers and data scientists.

## Installation

To install the package, run the following command in your terminal:

```bash
pip install -e .
```

This command installs the package in editable mode, allowing you to modify the code and see changes without reinstalling.

## Usage

Here is a simplified example of how to use the package:

```pytho
from llm_powered_wandb import process_notebook

# Specify your parameters
notebook_path = 'your_notebook.ipynb'  # Path to your Jupyter Notebook
api_key = 'your_openai_api_key'  # Replace with your OpenAI API key
project_name = 'your_project_name'  # Name of your W&B project

# Process the notebook
process_notebook(notebook_path, api_key, project_name)
```

## Contributing

Contributions are welcome! If you have suggestions or improvements, please feel free to submit an issue or a pull request.

## License

This project is licensed under the MIT License.
