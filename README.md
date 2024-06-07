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

6. Set the directories according to you preferences in the code. In `extract_sessions.ipynb` , `pdf_dorectory_manager.ipynb` and `main.ipynb`
7. Set api keys
8. When running `extract_sessions.ipynb`, openai library meeds to be set openai==0.28. It is already located in the first cell in the file
9.  Before running `main.ipynb` run:
    ```bash
    pip install --upgrade openai
    ```

10. After adjustments, running sequence must be as `pdf_dorectory_manager.ipynb` -> `extract_sessions.ipynb` -> `main.ipynb`


