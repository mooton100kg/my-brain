---
File:
  - https://www.rama.mahidol.ac.th/poisoncenter/sites/default/files/public/img/news/event/LA.pdf
---
# Mechanism
- Reversible inhibition of inactive Na channel
- ยาเข้าสู่ cell ได้เฉพาะ non-ionze form
	- ทำให้ยาชาออกฤทธิ์ไม่ดีใน inflam tissue → ↓ pH → ionization
## Effect 
1. Pain
2. Tempterature
3. Touch
4. Pressure
5. Motor func
## Pharmacokinetic
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['↑ Blood flow' ,'↓ Duration'],
	['Lipid solubility', '↑ Potent & duration'],
	['↑ Protein binding', '↑ Duration'],
	['Receptor affinity', '↑ Duration'],
	['↓ pKa', '↑ Onset'],
];

const header = []
// @no-refresh
dv.table(header, data);
dv.container.classList.add("side");
```
- pKa = ทำให้ยาเป็น non-ionize form ง่ายขึ้น
	- Mepivicaine = 7.6
	- Lidocaine, prilocaine, articaine = 7.8
	- Bupivicaine = 8.1

> [!info] PK
> Onset = pKa
> Duration = receptor affinity, blood flow, lipid solubility, protein binding
> Potency = lipid solubility

```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Procaine', 'Lidocaine', 'Tetracaine'],
	['Chloroprocaine', 'Mepivacaine', 'Bupivacaine'],
	['', 'Prilocaine', 'Ropivacaine'],
	['', '', 'Etidocaine'],
];

const header = ['Short duration<br>(20-45min)', 'Inter duration<br>(60-120min)', 'Long duration<br>(400-450min)']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'center');
```

# Rout
- Topical
- Infiltration = injected into tissue
- Nerve block 
	- Injected near major nerve
	- Injected into epidural space / subarchnoid space 
# Classification
## Amide
- Elimination = liver
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Lidocaine<br>(Xylocaine)', '', 'M/C used<br>Safe in children'],
	['Mepivacine', 'Toxic for newborn (ห้ามใช้ใน pregnancy)', 'เกิด Vasodilate น้อยสุด ทำให้ไม่ต้องให้พร้อม Epi ก็ได้'],
	['Bupivacaine', 'Severe myocardial depression (if IV)', 'Duration = longest<br>Used = epidural & spinal'],
	['Articaine', '', 'Duration = shortest<br><br>มี 1 ester chain'],
	['Prilocaine', 'Methemoglobinemia', ''],
];

const header = ['Medication' , 'S/E', 'Des']
dv.table(header, data);
dv.container.classList.add('top', 'side', 'spread');
```
## Ester
- Elimination = pseudocholinesterase in plasma
- Ester จะ toxic + allergic กว่า amide เพราะ methylparaben สามารถ cross-reacte กับ ester ได้
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Cocaine', 'Inhibit catecholamine reuptake<br>→ x symp = tachycardia → arrhythmia<br><br>Inhibit dopamine reuptake<br>→ reward pathway = euphoria → addiction', 'Used = topical<br><br>เป็น vasoconstrictor'],
	['Benzocaine', 'Methemoglobinemia', 'Used = topical'],
	['Procaine', 'CNS & CVS', 'Duration = long'],
	['Tetracaine', '', 'Duration = long<br>Used = spinal & corneal'],
];

const header = ['Medication', 'S/E', 'Des']
// @no-refresh
dv.table(header, data);
dv.container.classList.add('top', 'side', 'spread');
```
# Vasoconstrictor
- **หน้าที่**
	- Prolong numbness = ↓ blood flow
	- ↓ Toxicity = ↓ blood flow → ↓ systemic effect
	- Promote hemostasis = ↓ blood flow 

> [!tip] Vasoconstrictor & local anesthetic
> Local anesthetic มีฤทธิ์ vasodilation (ยกเว้น cocaine)

## Toxicity
- Max **Epi** for ASA 1 = 0.2 mg
- Max **Epi** for CVS = 0.04 mg
- Max **lidocaine** w/o vasoconstrictor = 5 mg/kg
- Max **lidocaine** with vasoconstrictor = 7 mg/kg
# LAST - local anesthetic systemic toxicity
- CNS (เกิดก่อน CVS) = inhibit pathway in amygdala
	1. Tongue numbness
	2. Tremor, generalized tonic-clonic seizure
- CVS = โดยเฉพาะ **bupivacaine**
	- Bradycardia, ↓ CO
	- Vasodilation → **hypotension** → cardiac arrest
## Management
- Decontamination (w/in 1-2 hr of ingestion)
	- Gastric lavage
	- Single dose activated charcoal
- Enhance elimination
- Antidote = intralipid emulsion (ILE) → ส่วนใหญ่ใช้กับ mepivacaine เนื่องจากมี long duration
	- Dose = 20% ILE 1.5 ml/kg IV bolus 1min → 0.25 ml/kg/min 30-60min
	- Indication
		- CNS = agitation, confusion, seizure
		- CVS = ventricular arrhythmia, hypotension, conduction block
	- S/E
		- ARDS = เพิ่ม pulmonary artery pressure
		- Fat overload syndrome
			- Hepatosplenomegaly
			- Jaundice
			- Pancytopenia
			- Coagulation disturbance
		- Pancreatitis 

- CNS = seizure
	- Benzodiazepine 
	- ± Rocuronium เเต่ไม่เเนะนำ succinylcholine เพราะทำให้เกิด hyperK & arrhythmia
# Calculation
![[Screenshot 2568-12-11 at 01.40.56.png]]
$$
Max\ ml = \frac{Max\ dose \times kg}{10 \times \%}
$$

