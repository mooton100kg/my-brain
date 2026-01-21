---
File:
  - https://www.icloud.com/iclouddrive/03dYSU4a7_KrWw0DGNv4KHxHg#CKD1
  - https://www.icloud.com/iclouddrive/0c6BCjIkO6Kaj3laZFPQZSFVg#CKD
---

# Criteria of CKD
- Abnormal of function <span class='hl3'>or</span> structure <span class='hl1'>> 3mo</span>
## Function
- GFR < 60
## Structure (≥ 1)
- Albuminuria > 30
- Urinary sediment abnormality
- Electrolyte abnormalities due to tubular disorder
- Histological abnormality
- Imaging
- Kidney transplantation
# Urine screening
![[Pasted image 20251107235602.png]]
# Staging of CKD #Elderly/imo
![[Pasted image 20251024065006.png|500]]
![[Pasted image 20251107235636.png]]
# Risk factor of CKD
- DM
- HT
- > 60 yr
- Autoimmune
- Systemic infection
- CVD
- Hx of AKI
- Nephrolithiasis
- Single kidney
- Recurrent UTI
- Drugs = NSAIDs, herb, CMT, contrast
- Renal cyst > 3
- Fm Hx of CKD
# Common cause of CKD
1. <span class='hl1'>DM</span> 
2. HT
3. Chronic tubular-interstitial nephritis
# S/S
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Asymptomatic', 'Edema', 'Uremic enceph'],
	['', 'Dyspnea', ''],
	['', 'Anemia', ''],
	['', 'HypoNa, HyperK, HyperPhos, Met acido', ''],
	['', 'Vit-D def', ''],
	['', 'HyperPTH (remal osteodystrophy)', ''],
];

const header = ['Stage 1-3', 'Stage 4-5', 'ESRD']
// @no-refresh
dv.table(header, data);
dv.container.classList.add('top');
```
# Investigation
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['U/S KUB', 'Kidney size ≤ 8cm <span class="h3">(ไม่จำเป็นเสมอไป)</span>'],
	['', 'Thin cortex < 1cm'],
	['', 'Increased echogenicity = ไตขวาตับ'],
	['BUN, Cr', ''],
	['CBC', 'NCNC anemia'],
	['PTH', 'HyperPTH (renal osteodystrophy)'],
	['UA', 'Broad waxy cast'],
];

const header = ['Investigation', 'Finding']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'side');
```
> [!tip] Large to normal CKD kidney size
> - HIV nephropathy
> - Infiltrative dz = amyloidosis, sarcoidosis, lymphoma, myeloma
> - DN (early)
> - Tubulo-interstitial nephritis (early)
> - ADPKD
# Management
- ประเมิน eGFR อย่างน้อยปีละครั้ง
-  ± Serum cystatin C ถ้าทำได้ใน CKD stage 3

## 1. Lifestyle modofication
- Energy 30-35 kcal/kg
- <span class='hl1'>Protein 0.6-0.8 g/kg</span>
- <span class='hl1'> Na &lt; 2g</span>
	- เกลือ 1 ช้อนชา
	- NaCl 5g
	- น้ำปลา 2 ช้องโต๊ะ
- K < 2g
	- ผักสีเขียว = high K
- PO4 < 800-1000 mg
- Mod intensity exercise 150 min/wk
- Stop smoking
- BMI 18-23
## 2. Drug therapy 1st line
### SGLT2i
- Goal
	- A1c 6.5-8%
	- FBG 80-130
- <span class='hl2'>In CKD</span>
	- Not initiate = GFR < 20
	- Stop = HD

> [!tip] ยา DM ที่ไม่ต้องปรับตามไต
> DPP4i = linagliptin, genigliptin

### Metformin
- <span class='hl2'>In CKD</span>
	- Reduce dose > 1000mg/d = GFR < 45
	- Stop = GFR < 30
### RASi = ACEi / ARB
- Monitor <span class='hl3'>Cr & K</span> after start 2-4 wk
	- Normokalemia + Cr ↑ < 30%
- Indication
	- DM = G1-4, A2 ขึ้นไป
	- Non-DM = G1-4, A3
- Goal 
	- UACR ≥ 300 (macroalbuminuria) = 120-130 / 70-79 
	- UACR < 300 = 130-139 / 70-79
- <span class='hl2'>In CKD</span>
	- Cr ↑ > 30% = ดูสาเหตุอื่นของ AKI + ดู renal artery stenosis
		- Cr ↑ 30-50% = reduce dose 50%
		- Cr ↑ > 50% = off
	- Hyper K = ทบทวนยาอื่นที่ให้ + เลี่ยงอาหารที่มี K สูง → หยุดยา
	- หยุดยาเลยในกรณี
		- Symptomatic hypotension
		- Refractory hyperkalemia
		- Reduce uremic symptom in eGFR < 15
	![[IMG_4812.png]]

### Statin
- ไม่จำเป็นต้องเป็น DLP
- Goal
	- LDL < 70
- <span class='hl2'>In CKD</span>
	- ESRD on HD = continue but dont start statin / ezetimibe

# <span class='hl1'>CKD complication</span> #Elderly/imo
- Renal anemia 
	- Mechanism 
		- ↓ EPO
		- ↑ Hepcidin = ↓ absorption
	- Mx = ESA
	- Goal = Hb 10-12
- CKD-MBD
	- Phos retension + Calcitriol def = 2nd hyperPTH
- Metabolic acidosis
	- Goal = HCO3 24-26 if AKI keep > 15
	- Mx = NaHCO3
- AKI ontop
	- Prevention
		- eGFR < 60 = avoid NSAIDs, herb, aminoglycoside
		- eGFR < 45 = avoid contrast
# Dialysis
- Indication
	- eGFR ≤ 6
	- CKD5 + eGFR > 6 + complication
		- HF, hypertension
		- HyperCa, metabolic acidosis, hyperPhos
		- AOC, seizure
		- Pericarditis, pleuritis
		- N/V, weight loss, malnutrition
# Contrast media
- Isotonic fluid prophylaxis = 0.9 NSS
	- Dosage (ปกติให้ไปเลย 24hr เเต่ดู volume status ด้วย)
		- Before 1hr = 3ml/kg/hr 
		- After 3-12hr = 1ml/kg/hr
	- Indication
		- AKI
		- eGFR < 30
		- eGFR 30-44 with risk factor (DM, HT, recent AKI)
		- HS with RRF > 100ml
- Hold medication
	- Duration = 24-48hr before / 48hr after
	- NSAID, diuretic, aminoglycoside, aphotericin, metformin