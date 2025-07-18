# Threats To MITRE(CWD, ATT&CK) AI-LLM Mapper

**Program Design Purpose**: The primary objective of this program is to leverage AI-LLM technology to streamline the processing of human language-based threat scenario documents, including technical blogs, CTI reports, online threats introduction materials and cyber attack training notes. The goal is to succinctly summarize the attack flow path outlined within such materials via mapping the attack behaviors to the MITRE-ATT&CK Matrix and matching the vulnerabilities to the MITRE-CWE Tree. 

To achieve this, the program will undertake the following tasks:

- **Identifying Cyber Attack Behaviors**: The program will parse the document to extract cyber attack behaviors, delineating each behavior individually. Subsequently, it will map these behaviors to the MITRE ATT&CK Matrix, thereby discerning the associated attack tactics and techniques.
- **Detecting Vulnerabilities**: Additionally, the program will identify vulnerabilities mentioned within the threat descriptions. It will then cross-reference these vulnerabilities with the MITRE Common Weakness Enumeration (CWE) to establish corresponding matches.

Upon completion of the mapping and matching processes, the program will automate the generation of a comprehensive report detailing the outcomes of these activities. This report will serve to provide valuable insights into the cyber threat landscape outlined in the original documents.
