---
name: medication-safety-nomenclature
description: Automatically applies ISMP Guidelines for Safe Electronic Communication of Medication Information to ensure safe drug name presentation, dose expression, and formatting in all critical pharmacy documents. Use this skill when creating or editing policies, procedures, order sets, medication administration records (MARs), reference documents, protocols, formulary documents, drug monographs, safety alerts, or any document containing medication names, doses, routes, or frequencies. This skill enforces FDA/ISMP tall man lettering, proper dose designations, route/frequency abbreviations, and eliminates dangerous abbreviations.
---

# Medication Safety Nomenclature

This skill ensures all medication-related content follows ISMP Guidelines for Safe Electronic Communication of Medication Information. Apply these rules automatically to all documents containing drug names, doses, or medication orders.

## Core Principles

**Automatic Application**: These rules apply to ALL documents created that contain medication information—no exceptions. Do not ask permission or explain what you're doing; just apply the rules.

**Error Prevention Priority**: When in doubt, choose the safer expression that reduces ambiguity and prevents misinterpretation.

## Drug Name Presentation Rules

### Generic Drug Names

- Use all **lowercase letters** (except when using tall man letters)
- Match FDA-approved nomenclature exactly
- Example: `metformin`, `lisinopril`, `morphine`

### Brand Drug Names  

- Use **uppercase first letter only**, followed by lowercase
- Do NOT use all capitals
- No trademark symbols (®, ™)
- Do not use discontinued brand names
- Example: `Tylenol`, `Zocor`, `Lantus`

### Tall Man Lettering

Apply **bolded UPPERCASE** letters to differentiate look-alike drug name pairs per FDA and ISMP lists. Reference `references/tallman-letters.md` for the complete list.

Critical examples:
- `vinCRIStine` vs `vinBLAStine`
- `HYDROmorphone` vs `morphine`
- `DOBUTamine` vs `DOPamine`
- `glipiZIDE` vs `glyBURIDE`
- `predniSONE` vs `prednisoLONE`
- `metFORMIN`
- `ALPRAZolam` vs `LORazepam`

### Salt Notation

- **Omit salt** unless multiple salts exist or it alters drug release
- When included, use full salt name AFTER drug name
- Approved abbreviations: K, Na, HBr, HCl
- Never use abbreviations at start of name (NOT "Na bicarbonate")
- Example: `metoprolol tartrate`, `metoprolol succinate`

### Drug Name Restrictions

**Never abbreviate drug names**:
- NOT "nitro" (could be nitroglycerin or nitroprusside)
- NOT "KCl" (write `potassium chloride`)
- NOT "MgSO4" (write `magnesium sulfate`)

**Remove numbers from drug names**:
- NOT "5-fluorouracil" → `fluorouracil`
- NOT "6-mercaptopurine" → `mercaptopurine`
- NOT "vitamin B6" → `pyridoxine`
- NOT "vitamin K1" → `phytonadione`

**Keep all elements on one line**:
- `NovoLOG Mix 70/30` (all together, not wrapped)
- Include modifiers: `dilTIAZem 24-hour extended release`

## Dose, Unit, and Direction Rules

### Dosing Units and Measures

**Use metric units only**:
- mg, mcg, g, kg (NOT µg, micrograms)
- mL, L (NOT cc)
- cm (for height)

**Avoid error-prone expressions**:
- NO trailing zeros: `5 mg` NOT "5.0 mg"
- ALWAYS use leading zero: `0.5 mg` NOT ".5 mg"
- NO decimal points with large doses: `500 mg` NOT "0.5 g"

### Route Abbreviations

Use all **UPPERCASE**, no spaces or periods:
- `IV`, `IM`, `SUBQ`, `PO`
- NOT "i.v." or "I.V." or "iv"

### Frequency Abbreviations

**Standard frequencies** - all uppercase:
- `BID`, `TID`, `QID`, `QHS`

**Time-based frequencies** - lowercase "q" and "h":
- `q4h`, `q6h`, `q12h`, `q5min`
- NO spaces, NO periods

### Prohibited Abbreviations

**Never use these dangerous abbreviations**:
- NOT "U" or "u" → write `units`
- NOT "IU" → write `units` or `international units`
- NOT "QD" or "qd" → write `daily`
- NOT "QOD" → write `every other day`
- NOT "MS" or "MSO4" → write `morphine sulfate`
- NOT "MgSO4" → write `magnesium sulfate`
- NOT "@" → write `at`
- NOT ">" or "<" → write `greater than` or `less than`
- NOT drug name + dose ("MTX10") → write `methotrexate 10 mg`

## Complete Order Expression

### Required Components

Every medication order/prescription must include:
1. Drug name (generic, and brand if prescribed)
2. Strength/concentration  
3. Dose (patient-specific)
4. Dosage form
5. Route of administration
6. Frequency
7. Purpose/indication

### Dose by Volume Restriction

**Never prescribe by volume alone** (except specific exceptions):
- NOT "acetaminophen 10 mL PO" → `acetaminophen 160 mg/5 mL, give 10 mL (320 mg) PO`
- Exceptions: vaccines, eye/ear drops, creams/ointments, liquid multivitamins, mineral oil

### Special Presentations

**Insulin on MAR**:
- Regular insulin U-500: `HumuLIN R (U-500) 60 units`
- All other concentrations: `HumuLIN R 20 units (U-100)`
- NOT "HumuLIN R U-100 20 units"

**Weight-based dosing**:
- Include both formula and calculated total dose
- Example: `vancomycin 15 mg/kg = 1,200 mg IV`

**Modified-release formulations**:
- Express release property unambiguously
- Example: `dilTIAZem 24-hour extended release (Cartia XT) 180 mg capsule`

## Protocol and Regimen References

When using chemotherapy regimens or protocol acronyms:
- Define the acronym at least once in the document
- Example: "FOLFOX (fluorouracil, leucovorin, oxaliplatin)"

## Warning Statements

Use **active voice with affirmative statements**:
- `IV use only` NOT "Not for intrathecal use"
- `For external use only` NOT "Do not swallow"
- `Single-dose vial` NOT "Contains no preservative"

## Application Workflow

When creating any document:

1. **Scan for medication content** - Check if document contains drug names, doses, routes, frequencies
2. **Apply drug name rules** - Correct capitalization, add tall man letters, remove abbreviations
3. **Apply dose/unit rules** - Fix trailing zeros, add leading zeros, expand units
4. **Apply route/frequency rules** - Standardize abbreviations, remove prohibited terms
5. **Verify completeness** - Ensure orders have all required components

**Make corrections silently** - Do not explain what you're correcting or why unless explicitly asked.

## Common Corrections

| Instead of | Use |
|------------|-----|
| Lasix 40mg po qd | furosemide 40 mg PO daily |
| Heparin 5000U SC BID | heparin 5,000 units SUBQ BID |
| Insulin Regular U-100 10u | HumuLIN R 10 units (U-100) |
| KCl 20mEq po bid | potassium chloride 20 mEq PO BID |
| .5mg Xanax | ALPRAZolam 0.5 mg |
| MS 2mg IVP q4h prn | morphine sulfate 2 mg IV q4h PRN |
| Digoxin 0.125mg | digoxin 125 mcg |
