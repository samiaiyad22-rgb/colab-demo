# Creative Ideas

This beginner-friendly Colab notebook asks for an everyday object and uses the OpenAI Responses API with `gpt-6-luna` to suggest one unusual, practical use.

## Run it in Google Colab

1. Download `creative_ideas.ipynb` and open [Google Colab](https://colab.research.google.com/).
2. Choose **File → Upload notebook** and select the downloaded notebook.
3. Run the cells from top to bottom.
4. Enter your OpenAI API key at the hidden `getpass` prompt, then type an everyday object.
5. Read the single idea printed by the notebook.

The notebook installs the OpenAI Python SDK if needed. Your account must have access to `gpt-6-luna`; API use may incur charges.

The API key is requested at runtime and is not included or printed. Keep it out of code cells and saved outputs. Local `.env` files and Colab checkpoints are ignored by Git.
