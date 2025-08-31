# Healthcare as a Point of Sale System
*August 31, 2025*

## Hospital-Centric Flow (Reordered System)
**Patient → Hospital**  
Patient shows up, gives ID + insurance info. That’s it. No billing, no co-pays, no insurer interaction.  

**Hospital → Insurer**  
Hospital codes the visit, generates claim, and sends it directly to insurer.  
Hospital handles: eligibility check, pre-authorization, claim submission, adjudication, appeal or resubmission if denied.  

**Insurer → Hospital**  
Insurer pays the hospital directly after adjudication. Settlement can be immediate or batch (daily/weekly).  

**Hospital → Patient (only if balance remains)**  
If deductible or coinsurance applies, hospital sends a simple post-visit bill. Patient pays hospital directly.  

## Core Change
Traditional order:  
Patient → Hospital → Insurer → Patient (EOB) → Patient (Bill) → Patient ↔ Insurer (Appeals)  

Redesigned order:  
Patient → Hospital → Insurer → Hospital → Patient (if balance)  

## Difference
Patient no longer acts as intermediary.  
Insurance interaction collapsed into direct hospital–insurer channel.  
Patient only touches the system twice: at intake and at final payment.  

## Benefits
Removes patient from backend  
Faster hospital payments (merchant-style)  
Appeals handled institutionally  
Patients see only one bill
