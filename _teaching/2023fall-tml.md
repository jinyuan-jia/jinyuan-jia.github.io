---
title: "Trustworthy Machine Learning"
collection: teaching
type: "Graduate course"
permalink: /teaching/2023fall-tml
venue: "Penn State, College of IST"
date: 2023-08-21
location: "State College, US"
---

## Overview
Machine learning techniques are widely used to solve real-world problems. However, a key challenge is that they are vulnerable to various security and privacy attacks, e.g., adversarial examples, data poisoning attacks, and membership inference attacks. In this course, we will discuss existing attacks and state-of-the-art defenses against those attacks.  

## Prerequisites
This course requires the knowledge of basic machine learning (e.g., an undergraduate machine learning course) as well as linear algebra and calculus.

## Logistics

- Instructor: **Jinyuan Jia, jinyuan@psu.edu**
- Teaching Assistant: **Hangfan Zhang, hbz5148@psu.edu** 
- Time: **TuTh 3:05 PM - 4:20 PM**
- Location: **Leonhard Bldg 203**
- Office Hours: **Jinyuan Jia: Wednesday  1:00 pm - 2:00 pm, E325 Westgate; Hangfan Zhang: Thursday 1:30-2:30 pm, E301 Westgate**


## Tentative Schedule (Subject to Change)

| Week | Date | Topics | Papers | Notes |
| - | ---- | ------ | ------- | -------- |
| 1 | 08/22 | Course overview |  | |
| 1 | 08/24 |Adversarial examples in image domain (white-box)|1. Towards Evaluating the Robustness of Neural Networks <br/> ||
| 2 | 08/29 |Adversarial examples in image domain (black-box)|1. HopSkipJumpAttack: A Query-Efficient Decision-Based Attack <br/> 2. (Optional) Delving into Transferable Adversarial Examples and Black-box Attacks  ||
| 2 | 08/31 |Empirical defenses against adversarial examples|1.Towards Deep Learning Models Resistant to Adversarial Attacks ||
| 3 | 09/05 |Certified defenses against adversarial examples|1. Certified Adversarial Robustness via Randomized Smoothing ||
| 3 | 09/07 |Adversarial examples in (large) language models and their defenses | 1. Text-CRS: A Generalized Certified Robustness Framework against Textual Adversarial Attacks <br/> 2. (Optional) Certified Robustness to Text Adversarial Attacks by Randomized [MASK] ||
| 4 | 09/12 | Adversarial examples for good use |1. AttriGuard: A Practical Defense Against Attribute Inference Attacks via Adversarial Machine Learning <br/> 2. (Optional) Glaze: Protecting Artists from Style Mimicry by Text-to-Image Models ||
| 4 | 09/14 | Data poisoning attacks to classifiers| 1. Poisoning Attacks against Support Vector Machines <br/> 2. (Optional) Poison Frogs! Targeted Clean-Label Poisoning Attacks on Neural Networks  ||
| 5 | 09/19 | Data poisoning attacks to foundation models| 1. PoisonedEncoder: Poisoning the Unlabeled Pre-training Data in Contrastive Learning <br/> 2. (Optional) Indiscriminate Poisoning Attacks on Unsupervised Contrastive Learning|Speakers: Sai Naveen Katla, Salika Dave|
| 5 | 09/21 | Model poisoning attacks to federated learning| 1. Local Model Poisoning Attacks to Byzantine-Robust Federated Learning <br/> 2. (Optional) FLTrust: Byzantine-robust Federated Learning via Trust Bootstrapping|Speakers: Hari Pranav Arun Kumar, Manasa Pisipati|
| 6 | 09/26 | Certified defenses against data poisoning attacks | 1. Intrinsic Certified Robustness of Bagging against Data Poisoning Attacks <br/> 2. (Optional) Certified Robustness of Nearest Neighbors against Data Poisoning Attacks <br/> 3. (Optional) Certified Defenses for Data Poisoning Attacks  |Speakers: Wei Zou, Yurui Chang|
| 6 | 09/28 | Backdoor attacks in image domain | 1. BadNets: Identifying Vulnerabilities in the Machine Learning Model Supply Chain <br/> 2. (Optional) Trojaning Attack on Neural Networks |Speakers: Yilong Wang, Minhua Lin|
| 7 | 10/03 | Backdoor attacks to pre-trained foundation models | 1. BadEncoder: Backdoor Attacks to Pre-trained Encoders in Self-Supervised Learning <br/> 2. (Optional) Poisoning and Backdooring Contrastive Learning||
| 7 | 10/05 | Defending against backdoor attacks in image domain | 1. Neural Cleanse: Identifying and Mitigating Backdoor Attacks in Neural Networks <br/> 2. (Optional)  STRIP: A Defence Against Trojan Attacks on Deep Neural Networks|Speaker: Ruimeng(Raymond) Shao|
| 8 | 10/10 | Backdoor attacks to (large) language models and their defenses|1. Backdoor Pre-trained Models Can Transfer to All <br/> 2. (Optional) PICCOLO: Exposing Complex Backdoors in NLP Transformer Models|Speakers: Harish Kolla, Girish Nagarajan|
| 8 | 10/12 | Privacy attacks to image classifiers| 1. Membership Inference Attacks against Machine Learning Models <br/> 2. (Optional)  Model Inversion Attacks that Exploit Confidence Information and Basic Countermeasures|Speakers: Srija Akula, Hanzheng Wang|
| 9 | 10/17 | Privacy attacks to federated learning| 1. Deep Leakage from Gradients <br/> 2. (Optional)  Deep Models Under the GAN: Information Leakage from Collaborative Deep Learning|Speakers: Yaopei Zeng and Yuanpu Cao|
| 9 | 10/19 | Privacy attacks to (large) language models and diffusion models| 1. Extracting Training Data from Large Language Models <br/> 2. (Optional) Extracting Training Data from Diffusion Models|Speaker: Keaton Yukio Kraiger, Vishal Ahir|
| 10 | 10/24 | Defending against privacy attacks | 1. Deep Learning with Differential Privacy <br/> 2. (Optional) SecureML: A System for Scalable Privacy-Preserving Machine Learning  |Speaker: Yanting Wang|
| 10 | 10/26 | Model stealing attacks| 1. Stealing Machine Learning Models via Prediction APIs <br/> 2. (Optional) Stealing Hyperparameters in Machine Learning ||
| 11 | 10/31 | Intellectual property protection| 1. Prediction Poisoning: Utility-Constrained Defenses Against Model Stealing Attacks <br/> 2. (Optional) Turning Your Weakness Into a Strength: Watermarking Deep Neural Networks by Backdooring <br/> 3. (Optional) Certified Neural Network Watermarks with Randomized Smoothing ||
| 11 | 11/02 | Image watermarking and its security| 1. Hidden: Hiding data with deep networks  <br/>  2. (Optional) Evading Watermark based Detection of AI-Generated Content ||
| 12 | 11/07 | Prompt injection attacks to large language models| 1. Ignore Previous Prompt: Attack Techniques For Language Models <br/> 2. (Optional) Prompt Injection Attacks and Defenses in LLM-Integrated Applications ||
| 12 | 11/09 | Machine generated text detection| 1. A Watermark for Large Language Models| |
| 13 | 11/14 | Deepfakes | 1. Generative Adversarial Nets <br/> 2. Stable Diffusion||
| 13 | 11/16 | Safety of LLMs| 1. Jailbroken: How Does LLM Safety Training Fail? <br/> 2. (Optional) Universal and Transferable Adversarial Attacks on Aligned Language Models |Speaker: Bochuan Cao||
| 14 | | Thanksgiving||
| 15 | 11/28 |Project Presentation| Group 1: Yurui Chang and Yuanpu Cao 	 ||
| 15 | 11/30 |Project Presentation| Group 1: Yanting Wang and Wei Zou <br/> Group 2 Hanzheng Wang <br/> Group 3: Yaopei Zeng ||
| 16 | 12/05 |Project Presentation| Group 1: Harish Kolla and Nagarajan Girish <br/> Group 2: Sai Naveen Katla and Salika Dave <br/> Group 3: HARI PRANAV ARUN KUMAR	 and Manasa Pisipati||
| 16 | 12/07 |Project Presentation| Group 1: Ruimeng Shao <br/> Group 2: Yilong Wang and Minhua Lin <br/> Group 3 Vishal Ahir and Keaton Kraiger||

## Paper Review
- Deadline: Monday or Wednesday 11:59 pm (EST). One paper per week. Please send your review to this email address: psutrustworthyml@gmail.com, and send it in a single thread (by replying). Note that ChatGPT should not be used to write the review.

## Group
- Students can form groups of at most 2 students for the lecture and class project.
- Lecture: Prepare the slides (or use others' with proper citations) and give a lecture. Choosing a topic for lecture. A group sends three preferred dates to psutrustworthyml@gmail.com by 11:59 pm (EST), 08/31.

- Class project: The project should be related to machine learning (published work cannot be used as the course project).

## Grading Policy
- 50% project
- 25% reading assignment
- 10% class participation and quiz
- 15% class presentation
  
Final grade cutoff:
- A [93%, 100%]
- A- [90%, 93%)
- B+ [87%, 90%)
- B [83%, 87%)
- B- [80%, 83%)
- C+ [77%, 80%)
- C [70%, 77%)
- D [60%, 70%)
- F [0%, 60%)

## Late Submission Policy
- 10% deduction for every 24 hours late.
- No more late submission is accepted after 3 days.
- Please email the instructor regarding extensions for special cases.

## ACADEMIC INTEGRITY STATEMENT
Academic integrity is the pursuit of scholarly activity in an open, honest and responsible manner. Academic integrity is a basic guiding principle for all academic activity at The Pennsylvania State University, and all members of the University community are expected to act in accordance with this principle. Consistent with this expectation, the University’s Code of Conduct states that all students should act with personal integrity, respect other students’ dignity, rights and property, and help create and maintain an environment in which all can succeed through the fruits of their efforts.

Academic integrity includes a commitment by all members of the University community not to engage in or tolerate acts of falsification, misrepresentation or deception. Such acts of dishonesty violate the fundamental ethical principles of the University community and compromise the worth of work completed by others.

## DISABILITY ACCOMMODATION STATEMENT
Penn State welcomes students with disabilities into the University’s educational programs. Every Penn State campus has an office for students with disabilities. Student Disability Resources (SDR) website provides contact information for every Penn State campus
(http://equity.psu.edu/sdr/disability-coordinator). For further information, please visit Student Disability Resources website
(http://equity.psu.edu/sdr/).

In order to receive consideration for reasonable accommodations, you must contact the appropriate disability services office at the campus where you are officially enrolled, participate in an intake interview, and provide documentation: See documentation guidelines
(http://equity.psu.edu/sdr/guidelines). If the documentation supports your request for reasonable accommodations, your campus disability services office will provide you with an accommodation letter. Please share this letter with your instructors and discuss the accommodations with them as early as possible. You must follow this process for every semester that you request accommodations.

## COUNSELING AND PSYCHOLOGICAL SERVICES STATEMENT
Many students at Penn State face personal challenges or have psychological needs that may interfere with their academic progress, social development, or emotional wellbeing. The university offers a variety of confidential services to help you through difficult times, including individual and group counseling, crisis intervention, consultations, online chats, and mental health screenings. These services are provided by staff who welcome all students and embrace a philosophy respectful of clients’ cultural and religious backgrounds, and sensitive to differences in race, ability, gender identity and sexual orientation.

Counseling and Psychological Services at University Park  (CAPS)
(http://studentaffairs.psu.edu/counseling/): 814-863-0395

Counseling and Psychological Services at Commonwealth Campuses
(https://senate.psu.edu/faculty/counseling-services-at-commonwealth-campuses/)

Penn State Crisis Line (24 hours/7 days/week): 877-229-6400
Crisis Text Line (24 hours/7 days/week): Text LIONS to 741741

## EDUCATIONAL EQUITY/REPORT BIAS STATEMENTS
Consistent with University Policy AD29, students who believe they have experienced or observed a hate crime, an act of intolerance, discrimination, or harassment that occurs at Penn State are urged to report these incidents as outlined on the University’s Report Bias webpage
(http://equity.psu.edu/reportbias/)
