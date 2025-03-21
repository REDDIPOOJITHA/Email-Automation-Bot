# EMAIL-AUTOMATION-BOT

An automated email sender that supports single, bulk, and scheduled emails with attachments in formats like PDF, images, documents, and spreadsheets.

## Features

1. Send single emails, bulk emails, or scheduled emails  

2. Attach PDF, PNG, JPG, DOCX, XLSX, PPTX, and TXT files  

3. Uses SMTP for secure email delivery  

4. Customizable email templates  

5. Easy setup and configuration  

## Installation

1. Clone the Repository

git clone <repository-url> cd Email-Automation-Bot

2.Install Dependencies  

pip install pandas streamlit python-dotenv tzlocal schedule pytz

3.Configure Email Settings  

- Rename `.env.example` to `.env`
  
- Add your email credentials and SMTP details  

## Usage

To run the Streamlit application, execute: 

streamlit run final.py


## Saving Attachments

- Place files in the `saved_attachments/` folder before running the bot.
  
- Supported formats: PDF, Images, DOCX, XLSX, PPTX, TXT.
