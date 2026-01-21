---
File:
  - https://www.icloud.com/iclouddrive/04f604FiQJnYldoPnqbqYkpFg#Dementia
---
# Criteria diagnosis #Elderly/imo
- เสีย ≥1 cognitive domain = <span class='hl1'>MARVEL</span>
	- **M**emory
	- **A**ttention
	- Social **R**ecognition
	- **V**isuospatial
	- **E**xecutive
	- **L**anguage
- เสีย IADL
- ไม่เป็น delirium
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Acute change in mental status', '&plus;', '&minus;', '&minus;'],
	['Inattention', '&plus;', '±', '±'],
	['AOC', '&plus;', '&minus;', '&minus;'],
	['Disorganized thinking', '&plus;', '±', '&minus;'],
	['Altered psychomotor activity', '&plus;', '±', '&plus;'],
	['Chronic duration', '±', '&plus;', '&plus;'],
];

const header = ['Feature', 'Dementia', 'Delirium', 'Depression']
dv.table(header, data);
dv.container.classList.add('top', 'side','center','middle');
```

- ไม่เป็น other mental disorder
# Mild cognitive impairment
![[Pasted image 20251108000139.png]]
# Investigation
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['CBC', 'Vit&minus;B12 def'],
	['FBS' , 'Hypo/hyperglycemia'],
	['Elyte', 'Hypo/hypernatremia'],
	['BUN, Cr', 'Renal fuction'],
	['LFT', 'Liver disease'],
	['fT4, TSH', 'Hypothyroidism'],
	['VDRL', 'Neurosyphilis'],
	['CT / MRI', 'Neurodegenerative disease'],
	['Anti&minis;HIV', 'HIV&minus;associated neurocognitive disorder'],
	['LP', 'CNS infection'],
	['PHQ&minus;9', 'Depression'],
];

const header = ['lab', 'Disease']
dv.table(header, data);
dv.container.classList.add("top");
```
# Cause
## Alzheimer (M/C)

- Onset = chronic gradual progression
- Pathophysiology = amyloid B deposition
- S/S
	- Cognitive impairment = **M**, V, E, L
- Imaging = hippocampal atrophy
## Vascular dementia
- Onset
	- Poststroke dementia = after stroke
	- Small vessel disease = chronic gradual progression
- S/S
	- Stroke = according to area
	- Small vessel disease
		- UMN sign
		- Cognitive impairment = **E**
- Imaging
	- Small vessel disease = whtie matter > 25%
## NPH - Normal pressure hydrocephalus
- <span class='hl1'>Clinical triad</span> #Elderly/imo 
	- Gait = Wide-based, magnetic gait
	- Urinary incontinence = Urgency ± nocturia
	- Cognitive impairment 
- Imaing 
	- Ventriculomegaly 
- Management = surgical drainage
## Chronic subdural hematoma
- Cause = repetitive minor head trauma
- Imaging = CT non contrast
- Risk factorirrhosis
# Management
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Donepezil<br>Rivastigmine<br>Galantamine', 'AchEI', 'N/V<br>Loss of appetite, weight loss'],
	['Memantine', 'NMDA antagonist', 'Headache<br>Constipation'],
];

const header = ['Medicine', 'Mechanism', 'S/E']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top",'middle');
```
