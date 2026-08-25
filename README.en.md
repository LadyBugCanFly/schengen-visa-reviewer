# Schengen Visa Reviewer

[中文](README.md) | [English](README.en.md)

A document self-check skill for ordinary applicants preparing a **short-stay Schengen tourist visa** application.

It does not predict or guarantee a visa decision. It helps identify missing documents, conflicting dates, implausible itineraries, unexplained finances, and weak evidence of timely return before submission.

## What it checks

- Finds the relevant official checklist based on the responsible country, place of application, and applicant circumstances, then compares documents item by item;
- reconciles dates across the application form, flights, accommodation, insurance, approved leave, and itinerary;
- verifies destinations, attractions, transport routes, and reservation requirements, including potentially invented or impractical AI-generated plans;
- compares payslips, bank statements, employment evidence, trip budget, and unusual deposits;
- reviews documented reasons to return, such as employment, study, and lawful residence;
- checks traveller counts, payer details, income, dates, and travel purpose across documents;
- runs a plain-language check against common grounds listed on the standard EU refusal form.

The report uses an A–D **document-readiness grade** and separates actions into must fix, recommended improvements, and optional polish. The grade is not a probability of approval.

## Scope

The current version supports **short-stay Schengen tourism applications only**, including tourist trips covering multiple Schengen countries.

It does not apply tourism criteria or issue a misleading readiness grade for business, family or friend visits, study, work, medical treatment, transit, or long-stay visas.

A French application is checked against the relevant French official requirements, while a Netherlands application is checked against Dutch requirements. One country's checklist is never automatically substituted for another. If the exact official checklist cannot be confirmed, the report is marked provisional.

## Install and use

In a Codex environment that supports installing skills from GitHub, provide this repository URL and ask it to install the `schengen-visa-reviewer` skill. Then try:

> Use $schengen-visa-reviewer to review my French short-stay tourist visa documents. I will apply in Singapore.

Before reviewing documents, the skill confirms the travel purpose, responsible country, place of application, and available materials.

## Privacy

Before uploading documents, redact passport and identity numbers, full home addresses, bank account numbers, application identifiers, barcodes, signatures, and unrelated transactions.

This public repository contains no applicant passports, bank statements, bookings, refusal documents, photographs, or private test reports.

## Disclaimer

This project reviews document readiness only. It does not represent a consular decision or provide legal advice. Official requirements may change; always verify the latest instructions from the relevant government, embassy, consulate, or appointed visa application centre before submission.
