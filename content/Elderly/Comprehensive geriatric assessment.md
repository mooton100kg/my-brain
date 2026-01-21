---
File:
---
- Frailty = vulnerability + multiple comorbidities
# ส่วนประกอบ
- Physical 
- Mental
- Function
- Psychosocial
- Spirituality
## Physical health
- U/D
- Medication, supplement, herbal
- Allergy, alcohol
- Vaccination
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Influenza', '&gt 65yr ฉีด high dose influ'],
	['Pneumococcal', '&gt 65yr <br>&lt 65yr + มีโรคร่วม'],
	['Tetanus', 'Tdap 1 ครั้ง จากนั้น dT ทุก 10 ปี'],
	['Herpes Zoster', '&gt 50yr 2 ครั้ง'],
	['RSV', '&gt 75yr <br>60-75yr + มีโรคร่วม'],
];

const header = []
dv.table(header, data);
dv.container.classList.add("side",'middle');
```
- Specific condition
	- Vision
		- Cataract
		- AMD
		- DR
		- Glaucoma
		- Presbyopia
	- Hearing
	- Malnutrition
		- Ca & vit-D
	- Urinary incontinence
		- Famale > male
		- 3IQ screening
			![[Pasted image 20251108000440.png]]
	- Polypharmacy
		- Criteria = <span class='hl1'>≥ 5</span> #Elderly/imo 
	- Dental 

> [!tip] Weight loss
> - ≥ 5% in 1mo
> - ≥ 10% in 6mo
## Mental
## Functional status
- <span class='hl1'>BADLs (basic activities of daily living) = DEATH</span> #Elderly/imo
	- **D**ressing
	- **E**ating
	- **A**mbulation
	- **T**oilet
	- **H**ygiene
	- <span class='hl2'>Test</span> = Barthel
- IADLs (instrumental activites of daily living) = SHAFT
	- **S**hopping
	- **H**ousekeeping
	- **A**ccounting
	- **F**ood preparation
	- **T**elephone / **T**ransportation
	- <span class='hl2'>Test</span> = Lawton
- AADLs (advanced activities of daily living)
	- Exercise
	- Leisure time
	- Ability to fulfil society / role
## Psychological health
```dataviewjs
const data = [
  ["Mini-Cog", "GDS - geriatric depression scale"],
  ["MoCA", "PHQ-9"],
  ["MMSE", ""],
  ["RUDAS", ""],
];

const header = ["Cognition", "Affection"]
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top");
```
- Mini-Cog
	- ≤ 3 = cognitive impairment
	![[Pasted image 20251108000542.png]]
- <span class='hl1'>MoCA</span> #Elderly/imo
	- ≥ 25 = normal
	- < 25 = mild cognitive impairment
	- < 22 = dementia
- MMSE
	![[Pasted image 20251108000615.png]]
## Socio economic environmental factor
![[Pasted image 20251108000642.png]]
## Spirituality
- Religion
- Belief
- Meaning of life
- Goal of life