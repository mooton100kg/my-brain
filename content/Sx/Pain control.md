# Pain control
![[Screenshot 2568-11-16 at 17.24.17.png]]
## Pain assessment
### 1. Type of surgery
![[Screenshot 2568-11-16 at 16.58.30.png]]
### 2. Severity of pain
- Numerical rating scale = สื่อสารได้ เข้าใจ ปกติ
	![[Pasted image 20251116165932.png|200]]
- Behavioral pain scale = ผู้ใหญ่เเต่อยู่ในสภาพที่สื่อสารไม่ได้
- Modified faces legs activity cry consolability scale (FLACC) = newborn
- Vitual analog scale
	![[image-34.png|218x74]]

### 3. Patient condition
- Special need
	- Modified faces legs activity cry consolability scale (FLACC)
	- Behavioral pain scale
	- Critical-care pain observation tool
- Kidney function
- Drug allergy
- U/D
## Pain management
![[Pasted image 20251116171513.png|200]]
### 1. Strong opioid
- Indication = severe pain
- Mechanism = mu opioid receptor
- Option
	- Morphine = <span class="hl1">ใน kidney ใช้ได้ เเต่ต้องลด dose</span>
	- Fentanyl <span class="hl3">(most potent / short duration)</span> = safe in liver / kidney insuff
	- Pethidine = <span class="hl1">euphoria</span>, seizure, serotonin syndrome
- Complication
	- RS depression
	- Sedation
	- Constipation
	- Urinary retention
	
	![[Screenshot 2568-11-16 at 17.17.28.png|350]]
### 2. Weak opioid
- Indication = Mod pain
- Mechanism = weak mu opioid receptor + SNRI
- Option
	- Tramadol
	- Codeine
- Complication
	- Serotonin syndrome = ถ้าให้พร้อม pethidine, TCA, SSRI
	- ↓ Seizure threshold
	
	![[Screenshot 2568-11-16 at 17.19.04.png|350]]
### 3. NSAIDs
- Indication = mild-mod pain
- Mechanism = inhibit COX, PGE2
- Option
	- Traditional = bleeding (COX1), dyspepsia
		- Diclofenac, ibuprofen, naproxen, indomethacin, mefenamic acid
	- COX-2 inhibitor = thrombotic risk (COX2), sulfa allergy
		- Celecoxib, <span class='hl1'>etoricoxib (เเพ้ sulfa กินได้)</span>, parecoxib (dynastat)
		
	![[Screenshot 2568-11-16 at 17.21.50.png|350]]
	![[Screenshot 2568-11-16 at 17.22.05.png|350]]
- Complication
	- Renal dysfunction
	- Liver injury = diclofenac, sulindac
	- Salt water retention
	- Angioedema
	- Reye's syndrome ใน <12yo
	- GI effect <span class='hl2'>risk</span>
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Hx of complicated ulcer', '&gt;65yr', 'No risk factor'],
	['&gt;2 risk factor', 'High dose NSAIDs', ''],
	['', 'Hx of uncomplicated ulcer', ''],
	['', 'Use aspirin/steroid/anti-coag', ''],
];

const header = ['High risk', 'Mod risk ≤2', 'Low risk']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'center');
```
- ข้อควรระวังในการใช้ยา
	- ไม่ได้ใช้ aspirin
		- <span class='hl2'>No PU risk</span> = traditional NSAIDs
		- <span class='hl2'>GI effect risk ≥ 1</span> = COX-2 inhibitor / traditional NSAIDs + PPI
	- ใช้ aspirin
		- Traditional NSAIDs + PPI
		- <span class='hl2'>Hx of GIB</span> = aspirin + PPI

> [!info] Random fact NSAIDs
> - Celecoxib ลดการเกิดมะเร็งใน famial adenomatous polyposis
> - NSAIDs = reversible bind to plt / aspirin = irreversible bind to plt
> - ลดโอกาสเกิด alzheimer
> - Indomethacin = ปิด ductus arteriosus
> - Traditional NSAIDs + PPI/misoprostol มีโอกาสเกิด PU พอๆ กับ COX-2 inhibitor

### 4. Paracetamol
- Indication = mild-mod pain
- Mechanism = inhibit COX2>1, endocannabinoid
- Complication
	- Acute liver failure
		- ระวังใน 
			- chronic alcoholism, liver dz
			- CYP2E1 inducer = phenytoin, rifampin
	
	![[Screenshot 2568-11-16 at 17.23.47.png|350]]

> [!tip] Multimonal analgesia
> ให้ยา ≥2 ชนิด / คนละ mechanism / หลีกเลี่ยง opioid
> - Pharmacological = opioid, non-opioid, NSAIDs, paracetamol
> - Non-pharm = regional, local

![[Screenshot 2568-11-16 at 17.26.17.png|350]]