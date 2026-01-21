- Hematuria = RBC ≥3 cell/HPF
- Classification
	- Gross haematuria (macrosopic / visible) = ฉี่เป็นสีเเดง
	- Microscopic haematuria (non-visible) = dipstick positive
![[Screenshot 2568-11-25 at 00.37.38.png]]![[Screenshot 2568-11-25 at 00.38.15.png]]

# Cause
- UTI = most common cause
- Renal, bladder, prostate cancer
- BPH
- Renal calculi
- Trauma
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['0-20', 'Acute glomerulonephritis<br>Acute UTI<br>Congenital tract anomaly with obstruction'],
	['20-40', 'Acute UTI<br>Stones<br>Bladder tumor'],
	['40-60', 'Bladder tumor<br>Stones<br>Acute UTI', 'Acute UTI<br>Stones<br>Bladder tumor'],
	['&gl;60', 'BPH<br>Bladder tumor<br>UIT', 'Bladder tumor<br>UTI'],
];

const header = ['Yr', 'Male', 'Female']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'side', 'center', 'middle');
```

> [!tip] Pseudohematuria
>- Definition = สีเเดงไม่ได้เกิดจาก RBC
>- Cause
>	- Rifampicin, methyldopa
>	- Hyperbilirubinuria, myoglobinuria
>	- Beetroot, rhubarb
# Clinical feature
## Ddx
- Vaginal bleed
- Trauma
- UTI
## History
- Timing
	- Initial haematuria = urethra
	- Total haematuria (เป็นสีเเดงทั้งลำ) = bladder, upper tract
	- Terminal haematuria (เป็นสีเเดงต้องท้าย) = bladder neck, prostatic urethra (จากการพยายามเบ่งฉี่)
- Associated symptom
	- UTI
	- Fever
	- Suprapubic pain, flank pain
	- Weight loss
	- Recent trauma
- Smoking, medication
- Clot 
	- เป็นเส้น = upper tract
	- เป็นก้อนกลม = lower tract
## Physical examination
- Abdominal exam
- DRE
## Investigation
- UA + dipstick
- CBC, Coag
- ± PSA
- Cr, BUN
### <span class='hl1'>Microscopic haematuria</span> #imo
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Female', '< 60' ,'≥ 60', ''],
	['Male', '< 40', '40-59', '≥ 60'], 
	['Pack-year', '< 10', '10-30', '≥ 30'], 
	['RBC UA', '3-10', '11-25', '&gt; 25'],
	['Tx', 'Repeat UA 6mo', 'Cystoscop / US', 'Cystoscopy / CT / US'],
];

const header = ['Criteria', 'Low risk (3%)', 'Intermediate risk (5%)', 'High risk (10%)']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'side', 'center');
```
- Additional risk = high risk
	- Lynch syndrome = CA colon, endometrium
	- Hx of urothelial cancer
	- Hx of gross hematuria
	- Occupational risk (aromatic amine) = สิ่งทอ สีย้อม
	- Chronic foley cath

> [!tip] When to refer to nephro
> - ≥ 45 yo w/
> 	- Unexplained gross haematuria w/o UTI
> 	- Gross haematuria after succesful treatment of UTI
> - ≥ 60 yo w/ unexplained microscopic haematuria ± dysuria/leukocytosis

### Specialist investigation
- Lower tract = cystoscope
- Upper tract 
	- U/S
	- CT urogram <span class='hl2'>(the best)</span> = contrast ทำลายไต
	- MRI = ใช้ใน pregnancy / child เเต่มีโอกาสเกิด systemic nephrogenic fibrosis
# Management
- Treat underlying pathology
- <span class='hl1'>Clot retension</span> = clot obs bladder outflow → acute urinary retention 
	- <span class='hl1'>Insert three-way cath for washout & irrigation </span>