# CMPINF 1205 Final Project

## Measuring Readability and Obfuscation of Privacy Policies in the OPP-115 Dataset
By Griffin Hurt

### Introduction
Privacy policies play an important role in how users navigate the internet and interact with the services they use. Despite being overlooked by many people, a privacy policy is a legally binding agreement between a service and its users determining how his/her data will be used and processed. Due to the immense privacy implications at stake, it is vital that users are able to read and comprehend the information before accepting. However, privacy policies are generally complex legal documents that hide their intentions behind jargon and long sequences of text. In class we discussed the Children’s Online Privacy Protection Act, also known as COPPA, which prevents websites from gathering personal information from children under the age of 13 (Children’s Online Privacy Protection Rule, 1998). However, many privacy policies are far too complicated for a young teenager to fully comprehend. This discrepancy between document complexity and the minimum age requirement of websites has limited the possibility for informed consent among users, and has large reaching consequences for the digital privacy of our youth.

### Previous Research

#### The OPP-115 Corpus
The OPP-115 Corpus is a set of 115 privacy policies in English that have been processed to make analysis a simpler process (Wilson et al., 2016b). The dataset has been cited more than 150 times according to Google Scholar, demonstrating its effectiveness for discovering common trends among privacy policies ([Google Scholar search], n.d.).

#### “Privacy Policy Analysis” by Lindsey Rojtas
During April of 2020, Lindsey Rojtas (2020), a student in CMPINF 1999, performed an analysis on the OPP-115 Corpus for policy word count, average word length, and type-token ratio (a metric used to determine the uniqueness of words in a text). While her project demonstrated some of the trends among privacy policies that suggest they may be too complex for a young audience, her analysis did not perform advanced natural language processing. This project builds from the work she performed and computes additional metrics on the dataset to measure readability and policy complexity.

### Readability
Many metrics exist to measure the readability of a text by grade level or age. Some of the most commonly used metrics are Flesch Reading Ease, the Gunning Fog Index, the Automated Readability Index, and the SMOG Index (*Readability Metrics*, n.d.). In addition to determining the level of education required to understand a document, the Time to Read metric can be used to determine how long a user will take to read and comprehend a policy (*Readability Metrics*, n.d.).
