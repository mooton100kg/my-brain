---
File:
---

# Surgical anatomy (couinaud classification)
![[IMG_4834.jpeg|300]]
- Segment 1 = anterior to IVC / posterior to portal vein
- Hepatic vein เเบ่งด้าน vertical ออกเป็น 4 ส่วน
- Portal vein เเบ่งด้าน hortizon ออกเป็น 2 ส่วน <br>
- Brisbane terminology = ใช้เรียก lobe ทำการ resection
# Child-Pugh score
- ใช้ประเมิน prognosis of chronic liver disease

> [!tip] วิธีจำ Child-Pugh score
> - **น้ำ** = ascites
> - **ซึม** = encephalopathy
> - **ไข่** = albumin
> - **เเข็ง** = PT or INR
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Ascites', 'None', 'Small or diuretic controlled', 'Tense'],
	['Encephalopathy', 'Absent', 'State I-II', 'State III-IV'],
	['Albumin (g/L)', '&gt; 3.5', '2.8-3.5', '&lt; 2.8'],
	['Bilirubin (mg/dL)', '&lt; 2', '2-3', '&gt; 3'],
	['PT<br>INR', '&lt; 4<br>&lt; 1.7', '4-6<br>1.7-2.3', '&gt; 6<br>&gt; 2.3'],
];

const header = ['S/S', '1', '2', '3']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'side', 'center');
```
- Class A = 5-6
- Class B = 7-9
- Class C = 10-15
# Liver tumor
```dataviewjs
/* const data = [
  ["2020–2021", "Intern"],
  ["2022–2023", "Resident"],
  ["2024–present", "Fellow"]
]; */

const data = [
	['Hemangioma = M/C', 'HCC'],
	['Focal nodular hyperplasia', 'Intrahepatic cholangiocarcinoma'],
	['Adenoma', 'Metastasis = M/C'],
	['Liver cysts', ''],
];

const header = ['benign', 'Malignant']
// @no-refresh
dv.table(header, data);
dv.container.classList.add("top", 'center');
```
## Hepatocellular carcinoma (HCC)
- CA อันดับ 6
- Most common primary CA liver
- Incidence = 10/100k <br>
- Risk factor = cirrhosis
	- HBV, HCV
	- Alcohol
	- Aflatoxin B1
	- Non-alcoholic fatty liver disease
	- DM
	- Smoking
### S/S
- <span class="hl2">Wt loss & RUQ pain</span>
- Worsening of pre-existing chronic liver disease
- Acute liver failure<br>
- Sigh of cirrhosis
- Hard enlarged RUQ mass<br>
- Rupture HCC = acute abdominal pain, hemodynamic instability
### Investigation
- AFP (alpha feto protein)
	- Cutoff = 10-20
	- Highly suggestive = > 200
- US
- CT with contrast <span class="hl1">(diagnosis)</span> = early enhancement in arterial phase + rapid wash out in postvenous phase
	![[IMG_4835.jpeg|300]]
- MRI = hepatocyte-specific contrast
- Biopsy

> [!tip] LI-RADS = imaging finding
> - LR-1 = Definitely benign
> - LR-2 = Likely benign
> - LR-3 = Intermediate likelihood of HCC
> - LR-4 = Likely HCC
> - LR-5 = **Definitely HCC**
> - LR-TIV = Definite tumor in vein (not specific for HCC)
> - LR-M = Likely malignant (not specific for HCC)

### Screening
- Indication
	- HBV carrier
		- Male > 40yr
		- Female > 50yr
		- Fm Hx
	- Cirrhotic HBV/HCV
	- Stage 4 primary biliary cirrhosis
	- Genetic hemachromatois & cirrhosis
	- Alpha 1 antitrypsin def
- Duration
	- No liver nodule = US q6m
	- Liver nodule <1cm = US q3m
	- Liver nodule >1cm = MRI ± Bx
### Management
 - Barcelona guideline
	 - Single ≤ 2cm = Resection / ablation
	 - 3 nodule ≤ 3cm / portal hypertension = LT
	 - Multinodular = TACE
	 - Portal invasion = targeted therapy
	 ![[Screenshot 2568-12-22 at 15.36.08.png]]
 - APASL
	 ![[Screenshot 2568-12-22 at 15.36.27.png]]
#### Resection
- Factor affecting resectability
	- Size
	- Number of tumor
	- Involvement of major structure
	- Hepatic function
	- No extra-hepatic spread
	- No portal hypertension
- ถ้ามี ascites ห้ามผ่าเด็ดขาด
#### Liver transplantation
- Indication ตาม Milan criteria
	- Single tumor ≤ 5cm <span class="hl3">or</span>
	- 2-3 tumor ≤ 3cm <span class="hl3">and</span>
	- No vascular invasion / extrahepatic spread
#### Local ablation
- Option
	- Ethanol injection
	- Radiofrequency / microwave ablation
#### TACE (transcatheter arterial chemoembolization)
- Delays tumor progression & vascular invasion
#### Systemic therapy
- Sorafenib
## Cholangiocarcinoma
- Incidence = 2/100k (ในไทยเยอะกว่านี้ เเล้วเเต่ภาค)
- Classification
	- Intrahepatic
	- Perihilar
	- Distal = cystic duct junction → ampulla of vater 
	![[Sx/Lecture/Img/Liver Tumors (Part 2).png]]
- Risk factor
	- Primary sclerosing cholangitis
	- Congenital biliary cystic dz, choledochal cyst, caroli's dz
	- <span class='hl1'>Parasite infection</span> = opisthorchis, chlonorchis
## Hepatic hemangioma
### Investigation
- US = well-defined hyperechoic lesion
- CT
	- Arterial phase = discontinuous, nodular, peripheral enhancement
	- Portal venous phase = progressive peripheral enhancement iwth more centripetal fill-in
- MRI = hypointense in T1, hyperintense in T2