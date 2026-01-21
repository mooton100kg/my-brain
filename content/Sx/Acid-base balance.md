---
File:
  - https://www.facebook.com/share/p/17GGpE3Eq7/
---

```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["List", ul(['1', '2'])]
]; */

const ul = items =>
  `<ul>${items.map(i => `<li>${i}</li>`).join("")}</ul>`;

const data = [
	['Normal', '7.35-7.45', '40', '24'],
	['RS acidosis', '< 7.4', '↑', '↑'],
	['RS alkalosis', '&lt; 7.4', '↓', '↓'],
	['Met acidosis', '< 7.4', '↓', '↓'],
	['Met alkalosis', '&lt; 7.4', '↑', '↑'],
];

const header = ['', 'pH', 'PaCO2', 'HCO3']
// @no-refresh
dv.table(header, data);
dv.container.classList.add('top', 'center', 'side');
```
- Metabolic acidosis   $P_{CO2} = 1.5 \times [HCO3] + 8 ± 2$
- Metabolic alkalosis   $P_{CO2} = 0.7 \times [HCO3] + 20 ± 5$
- Respiratory acidosis
	- Acute     $[HCO3] = 24 + (P_{CO2}-40)\ 0.1$
	- Chronic  $[HCO3] = 24+(P_{CO2}-40)\ 0.4$
- Respiratory alkalosis
	- Acute     $[HCO3] = 24 + (P_{CO2}-40)\ 0.2$
	- Chronic  $[HCO3] = 24 + (P_{CO2}-40)\ 0.5$
![[Screenshot 2568-12-21 at 00.24.30.png|300]]![[Screenshot 2568-12-21 at 00.38.01.png|300]]


## Anion gap
- AG = Na - (Cl + HCO3) = 12 mEq/L
- Delta AG = $\frac{AG - 12}{24 - HCO3}$
	- < 1 = HAGMA + NAGMA
	- 1-2 = HAGMA
	- > 2 = HAGMA + met alkalosis
# Metabolic acidosis

> [!info] Renal insufficiency
> - Early (GFR 20-40) = NAGMA
> 	- Imaired ammonium synthesis & secretion
> - Advanced (GFR < 20) = HAGMA
> 	- Retention of acid

## Wide anion gap (HAGMA) <span class='hl1'>= MUDPILES</span>
- <span class='hl1'>M</span>ethanol
- <span class='hl1'>U</span>remia
- <span class='hl1'>D</span>KA
- <span class='hl1'>P</span>araldehyde
- <span class='hl1'>I</span>ron / isoniazid
- <span class='hl1'>L</span>actic acidosis
- <span class='hl1'>E</span>thylene glycol
- <span class='hl1'>S</span>alicylate (ASA)
### Lactic acidosis
![[image-21.png|300]]

- L-lactic acidosis
	- Type A = hypoperfusion
	- Type B
		- B1 = liver disease, CA, B2 def
		- B2 = MFM, NRTI, INH, linezolid
		- B3 = inborn metabolism error
- D-lactic acidosis
	- Colonic bacteria overgrowth → fermentation
	- Short bowel syndrome
	- Episodic enceph after meal
## Normal anion gap (NAGMA / hyperchloremic met acido) <span class='hl1'>= HARDASS</span>
- <span class='hl1'>H</span>yperalimentation
- <span class='hl1'>A</span>ddison dz
- <span class='hl1'>R</span>TA
- <span class='hl1'>D</span>iarrhea
- <span class='hl1'>A</span>cetazolamide 
- <span class='hl1'>S</span>pironolactone
- <span class='hl1'>S</span>aline infusion
### RTA
- Type
	- 1 (distal) = impaired urinary acid excretion
	- 2 (proximal) = impaired bicarbonate reabsorption
	- 3 (combined) 
	- 4 (hypoaldosteronism)
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["List", ul(['1', '2'])]
]; */

const ul = items =>
  `<ul>${items.map(i => `<li>${i}</li>`).join("")}</ul>`;

const data = [
	['1 (distal)', 'Severe', '&plus;', '&gt; 5.3', '↓'],
	['2 (proximal)', 'Moderate', '±', '< 5.3', '↓'],
	['4 (hypoald)', 'Mild', '&plus;', '< 5.3', '↑'],
];

const header = ['Type', 'Acidosis', 'UAG', 'U pH', 'Serum K']
// @no-refresh
dv.table(header, data);
dv.container.classList.add('top', 'side', 'center');
```

# Metabolic alkalosis
- Saline-responsive
	- Vomiting
	- Diuretic = ↓ Na → ↑ aldosterone & ↓ K
	- Hypovolemia<span class="hl4"> → hyperaldosteronism</span>
- Saline-resistant
	- Hyperaldosteronism
	- Alkaline ingestion
	- Hypokalemia
## Calcium-alkali syndrome
- Triad
	- Hypercalcemia
	- Metabolic alkalosis
	- Renal insufficiency
- Risk factor
	- High Ca intake (> 4g)
	- Concomitant intake with Vit-D
	- Pre-existing CKD