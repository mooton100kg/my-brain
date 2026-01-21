# Cause
## Mechanical
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Stomach', 'Volvulus<br>Hiatal hernia<br>Mass compression<br>Pancreatic pseudocyst', '<span class="hl1">Cancer</span><br>Benign PU<br>Corrosive injury<br>FB<br>Polyp'],
	['Small bowel', '<span class="hl1">Adhesion (1)</span><br><span class="hl1">Internal hernia</span><br>Carcinomatosis<br>Malrotation', 'Cancer<br>Polyp<br>Harmatoma<br>FB'],
	['Large bowel', 'Volvulus (2)', '<span class="hl1">Cancer (1)</span><br>Diverticulitis<br>Radiation'],
];

const header = ['Organ', 'Extraluminal', 'Intraluminal']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'side', 'center', 'middle');
```
- Simple = ตันด้านเดียว
- Closed-loop = ตันทั้ง proximal & distal
	- ที่ ileocecaecal ทะลุก่อน เพราะ wall บางสุด
- Strangulation = โดน major arterial supply (พัฒนามาจาก closed-loop)
### Volvulus
- M/C location = sigmoid
- Risk factor
	- Chronic constipation
	- Age 70-80
	- Psychotropic drug
	- High fiber diet
- Imaging = <span class='hl1'>coffee bean sign</span>
- 
## Functional
- Paralytic ileus
- Metabolic
- Drug = opioid
- Pseudo-obstruction
- Idiopathic
### Ogilvie's syndrome (Colonic pseudo-obs)
- Definition = functional obs → massive dilatation of colon โดยที่ไม่มี mechanical obs
- Cause 
	- Narcotic
	- Bed rest
	- Comorbid disease
- Tx = treat cause
# Clinical feature
## History
- Cardinal sign of gut obs
	- Abdominal pain
	- N/V
	- Obstipation = absence of flatus & feves
	- Abd distension
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Esophagus', 'Drooling<br>Early vomiting<br>Pain while swallowing<br>Choking & coughing<br>Regurgitation<br>Hoarseness, heartburn'],
	['Gastric outlet', 'Post-prandial vomiting<br>Early satiety<br>Weight loss<br>Succession splash (>4hr after meal)'],
	['Small bowel', 'Colicky pain around umbilicus<br>Vomiting (clear > discolour > feculent)<br>Epigastric distension'],
	['Large bowel', 'Lower abd pain<br>Delayed vomiting<br>Generalized distension'],
];

const header = []
// @no-refresh
dv.table(header, data);
dv.container.classList.add("side");
```

- Sign of complete obs
	- ไม่ตด
	- NG feculent
	- Empty rectum on PR
	- No rectal gass on plain film
## Physical exam
- Sx scar
- Bowel sound
- Groin hernia
- PR
## Complication
- Dehydration
	- Hypovolumic shock
	- Elyte imbalance
	- AKI
- Ischemia, gasgrene, necrosis, perforation
	- Sepsis
	- Septic shock
- ↑ IAP
	- Abdominal hypertension/compartment
# Investigation
- Acute abdomen series
	- Small bowel obs
		- Spring coil appearrance
		- Step ladder pattern
		- String of bead / pearl sign
		- Diagnosis
			- Small bowel dilated (> 3 cm from outer wall to outer wall)
			- Different height in the same loop (> 5 mm) = ใช้เเยกกับ ileus
	- Bowel loop size (3 5 7 9)
		- Small bowel = 3 cm
		- Ascending colon = 5 cm
		- Transverse colon = 7 cm
		- Descending colon = 9 cm
- CT whole abd
- Barium = <span class='hl1'>C/I in peritonitis</span>
- ± MRI
- Colonoscope
- U/S
# Management
- Preoperative
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Admit ward', 'NPO'],
	['IV hydration', 'NG with decompression'],
	['Retain foley', 'Record V/S, I/O'],
	['CBC, elyte, BUN/Cr, LFT, Ca, Mg, CBG, amylase, anti-HIV', 'Omeprazole 40mg IV OD'],
	['Film acute abd series ± serial film q4-6h', 'Ceftriaxone 2g IV OD'],
	['Observe abdomen', 'Metronidazole 500mg IV q8h'],
	['(Central line insertion)', ''],
	['(CT whole abd)', ''],
];

const header = ['One day', 'Continue']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'center', 'spread');
```
<span class='hl1'>*ห้าม prep bowel ใน acute obs</span>
<span class='hl1'>** NG decompression ใส่เส้นใหญ่ ดูดเเบบ low negative intermittent</span>

## Indication for sx
- Peritonitis
- Evidence of perforation / strangulation
- Complete obs
- Failed conservative Tx in 48-72 hr
	- ดูผ่าน plain film = ดูว่า air ขยับมั้ย
	- NG เเล้วเป็นสีขี้

> [!info] SBO that can prolong conservative Tx
> - Early post-op
> - Carcinomatosis peritonii
> - Radiation enteritis
> - Crohn dz
> - Colonic diverticulitis
> - HIV
> - Hx of Sx

