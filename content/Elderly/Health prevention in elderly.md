---
File:
  - https://www.icloud.com/iclouddrive/046Gik-uqzaoUqLRuTAA7bL5Q
---
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['HT', '', '&gt;18yr = q1yr'],
	['DLP', 'Total cholesterol<br>HDL', '20&minus;75yr = q5yr<br><br>**Stop screening** after &gt;75yr<br>(if no CVD risk)'],
	['Obesity', 'Waist circumference<br>Male &lt; 90cm<br>Female &lt; 80cm', '&gt;18yr = q1yr'],
	['Depression', 'PHQ&minus;9', '&gt;60yr = q1yr'],
	['Osteoporosis', 'FRAX score' ,'&gt;60yr = q1yr'],
	['Eye', '', '60&minus;64yr = q2-4yr<br>&gt;60yr = q1-2yr'],
	['Fall' ,'Time up and Go', '&gt;60yr = q1yr'],
	['Teeth', '', '&gt;60yr = q1yr'],
	['CA breast', 'Pap smear<br>HPV<br>Acetic acid', '30&minus;65yr = q3yr<br>30&minus;65yr = q5yr<br>30&minus;55yr = q5yr<br><br>**Stop screening** after 65yr<br>(if negative x2 in 10yr)'],
	['Colorectal cancer', 'Fecal occult blood', '&gt;50yr = q1yr'],
];

const header = ['Disease', 'Screening', 'Recommendation']
// @no-refresh
dv.table(header, data);
dv.container.classList.add('top','side','center');
```
