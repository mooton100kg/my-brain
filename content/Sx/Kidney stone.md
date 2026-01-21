# Type of stone
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['CaOxalate', 'Uric stone'],
	['CaP', ''],
	['Struvite (MgNH4PO4)',''],
	['Cystine', ''],
];

const header = ['Radioopaque', 'Radiolucent']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'center');
```

# Clinical feature
## Ddx
- Appendicitis
- Diverticulitis
## History
- Colicky pain, flank pain
- Hematuria
- N/V = เพราะ visceral innervation ไปรวมกับ GI
## PE
- Abdominal exam = no tender
	- LLQ = appendicis
	- RLQ = diverticulitis
- CVA tendernesss = เเสดงว่ามี pyelonephritis ร่วมด้วย
## Investigation
- UA, UC
- <span class='hl2'>CT non-contrast low-dose = the best</span>
- ± U/S 
- CBC
- BUN, Cr = ดู AKI จาก prerenal (N/V) / post-renal (bilateral obs)
- 24hr urine collection = ดู pH, Na, Uric, Ca
### Stone characteristic
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["List", ul(['1', '2'])]
]; */

const ul = items =>
  `<ul>${items.map(i => `<li>${i}</li>`).join("")}</ul>`;

const data = [
	[ul(['Calcium oxalate', 'Calcium phsophate']),
	ul(['Struvite', 'Apatite', 'cystine']),
	ul(['Uric acid', 'Ammonium urate', 'Xanthine', '2,8-Dihydroxyadenine', 'Drug-stone'])],
];

const header = ['Radiopaque', ,'Poor radiopacity', 'Radiolucent']
// @no-refresh
dv.table(header, data);
dv.container.classList.add('top', 'center');
```
![[image-23.png|300]]
- Calcium oxalate
	- Risk factor
		- Dehydration
		- Hypercalciuria
		- Hyperoxaluria
		- Hypernatremia
		- Hyperuricosuria
		- Roux-en-Y gastric bypass
		- Nut, chocolate, tea, spinach, beet, rhubarb
		- Vit-C
- Uric acid
	- Risk factor
		- Acidic urine
		- Met acidosis
		- Hyperuricosuria
		- Gout
- Struvite
	- $MgNH_4PO_4$
	- Cause = urease producing bacteria
		- Protease (E. coli ไม่ใช่)
	- Staghorn calculi

# Management
- Pain control = NSAIDs > opioid
	- Colicky pain จะค่อยๆ หายเองใน 24hr
- ATB prophylaxis

- < 5 mm = observe
- 5-10 mm = a-blocker (medical expulsive therapy)
	- Non-selective = doxazosin
	- Uro selective
		- Xatral (alfuzosin)
		- Uroflow (tamsulosin)
		- Urief (silodozin)
## Indication for urgency intervention
- Urinary retension
- Bilateral obs
- Obs of solitary kidney
- Immunocompromised 
- Impending renal deteriation = ไตจะวาย
- Pain refractory to analgesia 
- Intractable N/V
## Intervention option
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['≤ 10 mm' ,'RIRS/SWL', 'RIRS/SWL'],
	['10-20 mm', 'RIRS/PCNL', 'RIRS/SWL'],
	['≥ 20 mm', 'PCNL', 'PCNL'],
];

const header = ['', 'Lower pole stone', 'Non-lower pole stone']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'side', 'center');
```
- SWL = shockwave lithrotripsy
	- Stone street / Steinstrasse = เศษนิ่วไปอุดในท่อไต
- USR = RIRS
	- URS = ureteroscopic lithrotripsy
	- RIRS = retrograde intrarenal surgery
- PCNL = percutaneous nephrolithrotripsy
## Prevention of recurrent kidney stone
- Fluid intake = กินเท่าไหร่ก็ได้ให้ฉี่ 2L/d
- Litmit Na intake