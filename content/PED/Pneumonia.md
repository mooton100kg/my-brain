# Pathogen
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["List", ul(['1', '2'])]
]; */

const ul = items =>
  `<ul>${items.map(i => `<li>${i}</li>`).join("")}</ul>`;

const data = [
	['<1m', ul(['GBS', 'Negative enteric bacilli']),''],
	['1-3m', ul(['<span class="hl2">Chlamydia</span>', 'S. pneumoniae', 'S. aureus', 'H. influenzae', 'B. pertussis']), ul(['RSV', 'Parainfluenza'])],
	['3m-5y', ul(['S. pneumoniae', 'H. influenzae']), ul(['RSV', 'Parainfluenza', 'Influenza', 'Adenovirus', 'Human metapneumovirus', 'Rhinovirus'])],
	['5-15y', ul(['S. pneumoniae', 'M. pneumoniae', '<span class="hl2">Chlamydophila</span>']),''],
];

const header = ['', 'Bacteria', 'Virus']
// @no-refresh
dv.table(header, data);
dv.container.classList.add('top', 'side', 'middle', 'center');
```
# Clinical feature
## History
- <span class='hl1'>ไข้ ไอ หอบ</span>
- Fever <span class='hl2'>ยกเว้น Chlamydia อาจจะไม่มี</span>
- ซึม เบื่ออาหาร 
## PE
- Tachypnea, dyspnea
- Retraction
- Fine crepitation ± wheeze
- ± Pleuritic chest pain 
## Investigation
- CBC
	- WBC > 15k & polymorphonuclear = bacteria
- CXR
	- Perihilar, interstitial infiltration = virus
	- Lobar consolidation = bacteria
	- Pneumotocele = S. aureus
		![[image-26.png|200]]
- H/C ทำใน systemic infection
- ± Sputum culture = ถ้าไอเสมหะได้
- ± ESR, CRP
- ± Cold agglutinin test = M. pneumoniae <span class="hl4">(sens spec ต่ำ)</span>

- ATK RSV, adeno, parainflu, influ
# Management
## Admission & ICU
- Indication for admission
	- Retraction 
	- หยุดหายใจเป็นพัก / เสียง grunting
	- SpO2 < 92 on RA
	- เบื่ออาหาร dehydration
	- Sign of shock
	- S. aureus / GAS
	- U/D = chronic lung, heart dz
	- ไม่ดีขึ้นใน 48hr
	- ไม่มีคนดูเเล
	- Complication = pleural effusion, empyema thoracis
- Indication for ICU
	- Tachypnea, tachycardia + severe respiratory distress
	- หยุดหายใจบ่อย
	- SpO2 < 92 on FiO2 0.6
	- Shock
## Viral pneumonia 
- ให้ supportive 
- ยกเว้น influ ให้เป็นถ้ามาภายใน 48hr, immunocompromised หรือ <2yo
	- Oseltamivir bid x 5
![[Screenshot 2569-01-05 at 22.24.58.png]]
## Bacteria pneumonia
### Grading
- <1mo นับเป็น severe หมด
![[Screenshot 2569-01-05 at 22.23.20.png]]
### Not severe (OPD case)
<table id="editor" class="top center">
        <thead><tr>
          <th>Age group</th>
        <th>ATB</th><th>Dose</th><th>Bacteria</th></tr></thead><tbody>
      <tr><td>1mo - 18yo</td><td>Amoxicillin</td><td>40-50 mgKDay<br>max 2000-3000 mgDay<br>tid x 7d</td><td><ul><li>H. influenzae</li><li>S. pneumoniae</li></ul></td></tr><tr><td rowspan="2" colspan="1">1-3 mo</td><td>Erythromycin</td><td>40-50 mgKDay&nbsp;<br>max 2000 mgDay<br>qid x 14d</td><td rowspan="2" colspan="1"><ul><li>C. trachomatis</li></ul></td></tr><tr><td>Azithromycin</td><td>10-20 mgKDay<br>max 500 mgDay<br>OD x 3-5d</td></tr></tbody></table>
  
### Severe (IPD case)
<table class="top center middle">
	<thead><tr>
		<th>Age group</th>
		<th colspan="2">ATB</th>
		<th>Dose</th>
		<th>Bacteria</th>
	</tr></thead>
	<tbody><tr>
		<td>&lt;1mo</td>
		<td>Penicillin<br>Ampicillin</td>
		<td>Aminoglycoside<br>3gen ceph</td>
		<td>IV x 7-10d</td>
		<td><ul><li>S. pneumoniae</li></ul></td>
	</tr><tr>
		<td>1mo - 18yo</td>	
		<td>Ampicillin<br>Ceftriaxone<br>Cefotaxime</td>
		<td>Erythromycin<br>Clarithromycin<br>Azithromycin</td>
		<td></td>
		<td><ul><li>M. pneumoniae</li><li>C. pneumoniae</li></ul></td>
	</tr><tr>
		<td></td>
		<td colspan="2">Cloxacillin</td>
		<td>IV</td>
		<td><ul><li>S. aureus</li></ul></td>
	</tr><tr>
		<td></td>
		<td colspan="2">Erythromycin<br>Azithromycin</td>
		<td>x 14d<br>3-5d</td>
		<td><ul><li>C. trachomatis</li></ul></td>
	</tr></tbody>
</table>

# Complication
- Parapneumonic effusion / empyema thoracis
	- มีไข้หลังได้ ATB 
	- เจอบ่อยใน S. pneumoniae 
- Lung abscess
- เฉพาะ S. aureus
	- Pneumatocele
	- Pneumothorax
- เฉพาะ M. pneumoniae
	- SJS
	- Hemolytic anemia
	- Pancreatitis, hepatitis
	- Pericarditis, myocarditis 
