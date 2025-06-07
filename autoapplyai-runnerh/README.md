# AutoApplyAI – Runner H Autonomous Job Agent

AutoApplyAI is an AI-powered agent built on [Runner H](https://runner.hcompany.ai/) that automates the job search, application, and interview prep pipeline.

## What It Does

- Parses your resume and extracts key skills
- Searches relevant jobs from online platforms
- Ranks job postings based on fit and pay
- Generates tailored resumes and cover letters
- Logs applications in Google Sheets or Notion
- Provides personalized interview prep plans

## Setup & Usage

1. Clone this repo  
2. Upload your resume to `resume_samples/`  
3. Set job preferences (location, roles) in the Runner H UI or `.env`  
4. Import `autoapplyai.hflow` into Runner H  
5. Run your agents and let AutoApplyAI handle the rest!

## Agent Tasks
Each task is modular and composable:
- `resume_parser`
- `job_scraper`
- `job_ranker`
- `resume_updater`
- `cover_letter_generator`
- `application_tracker`
- `interview_prep_planner`

## 🔗 Live Demo
Coming soon…

## 📣 Social Post
Follow our journey [@hcompany_ai](https://x.com/hcompany_ai)  
Post link: [DevPost/Medium article link here]
