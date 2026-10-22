# Prescription Clearance Desk

**Live demo:** https://bg1-pm.github.io/prescription-clearance-desk/

An AI-assisted workstation that clears specialty prescriptions for prior authorization: it reads the intake documents, checks the required elements, and shows the reviewer exactly where each finding came from in the source document.

## The problem
Prior authorization intake is slow, manual, and error-prone. Reviewers re-key data from faxes and referral packets, and missing elements are often caught days later, delaying therapy for the patient.

## Who it's for
Intake and prior authorization teams at specialty pharmacies, and the product and operations leaders who manage them.

## How to try it
1. Open the live demo link above.
2. Walk through a sample case. All patient data is **synthetic**; no real PHI is used.
3. To run the AI steps for real, paste your own Claude API key when prompted. The key stays in your browser tab and is not stored in this repository.

## What I learned
- Claude has become incredibly powerful at creating functioning demos from a properly formatted requirements document.
- It was also highly accurate in the evals I ran. The changes I made had more to do with how the workflow should work than with AI errors.
- The real pressure test is running this at scale and working through more of the edge cases.

---
Built as my capstone for the AI Product Management course (Cohort C11).
