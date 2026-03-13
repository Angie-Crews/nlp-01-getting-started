# Workflow 2.4 Optional Notes

## What I changed
- Created and updated `notebooks/web_words_crews.ipynb`.
- Changed source URL to Project Gutenberg *The Wonderful Wizard of Oz*:
  `https://www.gutenberg.org/files/55/55-h/55-h.htm`
- Added text-cleaning logic to remove common stopwords after lowercasing and punctuation stripping.
- Updated output visualization to a horizontal Top 15 bar chart.

## Why I made the change
- To test the pipeline on a different real-world text source.
- To reduce common-word noise and improve meaningful term frequency results.
- To improve chart readability.

## What I observed after running
- Top terms became more content-specific to the selected text.
- The bar chart labels were easier to read in horizontal format.
- Word cloud output appeared more focused after stopword filtering.
- Notebook executed successfully end-to-end in the project `.venv` kernel.
