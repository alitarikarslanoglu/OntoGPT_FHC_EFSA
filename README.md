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

5. Place `ClaimAnalysis.yaml` and `ClaimAnalysis.py` into `ontogpt > src > ontogpt > templates`

6. Set the directories according to you preference in the code. In each file, it is currently set to 'RootDirectory' in each notebook file
7. Set api keys
8.  Before running `main.ipynb` run:
    ```bash
    pip install --upgrade openai
    ```

9. After adjustments, running sequence must be as `pdf_dorectory_manager.ipynb` -> `section_detector.ipynb` -> `main.ipynb` -> `output_json_format.ipynb` -> `reference_retrieval.ipynb` -> `doi_generator.ipynb` -> `validation_data_preprocessing.ipynb` -> `evaluation_function.ipynb`


## ExampleData:

This document is the instance of how the automation created works.


