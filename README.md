# AI Job Application Assistant

An AI-powered application built with Streamlit that leverages a multi-agent system using CrewAI to assist job seekers. This tool helps create tailored resumes, analyze job postings, and prepare for interviews efficiently and effectively.

## Features
- **AI Multi-Agent System:** Powered by CrewAI to coordinate specialized agents for tasks like job posting analysis, resume tailoring, and interview preparation.
- **Resume Parsing:** Extracts and converts resume content from PDF to Markdown.
- **Job Posting Analysis:** Scrapes and analyzes job postings to identify key skills and requirements.
- **Professional Profiling:** Compiles comprehensive profiles using GitHub links and personal write-ups.
- **Resume Tailoring:** Aligns resumes with specific job requirements.
- **Interview Preparation:** Generates interview questions and talking points based on the job posting and tailored resume.

## How It Works
1. **Upload Your Resume:** Upload a PDF version of your resume.
2. **Input Additional Information:**
   - Job posting URL
   - GitHub profile URL
   - Personal write-up about your career goals
3. **Process the Application:**
   - **Agents in Action:**
     - The **Tech Job Researcher** analyzes job postings to extract key requirements.
     - The **Personal Profiler** uses GitHub and personal write-ups to create a professional profile.
     - The **Resume Strategist** tailors your resume to match the job requirements.
     - The **Interview Preparer** generates interview questions and talking points.
4. View and download the tailored resume and interview preparation materials.

## Technologies Used
- **Streamlit:** Provides an intuitive user interface for input and output.
- **CrewAI:** Enables multi-agent coordination to perform complex tasks.
- **LangChain Community Tools:** Powers semantic search, file reading, and web scraping.
- **Markdownify:** Converts text content to Markdown for better readability.
- **PyMuPDF (Fitz):** Extracts text from PDF resumes.
- **SerperDev API:** Assists in web scraping for job posting analysis.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/AI-Job-Application-Assistant.git
   cd AI-Job-Application-Assistant

