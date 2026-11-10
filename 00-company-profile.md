# Brightwater Credit Union (Fictional)
> This is a fictional organization created for portfolio purposes. Any resemblance to a real institution is unintended.

## Overview
Brightwater Credit Union is a New York state-chartered, federally insured credit union headquartered in Poughkeepsie, New York, serving members across the Hudson Valley.
- Employees: approximately 600
- Members: approximately 140,000
- Total assets: approximately $2.3 billion
- Branches: 18
- Services: checking and savings accounts, auto loans, mortgages, credit cards, small business lending, and online and mobile banking

## Regulatory Environment
- Gramm-Leach-Bliley Act (GLBA), implemented for credit unions through NCUA Part 748, which also requires reporting a reportable cyber incident to NCUA within 72 hours
- NYDFS 23 NYCRR Part 500 (Cybersecurity Requirements for Financial Services Companies)
- New York SHIELD Act (data breach notification)
- Truth in Savings Act, implemented for credit unions through NCUA Part 707 (deposit rate disclosures and advertising)
- Truth in Lending Act, implemented through Regulation Z (loan rate disclosures and advertising)
- NYDFS industry letter on cybersecurity risks arising from artificial intelligence (October 2024)
- NCUA Letters to Credit Unions 01-CU-20 (Due Diligence Over Third Party Service Providers) and 07-CU-13 (Evaluating Third Party Relationships)
- Framework adopted: NIST Cybersecurity Framework (CSF) 2.0

## AI Systems in Scope
1. "Ask Brightwater" – member-facing chatbot
   - Purpose: answer general member questions about products, rates, hours, and account procedures
   - LLM provider: Nimbus AI (fictional), accessed through the vendor's hosted API
   - Retrieval augmented generation (RAG) over member FAQs, product disclosures, and internal policy documents
   - Channels: website and mobile app
   - Phase 1 does not access individual member account data
   - System prompt contains no credentials or API keys
   - Target launch: Q1 2027
2. Staff use of generative AI tools
   - Used for drafting communications, summarizing documents, and research
   - Currently no formal policy governing approved tools or permitted data

## Out of Scope
- Core banking platform
- Payment processing and card systems
- Loan underwriting and credit decision systems

## Key Stakeholders
- Chief Executive Officer: final risk acceptance authority
- Chief Information Security Officer: owns the AI security risk program
- Chief Information Officer: owns the chatbot platform and vendor integration
- Chief Compliance Officer: regulatory alignment (NCUA, NYDFS)
- Head of Member Services: business owner of the chatbot
- Board Risk Committee: oversight and annual review

## Assessment Objective
Identify, assess, and recommend treatment for AI-related risks before the "Ask Brightwater" launch and to govern staff use of generative AI, aligned with the NIST AI Risk Management Framework.

## Assessment Details
- Prepared by: Amin Jlassi
- Date: October 2026
- Version: 1.0
