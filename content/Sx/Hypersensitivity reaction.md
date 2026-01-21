```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["List", ul(['1', '2'])]
]; */

const ul = items =>
  `<ul>${items.map(i => `<li>${i}</li>`).join("")}</ul>`;
  
const data = [
	['Pathway', 'IgE', 'IgG, IgM', 'Immune complex', 'T cell'],
	['Response','Anaphylaxis', 'Cytotoxic mediated', 'Immune complex reaction', 'Delayed hypersens reaction'],
	['Example', 
		ul(["Asthma", "Allergy", "Anaphylaxis"]),
		ul(['AIHA', 'MS', 'Goodpasture']),
		ul(['Arthus reaction', 'Serum sickness', 'Lupus nephritis', 'PSGN']),
		ul(['Tuberculin skin test', 'T1DM', 'Multiple sclerosis', 'Hashimoto thyroiditis'])],
];

const header = ['', 'Type 1', 'Type 2', 'Type 3', 'Type 4']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'side', 'center', 'spread');
```
# Type 1 : anaphylaxis response
- Pathway
	- IgE = mast cell & basophil
## Mechanism
1. APC present Ag to Th2 → IL-4
2. Stimulate B cell → IgE
3. IgE bind Ag → mast cell & basophil → degranulation
	- Histamine
	- Leukotriene
## Response
- Anaphylaxis
	- Skin wheel & flare
	- Bronchospasm
	- Hypotension
	- N/V, abs cramping
- Asthma
- Allergic rhinitis
- Atopic eczema
- Food / drug allergy
# Type 2 : cytotoxic mediated response
- Pathway
	- IgG, IgM
		- Cytotoxic T cell
		- Complement
## Mechanism
1. Ab bind cell → complement
2. Stimulate cytotoxic T cell → phagocytosis
## Response
- ITP
	- Target = Plt
	- S/S
		- Thrombocytopenia
		- Pethechiae, purpura
- AIHA (warm type)
	- Target = RBC
	- S/S
		- Anemia, jaundice
		- Coomb test 
- MG
	- Target = Ach receptor
	- S/S
		- Muscle weakness
- Goodpasture syndrome (anti-GBM dz)
	- Target = small vessel in lung & kidney
	- S/S
		- Pulmonary hemorrhage
		- Glomerulonephritis = basement membrane of glomerulus
- Blood transfusion reaction
- Erythroblastosis fetalis
# Type 3 : immune complex reaction
- Pathway
	- Immune complex
		- Complement
## Mechanism
1. Immune complex bind organ
2. Stimulat complement → inflammation
## Response
- Arthus recation
	- Cause = skin injection
	- S/S = swelling, erythema
- Serum sickness
	- Cause = เหมือน arthus reaction เเต่เป็น systemic
	- S/S = fever, lymphadenopathy, myalgia, arthralgia
- Lupus nephritis
	- S/S = dysmorphic RBC in UA
- PSGN
	- Cause = S. pyogenes
	- S/S
		- Proteinuria, hematuria
		- Fever
		- HT
# Type 4 : delayed hypersensitivity reaction
- Pathway
	- Th1
## Mechanism
1. APC stimulate Th1 → cytokine
2. Stimulate CD8 destroy tissure
## Response
- Poison ivy
- Tuberculin skin test
- T1DM
	- Target = B cell in pancreas
- Multiple slcerosis
	- Target = CNS
- Hashimoto thyroiditis
	- Target = thyroid cell
	- S/S = hypothyroidism in adolescence