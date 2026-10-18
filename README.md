# Naija Eye Tracker — Referral & Follow-up System for Low-Resource Eye Care

> Preventing avoidable blindness by tracking patients who get lost after referral.

### Live Project: github.com/NaijaEyeNurse/naija-eye-tracker

---

#### 1. The Problem I Saw As An Ophthalmic Nurse

In Nigeria, patients don't go blind because there is no treatment. They go blind because they get lost between primary clinic and hospital.

- **2 Division Hospital Eye Clinic, Ibadan:** 80+ patients/month present late, already blind in one eye. Diagnosis was possible months earlier.
- **Boripe PHC Outreach, Nov 2025:** We screened 400 people. 72 needed urgent referral to LUTH. Only 31 arrived. 41 lost. No system to trace them.
- **Shao Outreach, June 2026:** 350 screened, 89 referred. 45% could not be contacted after 2 weeks.

Current system: paper register. No follow-up. No accountability.

This is personal. My father lost vision from diabetic retinopathy due to late referral.

#### 2. What I Am Building

A simple, offline-first tool for primary care nurses to:

1.  Register screening: de-identified ID, age group, village, visual acuity, WHO red flags
2.  Generate referral slip to secondary facility
3.  Track status: Referred -> Contacted -> Attended -> Completed / Lost to follow-up
4.  Dashboard: List of patients who need a follow-up call today

**What this is NOT:** It does NOT diagnose disease. It supports the nurse to follow WHO Primary Eye Care referral protocol and to not lose patients.

#### 3. Tech Approach (Learning)

- **Standard:** FHIR R4 (Patient, Encounter, ServiceRequest, Task)
- **Stack:** Python, FastAPI, PostgreSQL, Streamlit for demo
- **Principles:** Minimal data, de-identified, consent for follow-up, purpose limitation (GDPR)

This is a prototype, not a certified medical device.

#### 4. My Background
Nursing Officer (Ward Leader), Ophthalmic Nurse, BNSc Nursing, LAUTECH.
300+ bed hospital, eye ward leadership, community eye outreaches.

Applicant — Global Master's in Health Informatics, Karolinska Institutet, Sweden. 2026.

Goal: Learn interoperability, clinical decision support, and ethical implementation of eHealth to adapt for low-resource settings like Nigeria.

#### 5. Roadmap

- [x] Phase 0: Problem documentation & data model (Current)
- [ ] Phase 1: Build paper-to-digital tracker with 50 test patients (Streamlit)
- [ ] Phase 2: Map to FHIR, add follow-up reminder logic
- [ ] Phase 3: At KI — Predict risk of loss to follow-up (not disease)

#### 6. Contact & Collaboration

Open to collaboration with eHealth students and primary care nurses.
Email: gabrielfestus@gmail.com 
Whatsapp: +2347068036236

---
*Built by a nurse, for nurses, to keep patients in care.*