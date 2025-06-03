# AFB-AI-GEN
The AFB Generator project is a Python-based tool developed to streamline feature selection for automation. It generates outputs from Test Briefs or Test Designs of new features, determining which areas should be automated and providing the necessary test steps. This process adheres to the principles of the automation pyramid.

Features:
	• AFB Generation: Automatically create Test Cases that require to be automate based on Test Brief
	
Project Structure:
	• main.py: Entry point to run the pipeline
	• parser.py: Splits input doc into feature statements
	• ner_extractor.py: Extracts actions, conditions, expected results
	• case_mapper.py: Maps parsed content to test case templates
	• schema.py: Defines structure like Test ID, Steps, Expected, etc.
	• exporter.py: Saves output to .xlsx, .json, etc
	• ui/app.py: Optional Streamlit dashboard for interactive generation
	• file_loader.py: Reads .docx, .pdf, or plain text input
	• test_*: Unit tests for pipeline modules
	

How to Use:

Requirements:

Motivations:
	• Why do we need AFB generator?
		○ To identify area to be automated from Test Design 
	• Why do we need a framework for that?
      To have a consistent format for generator

