---
File:
  - https://www.icloud.com/iclouddrive/05eJSJ0d1kEj_RC9YSv2TJt1A#Geriatric_Rheumatology
---
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Acute', 'Gout, CPPD, septic arthritis', 'Gonococcal, SLE, RA'],
	['Chronic' ,'TB, OA', 'SLE, OA'],
];

const header = ['', 'Mono-articular', 'Oligo/Poly-articular']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top",'side', 'center');
```
# Synovial fluid analysis
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Appearance', 'Clear yellow', 'Slightly turbid', 'Slightly turbid', 'Turbid'],
	['WBC', '0-200', '200-2000', '2000-50000', '&gt;50000'],
	['PMN', '&lt;10', '&lt;20', '20&minus;75', '&gt;75'],
];

const header = ['', 'Normal', 'OA', 'Crystal', 'Septic']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top",'side','center');
```

> [!tip] Gonococcal
> โอกาส G/S & C/S เเล้วขึ้นจาก synovial fluid น้อย ควรเก็บจาก GU ดีที่สุด


> [!tip] Gout
> Trigger by furosemide

# X-ray
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Gout', 'Punch-out erosion'],
	['CPPD' ,'Chondrocalcinosis'],
	['RA' ,'Peri-articular osteopenia<br>Marginal erosion'],
	['OA', 'Central erosion with gull winging<br>Joint space narrowing<br>Osteophytes'],	
];

const header = []
// @no-refresh
dv.table(header, data);
dv.container.classList.add("side");
```

# Gout
- Onset 
	- Male 40-50yr
	- Female > 60yr
- Location
	- 1st MTP
	- Ankle
	- Knee
- Gout = punch-out erosion
- Pseudogout = chondrocalcinosis
## Management
- Initial
	- Colchicine (0.6) 2 stat
		- S/E = diarrhea
	- NSAID
		- Option
			- Indomethacin (25) 2x3 > 2x2 > 1x3
			- Naproxen (250) 2x2
		- Avoid in elderly
	- Steroid
		- Option
			- Prednisolone 0.5 mg/kg/d x 2-5d 
				- S/E = hyperglycemia, infection, osteoporosis, hypertension, edema
- Long-term (uric acid < 6mg/dl)
	- Indication
		- Tophi
		- Radiographic
		- Frequently flares ≥ 2/yr
	- Xanthine oxidase inhibitor
		- Option
			- Allopurinol = HLA-B5801
			- Febuxostat
	- Uricosuric agent
		- Option
			- Probenecid
		- ใช้ใน
			- No renal stone
			- Normal renal function
			- Able to drink water 2-3 L/d
# Rhematoid arthritis
- Location = symmetrical + small joint of hand & feet
- Investigation
	- Anti-CCP
	- ESR, CRP
- X-ray
	- Peri-articular osteopenia
	- Marginal erosion
	- Joint space narrowing
## Management
- NSAIDs
- Steroid
- DMARDs = MTX
# Giant cell arteritis
- S/S
	- Cranial symptom = temporal headache, blindness
	- Polymyalgia rheymatica = pain around hip / shoulder girdle
	- Constitutional symptom
	- Large vessel involvement
- Investigation
	- CBC, ESR, CRP
	- Temporal artery Bx
## Management
- Prednisolone 1mg/kg/d
- MTX