The AFB Generator project is a Python-based tool developed to streamline feature selection for automation. it generates outputs from Test Briefs or Test Designs of new Features, determining which area should be automated and providing the necessary test steps. This process adheres to the principles of the automation pyramid

FEATURES:
AFB Generation: Automatically create Test Cases that require to be automate based on Test Brief

Project Structure:
main.py: Entry point to run the pipeline
parser.py: Splits input doc into feature statement
ner_extractor.py: extracts actions, conditions, expected results
case_mapper.py: Maps parsed content to test case templates
schema.py: defines structure like Test ID, Steps, Expected, etc
exporter.py: saves output to .xlsx, .json, ect
ui/app.py: optional Streamlit dashboard for interactive generation
file_loader.py: Reads.docx, .pdf, or plain text input
test_*: unit tests for pipeline modules

How to use:


Requirements:

Motivations:
