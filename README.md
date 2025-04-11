# Workflow Automation with Python – Course Projects

This repository showcases my work from the **DATA 2399: Workflow Automation with Python** course. Throughout the semester, I learned how to automate repetitive tasks, extract data from the web, integrate automation libraries, and design end-to-end workflows for real-world applications.

## Topics Covered
- Python scripting for automation
- String manipulation and regular expressions
- Web scraping using BeautifulSoup and pandas
- File and task automation with Python
- Working with Excel files using `openpyxl`
- Data visualization with `matplotlib`
- Automating email communications
- Optical Character Recognition (OCR) and translation workflows
- Designing custom automation workflows

## Tools & Technologies
- Python, Jupyter Notebook
- `pandas`, `BeautifulSoup`, `matplotlib`, `openpyxl`, `re`
- Automation libraries: `PyAutoGUI`, `os`, `shutil`, `Schedule`,`Time`, `smtplib`, `ssl`, `email.mime`
- OCR & Translation: `pytesseract`, `Pillow`, `googletrans`

## Highlights
- Created a custom scraper to extract structured set data from a web source
- Used pandas to clean and analyze scraped data
- Designed scripts to automate repeatable scraping and cleaning tasks
- Automated [email notifications](https://github.com/natalie-ava/workflow_automation/blob/main/projects/CA_email_automation.ipynb) using `smtplib` and `email.mime` to send personalized formatted messages with attachments as part of workflow execution
- Built a [text extraction and translation workflow](projects/NHuang_Text_Extraction_and_Translation.ipynb) using `pytesseract`, `Pillow`, and `googletrans`: used Optical Character Recognition (OCR) to extract printed text from an image, then automatically translated it to English using the Google Translate API — demonstrating multilingual automation for accessibility, localization, and content adaptation use cases.
- Developed an [end-to-end holiday gift guide automation system](https://github.com/natalie-ava/workflow_automation/blob/main/projects/LEGO_Final_Project.ipynb): scraped LEGO product data (name, price, age, rating, etc.) into a pandas DataFrame, saved to CSV using `os`, captured product images with `PyAutoGUI`, used `Pillow` and `ReportLab` to design custom posters, and scheduled automated emails to send gift suggestions to a potential buyer list.

## What I Learned
This course taught me how to think like an automation designer. I learned how to break down tedious workflows and rebuild them with code. I developed a deeper understanding of how Python can be used not just for analysis, but for streamlining everyday digital tasks in meaningful ways.
