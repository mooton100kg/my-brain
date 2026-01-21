- Acute vs Chronic (6mo)
	- Acute = HAV, HEV
	- Chronic = HBV, HCV, HDV, HEV (immunocompromise)
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["List", ul(['1', '2'])]
]; */

const ul = items =>
  `<ul>${items.map(i => `<li>${i}</li>`).join("")}</ul>`;

const data = [
	['HAV', 'X', 'Fecal oral'],
	['HBV', 'X', 'Parenteral, perinatal'],
	['HCV', '', 'Parenteral, perinatal'],
	['HDV', '', 'Parenteral'],
	['HEV', '', 'Fecal oral'],
];

const header = ['','Vaccine', 'Transmission']
// @no-refresh
dv.table(header, data);
dv.container.classList.add('side', 'top', 'center');
```
# HBV
- Viral marker
	- HBsAg = + ถ้ายังมีเชื้ออยู่
	- anti-HBs = ไม่เจอพร้อม HBsAg
	- anti-HBc
		- total anti-HBc = ถ้าติดก็ + ไม่ได้บอกอะไร
		- anti-HBc IgM = acute
		- anti-HBc IgG = ถ้าติดก็ + ไม่ได้บอกอะไร
	- HBeAg = active viral replication
	- anti-HBe = inactive viral replication
	![[Screenshot 2568-12-21 at 12.32.16.png|300]]
	