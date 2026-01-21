![[Screenshot 2568-12-20 at 13.06.31.png]]
# Acute rheumatic fever
- Definition = เกิดหลัง Streptococcal pharyngitis 2-4wk
## S/S
- **ไข้** = high grade for 1wk → low grade for 1-2wk
- **ข้อ** = arthritis → migratory polyarthritis (individual joint are effected for <1wk)
- **คอ** = sore throat
- **Car**ditis = โดยเฉพาะ mitral / aortic
- **Q** = cutaneous nodule 
## Jones criteria
- Diagnosis
	- Initial ARF = 2mj <span class='hl3'>or</span> 1 mj + 2mi
	- Recurrent ARF = 2mj <span class='hl3'>or</span> 1mj + 2mi <span class='hl3'>or</span> 3mi
	- Major 
		- Carditis
		- Arthritis
		- Chorea
		- Erythema marginatum = (pink rash with pale center & serpiginous margin)
		- Subcutaneous nodule 
	- Minor
		- Monoarthralgia
		- ≥ 38ºC
		- ESR ≥ 30 / CRP ≥ 3
		- Prolonged PR interval
## Management
- ATB
	- Penicillin
- Anti-inflammation 
	- NSAIDs = arthritis
	- Steroid = severe carditis
## ARF vs poststreptococcal reactive arthritis
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Post GAS pharyngitis', 'Yes', 'Yes'],
	['Latency period', '2-4wk', '7-10d'],
	['Peak age', '4-9yr', '8-14 / 21-37yr'],
	['Fever', 'Present', 'Present'],
	['Arthritis', 'Migratory, self-limiting', 'Additive, prolonged'],
	['Heart', 'Carditis in young children<br>Valvular heart เจอใน 25-34yr', 'No increased risk of valvular heart in adult'],
	['Response to NSAIDs', 'Remarkable good', 'Moderate'],
];

const header = ['Feature', 'ARF', 'PSRA']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'side', 'center', 'middle');
```
# SLE (systemic lupus erythematosus)
- Hypersenstivity type 3 = immune complex reaction
## S/S
- Specific skin lesion
	- Acute = malar rash 
	- Subacute
		- Papulosquamous variant = ddx psoriasis
		- Annular-polycyclic variant = ddx rheumatic fever, erythema marginatum
	- Chronic = discoid rash at concha
- Non-specific skin lesion
	- Generalized non-scarring alopecia
	- Raynaud's phenomenon
	- Photosensitive rash = sparing underside of chin & skin overlying joint
## Investigation
- ANA
- anti-dsDNA <span class="hl4">(homogenous pattern)</span>, anti-smith <span class="hl4">(speckled pattern)</span>
- C3, C4 = อาจจะลดลงตอนเกิดอาการ
- antiphospholipid Ab
## EULAR criteria
![[image-18.png]]
## Management
- Steroid high dose 
- Anti-malarial = chloroquine, hydroxychloroquine
- Immunosuppressant
	- Cyclophosphamide
	- Rituximab
# Vasculitis
![[Screenshot 2568-12-20 at 12.53.34.png]]
## Vasculitis mimic 
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Thrombosis', 'Antiphospholipid syndrome, TTP, purpura fulminans, warfarin induced skin necrosis, artherosclerosis'],
	['Emboli', 'Cholesterol emboli, IE, cardiac myxoma, tumor emboli'],
	['Vasospasm', 'Ergotism, cocain, raynaud phenomenon'],
	['Vessel wall pathology', 'Scurvy, amyloidosis, livedoid vasculopathy, fibromuscular dysplasia, coarctation of aorta'],
];

const header = ['Mechanism', 'Example']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'side');
```
## Secondary vasculitis
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["List", ul(['1', '2'])]
]; */

const ul = items =>
  `<ul>${items.map(i => `<li>${i}</li>`).join("")}</ul>`;

const data = [
	['Infection', 'Syphilis, TB, HCV, HBV, HIV, bacteria'],
	['Autoimmune', 'RA, SLE, sjogren, autoimmune myositis, sarcoidosis'],
	['Malignancy', 'Hematologic & solic'],
	['Drug', 'Hydralazine, PPI, MTM, azithromycin, minocycline, penicllamine, montelukast'],
];

const header = ['Category', 'Example']
// @no-refresh
dv.table(header, data);
dv.container.classList.add('top', 'side');
```
## Small vessel
### EGPA
- S/S
	- OSA, nasal polyp
	- Mononeuritis multiplex
- Investigation
	- Eo ≥ $10^9$ 
	- Biopsy = extravascular Eo
# Adult-onset stills' disease
## S/S
- High spiking fever <span class="hl4">usually in late afternoon</span>
- High serum ferritin = ใช้เเยกกับ macrophage activation syndrome
- Polyarthritis
- Leukocytosis
- ↑ LFT
- <span class='hl2'>Complication</span> = macrophage activation syndrome
## Yamaguchi classification criteria
- Major 
	- > 39ºC > 7d
	- Arthralgias / arthritis ≥ 2wk
	- Characteristic rash = salmon color rash
		![[image-19.png|200]]
	- Leukocytosis ≥ 10,000 wtih N ≥ 80
- Minor
	- Sore throat
	- Lymphadenopathy / splenomegaly
	- Abnormal aminotransfereses
	- -ve RF & antinuclear Ab