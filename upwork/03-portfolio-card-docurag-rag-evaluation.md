# Upwork Portfolio Card 2: RAG Evaluation & Safety Dashboard

## Portfolio title

RAG Evaluation & Safety Dashboard — Citations, Telemetry, Guardrails

## Short description

Built a PM-first RAG evaluation project focused on answer quality, citation validity, latency, fallback behavior, telemetry, and safety guardrails.

## Client-facing summary

This project shows how an AI chatbot or RAG system can be evaluated beyond “it gives answers.”

Many teams build chatbots quickly but do not measure whether the answers are grounded, cited correctly, safe, reliable, or usable under real constraints. This project focuses on the product-quality layer of RAG systems: retrieval quality, citation trust, telemetry, fallback behavior, and safety.

## Problem

AI/RAG products often fail because:

- Answers are not grounded in the provided documents.
- Citations are missing or incorrect.
- The system breaks under quota or rate-limit issues.
- Teams cannot see latency, error rates, or fallback behavior.
- Safety risks are not tested early.

## Solution

Built a RAG microbuild ladder that progressively adds:

- Baseline retrieval and Q&A.
- Caching and similarity guardrails.
- Citation generation and citation validation.
- Two-stage retrieval and reranking.
- Evaluation scorecards comparing configurations.
- Telemetry and ops dashboard.
- Safety and robustness guardrails for risky queries, prompt injection, and weak grounding.

## Tools and skills used

- RAG product thinking
- Retrieval evaluation
- Citation validation
- Telemetry design
- Safety and guardrail planning
- Streamlit dashboarding
- Python
- Product-quality metrics
- AI product documentation
- PM-style acceptance criteria

## Product/PM decisions

- Treated the RAG system as a product, not just a demo.
- Added scorecards to compare retrieval configurations.
- Included citation validity as a trust metric.
- Tracked fallback behavior and latency proxies.
- Added safety tests for risky domains and prompt-injection cases.
- Kept the build modular so each improvement can be evaluated separately.

## Business value

This type of work can help a client:

- Audit whether their chatbot is reliable enough for users.
- Identify hallucination and citation issues.
- Define evaluation metrics before scaling.
- Improve stakeholder confidence in AI outputs.
- Create a roadmap for safer RAG/chatbot deployment.

## Relevant Upwork services this supports

- RAG chatbot audit
- AI chatbot evaluation plan
- Citation quality review
- AI product QA checklist
- RAG MVP requirements
- AI safety/guardrail planning
- Product documentation for AI systems

## Suggested screenshot/video ideas

Use 2-4 images if possible:

1. RAG evaluation scorecard.
2. Telemetry dashboard screenshot.
3. Citation validation example.
4. Short Loom walkthrough explaining how the evaluation layer works.

## Links

- GitHub: https://github.com/apurv912/DocuRAG
- Portfolio: https://apurvadarsh.com

## Upwork caption

A PM-first RAG evaluation project showing how chatbot quality can be measured through retrieval results, citation validity, telemetry, fallback behavior, and safety guardrails. Useful for clients building AI assistants who need more than a basic demo.
