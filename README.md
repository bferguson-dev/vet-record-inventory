# Veteran Medical Record Evidence Inventory

A prompt-based framework for helping veterans organize what their records actually say.

## What This Project Does

This repository provides documentation, prompts, checklists, and testing guidance for using AI to create a factual inventory of uploaded veteran medical and evidence records.

The framework is designed to help a veteran identify documented:

* conditions
* symptoms
* diagnoses
* treatments
* medications
* procedures
* tests
* timelines
* missing records
* source locations

It also helps separate different evidence types, including military service treatment records, VA treatment records, private medical records, VA adjudication records, C&P exams, DBQs, lay statements, and other evidence.

The core prompt is in [PROMPT.md](PROMPT.md).

## What This Project Does Not Do

This project is not:

* a claim strategy tool
* a legal advice tool
* a medical diagnosis tool
* a VA rating predictor
* a nexus-letter generator
* a DBQ generator
* a substitute for a VSO, attorney, claims agent, medical provider, or VA-accredited representative

It should not be used to decide what claim to file, predict a VA outcome, create medical causation opinions, or replace qualified professional help.

## Who This Is For

This project is for U.S. veterans who want a structured way to understand what appears in their own uploaded records before deciding what to do next.

It may also be useful for family members, caregivers, VSOs, county Veterans Service Officers, state veterans departments, VA-accredited representatives, attorneys, claims agents, or other helpers who want a plain-English framework for organizing records.

Do not upload another person's records without permission.

## Important Warnings

This project is for educational and record-organization purposes only. It does not provide legal advice, medical advice, VA claim representation, diagnosis, nexus opinions, DBQs, rating predictions, or claim recommendations.

AI tools can miss evidence, misread records, or hallucinate. Users must verify all findings against the original records.

Veteran records may contain highly sensitive information, including SSN, full date of birth, VA file number, addresses, phone numbers, mental-health records, medical history, medications, and third-party information. Review privacy settings and consider redaction before uploading records to any AI platform.

Read [DISCLAIMER.md](DISCLAIMER.md) before using this project.

## Recommended AI Setup

This workflow is intended for paid ChatGPT or Claude accounts using Project, workspace, or similar features. Full VA and private medical record sets are often too large for free-account limits.

This is not a recommendation to buy an AI subscription. Free accounts may work for one or two small test files only. If cost is a barrier, consider free assistance from an accredited Veterans Service Organization, county Veterans Service Officer, state veterans department, or VA-accredited representative.

See [SETUP-GUIDE.md](SETUP-GUIDE.md) for setup guidance.

## Basic Usage Steps

1. Create a new Project or workspace in ChatGPT, Claude, or a similar AI tool.
2. Paste the prompt from [PROMPT.md](PROMPT.md) as the first message.
3. Upload records into that same Project or workspace.
4. Ask the AI to inventory the uploaded records.
5. Review the output against the original records.
6. Treat all output as a draft evidence inventory, not as advice or a claim recommendation.

## Recommended Records to Upload

Upload only records you are comfortable sharing with the AI platform.

Helpful records may include:

* DD-214 or separation documents
* service dates if DD-214 is unavailable
* military service treatment records / STRs
* separation exam and Report of Medical History, such as DD 2807 / DD 2808 if available
* military personnel records
* deployment records
* Line of Duty determinations
* toxic-exposure records if applicable
* VA Blue Button / My HealtheVet records from VA.gov
* VA treatment records
* private medical records
* specialist records
* imaging reports
* lab reports
* pathology reports
* sleep studies
* EMG/NCS reports
* vascular studies
* pulmonary function tests
* surgical records
* medication lists
* C&P exam reports
* DBQs
* nexus letters
* lay statements or buddy statements
* prior VA rating decisions
* VA decision letters
* VA code sheets
* full C-File if available

## Testing

Use [TEST-PLAN.md](TEST-PLAN.md) to evaluate whether the prompt produces a useful factual inventory, avoids legal and medical conclusions, handles missing or contradictory records, and cites sources clearly enough to verify.

## License

This project is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. You may share and adapt this material for noncommercial purposes, with attribution, as long as adaptations are distributed under the same license. Commercial use is not permitted without separate written permission.

See [LICENSE](LICENSE) for the full license text.
