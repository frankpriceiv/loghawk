# loghawk
# LogHawk

LogHawk is a Jupyter notebook that uses Qwen Coder to triage security logs. It assigns each entry a label, a severity score, and a short explanation. It also exports the results to CSV and JSON and generates an experimental Sigma detection rule for review.

## How to run

1. Open `Lab6.ipynb` in JupyterLab.
2. Run the first cell to install the `openai` package.
3. Run the connection cell and enter your API key in the hidden prompt.
4. Put your log file in the same folder as the notebook and set `LOG_FILE` to its filename.
5. Run the batch, export, and detection-rule cells in order. The offline tests can run without a model connection once the parsing functions are loaded.

## Output files

- `triage_results.csv` and `triage_results.json` contain the classifications.
- `detection_rule.txt` contains the generated Sigma rule.
