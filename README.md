# Cyber Research — Automated Reports

This project collects new cybersecurity reports from trusted sources.  
It creates short summaries and a final report.  
The goal is to help people understand recent cyber risks in a simple way.

## What this project does

- searches for recent cybersecurity reports
- reads the content
- writes a clear summary
- builds a final report you can read or share

## Requirements

- CrewAI requires Python >=3.10 and <3.14. Here’s how to check your version: python --version
  
Install the needed packages:

pip install -r requirements.txt

## Environment setup

Create a file named `.env` in the project folder.

Add your keys like this:

OPENAI_API_KEY=your_key_here  
SERPER_API_KEY=your_key_here  

Do not upload this file to GitHub.

## How to use

1. Open the notebook:

cyber_research_crewai.ipynb

2. Run each cell in order.
3. At the end, you will see the final report.

## Notes

- results may change each time you run the notebook
- this project is for learning and research purposes

## License

You may use and share this project. Add your preferred license if needed.
