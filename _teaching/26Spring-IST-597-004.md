---
title: "IST 597-004: LLM Foundation and Trustworthiness"
collection: teaching
type: "Graduate course"
permalink: /teaching/26Spring-IST-597-004
venue: "Penn State, College of IST"
date: 2026-01-12
location: "State College, US"
---

## Overview
Large Language Models (LLMs), such as ChatGPT and Gemini, are widely deployed in real-world applications, including conversational assistants, coding assistants, autonomous agents, creative content generation, and scientific research support. This course covers both the foundations and trustworthiness of LLMs. 

The first part of the course introduces the foundations of LLMs, including machine learning basics, LLM architectures, pre-training, reinforcement learning, and post-training. The second part discusses trustworthy LLMs in practice, including watermarking AI-generated content, privacy attacks and defenses, jailbreak attacks, prompt injection attacks and defenses, attacks and defenses for RAG and agents, attribution-based explanation, mechanistic interpretability, deepfakes, and hallucination.

## Logistics

- Instructor: **Jinyuan Jia, jinyuan@psu.edu**
- Teaching Assistant: **Wei Zou, wxz5259@psu.edu**
- Time: **Monday/Wednesday 2:30 PM - 3:45 PM**
- Location: **Westgate Bldg E206**
- Office Hours:
     - **Jinyuan Jia: Wednesday 1:20 pm - 2:20 pm, E325 Westgate**
     - **Wei Zou: Tuesday 3:00 pm - 4:00 pm, Westgate E301, Zoom link: https://psu.zoom.us/j/91305798243?pwd=UaqBV0RLkrOHNaY9Us1A2pkhJYZNQH.1**

## Tentative Schedule (Subject to Change)

Please check the following tentative schedule for the course. [The link to the course slides](https://drive.google.com/drive/folders/1zAEVMRv7ZTWEtCogwNhN2GZ5VYFr28Mn?usp=sharing)

| Date | Topics | Readings / Notes |
| ---- | ------ | ---------------- |
| 01/12/2026 | Course Overview | |
| 01/14/2026 | Machine Learning Basics | |
| 01/19/2026 | No Class for Holiday | |
| 01/21/2026 | Machine Learning Basics | |
| 01/26/2026 | LLM Architecture | Attention Is All You Need |
| 01/28/2026 | LLM Architecture | Language Models are Unsupervised Multitask Learners (optional) |
| 02/02/2026 | LLM Pretraining | Improving Language Understanding by Generative Pre-Training (optional); BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding (optional) |
| 02/04/2026 | LLM Pretraining | |
| 02/09/2026 | Reinforcement Learning Basics | Simple Statistical Gradient-Following Algorithms for Connectionist Reinforcement Learning (REINFORCE); Actor-Critic Algorithm (optional) |
| 02/11/2026 | Reinforcement Learning Basics | Proximal Policy Optimization Algorithms; Trust Region Policy Optimization |
| 02/16/2026 | LLM Post-training | Training Language Models to Follow Instructions with Human Feedback; Direct Preference Optimization: Your Language Model is Secretly a Reward Model (optional) |
| 02/18/2026 | LLM Post-training | DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning; GRPO variants, such as Dr. GRPO and DAPO (optional) |
| 02/23/2026 | Watermarking AI-generated Text | A Watermark for Large Language Models; Scalable Watermarking for Identifying Large Language Model Outputs (optional) |
| 02/25/2026 | Watermarking AI-generated Image | Evading Watermark-based Detection of AI-Generated Content; Tree-Ring Watermarks: Fingerprints for Diffusion Images that are Invisible and Robust (optional) |
| 03/02/2026 | Membership Inference Attacks and Defenses | Extracting Training Data from Large Language Models; Detecting Pretraining Data from Large Language Models (optional); Membership Inference Attacks Against Machine Learning Models (optional) |
| 03/04/2026 | Model Parameter Privacy | Stealing Part of a Production Language Model; Stealing Machine Learning Models via Prediction APIs (optional) |
| 03/09/2026 | No Class for Spring Break | |
| 03/11/2026 | No Class for Spring Break | |
| 03/16/2026 | Jailbreak Attacks and Defenses to LLM | Universal and Transferable Adversarial Attacks on Aligned Language Models; Tree of Attacks: Jailbreaking Black-Box LLMs Automatically (optional); Improving Alignment and Robustness with Circuit Breakers (optional) |
| 03/18/2026 | Jailbreak Attacks and Defenses to VLM | SneakyPrompt: Jailbreaking Text-to-Image Generative Models; RING-A-BELL! How Reliable Are Concept Removal Methods for Diffusion Models? (optional) |
| 03/23/2026 | Attacks and Defenses to RAG | PoisonedRAG: Knowledge Corruption Attacks to Retrieval-Augmented Generation of Large Language Models; ReliabilityRAG: Effective and Provably Robust Defense for RAG-based Web Search (optional) |
| 03/25/2026 | Attacks and Defenses to Agent | Agent Security Bench (ASB): Formalizing and Benchmarking Attacks and Defenses in LLM-based Agents; Defeating Prompt Injections by Design (optional) |
| 03/30/2026 | Prompt Injection Attacks | Formalizing and Benchmarking Prompt Injection Attacks and Defenses; Not What You've Signed Up For: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection (optional) |
| 04/01/2026 | Prompt Injection Defenses | SecAlign: Defending Against Prompt Injection with Preference Optimization; DataSentinel: A Game-Theoretic Detection of Prompt Injection Attacks (optional); The Attacker Moves Second: Stronger Adaptive Attacks Bypass Defenses Against LLM Jailbreaks and Prompt Injections (optional) |
| 04/06/2026 | Attribution-based Explanation | TracLLM: A Generic Framework for Attributing Long Context LLMs; ContextCite: Attributing Model Generation to Context (optional) |
| 04/08/2026 | Mechanistic Interpretability | Interpretability in the Wild: A Circuit for Indirect Object Identification in GPT-2 Small; Interpreting GPT: The Logit Lens |
| 04/13/2026 | DeepFake | |
| 04/15/2026 | Hallucination | |
| 04/20/2026 | Project Presentation | |
| 04/22/2026 | Project Presentation | |
| 04/27/2026 | Project Presentation | |
| 04/29/2026 | Project Presentation | |

## Assignments

### Paper Review
- Deadline: **Sunday or Tuesday 11:59 pm (EST)**.
- Students will review approximately two papers per week on average. Please check Canvas for details.
- ChatGPT should not be used to write paper reviews.

### Group Tasks
- Students can form groups of at most **2 students** for the lecture and class project.
- Lecture:
    - Prepare the slides, or use others' slides with proper citations, and give a lecture.
    - Choose a topic from **02/23 to 04/15** for the lecture.
    - Group sign-up for the group presentation is due on Canvas by **11:59 pm (EST), 01/31**.
    - Each group should present for at least **50 minutes**. For a group of two students, each student should present for about **25 minutes** on average.
- Class project:
    - The project should be related to machine learning.
    - Published work cannot be used as the course project.

### Class Attendance
- We occasionally have a class-attendance quiz, but not every lecture.
- The lowest three grades will be dropped for class attendance.
- In general, please let the instructor know if you cannot attend class.

## Grading Policy

| Component | Percentage |
| --------- | ---------- |
| Project | 50% |
| Paper Review | 25% |
| Class Participation | 10% |
| Class Presentation | 15% |

Final grade cutoff:

| Grade | Range |
| ----- | ----- |
| A | 93 - 100 |
| A- | 90 - 92 |
| B+ | 87 - 89 |
| B | 83 - 86 |
| B- | 80 - 82 |
| C+ | 77 - 79 |
| C | 73 - 76 |
| C- | 70 - 72 |
| D | 60 - 69 |
| F | 0 - 59 |

## Late Submission Policy
- 10% deduction for every 24 hours late.
- No more late submission is accepted after 3 days.
- Please email the instructor regarding extensions for special cases.

## Academic Integrity Statement
Academic integrity is the pursuit of scholarly activity in an open, honest, and responsible manner. Academic integrity is a basic guiding principle for all academic activity at The Pennsylvania State University, and all members of the University community are expected to act in accordance with this principle. Consistent with this expectation, the University's Code of Conduct states that all students should act with personal integrity, respect other students' dignity, rights, and property, and help create and maintain an environment in which all can succeed through the fruits of their efforts.

Academic integrity includes a commitment by all members of the University community not to engage in or tolerate acts of falsification, misrepresentation, or deception. Such acts of dishonesty violate the fundamental ethical principles of the University community and compromise the worth of work completed by others.

The use of Artificial Intelligence tools, such as ChatGPT, is a violation for paper reviews unless such use has been expressly permitted by the instructor and the assignment calls for its use. For the project report, ChatGPT can be used to polish grammar, but it cannot be used to generate the entire report.

While utilizing additional sources outside of this class is encouraged for gaining a better understanding of course concepts, seeking explicit answers for graded assignments from outside sources, such as Course Hero, Chegg, or tutoring services, is considered cheating and will not be tolerated. Sanctions range from failure of the assignment or course to dismissal from the University. Additionally, sharing course content without permission is a violation of copyright and may result in university sanctions and/or legal ramifications. Contact your instructor with questions related to this topic.

## Disability Accommodation Statement
Penn State welcomes students with disabilities into the University's educational programs. Every Penn State campus has an office for students with disabilities. The Student Disability Resources (SDR) website provides contact information for every Penn State campus: https://equity.psu.edu/offices/student-disability-resources/campus-offices. For further information, please visit the Student Disability Resources website: https://equity.psu.edu/offices/student-disability-resources/.

In order to receive consideration for reasonable accommodations, you must contact the appropriate disability services office at the campus where you are officially enrolled, participate in an intake interview, and provide documentation. See documentation guidelines: http://equity.psu.edu/sdr/guidelines. If the documentation supports your request for reasonable accommodations, your campus disability services office will provide you with an accommodation letter. Please share this letter with your instructors and discuss the accommodations with them as early as possible. You must follow this process for every semester that you request accommodations.

## Counseling and Psychological Services Statement
Many students at Penn State face personal challenges or have psychological needs that may interfere with their academic progress, social development, or emotional wellbeing. The university offers a variety of confidential services to help students through difficult times, including individual and group counseling, crisis intervention, consultations, online chats, and mental health screenings. These services are provided by staff who welcome all students and embrace a philosophy respectful of clients' cultural and religious backgrounds and sensitive to differences in race, ability, gender identity, and sexual orientation.

Counseling and Psychological Services at University Park (CAPS): http://studentaffairs.psu.edu/counseling/, 814-863-0395

Counseling and Psychological Services at Commonwealth Campuses: https://studentaffairs.psu.edu/counseling/caps-campuses

Penn State Crisis Line (24 hours/7 days/week): 877-229-6400

Crisis Text Line (24 hours/7 days/week): Text LIONS to 741741

## Educational Equity / Report Bias Statements
Consistent with University Policy AD29, students who believe they have experienced or observed a hate crime, an act of intolerance, discrimination, or harassment that occurs at Penn State are urged to report these incidents as outlined on the University's Report Bias webpage: http://equity.psu.edu/reportbias/.
