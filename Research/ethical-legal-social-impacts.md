# Ethical, Legal and Social Impacts of Computer Vision

## 1. Introduction

Computer Vision can be used in many areas, including healthcare, transport, manufacturing and security. These applications can help automate tasks and process visual information more quickly. However, the consequences depend on how the technology is used and who may be affected by its results.

For example, an error in an industrial inspection system may allow a defective product to pass a quality check. An incorrect facial recognition result could have more serious consequences if it leads to a person being questioned or wrongly suspected of an offence. The risks therefore need to be considered in relation to the specific application rather than treating all Computer Vision systems as equally risky.

## 2. Ethical Impacts

### 2.1 Accuracy and reliability

One ethical concern is whether a Computer Vision system produces reliable results. An incorrect prediction can affect decisions about people, products or services. This is particularly important when the output is used in areas such as healthcare, security or law enforcement.

Facial recognition provides a useful example. The National Institute of Standards and Technology (NIST) evaluates face recognition algorithms and reports differences in error rates between demographic groups. Its findings show that performance can vary depending on the algorithm, the image quality and the group being assessed (NIST, 2026).

This means that a system should be tested under conditions similar to those in which it will actually be used. Organisations should not assume that a model performs equally well for every person or environment.

### 2.2 Bias and discrimination

Computer Vision systems learn patterns from data. If the training data does not represent the population or conditions in which the system will be used, performance may be uneven.

NIST reports demographic differences in face recognition error rates, including differences associated with age, sex and race. The size and direction of these differences depend on the algorithm and the evaluation conditions (NIST, 2026).

Unequal performance can create unfair outcomes. For example, a false match in a security or policing context may lead to additional questioning or further investigation of an innocent person. Developers and organisations should therefore evaluate performance across relevant demographic groups and investigate differences before deploying a system.

### 2.3 Privacy and consent

Computer Vision systems may process images containing identifiable people. In some settings, cameras collect images without individuals actively choosing to provide them. This raises questions about whether people know that their images are being collected, why the images are needed and how long the data will be retained.

Facial recognition creates additional concerns because it can be used to identify or verify individuals. The UNESCO Recommendation on the Ethics of Artificial Intelligence identifies privacy and data protection as important principles throughout the AI lifecycle (UNESCO, 2021).

Organisations should consider whether collecting visual data is necessary for the intended purpose and whether a less intrusive alternative is available. They should also explain how the data will be used and apply appropriate safeguards.

## 3. Legal Impacts

### 3.1 Data protection and biometric data

In the European Union, the General Data Protection Regulation (GDPR) provides rules for processing personal data. Article 9 identifies biometric data processed for the purpose of uniquely identifying a natural person as a special category of personal data. Its processing is generally prohibited unless a relevant exception under the Regulation applies (European Parliament and Council of the European Union, 2016).

This is relevant to facial recognition systems that process facial data to identify individuals. Organisations need to establish an appropriate legal basis and determine whether the additional conditions for processing special-category data are satisfied. They must also consider other applicable GDPR requirements.

Not every use of Computer Vision involves biometric identification. For example, detecting a damaged product does not necessarily involve identifying a person. The legal requirements depend on the data being processed and the purpose of the system.

### 3.2 Regulation of AI systems

The EU Artificial Intelligence Act establishes a regulatory framework for AI systems and includes specific rules concerning certain biometric applications. It restricts the use of real-time remote biometric identification in publicly accessible spaces for law enforcement, subject to narrowly defined exceptions and safeguards (European Parliament and Council of the European Union, 2024).

The Regulation also addresses concerns such as the potential effects of inaccurate results, discrimination and interference with fundamental rights. Its requirements depend on the type of system and the intended use.

Organisations should therefore identify which legal requirements apply before deploying a Computer Vision system. They should not assume that a system is lawful simply because it is technically effective.

## 4. Social Impacts

### 4.1 Public safety and useful services

Computer Vision can support activities that benefit society. In healthcare, image analysis may assist professionals in examining medical images. In transport, visual systems can help detect pedestrians, vehicles and road features. In manufacturing, automated inspection can help identify defects.

These applications may improve efficiency and support human decision-making. However, the actual benefits depend on the system's performance and the way people use its results. A system that supports a professional should not automatically replace appropriate human judgement.

### 4.2 Surveillance and public trust

The use of cameras and facial recognition in public places can raise concerns about continuous surveillance. People may not know when their images are being analysed or how the results will be used.

The EU Artificial Intelligence Act recognises that real-time remote biometric identification for law enforcement can affect privacy and other fundamental rights, including freedom of assembly (European Parliament and Council of the European Union, 2024).

If people believe that their movements are constantly being monitored, they may become less comfortable participating in public activities. This can affect trust in organisations that use the technology.

### 4.3 Unequal consequences

The consequences of an error may not be the same for everyone. If a system produces different error rates across demographic groups, some people may face a greater risk of incorrect identification.

The NIST findings on demographic differences in facial recognition provide evidence that this concern should be evaluated rather than assumed to be the same across all systems (NIST, 2026).

Organisations should assess who may be affected, how serious the consequences could be and whether people have a way to challenge an incorrect result.

## 5. Possible Mitigation Measures

Several measures could reduce the risks associated with Computer Vision:

- **Testing:** evaluate the system using relevant data and conditions before deployment.
- **Fairness assessment:** measure performance across relevant demographic groups and investigate significant differences.
- **Human oversight:** ensure that consequential decisions are reviewed by a suitably qualified person.
- **Data protection:** collect only the visual data needed for a defined purpose and apply appropriate retention and access controls.
- **Transparency:** explain when and why the technology is being used, where appropriate.
- **Accountability:** document system performance, decisions and responsibilities so that problems can be investigated.
- **Regular review:** monitor the system after deployment and reassess it when the data, environment or intended use changes.
- **Appropriate regulation:** check the applicable legal requirements before introducing the system.

These measures do not remove every risk. Their effectiveness depends on the application, the quality of implementation and whether organisations monitor the system in practice.

## 6. Initial Conclusion

Computer Vision can support useful services, but its deployment can also raise concerns about accuracy, fairness, privacy, surveillance and accountability. Facial recognition is one example in which these issues can be especially important because errors may affect the identity and rights of individuals.

The research suggests that the risks should be assessed in the context of a specific application. The next stage will compare real-world cases to identify one that provides reliable evidence of both benefits and negative impacts.

## References

The full Harvard-style references for the sources used in this document are recorded in `references.md`.