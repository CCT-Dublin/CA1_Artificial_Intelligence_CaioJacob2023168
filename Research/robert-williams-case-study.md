# Case Study: Robert Williams and the Detroit Police Department

## 1. Introduction

Facial recognition is an application of Computer Vision that analyses facial images to estimate whether two images show the same person. It can support identity verification and help investigators search for possible suspects. However, its results can be affected by image quality, algorithm performance and the procedures followed by the people using it.

The case of Robert Williams demonstrates how an incorrect facial recognition result can contribute to a wrongful arrest. It also illustrates why technical systems need appropriate human oversight, reliable evidence and clear operational safeguards.

## 2. What Happened?

In October 2018, a theft involving watches was recorded by a surveillance camera at a shop in Detroit, United States. Investigators later used a still image from the footage to search for a possible match in a database of driving licence photographs.

The surveillance image was of poor quality, with limited lighting and the person’s face not clearly visible. The facial recognition search incorrectly identified Robert Williams as a possible match. Police subsequently used his photograph in a photo line-up presented to a shop security consultant who had not witnessed the theft in person.

Williams was arrested at his home on 9 January 2020, in front of his family. He was detained for approximately 30 hours before being released. He was not the person shown in the surveillance footage (American Civil Liberties Union, 2024).

The case raised questions not only about the accuracy of facial recognition but also about the investigation that followed the result. The incorrect match was treated as a basis for further investigative steps without sufficient independent verification.

## 3. How the Computer Vision System Was Used

Facial recognition systems analyse facial characteristics in digital images and compare them to estimate similarity. Depending on the application, a system may compare two images or search a larger database for possible candidates.

In this case, the police used a one-to-many identification search: an image of an unknown person was compared with photographs in a database. The result identified Williams as a possible candidate. This type of result should be treated as an investigative lead rather than proof of identity or involvement in a crime.

The case illustrates an important limitation of Computer Vision. A system can produce a plausible-looking match even when the images do not show the same person. Poor lighting, low image quality and an unclear facial view can make reliable comparison more difficult.

The available case sources do not establish the precise internal calculations or model architecture used to generate the match. Therefore, this analysis focuses on the documented use of the technology rather than assuming details about the specific algorithm.

## 4. Technical and Human Factors

The case involved both a technical error and failures in the investigative process.

### Technical factors

The surveillance image was blurry and poorly lit. The face was not clearly visible, making it a difficult input for reliable identification. The result was incorrect, demonstrating that a system's output can be misleading when the input image is unsuitable.

Research published by the National Institute of Standards and Technology (NIST) found that demographic differences in facial recognition performance vary across algorithms and applications. The study also distinguished false positives, where different people are incorrectly matched, from false negatives, where images of the same person fail to match (Grother, Ngan and Hanaoka, 2019).

These findings provide broader evidence that facial recognition systems require careful evaluation. They do not, by themselves, establish the precise technical cause of the error in Williams's case.

### Human factors

The investigation continued after the incorrect match. Williams's photograph was included in a photo line-up, and the resulting identification contributed to the case against him. The incident highlights the danger of treating an automated result as reliable without independently checking the supporting evidence.

Human oversight must involve more than simply having a person review a system's output. Investigators need to understand the system's limitations, question uncertain results and seek independent evidence before taking consequential action.

## 5. Ethical Impacts

### Accuracy and reliability

A false match can have serious consequences when used in criminal investigations. The case shows why facial recognition results should not be treated as conclusive evidence.

### Fairness and discrimination

Williams is Black, and the case formed part of a wider discussion about demographic differences in facial recognition performance. NIST research found that demographic differentials occur across many tested algorithms, although the size and direction of these differences vary by algorithm and task (Grother, Ngan and Hanaoka, 2019).

The case should not be used to claim that every facial recognition system is equally biased. Instead, it demonstrates why performance must be independently tested and why the consequences of errors must be considered for different groups.

### Accountability

Responsibility cannot be assigned to the software alone. Organisations must establish appropriate procedures for selecting images, interpreting results, verifying leads and making decisions. The case raises questions about the responsibility of investigators and the safeguards required when AI contributes to decisions affecting individual freedom.

## 6. Social Impacts

Williams's arrest affected his freedom, dignity and family life. He was arrested in front of his wife and young children and spent approximately 30 hours in detention for a crime he did not commit (American Civil Liberties Union, 2024).

Such incidents can undermine public confidence in both law enforcement and AI technologies. They may also create concerns that particular communities could be disproportionately affected by inaccurate identification.

More broadly, the case demonstrates that the social impact of AI depends not only on technical accuracy but also on how organisations use the technology and respond when something goes wrong.

## 7. Legal Consequences and the 2024 Settlement

In April 2021, civil rights organisations filed a federal lawsuit on Williams's behalf. The case concluded with a settlement announced on 28 June 2024 (University of Michigan Law School, 2024).

The settlement introduced several safeguards for the Detroit Police Department:

- Police cannot arrest someone solely on the basis of a facial recognition result or a photo line-up directly following a facial recognition search.
- Independent and reliable evidence must link a suspect to a crime before a photo line-up can be conducted on the basis of a facial recognition investigative lead.
- Police officers must receive training about the technology's risks and limitations.
- An audit must cover cases dating back to 2017 in which facial recognition was used to obtain an arrest warrant.
- The court retains jurisdiction to enforce the settlement for four years.

The settlement is significant because it establishes practical limits on how police can use facial recognition. It should be described as a settlement introducing safeguards, rather than as a court judgment that every use of facial recognition is unlawful.

Because the case occurred in the United States, its legal outcome should be distinguished from European Union legislation, including the GDPR and the EU Artificial Intelligence Act.

## 8. Benefits of Facial Recognition

Facial recognition can help investigators search large collections of images and generate possible investigative leads. When appropriately designed, tested and used, it may reduce the time required to compare images manually.

However, its usefulness depends on the application, the quality of the images, the performance of the algorithm and the safeguards surrounding its use. The potential benefits do not justify treating a possible match as proof of identity.

The Williams case therefore supports a balanced conclusion: facial recognition may have legitimate uses, but its results must be interpreted cautiously and supported by independent evidence when decisions have serious consequences.

## 9. Recommendations and Mitigation

The case suggests several practical measures for organisations using facial recognition:

1. **Require independent evidence:** A facial recognition result should be an investigative lead, not the sole basis for arrest or other serious action.
2. **Assess image quality:** Images that are blurry, poorly lit or unsuitable for reliable comparison should be treated with caution.
3. **Test demographic performance:** Systems should be evaluated across relevant demographic groups and real-world conditions. Results should be reviewed regularly because performance differs across algorithms.
4. **Train operators and investigators:** Staff should understand false matches, system limitations and the risks of relying too heavily on automated recommendations.
5. **Document decisions:** Organisations should record how results were used, what independent evidence was obtained and why consequential decisions were made.
6. **Establish accountability and audits:** Clear policies, independent review and retrospective audits can help identify failures and prevent similar incidents.
7. **Protect individual rights:** Facial recognition should be used only for a defined and legitimate purpose, with appropriate legal safeguards and oversight.

The 2024 Detroit settlement provides a real-world example of several of these safeguards being incorporated into police procedures (University of Michigan Law School, 2024).

## 10. Conclusion

The Robert Williams case demonstrates how an incorrect facial recognition result can contribute to serious harm when it is not adequately verified. The incident involved a technical false match as well as weaknesses in the subsequent investigation.

Independent research by NIST shows that facial recognition performance varies across algorithms and demographic groups. This evidence supports the need for testing, transparency and cautious interpretation, without implying that every system performs identically.

The central lesson is that responsible Computer Vision requires more than improving technical accuracy. Organisations must also establish effective human oversight, independent verification, accountability and safeguards that protect individuals from the consequences of incorrect results.

## References Used in This Research

American Civil Liberties Union (2024) *Williams v. City of Detroit*. Available at: https://www.aclu.org/cases/williams-v-city-of-detroit-face-recognition-false-arrest (Accessed: 14 October 2026).

Grother, P., Ngan, M. and Hanaoka, K. (2019) *Face Recognition Vendor Test (FRVT) Part 3: Demographic Effects*. NIST Interagency Report 8280. Gaithersburg, MD: National Institute of Standards and Technology. Available at: https://doi.org/10.6028/NIST.IR.8280 (Accessed: 14 October 2026).

University of Michigan Law School (2024) ‘Civil Rights Litigation Initiative Helps Achieve the Nation’s Strongest Police Department Policy on Facial Recognition Technology’, 28 June. Available at: https://michigan.law.umich.edu/news/civil-rights-litigation-initiative-helps-achieve-nations-strongest-police-department-policy (Accessed: 14 October 2026).