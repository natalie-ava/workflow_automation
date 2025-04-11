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
- Applied regular expressions for targeted string cleaning and transformation
- Integrated Python automation with OCR and translation tools to enable multilingual workflows
- [Excel workbook creation](https://github.com/natalie-ava/workflow_automation/blob/main/class_notes/NHuang_Excel_Chart.ipynb) and data entry using `openpyxl`
- Created visualizations using `matplotlib` to highlight [trends in product categories](https://github.com/natalie-ava/workflow_automation/blob/main/class_notes/NHuang_grids_on_canvas.ipynb)
- Used PyAutoGUI to automate GUI-based tasks and screen interactions
- Automated workflows involving data scraping, Excel manipulation, email delivery, and visual content generation

## Projects 
- Automated [email notifications](https://github.com/natalie-ava/workflow_automation/blob/main/projects/CA_email_automation.ipynb) using `smtplib` and `email.mime` to send personalized formatted messages with attachments as part of workflow execution
- Built a [text extraction and translation workflow](https://github.com/natalie-ava/workflow_automation/blob/main/projects/Text_Extraction_and_Translation.ipynb) using `pytesseract`, `Pillow`, and `googletrans`: used Optical Character Recognition (OCR) to extract printed text from an image, then automatically translated it to English using the Google Translate API — demonstrating multilingual automation for accessibility, localization, and content adaptation use cases.
- Designed a [Language Learning Email Automation](https://github.com/natalie-ava/workflow_automation/blob/main/projects/Language_Learning_Email.ipynb): used `PyAutoGUI` to organize input directories, `pytesseract` to extract foreign language phrases from images, and `googletrans` to translate them into English. Combined each phrase with a culturally relevant city photo and stored everything in a `pandas` DataFrame. Automated personalized email delivery using `smtplib`, `ssl`, `email.mime`, and `schedule` to send messages that included a phrase in a foreign language, the english translation, and a photo of a city where that language is predominantly spoken at a set time each day.
- Developed an [end-to-end holiday gift guide automation system](https://github.com/natalie-ava/workflow_automation/blob/main/projects/LEGO_Final_Project.ipynb): scraped LEGO product data (name, price, age, rating, etc.) into a pandas DataFrame, saved to CSV using `os`, captured product images with `PyAutoGUI`, used `Pillow` and `ReportLab` to design custom posters, and scheduled automated emails to send gift suggestions to a potential buyer list.

## What I Learned
This course taught me how to think like an automation designer. I learned how to break down tedious workflows and rebuild them with code. I developed a deeper understanding of how Python can be used not just for analysis, but for streamlining everyday tasks in meaningful ways.
