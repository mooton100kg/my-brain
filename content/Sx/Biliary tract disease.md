---
File:
  - https://www.icloud.com/iclouddrive/01aKbem-7NZMXY650w819p8Bg#Biliary_tract_disease_GALLSTONE_DISEASE_1
  - https://www.icloud.com/iclouddrive/0c9uJPrSoJLnAmjIOtwoKE7hw#Biliary_tract_disease_CBD_STONE__CHOLANGITIS_2
  - https://www.icloud.com/iclouddrive/007EuTLjkW1eiPdg5PASGMTbg#Biliary_tract_disease_MALIGNANT_CONDITIONS_3
---

![[Pasted image 20251103003216.png|300]]![[Pasted image 20251103003251.png|250]]
# Gall stone disease
## Asymptomatic gallstone
### Investigation
- U/S = GS with posterior acoustic shadowing
	![[Pasted image 20251103004039.png|200]]
### Management
- Expectant & reassure
- Prophylactic Sx
	- Absolute indication = risk of GB cancer
		- GB polyp > 1cm
		- GS > 3cm
		- Porcelain GB = หินปูนไปจับอยู่บนผนัง GB
			![[Screenshot 2568-11-03 at 00.37.19.png|150]]
	- Relative indication = hemolytic disease / cant assess to hospital
		- Hereditary spherocytetosis
		- Sickle cell anemia
		- Thalassemia
## Symptomatic gallstone
- Cause = transient cystic duct obstruction
### S/S
- Onset / duration = acute 1-5hr
- Biliary colic
	- Dullness steady pain at RUQ = ปวดเเบบจุกๆ เเน่นๆ
	- Associate with meal 
	- Radiate to right shoulder / scapula
	- No peritonitis
### DDx
- GERD
- Ruptured AAA
- Gastric, pancreatic, duodenal, colon cancer
### Management
- Elective cholecystectomy
- Avoid อาหารมัน อาหารมื้อใหญ่ ระหว่างรอผ่า
## Acute cholecystitis
- Cause
	- Calculous = cystic duct obstruction → GB inflammation
		- SIRS
		- GB distension
		- GB wall edema
	- Acalculous = severe stressed → microvascular occlusion → GB inflammation
		- Critically ill patient
		- Burn
		- Major operation
### S/S
- Biliary colic > 12hr
- RUQ peritonitis 
	- Murphy's sign = วางมือตรง RUQ ตอนหายใจเข้าจะเจ็บเเล้วหยุดหายใจ 
	- Guaring
	- ± GB mass
- Fever, leukocytosis
### Investigation
- U/S
	- Pericholecystic fluid
	- GB wall ≥ 5mm
	- Sonographic murphy
	![[Pasted image 20251103010117.png|200]]
### Criteria diagnosis (Tokyo 2018)
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	["Murphy's sign", 'Fever', 'Pericholecystic fluid'],
	['RUQ mass/pain/tenderness', 'CRP ≥ 1', 'GB wall ≥ 5mm'],
	['', 'WBC < 4,000 or > 10,000', 'Sonographic murphy'],
];

const header = ['A:<br>local inflammation', 'B:<br>systemic signs of inflammation', 'C:<br>imaging']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'center', 'spread');
```
- Suspected = 1A + 1B
- Definite = 1A + 1B + 1C
### Management
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Grading', 'Dose not meet other criteria', 'Associated with any one<br>1. WBC > 18,000<br>2. Palpable RUQ tender mass<br>3. &gt; 72hr<br>4. Marked local inflammation', 'Associated with organ dysfunction'],
	['ATB' ,'O', 'O', 'O'],
	['Sx', 'Urgent cholecystectomy ≤ 96hr', 'Urgent cholecystectomy ≤ 96hr', 'Cholecystostomy (GB drainage)'],
];

const header = ['', 'Grade 1', 'Grade 2', 'Grade 3']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'side','spread');
```
* ATB ดูตาม biliary tract infection
#### Cholecystectomy
- Laparoscopic cholecystectomy (LC)
- Open cholecystectomy (OC)
![[Pasted image 20251103011112.png|300]]
#### Cholecystostomy

![[Pasted image 20251103011051.png|200]]
## Mirizzi's syndrome
- Cause = obstruction of CHD 2º to impacted GS in cystic duct
	![[Pasted image 20251103011238.png|200]]

### S/S
- Obstructive jaundice
- Biliary colic
# Common bile duct stone
- Primary CBDS (20%) = เกิดจาก bile duct
- Secondary CBDS (80%) = มาจาก GS
## S/S
- Biliary colic + jaundice
- Cholangitis

> [!tip] CBDS vs Tumor
> CBDS = intermittent painful jaundice
> Tumor = progressive painless jaundice

## Investigation
- U/S = บางที่จะไม่เห็น CBDS เพราะ duodenal บัง
- CT scan = มอง <span class='hl2'>non-opaque</span> CBDS & GS ไม่เห็น เเต่ใช้ดีใน malignancy
- MRCP = **gold standard**
### U/S interpretation
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Normal', 'x', 'x', 'x', 'x'],
	['CBDS', 'o', 'o', 'o', 'o'],
	['± CBDS', 'o', 'x', 'o', 'o'],
	['± CBDS ± Tumor', 'x', 'x', 'o', 'o'],
	
];

const header = ['Cause of obs', 'GS', 'CBDS', 'Dilated bile duct', 'Obs jaundice']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'side', 'center');
```
## Management
- Asymp ก็ต้อง treat
- CBDS removal + cholecystectomy (in 2º CBDS)
	- 1st option = ERCP + LC
	- 2nd option = CBDE + OC + T-tube insertion
		![[Pasted image 20251103014256.png|200]]
# Cholangitis
- Cause = CBDS + infection
## S/S
- Reynold's pentad = severe cholangitis
	- Hypotension
	- AOC
	- Charcot's triad
		- Jaundice
		- RUQ pain (no murphy)
		- Fever
## Criteria diagnosis (Tokyo 2018)
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	["Fever / shaking chill", 'Tb ≥ 2', 'Biliary dilation'],
	['Evidence of inflammatory response<br>   WBC < 4,000 or > 10,000<br>   CRP ≥ 1', 'Abnormal LFT<br>ALP / GGT / AST / ALT > 1.5x UNL', 'Evidence of etiology<br>Stricture, stone, stent'],
];

const header = ['A:<br>systemic inflammation', 'B:<br>cholestasis', 'C:<br>imaging']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'center', 'spread');
```
- Suspected = 1A + 1B <span class='hl3'>or</span> 1C
- Definite = 1A + 1B + 1C
## Management
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Grading', 'Dose not meet other criteria', 'Associated with any two<br>1. WBC > 18,000 or < 4,000<br>2. T ≥ 39ºC<br>3. Tb ≥ 5<br>4. Alb < 0.7x LNL', 'Associated with organ dysfunction'],
	['ATB' ,'O', 'O', 'O'],
	['Sx', 'CBDS removal or biliary drainage (tumor)', 'CBDS removal or biliary drainage (tumor)', 'Urgent biliary drainage<br>± CBDS removal when stable'],
];

const header = ['', 'Grade 1', 'Grade 2', 'Grade 3']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'side','spread');
```
- Infection = ATB
- Obstruction
	- Biliary drainage = ERCP with stent insertion
	- CBDS removal 
		- 1st option = ERCP + LC
		- 2nd option = CBDE + OC
# Malignant condition
## Cholangiocarcinoma
- Origin = bile duct epithelium
- Risk factor
	- Liver fluke
	- Sclerosing cholangitis
	- Choledochal cyst
	- Hepatolithiasis
### Classification
- Intrahepatic CCA = อยู่ในตับ
- Perihilar CCA / Klaskin's tumor
- Distal CCA = ใต้ต่อ cystic duct
### S/S
- Intrahepatic CCA = abd pain, weight loss
- Perihilar CCA = obs jaundice
- Distal CCA = obs jaundice
### Management
- Curative 
	- Intrahepatic CCS = hepatectomy
	- Perihilar CCS = hepatectomy + bile duct resection
	- Distal CCA = pancreatoduodenectomy (whipple's operation)
- Palliative = biliary drainage
	- Internal drainage = ERCP with sten insertion
	- External drainage = PTBC (percutaneous transhepatic biliary drainage)
## Periampullary CA
### S/S
- Distal CCA = obs jaundice
- CA ampullar = obs jaundice + UGIB
- CA **head** of pancreas = obs jaundice + gastric outlet obstruction
- CA duodenum = obs jaundice + gastric outlet obstruction
### Management
- Pancreatoduodenectomy (whipple's operation)
	![[Pasted image 20251103020908.png|300]]
### Courvoisier's law #imo

> If pt. present wiht **jaundice + palpable GB**, the jaundice is unlikely to be due to **stone**

- เพราะว่า GS ส่วนใหญ่จะเกิดมานานจนมี fibrosis tissue ทำให้คลำไม่ได้ เเต่ tumor ทำให้เกิด complete obs ทำให้ GB โต
- Cause = periampullary CA
	- เเต่ intrahepatic & perihilar CA เกิดไม่ได้ เพราะอยู่ก่อน GB