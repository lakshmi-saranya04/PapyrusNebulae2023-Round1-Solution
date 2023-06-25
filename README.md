# PapyrusNebulae2023-Round1-Solution
This repository contains my Round 1 solution for the PapyrusNebulae 2023 Document Cloud Hackathon. Extracting info from PDF invoices using Adobe PDF Services Extract API. Python code with provided SDK. Includes samples, CSV format, and setup instructions for Adobe PDF Services account.

## Adobe PDF Data Extraction Challenge
This challenge aims to extract data from invoices in PDF format using Adobe PDF Services. The extracted data will be formatted and stored in a CSV file.

## Prerequisites
Before starting the challenge, make sure you have the following:

Python 3.x installed on your machine.
The JSON library, which is included in the Python standard library.

## Installation
To get started, follow these steps:

Set up a virtual integrated development environment (IDE) such as PyCharm or VSCode.
Install the required SDK for your preferred programming language: Java, Python, Node.js, or C#. The SDKs provide convenient methods and functions for interacting with the Adobe PDF Services API. If you prefer to use a different runtime, you can create the API requests manually by following the documentation provided here.

## Getting Started
Download the code folder to a specific path on your local machine.

Obtain Adobe PDF Services API credentials by signing up for a free trial account. Instructions for getting started with the free trial can be found here.

Note: The free trial provides 1000 free transactions, which should be sufficient for this exercise. If your credentials expire, create another credential using a different personal email address.

## Usage
### Extracting Data from JSON Files
The provided code includes a function named ExtractData that extracts relevant data from a JSON file and returns it in a structured format. This function is specifically designed to extract information from JSON files containing data related to invoices and business details.

#### To extract data from a JSON file:

Call the ExtractData function with the file path of the JSON file as the argument.
The function will return the extracted data as a list of rows.
##Extracting Data from a PDF File
The provided code also includes a function named getZipFiles that extracts text from a PDF file and saves it as a ZIP file containing JSON files. This function utilizes the Adobe PDF Services API to perform the extraction.

#### To extract data from a PDF file:

Call the getZipFiles function with the input PDF file path and the output ZIP file name as arguments.
The function will extract the text from the PDF file and save it as a ZIP file containing JSON files.
### Creating a CSV File
The provided code includes a function named Createcsv that creates a CSV file using the extracted data. The function expects the extracted data to be a list.

#### To create a CSV file:

Call the Createcsv function with the extracted data as the argument.
The function will create a CSV file named "ExtractedData.csv" and write the extracted data into it.
## Test Dataset
The "TestDataSet" folder contains 100 sample invoices. Your task is to extract data from these invoices and format it in the same way as the "ExtractedData.csv" file provided in the "SampleinvoicesAndData/ExtractedData" folder.

## Conclusion
By following the instructions provided and using the Adobe PDF Services API, you should be able to extract data from the sample invoices and generate a formatted CSV file.
