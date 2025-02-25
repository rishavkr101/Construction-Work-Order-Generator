# Construction Work Order Generator

This project is a Python-based tool that generates a professional Construction work order by taking user inputs and using the Hugging Face Inference API for text generation. It leverages prompt templating from the LangChain library to format and structure the final document.

## Features

- Dynamic User Input:Collects essential information such as company name, contractor name, project details, and work description.
- Unique Work Order Number:Generates a unique work order number based on the current date and random digits.
- Text Generation:Uses the Hugging Face Inference API (with the `mistralai/Mistral-7B-Instruct-v0.2` model) to generate detailed and formatted work order documents.
- Prompt Templating:Utilizes the `PromptTemplate` class from LangChain for flexible prompt creation.
- File Output:Saves the generated work order as a text file for easy access and record keeping.

## Requirements

- Python:Version 3.7 or higher.
- API Token:A valid Hugging Face API token is required(free to use with limitations). can aslo be done using other api such as  Open AI api ,etc
- Dependencies:The project uses third-party libraries listed in the requirements.txt file.

## Installation

1. Clone the Repository:
   git clone https://github.com/rishavkr101/Construction-Work-Order-Generator
