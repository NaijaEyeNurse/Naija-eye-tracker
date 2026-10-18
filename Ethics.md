# Ethics, Privacy & Safety — Naija Eye Tracker

This project deals with sensitive health data. Ethics is not optional.

### 1. Core Principle
This system supports referral tracking. It does NOT provide diagnosis, treatment advice, or replace clinical judgment. Final decision is always by qualified health worker following WHO Primary Eye Care manual.

### 2. Consent
- All patients screened during outreaches (Boripe, Shao) gave verbal consent for screening and for follow-up contact.
- For this prototype, no real patient names, phone numbers, or addresses are uploaded to GitHub.
- All data in this repository is synthetic / de-identified: e.g., BORIPE-001, Age group 50-60.

### 3. De-identification
- No direct identifiers: No name, no full date of birth, no phone number, no national ID.
- Patient ID is coded: SITE-YEAR-NUMBER (e.g., SHAO-2026-089)
- Village name is kept at community level only, not house address.
- Visual acuity is stored as category, not linked to image.

### 4. Data Minimization & GDPR Alignment
Even though data was collected in Nigeria, I build to Swedish/EU standard:
- Collect only what is needed for follow-up: ID, age group, VA, red flag, referral status, number of contact attempts.
- Purpose limitation: Data is only for ensuring patient completes referral.
- Storage: Original paper registers remain locked in facility. Digital prototype is local-only, not on cloud.
- Retention: Referral records kept for 6 months after completion, then archived.

### 5. Safety Measures
- No automated SMS yet — to avoid wrong number contact. Only log "Call due".
- Dashboard flags: If patient not contacted in 14 days, alert nurse.
- No AI model in Phase 1 & 2. No claim of accuracy.

### 6. Future Plan (At Karolinska Institutet)
- Formal ethical review for any use of real-world data.
- Seek approval from Oyo State Ministry of Health for expanded pilot.
- If AI is added in Phase 3, it will predict risk of Loss-to-Follow-Up, NOT disease. This avoids diagnostic regulation and reduces harm.

### 7. Disclaimer
This is a student learning project. Not a certified medical device under Swedish MPA or Nigerian NAFDAC. Do not use for real patient care without validation and approval.

---
*Author: Oladipupo D., Ophthalmic Nurse, RN, BNSc.*
*Contact: [add email]*
*Date: October 2026*