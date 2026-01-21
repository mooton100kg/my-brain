# สังคมผู้สูงอายุ
- Aging society = มีเเนวโน้มการเพิ่มขึ้นของ >60yr อย่างต่อเนื่อง
- ประเทศไทยเป็น aged society
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Aged society', '&gt; 10%', '&gt; 7%'],
	['Completely aged society', '&gt; 20%', '&gt; 14%'],
	['Super&minus;aged society', '&gt; 28%', '&gt; 20%'],
];

const header = ['Society', '≥ 60 yr', '≥ 65 yr']
// no-refresh
dv.table(header, data);
dv.container.classList.add('top', 'side', 'center');
```
- Homeostenosis = ภาวะที่ร่างกายเสียหายเกินกว่าที่จะซ้อมเเซมได้ → ตุย
# การเปลี่ยนเเปลงทางสรีรวิทยา
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Skin', '↓ Thickness<br>↑ Collagen cross-link', 'Wrinkles<br>Pressure injury<br>Xerosis'],
	['', '↓ Hair density & melanocyte', 'Gray & thinning of hair'],
	['', '↓ APC cell', 'Fungal infection<br>Neoplasm'],
	['Muscle', 'Fiber shrink<br>↓ Type II fiber (fast twitch)<br>↑ Lipofuscin', 'Sarcopenia'],
	['Skeletal', '↓ Bone density<br>Stiff joint', 'Osteoporosis<br>RA<br>OA'],
	['Nerve', '↓ Number of neuron<br>↓ Action potential speed<br>↓ Axon', 'Stroke<br>Dementia'],
	['Eye', '↑ Fat deposit<br>↑ Len thickness<br>↓ Pupil', 'Presbyopia<br>Cataract<br>AMD<br>Glaucoma<br>DR'],
	['Ear', '↑ TM thickness<br>↓ Elasticity of ossicular articulation<br>Organ atrophy<br>↓ Cochlear neuron<br>↓ Size & number of otolith', 'Presbycusis<br>Tinnitus, dizziness, vertigo'],
	['CVS', '↑ Lt. ventricular wall thickness', 'HT<br>Thrombosis<br>Anemia'],
	['Heart', '↑ Fat deposit', 'CHF<br>MI'],
	['Vasculature', '↓ Responsiveness to receptor', 'CAD<br>Atherosclerosis<br>Hemorrhoid'],
	['Pulmonary', '↓ Elastic recoil<br>↑ Collagen cross-link<br>↑ Residual volume', '↓ Exercise tolerance<br>Chronic bronchitis<br>Pneumonia<br>Sleep apnea<br>Lung cancer'],
	['Salivary gland', 'Fatty replacement of acini', ''],
	['GI', '↑ Dysphagia<br>↑ Achlorhydria<br>↑ Muscosal cell atrophy', '↓ Iron, B12, Ca<br>Constipation'],
	['Endocrine', '↓ GH, testosterone, estrogen<br>↑ PTH, ATP, NorE, EPO', 'DM'],
	['Immune', '↑ Autoimmune<br>↓ T cell', 'Autoimmune<br>Leukemia'],
];

const header = ['Organ', 'Change', 'Consequences']
// @no-refresh
dv.table(header, data);
dv.container.classList.add('top', 'side','middle');
```
# Basic evaluation
## ADL 
- BADL (basic) = Barthel's index
	- ใส่เสื้อ
	- อาบน้ำ
	- เข้าห้องน้ำ
	- เคลื่อนไหว
	- กินข้าว
	- ขี่
- IADL (instrumental)
	- ใช้มือถือ 
	- เดินทาง
	- จัดการเงิน
	- ทำงานบ้าน
## Depression
- PHQ-9
	- 7-12 = mild 
	- 13-18 = moderate
	- ≥ 19 = severe
- TGDS (thai geriatric depression scale)
	- 13-18 = mild
	- 19-24 = moderate
	- 25-30 = severe
## Nutrition
- Significant weight loss ≥ 5% 