# AI Job Search Automation with n8n

This project is an AI-assisted job search workflow built in n8n.

It searches for recent job postings, filters them by keyword, uses AI to analyze resume fit, and emails a daily summary of relevant jobs.

## What it does

- Searches LinkedIn jobs posted recently
- Uses Apify to fetch job listings
- Uses Google Drive to pull resume content
- Uses Gemini to analyze job fit
- Sends a Gmail summary with job links
- Can be expanded to generate tailored resumes

## Tools used

- n8n
- Apify
- Google Drive
- Gmail
- Gemini
- LinkedIn job search

## Current status

Working MVP:
- Job search runs successfully
- Gemini analysis runs
- Daily email summary sends correctly

## Next improvements

- Add multiple resume profiles
- Add ATS scoring
- Add company blacklist
- Add duplicate tracking
- Re-enable PDF resume generation