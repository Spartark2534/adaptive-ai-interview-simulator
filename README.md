
# Interview Ready AI — Adaptive Interview Simulator

An adaptive AI interview simulator designed to help freshers prepare for QA Engineer and Quality Analyst interviews.

Unlike static interview-question lists, this project explores how an AI interviewer can adapt its next question based on a candidate's previous response.

## The Problem

Most interview-preparation tools rely on fixed question lists. They may not respond to a candidate's actual understanding, reasoning, or knowledge gaps.

## Project Goal

Build a realistic, role-specific mock interview experience that asks one question at a time, adapts to candidate responses, and provides actionable feedback after the interview.

## Core Components

### 1. Question Architect
Creates a structured interview plan based on the target role, experience level, job description, and relevant candidate information.

### 2. Adaptive Interviewer
Conducts the interview one question at a time and adjusts follow-up questions and difficulty based on the candidate's responses.

### 3. Interview Evaluator
Reviews the completed interview transcript, evaluates answers against a defined rubric, and identifies strengths, weaknesses, and areas for improvement.

## Initial Target Audience

Students and recent graduates preparing for their first QA Engineer or Quality Analyst interview.

## Research and Foundation — Module 1

The initial research phase focuses on:

- Reviewing entry-level QA job descriptions
- Identifying common QA fresher competencies
- Using the ISTQB Certified Tester Foundation Level syllabus as a reference
- Developing a competency map for interview-question planning
- Defining candidate-answer evaluation criteria
- Designing adaptive interview decision rules
- Establishing fairness and evidence-based evaluation boundaries

## Key Design Principles

- Ask one question at a time.
- Adapt questions based on observable evidence in the candidate's response.
- Distinguish answer quality from the decision about what to ask next.
- Do not reveal correct answers during the active interview.
- Avoid unsupported assumptions about a candidate's abilities or experience.
- Use evaluation results to guide learning, not to make hiring decisions.
- Keep question planning, interviewing, and evaluation as separate responsibilities.

## Project Status

**Current milestone:** Module 1 — Foundation and Research.

The next milestones are to build the three AI components, test their behavior, refine the prompts, and prepare a project demonstration.

## Planned Technology and Tools

- Gemini Gems
- NotebookLM
- Google Drive
- GitHub
- Canva

## Disclaimer

This is an interview-preparation project. Its evaluations are intended to support practice and learning, not to determine a candidate's suitability for employment.

## Sources

- [ISTQB Certified Tester Foundation Level](https://istqb.org/certifications/certified-tester-foundation-level-ctfl-v4-0/)
- [ISTQB CTFL v4.0.1 Syllabus](https://istqb.org/wp-content/uploads/2024/11/ISTQB_CTFL_Syllabus_v4.0.1.pdf)

Job-description research references and supporting research notes will be documented in the project files.
