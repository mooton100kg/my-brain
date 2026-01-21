---
File:
  - https://youtu.be/Igb1rta3-c4?si=3J7PoifXBs5YPWsY
  - https://youtu.be/H-nGqfr5fas?si=VEKYvJaAJUU3JddK
Ref: "[[Ascites]]"
---
# Pathogenesis
- Intestinal bacteria → portal circulation → ascitic fluid
- มักเจอใน cirrhosis
	- มี bacterial overgrowth
	- Portal hypertension → ↑ intestinal permeability
	- Acquired immune def
- <span class='hl1'>Risk factor</span>
	- Low total protein in ascitic fluid (< 1.5)
	- Varices
	- Advanced cirrhosis (Child-Pugh C)
	- Hx of SBP
	- UTI
	- Intestinal bacterial overgrowth
	- Malnutrition
	- PPI
- Pathogen
	- E. Coli
	- ยกเว้น neohrotic จะเจอเป็น S. Pneumo
# S/S <span class='hl1'>(FBI)</span>
- <span class='hl1'>F</span>ever
- <span class='hl1'>B</span>elly pain = diffuse abdominal pain
- <span class='hl1'>I</span>ncreasing ascites
- Diarrhea = sign of bacterial overgrowth
- Cirrhosis syndrome
	- **A**ltered mental state = hepatic enceph
	- **B**leeding = varices
	- **C**olor = jaundice
	- **D**istension = ascites
# Investigation
- CBC, LFT
- Blood culture
- U/S, CT
- Paracentesis
## Diagnosis (paracentesis)
- Color
	- Hazy
	- Cloudy
- Cell count
	- PMN > 250
- Cell culture 
	- Single organism
- Low SAAG high protein
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["List", ul(['1', '2'])]
]; */

const ul = items =>
  `<ul>${items.map(i => `<li>${i}</li>`).join("")}</ul>`;

const data = [
	['NMBA', '< 250', 'เจอ', 'Opsonization จัดการเองได้ ไม่ต้องเรียก PMN'],
	['CNNA', '≥ 250', 'ไม่เจอ', 'Neutrophil สู้ชนะ'],
	['SBP', '≥ 250', 'เจอ', 'Neutrophil สู้เเพ้'],
	['Polymicrobial NMBA', '< 250', '+<br>&gt;1 organism', 'Mild bowel perforate'],
	['2º peritonitis', '≥ 250', '+<br>&lt;1 organism', 'Severe bowel perforate'],
];

const header = ['', 'PMN', 'Bacteria', '']
// @no-refresh
dv.table(header, data);
dv.container.classList.add('top', 'side', 'middle');
```
# Management
- IV albumin 20%
- ATB + repeat tap 48hr 
	- Goal = PMN ↓ ≥ 25%
	- If PMN ↓ < 25%
		- Bowel perforate → CT
		- เชื้อไม่ตรงยา
	![[image-20.png]]
- Lactulose if hepatic enceph

> [!info] 
> - Uncomplicated SBP = community acquired SBP without shock, ileus, GIB, hepatic enceph, Cr > 3
> - High risk SBP = advanced liver, renal failure (Cr > 1, BUN > 30, Tb > 4)
