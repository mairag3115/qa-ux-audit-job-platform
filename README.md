# QA + UX Audit – Job Platform

## Overview
This project is a manual QA and UX audit of a job platform. The goal was to evaluate the main user flow, identify functional issues, detect usability problems, and propose improvements that could enhance the user experience.

## Platform Analyzed
Computrabajo

## Project Goal
To simulate a real QA and UX review process by analyzing a job search platform from both a testing and usability perspective.

## Scope
The project evaluates the following user flow:
- User registration / login
- Job search
- Job filtering
- Viewing job details
- Applying to a job
- Returning to search results after interaction

## Deliverables
- Test cases
- Bug reports
- UX findings
- Improvement proposals
- Final report
- Screenshot evidence

## Key Findings
- The empty results page does not provide a direct action to clear filters or recover the search quickly.
- Returning from the application flow may leave the search results page visually dimmed, affecting navigation clarity.
- Search and filtering behavior can create confusion when results are limited or no longer visible.
- Users may need clearer recovery actions and stronger feedback during the application flow.

## Bug Highlight
**BUG-01:** Search results page remains dimmed after returning from a job application flow.

This issue may affect navigation confidence and create the impression that the interface is blocked or not fully restored.

## UX Highlight
The empty results page provides general recommendations, but it does not include a direct and visible action to clear filters or quickly recover the search. This adds friction to the user journey.

## Repository Structure
- `test-cases/` → documented manual test cases
- `bug-reports/` → bug reports with severity and priority
- `ux-findings/` → usability issues identified
- `improvement-proposals/` → suggested product improvements
- `screenshots/` → supporting visual evidence

## Tools Used
- Manual testing
- Screenshot evidence
- Markdown documentation
- GitHub

## Skills Demonstrated
- Manual testing
- Bug documentation
- UX analysis
- Functional analysis
- Critical thinking
- Product evaluation
- Written communication

## Evidence Included
This repository includes real screenshot evidence collected during testing and navigation scenarios.

## Conclusion
This project combines QA and UX analysis to provide a broader view of product quality. Beyond functional correctness, the audit highlights how usability, recovery actions, and navigation clarity directly impact the overall user experience.