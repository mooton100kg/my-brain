# S/S
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["List", ul(['1', '2'])]
]; */

const ul = items =>
  `<ul>${items.map(i => `<li>${i}</li>`).join("")}</ul>`;

const data = [
	['Mcburney', 'Tenderness at McBurney point', 'Most reliable'],
	['Psoas', 'Pain on extension of right thigh', 'Retrocecal'],
	['Rovsing', 'Pain in RLQ on palpation of LLQ', 'Cecal distension'],
	['Obturator', 'Pain on internal rotation of right thigh', 'Pelvic'],
];

const header = ['Sign', 'Description', 'Meaning']
// @no-refresh
dv.table(header, data);
dv.container.classList.add('top');
```
## Alvarado score
- <span class='hl1'>MANTRELS</span>
	- <span class='hl1'>M</span>igratory
	- <span class='hl1'>A</span>norexia
	- <span class='hl1'>N</span>/V
	- <span class='hl1'>T</span>enderness RLQ = 2
	- <span class='hl1'>R</span>ebound 
	- <span class='hl1'>E</span>levated temp (> 37.3)
	- <span class='hl1'>L</span>eukocytosis (> 10,000) = 2
	- <span class='hl1'>S</span>hift of neutrophil
![[Screenshot 2568-12-20 at 17.46.46.png|400]]
![[Screenshot 2568-12-20 at 17.47.36.png|300]]
# Management
- Surgery
	- LC ทำใร uncomplicate case มีโอกาสเกิด abscess ได้ post-op 2wk
![[Screenshot 2568-12-20 at 17.50.26.png]]