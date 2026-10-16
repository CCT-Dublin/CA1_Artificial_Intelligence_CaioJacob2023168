# Poster Content Plan: Computer Vision and Facial Recognition

**Student Name:** Caio Jacob  
**Student ID:** 2023168  
**Programme:** BSc (Hons) in Computing in IT  
**Module:** Artificial Intelligence (Stage 4, Semester 1)  
**Assessment:** CA1 (40%)  
**College:** CCT College Dublin  
**Selected AI System:** Computer Vision (Facial Recognition Technology)  
**Real-World Case Study:** Robert Williams and the Detroit Police Department  

---

## Poster Title & Header Block

* **Main Title:** Computer Vision in Law Enforcement: Ethical, Legal, and Social Impacts of Facial Recognition
* **Subtitle:** The Robert Williams Case Study and Approaches to Responsible Use
* **Student Details:** Caio Jacob (Student ID: 2023168)
* **Institution:** Department of Information Technology, CCT College Dublin
* **Module:** Artificial Intelligence | **Lecturer:** David McQuaid

---

## Section 1: AI System – Computer Vision & Facial Recognition (20 Marks)

Computer Vision (CV) is a specialized branch of Artificial Intelligence enabling computational systems to process, analyze, and extract structured semantic representations from digital visual inputs, including still images and video streams (Caballar and Stryker, 2025). The foundational pipeline encompasses digital image acquisition, pre-processing, feature extraction, and mathematical classification or similarity comparison (Sturdevant, 2023).

Within Computer Vision, Facial Recognition Technology (FRT) maps spatial facial geometry, nodal distances, and biological contours into high-dimensional numerical feature vectors, termed face embeddings. Recognition operates across two primary paradigms:
1. **One-to-One (1:1) Verification:** Authenticates an individual's identity by comparing a captured face vector against a single enrolled biometric template (e.g., automated border control gates).
2. **One-to-Many (1:N) Identification:** Scans an unknown probe image across a large gallery database to return candidate identities ranked by mathematical similarity scores.

In law enforcement, 1:N facial recognition is deployed to identify unknown suspects from surveillance cameras or crime scene photography. When designed and evaluated responsibly, the technology provides substantial investigative benefits by rapidly screening massive image repositories that would otherwise require exhaustive, error-prone manual searching (Caballar and Stryker, 2025). However, algorithm accuracy depends critically on input resolution, illumination, angle, and whether underlying neural models exhibit uniform performance across diverse human demographics.

*(Word Count: 201 words)*

---

## Section 2: Ethical, Legal, and Social Impacts (30 Marks)

Deploying Computer Vision in high-stakes public settings generates interrelated ethical, legal, and social repercussions:

### Ethical Impacts
* **Algorithmic Performance Differentials:** NIST evaluations have identified demographic differences in the error rates of tested facial recognition algorithms, although the magnitude and direction of these differences vary across algorithms and applications (Grother, Ngan and Hanaoka, 2019).
* **Automation Bias:** Over-reliance on automated recommendations can lead users to give excessive weight to probabilistic AI outputs, particularly when the limitations of the system are not properly understood.

### Legal Impacts
* **Regulatory Frameworks:** Although the Robert Williams case occurred in the United States, the European context illustrates how facial recognition is legally governed. Under Article 9 of the General Data Protection Regulation (GDPR), processing biometric data for unique identification is generally prohibited absent strict statutory exemptions (European Parliament and Council, 2016). Furthermore, the EU Artificial Intelligence Act restricts real-time remote biometric surveillance in public spaces for law enforcement (European Parliament and Council, 2024).
* **Due Process:** Treating uncorroborated algorithmic outputs as probable cause infringes upon constitutional guarantees and the presumption of innocence.

### Social Impacts
* **Erosion of Public Trust:** Biometric misidentifications and perceived disparities can undermine community trust in law enforcement institutions.
* **Chilling Effect on Civil Liberties:** Pervasive, unconsented biometric monitoring across public spaces may suppress freedom of assembly and democratic civic participation (UNESCO, 2021).

*(Word Count: 220 words)*

---

## Section 3: Real-World Case Study – Robert Williams & Detroit Police (20 Marks)

In October 2018, a shoplifting incident involving luxury watches occurred at a retail store in Detroit, Michigan. Investigators obtained a low-resolution, poorly illuminated still image from store surveillance footage and executed an automated 1:N facial recognition search against a statewide database containing millions of driver's license photographs.

The system returned an incorrect candidate match identifying Robert Williams, an innocent Black man. Rather than treating this result purely as an unverified investigative lead, detectives placed Williams's photograph in a photo line-up shown to an off-site loss-prevention contractor who had not witnessed the theft in person. Based on this tainted identification, an arrest warrant was issued.

On 9 January 2020, Williams was arrested on his front driveway in front of his wife and two young daughters (aged 2 and 5) and held in custody for approximately 30 hours (American Civil Liberties Union, 2024). During interrogation, detectives placed the surveillance still next to Williams's license photo and realized the obvious visual discrepancy, conceding that "the computer must have got it wrong."

This case demonstrates how a poor-quality image, an incorrect facial recognition result, and insufficient independent verification can contribute to severe real-world harm: wrongful deprivation of liberty, personal trauma, and unjustified criminal records (University of Michigan Law School, 2024).

*(Word Count: 206 words)*

---

## Section 4: Mitigations, Recommendations & Maximizing Benefits (Contextual Analysis)

To preserve the positive investigative utility of Computer Vision while mitigating societal harms, organizations must implement a multi-layered governance model:

1. **Mandate Independent Corroborating Evidence:** Algorithmic matches must remain preliminary investigative leads. The landmark June 2024 Detroit settlement legally prohibits arrests or photo line-ups based solely on facial recognition outputs without independent corroborating evidence linking the suspect to the crime (University of Michigan Law School, 2024).
2. **Enforce Input Quality Thresholds:** Strict technical pre-screening must automatically reject blurred, low-resolution, or poorly illuminated imagery unsuitable for reliable biometric feature extraction.
3. **Continuous Demographic Auditing:** Systems must undergo independent, ongoing benchmarking using NIST standards to identify, measure, and reduce demographic differences in accuracy (Grother, Ngan and Hanaoka, 2019).
4. **Meaningful Human Oversight:** Officers must receive comprehensive training on automation bias and algorithm limitations, ensuring automated suggestions are critically scrutinized rather than passively accepted.
5. **Auditing and Redress Mechanisms:** Law enforcement agencies must maintain searchable query logs and conduct retrospective audits of past cases to ensure accountability and rectify wrongful arrests (University of Michigan Law School, 2024).

Implementing these technical and operational safeguards ensures that Computer Vision accelerates legitimate criminal investigations while rigorously upholding civil liberties, fairness, and fundamental human rights.

*(Word Count: 198 words)*

---

## Summary Word Count Table (Body Text Only)

| Poster Section | Weighting | Word Count |
| :--- | :--- | :--- |
| **Section 1: AI System – Computer Vision & Facial Recognition** | 20 marks | 201 words |
| **Section 2: Ethical, Legal, and Social Impacts** | 30 marks | 220 words |
| **Section 3: Real-World Case Study (Robert Williams)** | 20 marks | 206 words |
| **Section 4: Mitigations, Recommendations & Balancing Impacts** | Context / Synthesis | 198 words |
| **Total Core Poster Body Text** | **100% of body text** | **825 words** |

*(Requirement: 500–1000 words. 825 words sits exactly within the ideal 700–850 word range for maximum poster legibility without visual clutter. Titles, headers, author details, and references are excluded per assignment brief).*

---

## Section 5: References (Harvard Style)

* American Civil Liberties Union (2024) *Williams v. City of Detroit*. Available at: https://www.aclu.org/cases/williams-v-city-of-detroit-face-recognition-false-arrest (Accessed: 14 October 2026).
* Caballar, R.D. and Stryker, C. (2025) ‘What is computer vision?’, *IBM Think*, 17 September. Available at: https://www.ibm.com/think/topics/computer-vision (Accessed: 10 October 2026).
* European Parliament and Council of the European Union (2016) ‘Regulation (EU) 2016/679 of the European Parliament and of the Council of 27 April 2016 (General Data Protection Regulation)’. *Official Journal of the European Union*, L 119, pp. 1–88. Available at: https://eur-lex.europa.eu/eli/reg/2016/679/ (Accessed: 10 October 2026).
* European Parliament and Council of the European Union (2024) ‘Regulation (EU) 2024/1689 of the European Parliament and of the Council of 13 June 2024 laying down harmonised rules on artificial intelligence (Artificial Intelligence Act)’. *Official Journal of the European Union*. Available at: https://eur-lex.europa.eu/eli/reg/2024/1689/oj (Accessed: 10 October 2026).
* Grother, P., Ngan, M. and Hanaoka, K. (2019) *Face Recognition Vendor Test (FRVT) Part 3: Demographic Effects*. NIST Interagency Report 8280. Gaithersburg, MD: National Institute of Standards and Technology. Available at: https://doi.org/10.6028/NIST.IR.8280 (Accessed: 14 October 2026).
* Sturdevant, M. (2023) ‘Introduction to computer vision’, *IBM Developer*, 5 March. Available at: https://developer.ibm.com/articles/introduction-computer-vision/ (Accessed: 10 October 2026).
* UNESCO (2021) *Recommendation on the Ethics of Artificial Intelligence*. Paris: UNESCO. Available at: https://www.unesco.org/en/artificial-intelligence/recommendation-ethics (Accessed: 10 October 2026).
* University of Michigan Law School (2024) ‘Civil Rights Litigation Initiative Helps Achieve the Nation’s Strongest Police Department Policy on Facial Recognition Technology’, 28 June. Available at: https://michigan.law.umich.edu/news/civil-rights-litigation-initiative-helps-achieve-nations-strongest-police-department-policy (Accessed: 14 October 2026).
