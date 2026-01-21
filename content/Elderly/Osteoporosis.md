---
File:
  - https://www.icloud.com/iclouddrive/059XD_z7_ivWh4SB-WSTdOcBA#Fall_and_osteoporosis
  - https://www.icloud.com/iclouddrive/007z_SMkvRNqhGowRewdiwUVA#Osteoporosis_rehabilitation
---
# Diagnosis criteria
- Spine / hip fracture from mild trauma
- T-score ≤ -2.5
- -1.0 ≤ T-score ≤ -2.5 <span class='hl3'>+</span> FRAX hip fracture risk ≥ 3%
- -1.0 ≤ T-score ≤ -2.5 <span class='hl3'>+</span> Fracture at proximal humerus, pelvis, forearm from mild trauma
# Investigation
## <span class='hl1'>FRAX score</span> #Elderly/imo
- หญิง เเก่ ผอม เตี้ย เครียด RA on steroid สูบบุหรี่ ดื่มเหล้า เเม่เคยหัก

> [!tip] Common Fx location
> Hip wrist spine humerus

## Bone mineral density (BMD)
### Criteria for testing
- Age
	- Female > 65yr
	- Male > 70yr
- Early menopause < 45yr / bilateral oophorectomy
- Hypoestrogenism > 1yr
- Post menopausal < 65yr with
	- Prednisolone 5mg/d > 3mo
	- Parental hip fracture
	- BMI < 20
	- Height loss ≥ 4cm
	- Aromatase inhibitor (CA breast) / Androgen deprivation therapy (CA prostate)
	- Radiographic osteopenia
	- Hx of fragility fracture (หักจาก standing height)
- F/U after osteoporosis Tx q1-2yr
### Testing site = เอาตัวที่เเย่ที่สุด
- Lumbar spine
- Femoral neck / total hip
- Distal radius ในกรณีสงสัย hyperparathyroidism เพราะทำให้มีปัญหาที่ cortical bone
### Interpretation
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Normal', 'T-score ≥ -1.0'],
	['Osteopenia', '-2.5 < T-score < -1.0'],
	['Osteoporosis', 'T-score ≤ -2.5'],
	['Severe osteoporosis', 'T-score ≤ -2.5 <span class="hl3">+</span> fragility fracture'],
];

const header = ['Diagnosis', 'BMD']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top");
```
# Management
## Nonpharm
- กินอาหาร
	- TP 1-1.2 g/kg/d
	- Ca 1,000-2,000 mg/d = นมถั่วเหลือง ปลา ไข่ไก่
	- Vit-D 20,000 unit/wk = เห็ดหอม เเซลมอน
		- Keep 25OHD 30-50 ng/dL
- Weight bearing & resistance exercise
- Stop smoking
- Restrict alcohol 
- Caffeine < 400 mg/d
## Pharm
- Bisphosphonate = <span class='hl2'>1st line</span>
	- Option
		- Alendronate
		- Risedronate
		- Zoledronic acid
		- Ibandronate
	- Bisphosphonate holiday = สามารถหยุดยาได้หลับกินติดต่อกัน เพราะยาสะสมในกระดูก
	- S/E
		- Acute phase reaction in IV = fever & myalgia
		- GI irritation = esophagitis, ulcer
		- Atypical femoral fracture เจอในคนที่ใช้ยานานๆ ทำให้ cortex หนาเเต่ medulla บาง
			- PO 5yr
			- IV 3yr
		- Osteonecrosis of jaw
	- C/I
		- GFR < 30 = risedronate / ibandronate
		- GFR < 35 = alendronate / zoledronic acid
		- ไม่เเน่นำในคนที่เป็น GERD เพราะ S/E จะเเรงกว่าคนปกติ
- Monoclonal Ab to RANKL
	- Option = denosumab(60) sc q6mo
	- S/E 
		- Hypocalcemia
		- Atypical femoral fracture
		- Osteonecrosis of jaw
	- C/I = pregnancy / lactation

# Fracture
## Investigation
- X-ray
	- Wrist = PA + lateral
	- Hip = AP + <span class='hl1'>lateral cross table</span>
## Management
- In proximal humerus Fx
	- Internal fixation w/in 48hr + early ambulation