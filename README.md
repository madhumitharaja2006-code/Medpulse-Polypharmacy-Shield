Project Description:

Elderly patients managing chronic illnesses (e.g., Chronic Kidney Disease, Hypertensive Heart Disease) frequently visit multiple specialists across different healthcare tiers—from Tier-1 corporate hospitals with digital records to rural Tier-3 clinics relying on cursive handwritten prescriptions. This fragmentation leads to polypharmacy blindspots: fatal drug-drug interactions (e.g., ACE inhibitors + Potassium-sparing diuretics) and accidental double-dosing (taking the same generic salt under two different brand names). Furthermore, standard AI prescription scanners fail because doctors' cursive handwriting is notoriously illegible, leading to dangerous AI hallucinations.

MedPulse is a mobile-first, multilingual healthcare application designed strictly for the elderly. It acts as a safety bridge between all treating physicians, acting as a real-time AI pharmacist that cross-checks every newly prescribed medication against the patient's existing regimen, ensuring 100% medication safety before a single pill is swallowed.


Proposed Solution:

MedPulse solves the polypharmacy crisis through a blend of hyper-accessible Elderly UI, ABDM (Ayushman Bharat Digital Mission) identity syncing, and a novel 2-Step AI Vision architecture.

Key Technical & UX Innovations:

The 2-Step Dual Camera Verifier (Addressing Innovation & Technical AI Implementation): To combat messy doctor handwriting, MedPulse uses a two-stage vision engine.
Step 1: The AI scans the handwritten prescription to form a "Preliminary Estimate".
Step 2: The patient scans the physical pharmacy blister strip. The AI matches the dispensed drug against the prescription to guarantee 100% accuracy.

Multi-Tablet Equivalence Engine: If a doctor prescribes 150mg, but the pharmacy only stocks 75mg strips, MedPulse's AI calculates the equivalence when the patient scans two 75mg strips, verifying the dosage is correct.

Visual Pill Checklist & Tap-to-Lock: To prevent accidental double-dosing, the daily schedule displays the exact color/visual thumbnail of the scanned blister strip. Tapping the pill locks the UI for that time window (Morning/Lunch/Night).

AI Auto-Quarantine & Caregiver WhatsApp Alerts: If a life-threatening interaction is detected (e.g., NSAIDs colliding with CKD meds), MedPulse quarantines the pill, overlays a global red alert, triggers a Web Audio API silent-mode override siren, and dispatches a WhatsApp alert to the primary caregiver.

Smart Follow-Up Engine: The app scrapes specialist hospital portals for wait times. If a doctor has a 30-day waitlist, the calendar automatically blocks out the next 29 days in Red, marks day 30 in Blue, and triggers proactive booking reminders.

Doctor's Unified QR Portal: Any consulting doctor can scan the patient's MedPulse QR code to instantly access a unified dashboard containing reconciled chemical salt constituents, forensic overdose alerts, lab trends (eGFR, Potassium), and interactive PACS-style DICOM viewers for X-Rays and MRIs.
