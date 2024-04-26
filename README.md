# OntoGPT

## Quick Start

OntoGPT runs on the command line, though there's also a minimal web app interface (see `Web Application` section below).

1. Ensure you have Python 3.9 or greater installed.
2. Install with `pip`:

    ```bash
    pip install ontogpt
    ```

3. Set your OpenAI API key:

    ```bash
    runoak set-apikey -e openai <your openai api key>
    ```

4. See the list of all OntoGPT commands:

    ```bash
    ontogpt --help
    ```

5. Place 'food_ingredient_ontology.yaml' and 'food_ingredient_ontology.py' into 'ontogpt > src > ontogpt > templates'

6. Run 'run_command.ipynb'
