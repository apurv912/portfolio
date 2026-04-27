# Upwork Portfolio Card 1: AI Job Search Automation Engine

## Portfolio title

AI Job Search Automation Engine — Gmail to Scored Job Tracker + CV Pack

## Short description

Designed an AI-assisted job search automation workflow that ingests job alerts from Gmail, filters and scores opportunities, and generates structured CV tailoring outputs.

## Client-facing summary

This project shows how a messy email-based workflow can be converted into a structured AI-assisted operations system.

The problem was simple: job alerts were scattered across Gmail, different platforms, and inconsistent formats. Manually reviewing each job, checking relevance, scoring fit, and preparing tailored CVs was slow and repetitive.

I designed an automation workflow that turns incoming job alerts into a scored, structured tracker and then supports CV pack generation for high-fit jobs.

## Problem

Manual job search workflows are repetitive and error-prone:

- Job alerts arrive from multiple sources.
- Relevant and irrelevant jobs are mixed together.
- Manual review takes time.
- CV tailoring is inconsistent.
- It is difficult to know which jobs deserve immediate attention.

## Solution

Built a workflow that:

- Reads job alert emails from Gmail.
- Extracts job information into structured fields.
- Filters irrelevant roles before using AI.
- Scores jobs using a defined rubric.
- Routes jobs into apply/skip/review decisions.
- Supports tailored CV generation for high-priority jobs.

## Tools and skills used

- Gmail workflow design
- Google Sheets as operations tracker
- AI-assisted extraction and scoring
- n8n / automation logic
- Python / Flask for document generation support
- Product scoring rubric
- Prompt design
- Cost-aware system design
- Product documentation

## Product/PM decisions

- Used Gmail as the source instead of fragile job-board scraping.
- Added hard filters before AI calls to reduce cost.
- Created a scoring rubric to make decisions consistent.
- Added proofcheck logic to avoid inserting claims that cannot be defended.
- Designed the system as a low-cost, local-first workflow.

## Business value

This type of system can help a client:

- Reduce manual review time.
- Create a structured pipeline from messy email data.
- Prioritize high-value opportunities or leads.
- Standardize decision-making.
- Lower the cost of AI-assisted operations.

## Relevant Upwork services this supports

- Gmail/email workflow automation
- Google Sheets workflow setup
- AI-assisted data extraction
- Automation blueprint
- Operations tracker design
- AI scoring/rubric design
- Lightweight internal tool planning

## Suggested screenshot/video ideas

Use 2-4 images if possible:

1. Architecture diagram of the workflow.
2. Sample Google Sheets tracker with dummy data.
3. Scoring rubric screenshot.
4. Short Loom walkthrough explaining the workflow in under 2 minutes.

## Links

- GitHub: https://github.com/apurv912/job-search-automation
- Portfolio: https://apurvadarsh.com

## Upwork caption

A practical AI workflow automation case study: turning unstructured Gmail job alerts into a structured scoring and CV-generation pipeline. This demonstrates workflow mapping, AI-assisted extraction, decision logic, and product operations thinking.
