- Indication
	- ให้ใส่ ETT ได้ง่าย
	- Control seizure
	- ให้คนไข้นิ่งๆ ตอนผ่าตัด
	- ลดการใช้ยาสลบ
- Classification
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["List", ul(['1', '2'])],
  ["sublist", ul([
	  {
		  label: '1',
		  children: ['2', '3', '4']
	  }])
	],
]; */

const ul = items =>
  `<ul>${items.map(i =>
    typeof i === "string"
      ? `<li>${i}</li>`
      : `<li>${i.label}${ul(i.children)}</li>`
  ).join("")}</ul>`;


const data = [
	[ul(['Succinylcholine']),
	ul([
	{
		label: 'Benzylisoquinolinium',
		children: ['Mivacurium', 'Atracurium', 'Cisatracurium']
	},
	{
		label: 'Aminosteroid',
		children: ['Pancuronium', 'Vecuronium', 'Rocuronium']
	}])
	]
];

const header = ['Depolarize', 'Non-depolarize']
// @no-refresh
dv.table(header, data);
dv.container.classList.add('top', 'center');
```
# Depolarize
## Succinylcholine
- Onset = 45sec
- S/E
	- Malignant hyperthermia
	- Massester spasm
	- Hyperkalemia → arrhythmia = VT/VF
	- Myalgia
	- ↑ IOP, ICP
# Non-depolarize
## Rocuronium
- Onset = 3min
	- เเต่ถ้าให้ double dose → onset จะเท่ากับ succinylcholine เเต่มีข้อเสียคือ duration จะนานมาก
# การเเก้ฤทธิ์ยา
- Neostigmine + atropine
	- Neostigmine = anticholinesterase
		- S/E
			- Bronchorea
			- Bronchospasm
			- Bradycardia
	- Atropine = anticholinergic
		- เเก้ S/E ของ neostigmine = bradycardia