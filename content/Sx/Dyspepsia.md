# Rome IV criteria for functional dyspepsia
- ≥ 1
	- Bothersome postprandial fullness
	- Bothersome early satiation
	- Bothersome epigastric pain
	- Bothersome epigastric burning
- And
	- No evidence of structural disease
## Postprandial distress syndrome
- ข้อใดข้อหนึ่งอย่างน้อย 3d/wk
	- Bothersome postprandial fullness
	- Bothersome early satiation
## Epigastric pain syndrome
- ข้อใดข้อหนึ่งอย่างน้อย 1d/wk
	- Bothersome epigastric pain
	- Bothersome epigastric burning
# 2º dyspepsia
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["List", ul(['1', '2'])]
]; */

const ul = items =>
  `<ul>${items.map(i => `<li>${i}</li>`).join("")}</ul>`;

const data = [
	['Medication', ul(['NSAIDs', 'MFM', 'CCB', 'PPI'])],
	['Mucosal disease', ul(['Peptic ulcer', 'Parasite', 'CA'])],
	['Pancreato-biliary disorder', ul(['Symptomatic gallstone', 'Chronic pancreatitis'])],
	['Endocrine disorder', ul(['Hyper/hypothyroidism', 'Hyper/hypocalcemia'])],
	['Vascular ischemia', ul(['Chronic mesenteric ischemia'])],
];

const header = []
// @no-refresh
dv.table(header, data);
dv.container.classList.add('side', 'middle');
```
