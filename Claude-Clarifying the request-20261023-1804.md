# Clarifying the request

**Created:** 10/7/2026 22:23:46  
**Updated:** 10/23/2026 17:41:07  
**Exported:** 10/23/2026 18:04:10  
**Link:** [https://claude.ai/chat/3618d6dd-e0ac-45d3-9629-5b20892a234f](https://claude.ai/chat/3618d6dd-e0ac-45d3-9629-5b20892a234f)  

## User:

> 10/7/2026 22:23:47

```text
 
Student Assignment Brief  


This document is intended for Coventry University Group students for their own use in completing their assessed work for this module. It must not be passed to third parties or posted on any website. If you require this document in an alternative format, please contact your Module Leader. 


Contents:
•	Assignment Information
•	Assignment Task
•	Marking and Feedback
•	Assessed Module Learning Outcomes
•	Assignment Support and Academic Integrity
•	Assessment Marking Criteria
The work you submit for this assignment must be your own independent work, or in the case of a group assignment your own groups’ work. More information is available in the ‘Assignment Task’ section of this assignment brief.

Assignment Information
Module Name: Machine Learning and Big Data
Module Code: 7006SCN
Assignment Title: Written
Assignment Due: Monday, 26/10/2026, at 6pm UK time
For assessments that are submitted through Turnitin, the University allows a 24-hour grace period for receipt of submission. Therefore, submissions will only be accepted up until the 27/10/2026 by 18.00hrs. This should NOT be viewed as extra time to complete the assessment but is provided to allow for any unforeseen technical issues that may occur around the submission deadline, especially when Turnitin is handling large numbers of submissions. 
Please note that this assessment is eligible for an extension after approving by the Registry.


If you do not pass this assessment, you may have an opportunity to resit it. If you do need to resit, you will be asked to use the feedback provided to revise your original submission, so that it meets the pass requirements for the module. You must clearly indicate the changes you have made in the new submission. Please check your SOLAR results and the submission links on your Aula module page to see when the resit is due.
Assignment Credit: 30 credits
Word Count (or equivalent): 1200 words +/- 10%
You should state your word count at the end of written work. If you exceed the word limit by more than 10% (i.e. if you exceed 2200 words), then your work will only be read up to the allocated limit.
Assignment Type: Applied Core Assessment
Percentage Grade (Applied Core Assessment). You will be provided with an overall grade between 0% and 100%. To pass the module you need to get a grade of 40% or above. If you have not passed the module on the 1st attempt, you will have an opportunity for resits.
Document to Submit
Report Submission
Your Submission is expected to be a Report single Word (docx) submitted via Turnitin on Aula before 18:00. Late work will receive a mark of zero.
You are expected to state the wordcount at the start of the Report “7006SCN2627SEPNOV_Report_AnswerSheet_Dr_KStamou_v1.docx”.
Your CW is expected to include answers to the below-listed FOUR (4) Tasks in the “Task Requirements” section such as made of written text – Report (Number of words), hyperlink per Tast and screenshot(s) where requested. 
 All FOUR GitHub notebook hyperlinks and the Tableau Public link must be active and accessible at submission.
If Your GitHub notebook hyperlinks and the Tableau Public link are NOT accessible Your Assessment with be assessed with a mark of “0”.
If your project code repository is hosted anywhere other than the module GitHub organisation 7006SCN2627SEPNOV, your overall mark for this assessment is capped at 20%. See “Repository location” under Technical Requirements.

If your project code repository is publicly visible, 10 marks are deducted from your overall mark. Your repository must be private for the duration of the module. See “Repository visibility” under Technical Requirements.

Assignment Task
Apply foundational concepts of Big Data within various ML (Machine Learning) algorithms to solve the real-world problem
In this assignment, you will have to apply various machine learning algorithms and methods to solve a real-world problem that describes the dataset that You are allocated based on Your Student-mail (please view “7006SCN2627SEPNOV_Dataset Catalogue_Released.xlsx”). This problem could belong to the class of classification, regression, or clustering problems.
During this module, you learn about implementing Machine Learning (ML) processes to big data starting from the big data foundations, through data pre-processing to data analysis appropriate for a specific goal. You explore several classification, regression, and clustering algorithms, such as Logistic Regression, K-nearest Neighbour, Support Vector Machines, and Decision Trees, and Deep Learning approaches using Pyspark. You learn the themes of Big Data ingestion, Distributed preprocessing, Feature engineering, Model training and tuning, Distributed computing optimisation, Model evaluation and stability analysis, Tableau storytelling and business insights, Professional version control practices which you are expected to demonstrate in your work.
This assignment is based on analysis of an assigned Big Data dataset based on the “7006SCN2627SEPNOV_Dataset Catalogue_Released.xlsx” as You are allocated by Your Module Leader. For the dataset, You will be allocated it should be matching Your Student-Name-e-mail (Please check “7006SCN2627SEPNOV_Dataset Catalogue_Released.xlsx” as released on Aula).   Your task is to apply a minimum of FOUR classification or regression or clustering techniques to analyse the chosen dataset. 

Big Data Requirements
Your allocated Big Data dataset is verified to meet the following requirements for your coursework submission to be accepted and eligible for marking. You are expected to confirm each of them yourself and to record your figures in Task 1.


Requirement	Mandatory
10 million or more rows/entries	✔
≥10 columns/features	✔
Suitable for classification/regression/clustering	✔
Entire pipeline implemented in PySpark	✔
Dataset NOT from Kaggle [https://www.kaggle.com/]
✔
Dataset NOT from the ones used during teaching	✔
Ethical and licensing compliance	✔

Dataset Pool and claiming
Each Student is allocated a unique Dataset as logged on “7006SCN2627SEPNOV_Dataset Catalogue_Released.xlsx” and is allocated randomly by Your Module Leader. This guarantees that no more than one students analyse the same data.
•	Your allocation is published on Aula in “7006SCN2627SEPNOV_Dataset Catalogue_Released.xlsx”, matched to Your Student-Name and e-mail (Student-Name-Mail-Dataset). The register is read-only-view.
•	You are allocated to use even a truncated version of your allocated dataset as long as it is compliant with Big Data Requirements.
•	Allocations are released in the Week 1. You are expected to confirm that you have located and can access your allocated dataset through the MS Forms checklist 7006SCN CW-Project_Checklist form  – Fill in form
•	by the end of Week 2.
•	If you cannot access your allocated dataset, or the source has moved or been withdrawn, contact Your Module Leader in Week 1. Any change of allocation is made by Your Module Leader and re-published in the 7006SCN2627SEPNOV_Dataset Catalogue_Released.xlsx. You must not change it yourself.
•	You are not allowed to select, swap or propose a dataset, even if it satisfies all eight Big Data Requirements. If you analyse a dataset other than the one allocated to you by Your Module Leader, your overall mark for this assessment is capped at 30-39% (FAIL).
•	Record the Pool reference of your allocated dataset (for example TR-04) in your Report front matter and in your Project Repository, in results/task1.json. This is how your allocation is verified.
You are welcome to discuss the progress of your work with your module team to get formative feedback and improve the final submission. 
Technical Requirements
Your GitHub 7006SCN2627SEPNOV/repository (formatted as Username_SID) must contain 4 Notebooks:  
/notebooks/Task1.ipynb     # Week 1–2 work
/notebooks/Task2.ipynb     # Week 3-4 work
/notebooks/Task3.ipynb     # Week 5 work
/notebooks/Task4.ipynb     # Week 6 work

/results/task1.json ... task4.json
/README.md                         

Repository location 
Your project code repository must be created inside the module GitHub organisation 7006SCN2627SEPNOV. This is not a formatting preference. It is how the module verifies that the work is yours, that it was developed across the teaching weeks, and that your commit history is intact.  
Requirement	Standard
Required	github.com/7006SCN2627SEPNOV/7006SCN_<Initials>_<SID>
Penalty	If your project code repository is hosted outside the module organisation - in a personal GitHub account, another organisation, or on any other platform such as GitLab or Bitbucket - your overall mark for this assessment is capped at 20%.
Effect	20% is below the 40% pass mark, so this cap means the assessment is not passed regardless of the quality of the work inside the repository.
How it is checked	 The organisation is read from the repository URL you submit and compared with 7006SCN2627SEPNOV.
Mirrors and backups	You may keep a private backup elsewhere. The repository you submit, and the one your notebook hyperlinks resolve to, must be the one in the module organisation.
If you cannot access the organisation	Contact the Module Leader in Week 1. Access problems raised in Week 1 are resolved; a repository built elsewhere and moved at the deadline loses its commit history/weekly progression and will still be capped.

Repository Visibility
Your repository must be set to Private and must stay Private until results are released. A public repository exposes your notebooks, your commit history and your results files to the rest of the cohort.
Requirement	Standard
Required	Visibility set to Private, from creation in Week 1 until results are released
Penalty	If your repository is publicly visible at the submission deadline, 10 marks are deducted from your overall mark out of 100.
How it is checked	Visibility is read from GitHub at the deadline, not from anything you declare.
If your work is copied	The 10-mark deduction covers the breach of this requirement only. If another submission is found to derive from your public repository, both submissions are referred as an Academic Conduct Offence.
Marker access	Private does not mean inaccessible. Repositories created inside 7006SCN2627SEPNOV are visible to the module team automatically.
Afterwards	You may make the repository public once results are released, and you are encouraged to do so if you want it as a portfolio piece.

Version Control Requirements (Assessed Across All Tasks)
Requirement	Standard
Minimum commits	3 meaningful commits per task (12 commits overall)
Commit messages	Must describe the change clearly,  in the format [TaskN] verb object - reason or measured result
Example	[Task3] set shuffle partitions 200 to 64 - stage 7 time 41s to 18s
Measured outcome	At least one commit per Task must report a measured value
Weekly progression	Commits must be timestamped in the correct weeks. Tasks 1 and 2 (likewise Tasks 3 and 4) span two teaching weeks, so at least one commit must fall in each of them
Commit citation	Each sub-section of your Report must name the short commit hash that produced its evidence
README.md	Must be maintained throughout
Branch usage	Optional but rewarded 

Machine Learning Requirements
You are expected to apply a minimum of FOUR algorithms. So that your comparison is meaningful, you are expected to take one from each of the first three families below, plus one free choice.
Family	Examples in Spark MLlib	Taught in
Linear / generalised linear	LogisticRegression, LinearRegression, GeneralizedLinearRegression	Day 5 ML Algorithms on Spark I: Regression
Tree-based ensemble	RandomForestClassifier/Regressor, GBTClassifier, DecisionTree	Day 5 ML Algorithms on Spark II: Classification1
Distance, kernel or neural	KMeans, BisectingKMeans, LinearSVC, NaiveBayes, MultilayerPerceptronClassifier	Day 5 Classification2; Day 6 Unsupervised Learning I: Clustering
Free choice	Any of the above, or ALS, LDA, or an algorithm beyond the taught set	Justify in sub-section 2.1

Tableau Requirements
Your Tableau Public workbook must include all the four dashboards:
1.	Data quality & pipeline monitoring
2.	Model performance & feature importance
3.	Business insights
4.	Scalability & cost analysis   
Task Requirements (Week-Aligned)
•	Task1  - Problem, Data and Pipeline (Week 1–2)
[Aligned lectures: Introduction to Big Data; Big Data Storage & Processing; Processing Frameworks: Hadoop & Spark; Data Ingestion & Management; Cloud Platforms for Big Data; Modern Data Architectures; Feature Engineering at Scale; Distributed Data Wrangling; Exploratory Data Analysis (EDA) at Scale; Dimensionality Reduction; Data Partitioning & Sampling; Data Pipelines]

•	Task2 - Modelling at Scale (Week 3 - 4)
[Aligned lectures: ML Algorithms on Spark I: Regression; ML Algorithms on Spark II: Classification1; ML Algorithms on Spark II: Classification2; Model Training & Tuning at Scale; Model Evaluation Deep Dive; Unsupervised Learning I: Clustering; Recommendation Systems; Handling Imbalanced Data; Introduction to Natural Language Processing (NLP); NLP Application: Topic Modelling; Introduction to Time Series Analysis; Forecasting with ML]

•	Task3 - Evaluation, Optimisation and Explainability (Week 5)
[Aligned lectures: Introduction to Deep Learning for Big Data; Distributed Deep Learning Frameworks; Model Deployment & Serving; Performance Tuning & Debugging; Ethics, Bias, and Fairness in ML; ML Explainability (X Introduction to Deep Learning for Big Data; Distributed Deep Learning Frameworks; Model Deployment & Serving; Performance Tuning & Debugging; Ethics, Bias, and Fairness in ML; ML Explainability (XAI)]

•	Task4. Tableau Storytelling and Critical Reflection (Week 6)   
[Aligned lectures: Exploratory Data Analysis (EDA) at Scale; Finalizing CW sessions 1 to 3; Preparation for Assessment - submission; Preparation for Assessment submission - review; Critical Reflection]



Task	Brief	Word count	Requirements	Expected output	Marking
1	Define the problem here, describe the allocated dataset, justify the 5 V's of Big Data, and explain your preprocessing, feature engineering and PySpark Pipeline decisions.	350 words	Hyperlink: “Task1 Notebook (GitHub)”
Evidence pack (embedded in report)
Notebook requirements: Student-Name-Mail-Dataset declaration, SparkSession initialisation, dataset loading, schema inspection, row and column count, file size verification, partition count, PySpark Pipeline construction
Minimum 3 commits, at least one in each of Weeks 1 and 2
	Problem and dataset description
Big Data justification table (5 V's, licence, ethical note)
Data preparation and pipeline table
One evidence pack image	30%
2	Overview Your FOUR selected ML algorithms, justify the selection of each algorithm for the problem, discuss your hyperparameter tuning, and compare the four models on their evaluation metrics.	400 words	Hyperlink: “Task2 Notebook (GitHub)”
Notebook requirements: minimum four ML algorithms across at least three families, hyperparameter tuning using CrossValidator, training times, full metrics, confusion matrices, ROC and PR curves  Minimum 3 commits, at least one in each of Weeks 3 and 4	Algorithm selection table   Tuning and compute table  Metrics comparison table for all four models One composite evidence image 	40%
3	Provide some interpretation of the Spark UI, justify Your caching, persisting and resource configuration decisions with measured before and after timings, present Your stability analysis and discuss Your model explainability and fairness.	300 words	Hyperlink: “Task3 Notebook (GitHub)”, 
Notebook Requirements:  Spark UI screenshot, caching or persisting, resource configuration, repartitioning strategy, perturbation analysis, SHAP or LIME output
Minimum 3 commits in Week 5	Spark UI and optimisation table with measured before and after
Stability table
Explainability and named bias risk 	20%
4	Describe and present Your FOUR Tableau dashboards whilst providing Your narrative insights on each, and reflect critically on the limitations of Your analysis.	150 words	Hyperlink: “Tableau Workbook (Public Link)”
Hyperlink: “Task4 Notebook (GitHub)”
Notebook requirements: data export for Tableau, preprocessing for visualisation
Minimum 3 commits in Week 6	Contact sheet of all four dashboards
Three insights, each written as observation, evidence, and the decision it supports
Critical reflection	10%

Mark Allocation:
Every sub-section of the Answer Sheet is listed below so that you know where the marks are. The Marks column totals 100.

Row	Sub-section	Comp.	Judg.	Marks	What earns the marks
1.1	Problem, dataset and why this pairing	2	6	8	Problem framed against the allocated dataset; Pool reference, source and licence declared
1.2	Big Data and compliance table	3	5	8	Five V's evidenced from your own data, with licence and ethical note
1.3	Data preparation and pipeline table	4	6	10	Preprocessing and feature engineering decisions justified; pipeline stage order explained
EP1	Evidence pack 1	3	1	4	Student-Name-Mail-Dataset header, SparkSession, printSchema, row and column count, file size, partitions, pipeline stages
	Task 1 subtotal	12	18	30	
2.1	Algorithm selection table	4	8	12	Four algorithms across three families, each justified for this problem, with the ParamGrid searched
2.2	Tuning and compute table	5	7	12	Best parameters, CV folds, training time and executor configuration per model, interpreted
2.3	Metrics comparison table	5	7	12	Complete metrics for all four models, with a reasoned comparison and recommendation
EP2	Evidence pack 2	2	2	4	One loop output with all four training times, plus confusion matrices, ROC and PR panels
	Task 2 subtotal	16	24	40	
3.1	Spark UI and optimisation table	3	5	8	Stage timeline read correctly; each change carries a measured before and after
3.2	Stability table	3	3	6	Perturbation applied, delta per metric per model, most and least stable explained
3.3	Explainability and fairness	2	4	6	SHAP or LIME output, top five features, one named bias risk discussed
	Task 3 subtotal	8	12	20	
4.1	Dashboard contact sheet	3	1	4	All four dashboards present and legible on one sheet
4.2	Insights and critical reflection	1	5	6	Each insight as observation, evidence, and decision; reflection on limitations
	Task 4 subtotal	4	6	10	
	TOTAL	40	60	100	

“Comp.” is Compliance and Evidence, worth 40 marks in total. These marks are checked against your repository and your results files, and are either met or not met. “Judg.” is Academic Judgement, worth 60 marks in total, and is marked by your tutor against the bands in the Assessment Marking Criteria.
Version control is marked inside each Task's compliance allocation. Your commit count, message format, measured-outcome commit and weekly progression are all assessed there.
 Two repository rules adjust the final mark. A publicly visible repository costs 10 marks, and a repository hosted outside 7006SCN2627SEPNOV caps the overall mark at 20%. Deductions are applied to the combined mark first, then the cap.

Submission Instructions:
Include an AI-Use Declaration (see below) before your reference list
Mark and Feedback date: 9/11/2026
Mark and Feedback method: given on each script.  
This assessment is in Amber category for the use of AI, meaning that you can use AI for assistance.
AI￼Use Declaration (Required)
You must include an AI￼Use Declaration in your report after your Report heading. This declaration must:

•	Identify which AI tools were used

•	Explain how they were used

•	Specify which sections they contributed to

•	Confirm that you reviewed, edited, and verified all AI￼generated content

Failure to declare AI use will be treated as an Academic Conduct Offence.
Guidelines for Using AI in assessment 
You are allowed to use AI tools (such as ChatGPT, Copilot, Grammarly, etc.) to support your work, but you must follow these rules:
Be transparent.
·	Clearly mention where and how you used AI in your assignment.
·	This applies to text, code, images, or data.
 
Annotate AI use in your work.
 
·	Example for essays/reports:
·	“Section 2.2: I used ChatGPT to check grammar and rephrase sentences.”
·	“Literature review draft was generated with AI help, then edited and referenced manually.”
Example for code:
·	Add a comment:
·	# Function structure suggested by GitHub Copilot, modified by me
 
Do not present AI output as your own thinking.
·	You must adapt, edit, and understand anything AI suggests.
·	If you cannot explain it, don’t include it.
 
Always check AI content
·	Verify accuracy, especially for references, facts, or citations. AI may generate incorrect or fake material.
 
Balance your own work and AI help
·	AI should support your learning, not replace it.
·	Most of your assignment must still show your understanding and skills.
 
Include a short AI-use statement.
 
·	At the end of your submission, add a section:
 “AI Use Declaration: I used ChatGPT to generate code comments in Section 4, and Grammarly for grammar checking in Section 5.”
You should include a summary of where and how you used AI tools at the end of your work before your reference list. This could include the adaptation of the following table:  
 Tool  	How used in this assignment  
e.g. ChatGPT-3.5  	Key word search on topics related to learning outcomes  
e.g. Microsoft Copilot  	Summarising documents as part of background research  
·	MUST remember, use of AI will impact your score even when referenced and mentioned. Not mentioning use of AI may be a case of ACO.


Marking and Feedback
How will my assignment be marked?
Your assignment will be marked by the module team.
How will I receive my grades and feedback?
Provisional marks will be released once internally moderated.  Feedback will be provided by the module team alongside grades release.  Students will be able to access their feedback via Aula.  Your provisional marks and feedback should be available within 2 weeks (10 working days).
Feedback comments can be accessed by clicking on your submission in Turnitin and selecting the comments icon. The completed marks rubric can be accessed through the rubric icon.
What will I be marked against?
Details of the marking criteria for this task can be found at the bottom of this assignment brief. 

Assessed Module Learning Outcomes
The Learning Outcomes for this module align to the marking criteria which is provided above. Ensure you understand the marking criteria to ensure successful achievement of the assessment task. The following module learning outcomes (highlighted in bold) are assessed in this task:
On successful completion of this module a student should be able to:
·	Perform appropriate preparation of a dataset and evaluate the performance of different learning algorithms on this dataset with focus on statistical concepts.
·	Critically evaluate the key concepts and models of machine learning, such as supervised learning (classification or regression), learning unsupervised (clustering) and dimension reduction techniques. 
·	Critically analyse the challenges of Big Data and apply appropriate machine learning techniques for processing large-scale datasets. 
·	Critically evaluate the ethical and social implications of using machine learning in real-world applications for big data. 
·	Create and implement machine learning algorithms using suitable tools, libraries, and platforms. 


Assignment Support and Academic Integrity
If you have any questions about this assignment, please see the Student Guidance on Coursework for more information. 
Spelling, Punctuation, and Grammar:
You are expected to use effective, accurate, and appropriate language within this assessment task. 
Academic Integrity:
The work you submit must be your own, or in the case of groupwork, that of your group. All sources of information need to be acknowledged and attributed; therefore, you must provide references for all sources of information and acknowledge any tools used in the production of your work, including Artificial Intelligence (AI). We use detection software and make routine checks for evidence of academic misconduct.
Definitions of academic misconduct, including plagiarism, self-plagiarism, and collusion can be found on the Student Portal. All cases of suspected academic misconduct are referred for investigation, the outcomes of which can have profound consequences to your studies. For more information on academic integrity please visit the Academic and Research Integrity section of the Student Portal.
Support for Students with Disabilities or Additional Needs:
If you have a disability, long-term health condition, specific learning difference, mental health diagnosis, or symptoms and have discussed your support needs with health and wellbeing you may be able to access support that will help with your studies.
If you feel you may benefit from additional support, but have not disclosed a disability to the University, or have disclosed but are yet to discuss your support needs it is important to let us know so we can provide the right support for your circumstances. Visit the Student Portal to find out more.
Unable to Submit on Time?
The University wants you to do your best. However, we know that sometimes events happen which mean that you cannot submit your assessment by the deadline or sit a scheduled exam. If you think this might be the case, guidance on understanding what counts as an extenuating circumstance, and how to apply is available on the Student Portal. 

Administration of Assessment
Module Leader Name: Dr Katerina Stamou 
 Module Leader Email: ac2028@coventry.ac.uk  
Assignment Category: Written
Attempt Type: Standard 
Component Code: CW 
Assessment Marking Rubric: 
*Stability: Stability indicated how a machine learning algorithm output is changed with small perturbations to its inputs. A stable learning algorithm is one for which the prediction does not change much when the training data is modified slightly. A learning algorithm is said to be stable if the learned model doesn't change much when the training dataset is modified.
* Business value = Turning Data into Actionable Insight: The ultimate value of a Tableau dashboard is that it closes the gap between data and decision-making, enabling a faster, more accurate, and data-driven organizational culture.
Your mark is made of two parts. Compliance and Evidence is worth 40 marks and is checked against your repository and your results files. Academic Judgement is worth 60 marks and is marked against the bands below. The two parts add to 100.
Part 1 — Compliance and Evidence (40 marks)
Task	What is verified	How it is verified	Marks
1	Project code repository is inside 7006SCN2627SEPNOV	Organisation read from the submitted repository URL	Cap - see Adjustments
1	Project code repository is private, not publicly visible	Read from GitHub at the deadline	Penalty - see Adjustments
1	Repository accessible, four notebooks present, README maintained	Repository cloned and file structure inspected	1
1	Dataset analysed is the one allocated in 7006SCN2627SEPNOV_Dataset Catalogue_Released.xlsx	Pool reference in results/task1.json compared with the register	2
1	Dataset is 1 GiB or more; Pool reference, source URL and licence declared	results task1.json	3
1	Pipeline has at least three stages; cluster configuration recorded	results/task1.json	3
1	Task 1: three or more commits, correct message format, one measured-outcome commit, commits in both Weeks 1 and 2	Commit log and timestamps	3
	Task 1 subtotal		12
2	Four algorithms spread across at least three families	results/task2.json	3
2	Every model tuned with CrossValidator, with best parameters and fold count	results/task2.json	4
2	Training time recorded per model and metrics complete for all four	results/task2.json	4
2	Metric sets distinct across models; declared models appear in the notebook source	Results cross-checked against the notebooks	2
2	Task 2: three or more commits meeting the standard, in both Weeks 3 and 4	Commit log and timestamps	3
	Task 2 subtotal		16
3	At least one optimisation carries a measured before and after timing	results/task3.json	2
3	Stability analysis covers all four models	results/task3.json	2
3	SHAP or LIME output with five or more features and a named bias risk; caching or persisting applied	results/ task3.json	2
3	Task 3: three or more commits meeting the standard, in Week 5	Commit log and timestamps	2
	Task 3 subtotal		8
4	Four dashboards declared and the Tableau Public link resolves	results/task4.json and the link	1
4	Word count within 1320; commit hashes cited in the Report exist in the log	Report checked against the commit log	2
4	Task 4: three or more commits meeting the standard, in Week 6	Commit log and timestamps	1
	Task 4 subtotal		4
	PART 1 TOTAL		40

Part 2 — Academic Judgement (60 marks)
Marks by Task: Task 1 is worth 18, Task 2 is worth 24, Task 3 is worth 12 and Task 4 is worth 6. Award each Task across its criteria, then check the result against the band descriptor.
Band	Outcome	General standard
0-29%	Fail	Little or no valid attempt. Requirements are not met and the work cannot be assessed against the criterion.
30-39%	Fail	A marginal attempt. Some relevant content, but major omissions or errors, or content that is generic rather than about your own work.
40-49%	Pass	Descriptive. The minimum requirements are met, reasons are stated but thin, and the analysis does not go beyond what was done.
50-59%	Pass	Sound. Reasoning is consistent and anchored to your own evidence, with some interpretation of results.
60-69%	Good	Analytical. Choices are argued from the properties of the data and the problem, rather than justified after the fact.
70-79%	Very good	Critical. Alternatives are considered and rejected with reasons, and risks and trade-offs are anticipated.
80-89%	Excellent	Authoritative. Reasoning is coherent across the whole submission, limitations are owned, and taught material is extended rather than applied.
90-100%	Outstanding	Professional standard. The work would withstand scrutiny from a specialist and shows judgement about how far its own evidence reaches.

Task 1 — Problem, Data and Pipeline (18 marks) 
Band	Marks	Descriptor
0-29%	0-5	No usable problem statement, or the dataset is described with no problem attached. The five V's are absent or reproduced as definitions. Preparation steps are missing or could apply to any dataset.
30-39%	5.5-7	A problem and a dataset are named but not connected. Some V's carry a figure, others are asserted. Preparation steps are listed without reasons. Licence or ethical note missing.
40-49%	7-8.5	Problem and dataset are both stated clearly, but the link between them is asserted rather than argued. Each V has a figure from your own data. Preparation decisions carry brief reasons. Licence stated.
50-59%	9-10.5	Problem and dataset are argued together, with the target variable and its meaning explained. Pipeline stages are in a defensible order with reasons given. The ethical note is relevant to this data.
60-69%	11-12.5	The pairing is justified from the properties of the data. The V's are weighted, so it is clear which dominate here and why. Stage order is explained, including why it must be that order.
70-79%	12.5-14	Alternatives to the chosen preparation are considered and rejected with reasons. Leakage, scale or skew risks are anticipated and addressed. Compliance reasoning engages with the actual licence terms.
80-89%	14.5-16	The dataset's limitations for this problem are identified early and carried forward into later Tasks. Preparation forms a coherent design rather than a sequence of steps.
90-100%	16.5-18	Framing that would survive scrutiny from a domain specialist. The compliance and ethical analysis are evaluative and raises a risk a careful practitioner would raise.

Task 2 — Modelling at Scale (24 marks)
Band	Marks	Descriptor
0-29%	0-7	Fewer than four algorithms, or no reasoned selection at all. Tuning absent or unreported. Metrics missing, incomparable, or not attributable to your own run.
30-39%	7-9.5	Four algorithms are present but justified as textbook descriptions of how each one works. Tuning is described without results. Metrics are tabulated inconsistently across models.
40-49%	9.5-11.5	Four algorithms across three families, each with a stated reason for this problem. Best parameters reported. Models compared on the metrics and a choice stated.
50-59%	12-14	Selection reasons refer to this dataset rather than to algorithms in general. The tuning process is described and its outcomes reported. The chosen model is defended on a named metric.
60-69%	14.5-16.5	Selection is argued from dimensionality, class balance, linearity or scale. Tuning outcomes are interpreted, so it is clear why these values won. The deciding metric is itself justified.
70-79%	17-19	Selection forms a coherent experimental design, and the ParamGrid choices follow the same reasoning. Accuracy is traded against compute cost with reference to the executor configuration.
80-89%	19-21.5	Class imbalance is handled and its effect on metric choice discussed. Where metrics conflict, the tension is resolved with a defensible rule. Enrichment topics are used where they earn their place.
90-100%	21.5-24	The modelling section reads as a controlled experiment. Conclusions are hedged to what the evidence supports, and compute cost is treated as a real constraint on the recommendation.


Task 3 — Evaluation, Optimisation and Explainability (12 marks)

Band	Marks	Descriptor
0–29%	0-3.5	No optimisation attempted, or none measured. Stability analysis absent. No explainability output.
30–39%	3.5-4.5	Generic advice about caching and partitioning. The Spark UI is reproduced rather than read. Perturbation applied but not interpreted. SHAP or LIME output presented without comment.
40–49%	5-6	Stage timeline read correctly and at least one change reported with its measured effect. Most and least stable models identified. Top features listed and a bias risk named.
50–59%	6-7	The optimisation is linked to what the timeline showed. Stability deltas are compared across models. The named bias risk relates to the actual feature set.
60–69%	7-8.5	The bottleneck is diagnosed rather than just observed, and the change follows from the diagnosis. Stability differences are explained by how each algorithm works. The bias risk has a plausible mechanism.
70–79%	8.5-9.5	Skew, shuffle behaviour or spill is identified from the evidence, and the optimisation is reasoned from distributed computing principles. Stability is connected to which model would be trusted in deployment.
80–89%	9.5-10.5	Interpretability and explainability are distinguished. A mitigation for the bias risk is proposed and its limits acknowledged. The optimisation reasoning generalises beyond this single run.
90–100%	11-12	The evaluation would inform a real deployment decision. Fairness analysis is critical rather than compliant, and the trade-off between performance, stability and explainability is resolved.



Task 4 — Tableau Storytelling and Critical Reflection (6 marks)
Band	Marks	Descriptor
0–29%	0-1.5	Fewer than four dashboards, or dashboards illegible. Insights absent or unrelated to the analysis.
30–39%	2	Dashboards present but default-styled with no design decisions. Insights restate what the chart shows. No reflection, or reflection is generic self-praise.
40–49%	2.5-3	Four dashboards legible and purposeful. Three insights, each written as observation, evidence, and a decision it supports.
50–59%	3-3.5	Insights cite your own dashboards by figure number. The reflection notes at least one real limitation of the work.
60–69%	3.5-4	Insights connect the modelling work to a decision someone would actually take. Dashboard design choices are explained rather than left implicit.
70–79%	4-4.5	The reflection identifies a genuine limitation of the analysis and states what would be done differently, with a reason.
80–89%	5-5.5	Reflection shows judgement about the reliability of the whole pipeline, not only the dashboards, and draws on Day 9 Model Deployment & Serving.
90–100%	5.5-6	A narrative that would stand up in front of a stakeholder audience. Limitations are stated with the confidence of someone who knows how far the evidence reaches.

Adjustments
Rule	Adjustment	Detail
Project code repository is publicly visible at the deadline	minus 10 marks	A deduction from the combined mark, not a cap. Visibility is read from GitHub at the deadline. The deduction covers the breach of the technical requirement only. Where another submission is found to derive from the public repository, both scripts are referred as an Academic Conduct Offence.
Project code repository hosted outside 7006SCN2627SEPNOV	capped at 20%	Applies where the repository sits in a personal GitHub account, another organisation, or a non-GitHub platform. 20% is below the 40% pass mark, so the cap means the assessment is not passed. A private backup elsewhere is permitted.
Dataset other than the one allocated by Your Module Leader	capped at 30-39%	You are not permitted to propose your own dataset. Verified against the Pool reference recorded in results/task1.json.




```

what exaclty is the ask?

## Assistant:

> 10/7/2026 22:23:55

The ask is a coursework report for **7006SCN Machine Learning and Big Data** (Coventry University). It's one Word document backed by a GitHub repo and a Tableau workbook, worth 30 credits and 100% of the grade. It's due **Monday 26 Oct 2026, 6pm UK time**. A 24-hour grace window runs to 27 Oct 6pm, but it's only for technical problems, and late work scores zero.

**The core task**

Take the big dataset you've been allocated and solve a real-world problem with it (classification, regression or clustering) using **PySpark for the entire pipeline**. The dataset is assigned to you by the module leader, matched to your student email in the Dataset Catalogue spreadsheet on Aula. You can't swap it or pick your own. The brief also requires it to have at least 10 million rows, at least 10 columns and at least 1 GiB of size (a truncated version is fine if it still meets those limits).

**What you submit**

1. **One Word report** (about 1,200 words, ±10%), using the provided answer-sheet template. The word count goes at the start. Include an AI-use declaration before the reference list.
2. **A private GitHub repo** inside the module organisation `7006SCN2627SEPNOV`, named `7006SCN_<Initials>_<SID>`, containing:
   - `notebooks/Task1.ipynb` to `Task4.ipynb`
   - `results/task1.json` to `task4.json`
   - `README.md`
3. **A public Tableau workbook** with four dashboards: data quality and pipeline monitoring, model performance and feature importance, business insights, and scalability and cost.

**The four tasks**

| Task | Focus | Words | Weight |
|---|---|---|---|
| 1 | Problem, dataset, 5 V's, preprocessing and pipeline | 350 | 30% |
| 2 | Four ML algorithms (one each from linear, tree-ensemble and distance/kernel/neural, plus a free choice), CrossValidator tuning, and a metrics comparison | 400 | 40% |
| 3 | Spark UI reading, caching and repartitioning with before/after timings, stability analysis, SHAP or LIME, and a named bias risk | 300 | 20% |
| 4 | Tableau dashboards, three insights (observation, evidence, decision), and critical reflection | 150 | 10% |

Each task also needs a notebook hyperlink and an evidence image or table, as listed in the brief.

**Version control is marked**
- At least 3 meaningful commits per task (12 or more overall).
- The message format is `[TaskN] verb object - reason or measured result`.
- At least one commit per task must report a measured value.
- Commits must fall in the right weeks. Tasks 1 and 2 each need at least one commit in each of their two weeks.
- Each report sub-section must cite the short commit hash of its evidence.

**Marking split**
- **40 marks Compliance:** checked mechanically against your repo and JSON files.
- **60 marks Academic Judgement:** a tutor marks your reasoning against the grade bands. Higher bands reward argued choices, anticipating risks like leakage, and owning limitations.

**Penalties that can sink you**
- Repo outside the module organisation: **capped at 20%**, which is a fail.
- Repo public at the deadline: **−10 marks**.
- Wrong dataset: **capped at 30–39%**, which is a fail.
- Broken GitHub or Tableau links: **0**.
- Undeclared AI use: treated as an academic conduct offence. AI is allowed (Amber category), but you must disclose it and be able to explain everything you submit.

Since the deadline is 26 October and today is 7 October, you have about three weeks. Because the weekly commit-timing rules reflect the teaching weeks, check right away that your commit history in the org repo is on track. I can help build a plan around that, or work through a specific task.

## User:

> 10/7/2026 22:28:31

did they definelty ask each week each commit or at last can i do do 3 at once with incremental updattes

## Assistant:

> 10/7/2026 22:28:39

Short answer: no, you can't just do it all at the end. The brief explicitly ties commits to the teaching weeks, and the check is mechanical.

**What the brief actually says**

- **Weekly progression:** "Commits must be timestamped in the correct weeks. Tasks 1 and 2 (likewise Tasks 3 and 4) span two teaching weeks, so at least one commit must fall in each of them."
- **Minimum commits:** 3 meaningful commits per task (12 overall).
- **Week mapping:** Task 1 is Weeks 1-2, Task 2 is Weeks 3-4, Task 3 is Week 5, Task 4 is Week 6.
- **Why they do this:** the brief says the module-org repo is how they verify the work "was developed across the teaching weeks, and that your commit history is intact." Compliance marks for each task include "commits in both Weeks X and Y" and are checked against the commit log and timestamps.

So it's not "each week, one commit" strictly. It's:

| Task | Weeks | Requirement |
|---|---|---|
| 1 | 1-2 | 3+ commits, at least 1 in Week 1 and 1 in Week 2 |
| 2 | 3-4 | 3+ commits, at least 1 in Week 3 and 1 in Week 4 |
| 3 | 5 | 3+ commits, all in Week 5 |
| 4 | 6 | 3+ commits, all in Week 6 |

**Can you batch 3 incremental commits at once?**

Making three commits in one sitting is fine for the "3 commits" count, as long as they're meaningful, each with a proper `[TaskN] verb object - result` message and at least one reporting a measured value. What you can't fix is the **timestamps**. If the teaching weeks have already passed and your commits all land in the last few days, the weekly-progression marks are very likely lost.

**Two things I'd caution against**

- **Don't backdate commits** (editing `GIT_AUTHOR_DATE` or similar). GitHub records push times too, the module team can see the org's activity, and the brief treats integrity of the history as the point. Faking it risks an academic conduct case, which is far worse than losing a few marks.
- **Don't delete and recreate the repo** to "fix" history. A repo built elsewhere and moved loses its history and is capped at 20%.

**What I'd do**

First, check your repo's commit log now (`git log --format="%h %ad %s" --date=iso`) and see what you already have and which weeks they fall in. If you're behind on early weeks, you'd lose only the weekly-progression and possibly some commit-count marks (a few of the 40 compliance marks), not the whole assessment. The best move is to make your remaining commits genuine, incremental and well-messaged as you finish each notebook, and if you missed a week, email the module leader (Dr Stamou, ac2028@coventry.ac.uk) early, especially if there was an access or extenuating reason. The brief says problems raised early get handled, while problems found at the deadline don't.

Which weeks are you currently in, and do you have any commits in the org repo yet? I can help you plan from there.

## User:

> 10/8/2026 22:52:29

> File: 7006SCN2627SEPNOV_Report_AnswerSheet_Dr_KStamou_v1 (2).docx

> File: 7006SCN2627SEPNOV_Report_AnswerSheet_Classification_Dr_KStamou_v1.docx

> File: 7006SCN2627SEPNOV_Report_AnswerSheet_Regression_Dr_KStamou.docx

> File: 7006SCN2627SEPNOV_Report_AnswerSheet_Clustering_Dr_KStamou.docx

> File: 7006SCN2627SEPNOV_Dataset Catalogue_Released_Dr_KStamou (1).xlsx

33	Sridhar	Gude	NYC TLC Yellow Taxi Trip Records, Jan–Jun 2024	NYC TLC	https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page (direct files: https://d37ci6vzurychx.cloudfront.net/trip-data/; AWS mirror: https://registry.opendata.aws/nyc-tlc-trip-records-pds/)	Free - no registration	Six monthly Parquet files Jan-Jun 2024 merged. Target: payment type.

## Assistant:

> 10/8/2026 22:52:51

> Identifying the payment type for a taxi trip record.
>
> - Identifying the payment type for a taxi trip record.
> - **Done**

Let me check the templates and the catalogue so I can match your row to the right answer sheet.

> Reviewing the pasted allocation details to understand the request.
>
> - Read file-reading skill before opening uploads
> - Find allocation row and read classification template
> - Reviewing the pasted allocation details to understand the request.
> - **Done**

Your row is confirmed. The Sheet1 tab of the catalogue lists **No. 33, Sridhar Gude, gudes@coventry.ac.uk, NYC TLC Yellow Taxi Trip Records Jan-Jun 2024**, with the target given as payment type.

**What this means for you**

- **Problem type:** classification, so the **Classification answer sheet** is your template. Ignore the Regression and Clustering ones.
- **Pool reference:** the catalogue only shows "No. 33". The brief wants a Pool reference like "TR-04" in your report and in `results/task1.json`. Check Aula or ask Dr Stamou what yours is, because the compliance marks compare it against the register.
- **Task 2 shape:** you need four models across three families. A natural set is Logistic Regression, Random Forest or GBT, and a Multilayer Perceptron or Naive Bayes, plus a free choice.

**Things in this dataset that can earn judgement marks**

1. **Leakage is the big one.** In the TLC data, `tip_amount` is essentially only recorded for credit-card trips, and cash tips are logged as 0. `total_amount` also includes the tip. Both leak the target, and a model using them looks brilliant for the wrong reason. Drop them and say why. This is exactly the "leakage risk anticipated" language in the 70-79% band.
2. **Class imbalance.** Credit card dominates, cash is a clear minority, and "no charge" and "dispute" are tiny. Decide early whether to keep five classes, merge the rare ones, or go binary (card vs cash). Then justify your metrics (weighted or macro F1, PR curves, not just accuracy). This also feeds the "handling imbalance" band in Task 2.
3. **Payment type 0 (flex fare) in 2024.** It tends to come with missing values in fields like `passenger_count` and `congestion_surcharge`, so the missingness itself may predict the class. This is worth a sentence on veracity.
4. **Data quality.** Expect negative fares, zero distances, absurd durations and timestamps outside Jan-Jun 2024. Filter them and report the counts.
5. **Schema drift when merging the six Parquet files.** Column types can differ between months, such as int vs bigint or `Airport_fee` casing. Read them with an explicit schema or cast before the union.

**One risk to check now:** the rubric requires the dataset to be **1 GiB or more**, and the row count to be 10M or more. Six months of yellow taxi should be roughly 20 million rows, which is fine. But the six Parquet files are compressed and may total only a few hundred MB on disk. Check the actual size in your notebook (`du -sh`), and ask Dr Stamou whether uncompressed or in-memory size counts, before you assume it passes.

I read the template's Task 1 section. It wants a 1.1 problem framing, a 1.2 table of the five V's with licence and ethical note, a 1.3 five-stage pipeline table, an evidence pack image, and a 30-word process note. Every claim needs a figure reference, a taught-session name and a commit hash.

Do you want to start by drafting Task 1 (1.1 to 1.3 text) from this dataset, or by planning the PySpark notebook structure first?

## User:

> 10/8/2026 22:54:02

yes now please finish the whole task 1 keep it naturla human languag simple english using /humanizer simple end ot end please nic eneat dont run the ipynb i will run and give you u cant add finishding base don what we get

## Assistant:

> 10/8/2026 22:57:40

> Assembling pipeline stages and validating pre-fit null checks.
>
> - Drafting the Task 1 notebook and its plain-English report.
> - Read humanizer skill
> - Structuring the pipeline stages for cleaning and feature encoding.
> - NYC TLC trip record data terms of use license yellow taxi data dictionary payment_type
> - Assembling pipeline stages and validating pre-fit null checks.
> - Check nbformat is available
> - Install nbformat
> - Generator script that builds the Task 1 notebook (not executed)
> - **Done**

Building the Task 1 notebook file now (writing it only, not running any Spark code), then the report text.

> Condensing each data-quality section into terse summary lines.
>
> - Generate notebook and syntax-check code cells
> - Write README, gitignore and Task 1 report draft; rough word count
> - Condensing each data-quality section into terse summary lines.
> - Tighten report draft to word budget and list outputs
> - Presenting file(s)...
> - **Done**

> File: [/mnt/user-data/outputs/README.md](https://claude.ai/api/organizations/afcc61c1-790c-471f-97f8-f2613e3a76b5/conversations/3618d6dd-e0ac-45d3-9629-5b20892a234f/wiggle/download-file?path=%2Fmnt%2Fuser-data%2Foutputs%2FREADME.md)

> File: [/mnt/user-data/outputs/Task1_report_draft.md](https://claude.ai/api/organizations/afcc61c1-790c-471f-97f8-f2613e3a76b5/conversations/3618d6dd-e0ac-45d3-9629-5b20892a234f/wiggle/download-file?path=%2Fmnt%2Fuser-data%2Foutputs%2FTask1_report_draft.md)

> File: [/mnt/user-data/outputs/notebooks/Task1.ipynb](https://claude.ai/api/organizations/afcc61c1-790c-471f-97f8-f2613e3a76b5/conversations/3618d6dd-e0ac-45d3-9629-5b20892a234f/wiggle/download-file?path=%2Fmnt%2Fuser-data%2Foutputs%2Fnotebooks%2FTask1.ipynb)

---

**Sources:**

- [data dictionary trip records yellow](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)
- [dataset taxi yellow](https://learn.microsoft.com/azure/open-datasets/dataset-taxi-yellow)
- [data dictionary trip records yellow](https://cdn.muckrock.com/outbound_composer_attachments/tosfeathers/95263/data_dictionary_trip_records_yellow.pdf)
- [TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- [2020 yellow taxi trip data january june](https://catalog-old.data.gov/dataset/2020-yellow-taxi-trip-data-january-june)
- [2023 yellow taxi trip data](https://catalog-old.data.gov/dataset/2023-yellow-taxi-trip-data)
- [2019 yellow taxi trip data](https://catalog.data.gov/dataset/2019-yellow-taxi-trip-data)
- [2022 yellow taxi trip data](https://catalog-old.data.gov/dataset/2022-yellow-taxi-trip-data)
- [2018 yellow taxi trip data](https://catalog-old.data.gov/dataset/2018-yellow-taxi-trip-data)

## User:

> 10/9/2026 16:58:08

> File: sridhar-week1.ipynb

take this and acheck and add if anythings needed keepi ti ai free keep it simple and is ther enay word form atha i need ned to fill check and get full gfinal dleiverbaleds end ot end do thourugh inspections

## Assistant:

> 10/9/2026 17:02:37

> Handling empty table cells and their default font sizes.
>
> - Inspect uploaded notebook cells and outputs
> - Drafting hedged wording for unresolved gap percentages in the report.
> - Check catalogue for pool reference column and student row
> - Dump classification answer sheet structure
> - Mapping figure labels to notebook cells for citation references.
> - Inspect run formatting for filling the docx
> - Handling empty table cells and their default font sizes.
> - Check row height rules and paragraph defaults in answer sheet tables
> - **Done**

Checking your run results and updating the notebook (new size and gap checks, figure labels), then filling the Word answer sheet.

> Trimming the report length to meet the target word count.
>
> - Update the user's notebook: add size/gap checks, figure labels, fix JSON and EP1 cells
> - Fix cell lookup and rebuild notebook
> - Filling in student details and documenting AI tool usage.
> - Read docx skill before editing the Word template
> - Fill Task 1 parts of the Word answer sheet
> - Drafting each table and step summary within word limits.
> - Tighten Task 1 text to fit the word budget and rebuild docx
> - Trimming the report length to meet the target word count.
> - Render docx to PDF and validate
> - **Done**

Checking the rendered pages of the filled Word sheet now, then I'll give you the final list.

> Finalized the summary and prepared the requested document updates.
>
> - Look at page 1 of the rendered answer sheet
> - Render Task 1 pages at higher resolution
> - Task 1 page A
> - Task 1 page B
> - Finalized the summary and prepared the requested document updates.
> - Remove superseded draft file
> - Presenting file(s)...
> - **Done**

Your notebook ran clean and the numbers look right, but one compliance problem needs your action first. The updated notebook and the filled Word answer sheet are attached (`Task1.ipynb` and `7006SCN2627SEPNOV_Report_AnswerSheet_Classification_Task1_filled.docx`).

**The 1 GiB problem**

Your six Parquet files total only **0.32 GiB** on disk, and the rubric line for Task 1 says the dataset must be 1 GiB or more. I added a cell that measures the same data as plain CSV (written, measured, then deleted) and one that estimates the size from the column types. Parquet is compressed, so the CSV figure should be well over 1 GiB. Please also email Dr Stamou (ac2028@coventry.ac.uk) and ask whether uncompressed size counts. The report's process note says you "raised it with the module leader", so do that before you submit.

**What I checked in your run**

- 20,332,093 rows, 19 columns, 24 partitions and a 7-stage pipeline. All good.
- Payment codes 0, 3, 4 and 5 make up 12.04% of rows, so dropping them is a real choice. The report states it as a limitation.
- The gaps in five columns are all exactly 9.72%, the same as flex fare trips. That looks like one cause, but your output doesn't prove it. I added two check cells (Fig. T1.7a and T1.7b) to confirm it.
- The tip leakage is clear: cash averages 0.00 and card averages 4.30.

**What I changed in the notebook**

- Added the size-check cell and the two gap-check cells.
- Added figure labels (Fig. T1.1 to T1.7 and EP1) above each output, so the report's references point to something real.
- Extended the `results/task1.json` cell (CSV size, payment counts, gaps in kept data) and the EP1 cell.

**What the Word sheet now has**

Student details (name, dataset), the Task 1 AI-use row, sections 1.1 to 1.3, the EP1 caption, the process note, three references and the word count (about 440). Everything you still need to fill is highlighted in yellow. Task 1 is a bit over its 350 target, so keep Tasks 2 to 4 tight to stay under 1320 in total.

**Your steps, in order**

1. Edit the first code cell: fill in `SID` and `POOL_REF`. The catalogue file only shows "No. 33", so check Aula for a TR-style code.
2. In the same kernel, run the new cells, then the `task1.json` cell, then the EP1 cell. If the kernel restarted, use Run All. The CSV check takes a minute or two.
3. Check the T1.7a and T1.7b outputs. If the gaps aren't mostly flex fare trips, tell me and I'll fix the Veracity and Imputation wording. Then paste the CSV GiB into the highlighted Volume cell.
4. Screenshot the EP1 cell into the Word sheet.
5. Commit with messages like these, once you have the real hashes:
   - `[Task1] load six parquet files with explicit casts - 20,332,093 rows in 7.4s`
   - `[Task1] add cleaning funnel, drop tip_amount and total_amount - 86.45% rows kept`
   - `[Task1] fit 7-stage pipeline on train split - 59.1s fit, 551 features`
6. Fill in the yellow items: SID, pool reference, the five commit hashes, the notebook link and your prompt count. Also paste your prompts into the Prompt Log and sign the declaration.

**About keeping it AI free**

I wrote the text in plain English, but I can't promise it will pass AI detection, and I wouldn't try to hide it. The brief allows AI (Amber category) if you declare it and can explain every line. So read it through, change anything that isn't how you'd say it, and only keep claims you understand. The declaration row I added says Claude wrote the first draft and you checked the figures. Add "and edited" only if you did.

**Two reminders**

- Commit timestamps are checked against the teaching weeks, and the weekly-progression marks depend on them. Don't backdate anything.
- The template footer says "Due: 2 November 2026", but the brief says 26 October 6pm. Trust the brief, and check Aula if you're unsure.

> File: [/mnt/user-data/outputs/notebooks/Task1.ipynb](https://claude.ai/api/organizations/afcc61c1-790c-471f-97f8-f2613e3a76b5/conversations/3618d6dd-e0ac-45d3-9629-5b20892a234f/wiggle/download-file?path=%2Fmnt%2Fuser-data%2Foutputs%2Fnotebooks%2FTask1.ipynb)

> File: [/mnt/user-data/outputs/7006SCN2627SEPNOV_Report_AnswerSheet_Classification_Task1_filled.docx](https://claude.ai/api/organizations/afcc61c1-790c-471f-97f8-f2613e3a76b5/conversations/3618d6dd-e0ac-45d3-9629-5b20892a234f/wiggle/download-file?path=%2Fmnt%2Fuser-data%2Foutputs%2F7006SCN2627SEPNOV_Report_AnswerSheet_Classification_Task1_filled.docx)

> File: [/mnt/user-data/outputs/README.md](https://claude.ai/api/organizations/afcc61c1-790c-471f-97f8-f2613e3a76b5/conversations/3618d6dd-e0ac-45d3-9629-5b20892a234f/wiggle/download-file?path=%2Fmnt%2Fuser-data%2Foutputs%2FREADME.md)

## User:

> 10/9/2026 17:17:37

hold on why we filled classification word doc? and why u didnt paste the screenshot of eveidence you can caputre from output and show right?

## Assistant:

> 10/9/2026 17:25:33

> Explaining how the payment type target became binary classification.
>
> - Explaining how the payment type target became binary classification.
> - Compare Task 1 sections of generic and classification answer sheets
> - **Done**

**Why the Classification sheet:** your target is payment type, and I turned it into a yes/no problem (cash vs card). That is classification, so I used the Classification version. I picked it without asking you, which I should have done.

I just compared the Task 1 section of the Classification sheet with the generic one (`..._Dr_KStamou_v1`, the file the brief names). They are word for word the same, so nothing in the Task 1 text needs to change either way. The differences are in Tasks 2 to 4. I didn't compare those sections, so I can't tell you what differs.

Before you submit, check on Aula which file you are meant to hand in. If it's the generic one, the Task 1 text pastes straight across. The brief names the generic file, so if Aula says nothing, ask Dr Stamou.

**Why no screenshot:** there are three reasons.

1. **I can't take a real screenshot.** I only have your notebook file, not your screen. The best I could do is draw the output text into a picture, and that is a re-creation rather than a capture.
2. **The evidence pack is marked as proof of your own run.** The brief asks for one image "produced from a single notebook cell". An image I generate and you paste in could look like a screenshot of your run when it isn't. If anyone checked it against your repo, that would be a problem for you, not for me.
3. **The output in your file is out of date.** It still shows `TODO_POOL_REF`, has no CSV size line, and has no SID. The final image has to come from the cell after you fix those and re-run.

The real screenshot is quick: re-run the EP1 cell (the last one) after the edits, then use your screenshot tool (Win+Shift+S, Cmd+Shift+4, or the notebook's screenshot button). Crop to the output and paste it into the grey EP1 box in the Word sheet. The caption is already filled in.

If you want a preview of how it will look, I can render your current output text as a picture and label it as a stand-in. Don't submit that one.

## User:

> 10/10/2026 11:51:59

who aske pool ref? and check agaoin throoughly which all i need to submit read all pdfs ned ot end

## Assistant:

> 10/10/2026 11:52:52

> Compiling the full submission checklist from the brief.
>
> - Checking submission requirements and locating referenced documents.
> - Re-check catalogue for pool reference and read full answer sheet requirements
> - Read pool reference instruction, final checklist, and diff generic vs classification sheets
> - Comparing the two documents for substantive differences.
> - Diff tables between generic and classification answer sheets
> - Compiling the full submission checklist from the brief.
> - Set pool reference to catalogue number in notebook and Word sheet
> - Presenting file(s)...
> - **Done**

The module asked for the pool reference, in three places, and I told you to look for a code that doesn't exist in your files. I've now corrected that.

**Who asked for the pool reference**

- **The brief:** it says to record it "in your Report front matter and in `results/task1.json`".
- **The Word sheet:** it has a "Dataset Pool reference" field in Student Details.
- **The checks:** the marker compares the reference in `task1.json` against the register.

I told you to look for a "TR-04" style code, but that was only the brief's example. Your catalogue has no such column. It only lists the row number, which for you is **No. 33**. The generic answer sheet also pre-fills that field with "Student-Name-Mail-Dataset", which suggests your name, email and dataset are what identify you. So I put "No. 33 in the Dataset Catalogue", plus your name, email and dataset, in the Word sheet. The notebook now has `POOL_REF = "No. 33 (Dataset Catalogue)"`. If Dr Stamou says a different reference is expected, change it in both places.

**What I read**

There are no PDFs in this chat. I re-read the assignment brief you pasted, the Classification and generic answer sheets, and the catalogue (both tabs).

**What you submit**

**1. One Word file on Turnitin**
- **Deadline:** Monday 26 Oct 2026, 6pm UK. The 24-hour grace is for technical problems only, and late work scores zero. The template footer says 2 November, but the brief says 26 October, so trust the brief.
- **Which sheet:** the Classification and generic sheets differ only in one intro sentence and the pre-filled pool field. The brief names the generic file. Ask Dr Stamou or check Aula which one to hand in.
- **Content:** everything on the sheet.
  - Student Details, including the total word count (maximum 1,320).
  - The signed MS Forms checklist screenshot.
  - The AI-Use Declaration and the signature line.
  - Tasks 1 to 4.
  - References.
  - The Prompt Log (paste your prompts, in order).
- **Commit hashes:** the checklist says eleven hashes, but the sheet has a hash line on every block, so fill them all.

**2. GitHub repo**
- **Location and name:** inside `7006SCN2627SEPNOV`, named `7006SCN_<Initials>_<SID>`.
- **Visibility:** private, because public costs 10 marks and a repo outside the org is capped at 20%.
- **Contents:**
  - `notebooks/Task1.ipynb` to `Task4.ipynb`
  - `results/task1.json` to `task4.json`
  - `README.md`
- **Commits:** at least 3 per task in the `[TaskN] verb object - result` format, with the right weeks.

**3. Links inside the Word file**
- All four notebook links.
- The Tableau Public link, with the four dashboards.
- If any link doesn't open in a private window, the whole assessment is marked zero.

**4. MS Forms checklist** (the "7006SCN CW-Project_Checklist"). The brief says to fill it in by the end of Week 2. I can't see whether you did, so check.

**What I haven't verified**

Your dataset's size (the 1 GiB rule) and which Word file to use are both still questions for Dr Stamou. I've also only written the Task 1 part of the sheet. Tasks 2 to 4 are blank until we do them.

> File: [/mnt/user-data/outputs/notebooks/Task1.ipynb](https://claude.ai/api/organizations/afcc61c1-790c-471f-97f8-f2613e3a76b5/conversations/3618d6dd-e0ac-45d3-9629-5b20892a234f/wiggle/download-file?path=%2Fmnt%2Fuser-data%2Foutputs%2Fnotebooks%2FTask1.ipynb)

> File: [/mnt/user-data/outputs/7006SCN2627SEPNOV_Report_AnswerSheet_Classification_Task1_filled.docx](https://claude.ai/api/organizations/afcc61c1-790c-471f-97f8-f2613e3a76b5/conversations/3618d6dd-e0ac-45d3-9629-5b20892a234f/wiggle/download-file?path=%2Fmnt%2Fuser-data%2Foutputs%2F7006SCN2627SEPNOV_Report_AnswerSheet_Classification_Task1_filled.docx)

## User:

> 10/10/2026 13:03:59

Id 17165640 this is id  and fill it propelryu andlaso when to submit this 1200 word is it final?i am not sdure check clwelallry taksk 1 is week 1? am is ubmititng correct clelallry check and telll is pynb perfect how much would u grade

## Assistant:

> 10/10/2026 13:04:32

> Estimating likely grade and flagging compliance risks honestly.
>
> - Estimating likely grade and flagging compliance risks honestly.
> - Put SID into notebook and Word sheet and re-validate
> - Presenting file(s)...
> - **Done**

Your SID (17165640) is now in the Word sheet and in the notebook's declaration cell. The notebook has no `TODO` left in it, and the Word file passed my validation check. Re-run the notebook once so the new SID shows in the EP1 screenshot.

**When to submit**

Monday 26 October 2026, 6pm UK time. UK clocks go back on 25 October, so that is 6pm GMT, which is **11:30pm in India**. The extra day to 27 October is only for technical problems with Turnitin, and late work scores zero. Aim to submit well before the deadline.

**Is the 1,200 words final?**

No. The 1,200 words (maximum 1,320) is the **whole report**. What I filled is only Task 1, at about 440 words. The budget for the whole report is Task 1 at 350, Task 2 at 400, Task 3 at 300 and Task 4 at 150. Tasks 2 to 4 are still blank, so the report is not final. Add the total word count in Student Details at the end.

**Is Task 1 Week 1?**

Task 1 covers **Weeks 1 and 2**. Task 2 is Weeks 3 and 4, Task 3 is Week 5, and Task 4 is Week 6. I can't see your teaching calendar, so I don't know which week it is now. Check your commit history with `git log --format="%h %ad %s" --date=short`. If your Task 1 commits will only be dated after Week 2, you lose the weekly-timing part of the 3 commit marks, which is a small part of Task 1's 12 compliance marks. Don't backdate commits. You can raise it with Dr Stamou.

**Am I submitting correctly?**

Not yet. Here is where you stand:

- **Done:**
  - Task 1 notebook and Task 1 text, both in draft.
  - SID and pool reference.
- **Still to do before submission:**
  - Re-run the notebook, then take the EP1 screenshot.
  - Fill the highlighted items in the Word sheet.
  - Do Tasks 2 to 4, with their notebooks, JSON files and the Tableau workbook.
  - Create the private repo inside the module org, with commits in the required format.
  - Add the AI declaration details, the Prompt Log and the signed checklist screenshot.

**Is the notebook perfect, and what grade would I give it?**

It isn't perfect. I can't run Spark here, so the new cells (size check, gap checks, JSON, EP1) are syntax-checked but untested. Your original cells did run cleanly.

Here is my rough estimate for **Task 1 only**, which is 30% of the whole grade:

- **Judgement marks, out of 18:** about 12 to 13, which is the 60-69% band. The reasons are the leakage argument, the explained stage order, the rejected PCA, and the dataset limitations carried forward. Reaching 70% or more would need a stronger discussion of the actual licence terms and a tighter argument for which of the five V's matter most.
- **Compliance marks, out of 12:** this depends on things I can't see. The 1 GiB dataset-size rule (3 marks) is at risk. The commit weeks (3 marks) and the repo location and privacy (a cap or deduction) are unknown to me.

If everything holds, Task 1 should land around 22 to 26 out of 30. If the size rule and commit weeks both go against you, expect around 17 to 20. A tutor may mark differently, and I can't predict the whole assessment from Task 1 alone.

> File: [/mnt/user-data/outputs/notebooks/Task1.ipynb](https://claude.ai/api/organizations/afcc61c1-790c-471f-97f8-f2613e3a76b5/conversations/3618d6dd-e0ac-45d3-9629-5b20892a234f/wiggle/download-file?path=%2Fmnt%2Fuser-data%2Foutputs%2Fnotebooks%2FTask1.ipynb)

> File: [/mnt/user-data/outputs/7006SCN2627SEPNOV_Report_AnswerSheet_Classification_Task1_filled.docx](https://claude.ai/api/organizations/afcc61c1-790c-471f-97f8-f2613e3a76b5/conversations/3618d6dd-e0ac-45d3-9629-5b20892a234f/wiggle/download-file?path=%2Fmnt%2Fuser-data%2Foutputs%2F7006SCN2627SEPNOV_Report_AnswerSheet_Classification_Task1_filled.docx)

## User:

> 10/10/2026 15:05:17

i am focus ed on week1 na why ui saying to do 2 and 3 takss?

## Assistant:

> 10/10/2026 15:05:24

> Clarifying why the full task list was mentioned.
>
> - Clarifying why the full task list was mentioned.
> - **Done**

You're right, I mixed two different things. You asked "which all I need to submit", so I listed the final submission. That is not your Week 1 to-do list. For now, ignore Tasks 2, 3 and 4.

Task 1 runs across Weeks 1 and 2. Here is what's left for Week 1:

1. **Re-run the notebook** top to bottom, so the new SID, the size check and the gap checks all run.
2. **Check the outputs** of Fig. T1.6 (CSV size) and Fig. T1.7a/b (the gap checks), and tell me if anything looks odd. The report text assumes the gaps mostly belong to flex fare trips.
3. **Take the EP1 screenshot** from the last cell.
4. **Make sure the repo exists** inside `7006SCN2627SEPNOV`, is private, and is named `7006SCN_<Initials>_<SID>`.
5. **Make at least one commit now** in the `[Task1] verb object - result` format, so you have a Week 1 commit. For example: `[Task1] load six parquet files with explicit casts - 20,332,093 rows in 7.4s`.
6. **Email Dr Stamou** about the 1 GiB size question. The brief says dataset problems are best raised in Week 1.
7. **Fill in the MS Forms checklist** if you haven't. The brief wants it done by the end of Week 2.

In Week 2 you add two more commits for Task 1 and fill the commit hashes into the Word sheet. Tasks 2 to 4 start in their own weeks.

If you want, send me the new outputs once you've re-run and I'll check the Task 1 numbers and wording against them.

## User:

> 10/10/2026 15:07:44

for each week did they ask 3 commits?

## Assistant:

> 10/10/2026 15:07:48

> Figuring out the minimum commit requirements per task.
>
> - Figuring out the minimum commit requirements per task.
> - **Done**

No. The brief asks for 3 commits per task, not 3 per week.

| Task | Weeks | What's required |
|---|---|---|
| 1 | 1 and 2 | 3 commits in total, with at least 1 in Week 1 and at least 1 in Week 2 |
| 2 | 3 and 4 | 3 commits in total, with at least 1 in Week 3 and at least 1 in Week 4 |
| 3 | 5 | 3 commits, all in Week 5 |
| 4 | 6 | 3 commits, all in Week 6 |

That makes 12 commits overall.

For Task 1, you could do 1 commit in Week 1 and 2 in Week 2, or 2 in Week 1 and 1 in Week 2. Either meets the rule. Just don't leave all 3 for Week 2, because then Week 1 has none.

Every commit has to follow the format `[TaskN] verb object - reason or measured result`, and at least one commit per task must include a measured value (for example a row count or a time). Each commit should also be a real change, not an empty or repeated one.

## User:

> 10/10/2026 15:11:51

now how much would u grade?

## Assistant:

> 10/10/2026 15:11:59

> Scoring a task against the grading rubric.
>
> - Scoring a task against the grading rubric.
> - **Done**

Here is my estimate for Task 1 only, which is 30% of the whole grade. I'd put it at about **20 to 23 out of 30, roughly 67 to 77%**, with a full range of 17 to 26. A tutor may mark differently, and I can't predict the whole assessment from Task 1 alone.

**Academic Judgement (18 marks): about 12 to 13**

This is the 60-69% band. The strengths are:
- The leakage argument, with measured numbers (cash tip 0.00 against card 4.30).
- The stage order is explained.
- PCA is considered and rejected.
- The dataset's limits are named, including that flex fare trips are excluded.

To reach 70% or more, you'd need a sharper argument for why Volume and Veracity dominate. You'd also need to engage with the actual licence terms, not just "no licence stated".

**Compliance and Evidence (12 marks): about 8 to 10**

This depends on things I can't see:
- **Dataset size (3 marks):** your Parquet files are 0.32 GiB, under the 1 GiB rule. The CSV check and the email to Dr Stamou are your protection.
- **Commits (3 marks):** you need 3 properly formatted commits, one with a measured value, with at least one in Week 1 and one in Week 2.
- **Repo (1 mark and the caps):** it must be inside the module org, and private.
- **Pipeline and cluster config (3 marks):** this should be fine.
- **Pool reference (2 marks):** it has to match the register, and "No. 33" is my best guess at what that means.

**What would pull the mark down if skipped**

- The EP1 screenshot is missing from the Word sheet (the evidence pack is worth 4 marks).
- The commit hash lines are left blank. The sheet says each sub-section must cite its hash.
- The Fig. T1.7 check shows the gaps are not mostly flex fare trips. Then the Veracity and Imputation wording would be wrong, and I'd need to fix it.

If you re-run the notebook and send me the outputs, I can tighten the estimate.

## User:

> 10/10/2026 15:28:18

in doc isee u wrote fitgures t1 liek the that whereare they

## Assistant:

> 10/10/2026 15:28:25

> Clarifying how figure labels map to notebook outputs.
>
> - Clarifying how figure labels map to notebook outputs.
> - **Done**

The Fig. T1.x labels point to outputs inside your notebook. They are not images in the Word file. The only picture in the Word sheet is the EP1 evidence pack, which you paste in yourself.

The sheet's own rule says every claim must cite "a numbered figure or table from your own notebook". So the marker reads your text, then opens `Task1.ipynb` on GitHub and finds that label. I added a table of labels right under the notebook title, and a bold label above each output cell, so each one is easy to find.

| Label | Where it is in the notebook | What it shows |
|---|---|---|
| Fig. T1.1 | Section 6, first output | Trips by payment code |
| Fig. T1.2 | Section 6, "Why tip_amount and total_amount must NOT..." | Cash vs card tips |
| Fig. T1.3 | Section 6, same cell as T1.1 | Trips per hour and per day |
| Fig. T1.4 | Section 6 (missing values) and Section 7 (cleaning funnel) | Missing values and rows removed |
| Fig. T1.5 | Section 7, class balance | Cash share of kept trips |
| Fig. T1.6 | Section 5, new size-check cell | Parquet, CSV and logical size |
| Fig. T1.7 | Section 6 (gaps by payment code) and Section 7 (gaps left in kept data) | Where the missing values sit |
| Fig. EP1 | Last cell | The evidence pack |

These labels only appear in your notebook once you re-run it and commit it. The outputs have to be saved in the `.ipynb` file on GitHub, so run all cells first, then save, then commit. If the marker can't see the outputs, the citations point at nothing.

If you'd rather show them in the Word file too, you can screenshot any of these outputs and paste them under the related section. The sheet doesn't require it, and it would add to your word count only if you add captions.

## User:

> 10/10/2026 15:29:55

where are figures?

## Assistant:

> 10/10/2026 15:30:05

> Locating where the requested figures actually originate.
>
> - Locating where the requested figures actually originate.
> - Check which notebook cells currently hold saved outputs
> - **Done**

The figures are the outputs of cells in your notebook. They are not pictures in the Word file. In the Word sheet, only the EP1 box holds an image, and it's still empty because you paste your own screenshot there.

The labels are in the `Task1.ipynb` I gave you, but the outputs are not all there yet:

| Figure | Output in the notebook file now? |
|---|---|
| T1.1, T1.2, T1.3, T1.4, T1.5 | Yes. They are the outputs from your own run, kept as they were. |
| T1.6 (size check) | No, the new cell is empty until you run it. |
| T1.7a and T1.7b (gap checks) | No, the new cells are empty until you run them. |
| EP1 (last cell) | No, I cleared it because it needs your SID and the CSV size line. |

Two reasons the outputs are missing for those cells: they are new, and I edited the SID and EP1 cells, which cleared their old outputs.

To get everything in place:
1. Open `Task1.ipynb` and click Run All. If your Spark session is gone, this also reloads the data.
2. Save the notebook so the outputs are stored in the file.
3. Commit it and push. The marker reads the outputs from GitHub.

Once it has run, each label sits directly above its output, so you can scroll to "Fig. T1.2" and see the table. If you also want the figures inside the Word file, take a screenshot of each output and paste it under the matching section. The sheet doesn't require that, though.

## User:

> 10/10/2026 15:40:37

![1791626896922_image.png](data:image/webp;base64,UklGRmCvAABXRUJQVlA4IFSvAACwNwOdASogBkoCPm02l0kkIyIhIrPJWIANiWdu/lm/wHXu17/S/1D8WPBYtDP2nlAW5eoF8Vf6j+m7CeAD+Gfx//n/0H+6eAv/df0j+s+sD4P7AH8t/rH45frd7vfPG9P/4fqO/kX+A8tz/g/yX+A9Zf5n/j//T/mP8x8EP5d/Vf+r/mP9B//++I9C/+AesNZvNfyH7PfoJgcOC92TeDsZ3IHmZ9IgYR/D/7x9uHuN8g3aFeaU/uv7B6DPy3/b/8z/Ee4D+b/1z9UO0d727186nZ35Anq/NP/zU/xMfIcwf5vwc+hP/l+oL/tvTn6K/MX5w3/k9Vv9z9Kr0cv+1//f+v8D3+B/7P///63wHf0T/Vf//2t/Vc/0vpUegB///bG/gH//60/qv/a/yg9//zL9Z/xX9s/xv/G/wnpf46faH7X/jf+z/h/Ze/0P8R4avQv3v/i/3L/P+wX8h+4v6j+3f5j3rfwn+6/xX5Vehf5f+wf7b+9/lF8gv5T/Qf9X/aP8l+znxT/Q/8f++/5n9afGk0L/Mf8j/C/57/0fAF60fSP9x/fP9J/8/8v6GP9j/d/8t7E/oP9n/2f+B/zP7OfYD/J/6j/sf7//kP2f+WP8p/3f8x5MP2r/P/9b/Q/lx9gP8x/sv/L/xP+l/bj6Vf57/xf5X/SfuJ7X/0D/I/+D/L/7T/6f8T/////9Bv5n/Y/+h/hP89+f///+9j///9X4M/uz///+t8MP7bf/f/rWK+nLcfnUy3rLfZ8y13MIJ134oFriEFxhYRTVtHHT35ghRspIxpVteH5GhlurUI7GMtf6A/2A1r0B/sBrXoD/YDWvQH+wGtegP9gNa9Af7Aa16A/2A1r0B/sBrXoD/YDWvQH+wGtegP9gNVBNPbRH7OgE1lRDtRot+ohZCd7QJdNNjOcaobuO5dsE3MlpRJ+uGP6C7mvIK6A7MTVGYZRHb3Es4BEZNucSlycW2eR6qdzNolLk4ts8j1U7mbRKXJxbZ5Hqp3M2iUuTi2zyPVTuZtEpcoV/UMXrE4AllA0QlTk2uIiuCtgDfBprgYoCk79rXCErkLyGV9hHt4jHpV9HCDNfellwgGElBbFJU7SypygkoTaqD9BlLk4ts8j1U7mbRKXJxbZ5Hqp3M2iUuTi2zyPVTuZtEpcnFtnkeqnczaJS5RrG9Fp9SvSH8VUL8GgjcinUF2g+XmnHUIj89lteS1aJe1S4+1HqlOu0QC9sDlGLIqBpz+NFpyprKcpCWDMMJqz9olxjRaNVv+UIAkv1R6mWj5cMwyg8KD7S7LpX0ke4fTe3xLsulfTfJeDKB4oh/7EujUr32AaWTlOsnUtxt+31dQ8jnRUMQDKhCm5PJvOyag+hDG+ioYgGVCFNyeTedk1B9CGN9FQxAMqEKbk8m87JqDq9Dm0cRitwVy41a1ixceptXL847j2ENbQRSVtlte9jfEGRIOGLb66AsYygC/BITgPah0UgzfmQAZpMf6q6qckIMLCXx7n+tAE2E/K5EADDI5k0gTVGuuRQEzX73bl1tYS/PWdmgIvFIVfaCgAmoBgxm5R7yce/jOd7IfQf7N3SAPsA18KEWPa8wxHxHDyXSBdxcZP6I0+3u+N+78IiyucKmKYWPouusITc6vyoNmrV/605/L5h1hgXJKvQ++7GDqhGA9acW5QmexyaTLcx/Oyag+hDG+ioYgGVCFNyeTedk1B9CGN9FQxAMqEKbk8m87JqD6EMb6KhiAZUIU3BK8MapxCD92O0FwdT5hz/AIzgSqGAgHdEVyYzoIt0AUVonlnHsEQl+CHHZGHNNb+IUu0WeL6gCl1oF8DLjfP43e1zFCS9D8fIAqe5//ruf9wX3d8+HluqXtVCQPFdxlDBpIroyAdiFiCcV2GsGOYHqUrvi3pl2VssYaTP5DrzXgSAAkrlJ0bicwNHwb1vYCGYw5xp8DMzJ4pPKB2T1iTCEiCbvtq+WwlocW/9NC1T2vyrVodfYFgiJgIQq2TfjuT93FBRKe/aSyR5cTclS4b9pLJHlxNyVLhv2kskeXE3JUuG/aSyR/hrSG/mkfGu5heIRhQy63TjmhrwqFZ1GIGiwsvg/rrdoYEQNISa+DFHNncq1Ds+YeBDvRuufejsvexR1Il6hXHBnuB4SAmfg901kpZt5p241uyFPHE0Irf75wDgMC7JNt+4lIfCEN9x2vcI4sBy4RkAfQdCUVqeQUL0NdzVn0PsBmPkzzHz/RrCztXCQrL3/azqfd5n1ruNPr3sehXvY9Cvex6Fe9j0K97HoV72PQr3sehXvY9Cvex6Fe9j0K97HoV72PQr3segscmTK2YaT3VsghBsaKKR3+jNNCO4BDP9DFL8uwHV5KVD/qqoJTE97HoV7dfQr3sehXvY9Cvex6Fe9j0K97HoV72PQr3sehXvY9Cvex6Fe9j0K97HoV72PQr3sehXvY9Cvex6Fe9j0K97HoV72N193Q8VxCJqYshsidwoYdWs5mjLgwUWKWqnczaJS5OLbPI9VO5m0SlycW2eR6qdzNolLk4ts8j1U7mbRKXJxbZ5Hqp3M2iUuTi2v51MUbXCUUlWDRTz2cH2A64zYBS1U7mbRKXJxbZ5Hqp3M2iUuTi2zyPVTuZtEpcnFtnkeqnczaJS5OLbPI9VO5m0SlycW1/UWnhgfoAM+zqPnS/lc8Glkb7qI+2UfwNPZnMU2fLixMQhVVTvFrVYHgyfR/gsXUF2DYPo90MqVy3ETp9+FY4TA484vd++qSZUE66JgEpwbre8MzkCjBTfvM080/oWuhK19wbmXkN54eIXd8iT2yjn/KeCSPVTuZtEpcnFtnkeqnczaJS5OLbPI9VO5m0SlycW2eR6qdzNolLk1PakK54CTL0cNnEgToJTjI6y4GTucDIv6ZCEuTS6cTZsFLk001U7mbRKXJxbZ5Hqp3M2iUuTi2zyPVTuZtEpcnFtnkeqnczaJS5OLbPJO9FWYDO0EYLq2HY8HEH4iK5OLbPI9VO5m0SlycW2eR6qdzNolLk4ts8j1U7mbRKXJxbZ5Hqp3M2iUuTi2zyPVTuZt/oyDm9uEDwgu3UUgQzGUD70mE8vzFHIae/dtjzqGUqkERzXpS8AqNo76k2jvqTaO+pNo76k2jvqTaO+pNo76k2jvqTaO+pNo76k2jvqTaO+pNo76k2jvqTaO+pNmL7aaKNZBFEGCUXJfxKzD4jA396RRhfDkFxiP09sDfN8lwb330zNrav4lSFvvpb/cjEYy/QysRTa2UcQIOtJvcz3sSaVny046eLxTgDWBn5SBlyxtCS1IY5MzmB3I+tWzaxbvXUlGcFS0pbF0aNRfasx++WdJwRkhyUEj5RJ+3x1xfkfTCYiZWbF8qXwli1jdWDuXXW0ZHUomdchh6AXoUyWL5/19wfvaeTSUeEIULYAVHnBaxs25mrrngbXB4rsdGLL05mXYAxFyfDgEpF2OjFl6czLsAYi5PhwCUi7HRiy9OZl2AMRcnkcKey/6ItBUlCyGLeNjPLZ0O8129P5YxT/o28WdtkMw5mbwywkXO2F9Xf8OPqpyLwqX0VBCiZoCqCkwtq30QeSZ5KckBbRv2O6eRcDHDCuaEX+gLStJ7OhMoLN2Qc/+b5dpThEOH4S93NniFeWeuyZ4ZSfrERYBwwrZijuQ0JnmYdA3avL8U96PTh6+DYelpSnx3dc0arUqPOiNvQoZa+SA2il7Yaeym2f9CrVUjCI8jyIPIQHjtLyJxo1rWMQVSlVbiRawD3rkpUvc36MeJrqDlE+cASAFvjO1NoTjY8DaV2xMhjo3IVMuHr6qSqSEOKDF/H490l7lCp1StlrVSBVBnFk/jDUHSbMXsKvkoysvfl31lvO7BlF8MD16hy3Jap+0K8Dn1v3qcB6epzI7uQ/bY/D1999cKu5Msz/usZCud5Ufl2TzFlXeJ0UM3VK2eR6qdzNolLk4ts8j1U7mbRrdxwEV0Oqb7C8wu/UnV5ml+m2dyrU8teaBCk2R9hAj8XvlLui2SVB5xkq44S92D4KBCwWHd5MXj1a5SJq9ydmdO4nlpKwAXGwC8LxNweqCWApwaOPO0CQ6TSR56LGMjlrzLRMhfE1ibvwLqELgAIA2mJbOVlpULwz6ZP5alAPj/HXeNrvUKt2fAwdDDrsLb7tflBz3090bYY7LHKka8WcHzjYj6OOK7TLMkxd366M/UIP0Su1RD05y0ScSFtLd8aTUIqcKiCyrhb6K1b8gn3vIO05bQAlwXJCnLalAWelfm53MVehUf2ddblXPgZ2JsTQYsKs5Q0UYMwQrdgIPcmTh8xD4CGFkww1emxJJvxjpg/N7q5339hmDqOfxP0OVwm9cDKnYEIeffX4InK7dwTKiOxOj4U+uxMImOE8ljMQJcnFtnkeqnczaJS5OLbPI9VO5m0a3VpYALR0ffcw8FGcIM19WVJO1Y0ZfJWZmq6wzfao/+ujCo9+KSHC2ujLfm0RHWyRzaDgTuwORFkQ2weTs0dfHGX6teLc/5cTLK3gYf6tHjsCmcJJvKFHKzkqagpCmcr2j02goSn0INsl5DEwew3Jpxz3Fe/7L6VX4bdthq4IkleAj/zNjTvGPPKpzefXGtlfScscdhxkAfSTmCQC+Y09A5y/Q3uoEmHBNn2W5sE3B2JCifTRC7h0GAzjlmrGpyH1LM+35raiBAIe9XykGaktkOHV+lMicMD3h/dzI2oAMoEBkuO2B3zklFBPFtnkeqnczaJS5OLbPI9VO5m0SlyicJQAvHq3ChroOdfjrxa9ohClGq5IkEGN/FLjRrUtEIEn2CZs+XGv2MpYGN7Amr9I1gArOS82a1CtUcRHJ9YpccYM3sH3uG1hcx7MF0wUdYs6V/Jf0cmsvOhUTt2dgkn4Pj7Cg7aRq89/9jATrueNiA4zkHLc8s6WWcu+JSyuZbRWfrM4zFNBUaQBZhsQB3Jb4F5unvMJLWdZM8XP5LrkL20RJwqt/hQ3IUCN7+cgoxIf8OcSu4cxgKmPnMXFyIncYPiMFl+1uK/wvylJrM9q4OcSlfeeWEJ8v4tHT2ZB0GUYOP+9veAzdUrZ5Hqp3M2iUuTi2zyPVTuZtEpcnFtnke+eTeJ2dNEVw5O9j92vk7+3pFckyr7cbhUUkPMpRdN9TkyS44Ni3EEc6sNvQZDaadGn75yZcgXKH0nSC3x/+pYW51/9UWn4w19IbY/Prv2D0K4hHEDR1EWS3ZUf6o9eBwXtIAdt9Yep97WGGXe3w8t81EDDGpBae6HGcuUZIYrwEuXLJs/3L4l28dCkT2219cWAllN0nCfdO32h/txL5dZGg80x0fEtlINr7dagyoW0DorMESlycW2eR6qdzNolLk4ts8j1U7mbRKXJxbZ5HvngxlK7GXdqV3vLwbBEDab5kTtABhoHPums3VbFhwRO2K/vCQ/8LHSUc7AGBLgyBWH/wYZKizAwgtSvACo2jnAG5cj1U7mbRKXJxbZ5Hqp3M2iUuTi2zyPVTuZtEpcnFuC6uRnzzRQjk82sI9LBwXQIL20fq2DNyTAuZ3JaHPGY5qxd5WMjuz+rWOOEGbL5DYjcYs0Ua97HoV72PQr3sehXvY9Cvex6Fe9j0K97HoV72PQr3sehXvY9Cvex6Fe9j0K97HoV72PQr3sehXvY9Cvex6Fe9j0K97HoV7zfNjvP3ET+Bl2qCL7p79MxgBS0gyZfQFBWhhZFyYDvaBMUgejoo/of8vCHP//EZQx4rEdGE7v4Ujgi5CX1vi7Pq2dXjxVTx+OxvCUn9HZ//+Ld6pvpmhSmK4c77KMnpNDp9Ih948ANA+gedVzStQ/olJGoj4ZQcqg3QGWlBk+iRDjQCGqn1sMjVyRgHiWq7H8VX8mqxRYHyxdlqguitO38XtFZdigHjjB5Z3Gi9ORzoqGIBlQhTcnk3nZNQfQhjfRUMQDKhCm5PJvOyag+hDG+ioYgGVCFNyeTedk0/7sg1i+YWKJf5zZdodTQ6uyrUVI2Wlri+XftD15tgLxLXjey3G0k4aUuIYdLw+X9OikaZ+ZrT/8XtsB5aBrWKS62G7K794i8vcrZ9mosvbgp33p83YAyRR6Y6TJTdO5zesLDrvhWtJyzPwDfOA3QyZ3IF1netDdwvJ16lUtfT725XPx2XXr/tAFnGMuHR5AjgPc6gyM1RlcKKSftJZI8uJuSpcN+0lkjy4m5Klw37SWSPLibkqXDftMZIDzs0Vjpr8OK+aHeQCJZfYVY5524BBH4s2Gcco4zxuQkjMbWeeraqLQATQ9R7ljGXwyh6g9BfTCv/SOAnzn6ngz+DNeOH50lmRPnrAzvsqBrZI3NT06i/+mCJS5OLbPI9VO5m0SlycW2eR6qdzNolLk4ts8j1U7mbRKXJxbZ5Hq2vNXXI0L9PCYeZo0a2GFjxg9Vor4sM+Y+jTVRt4tqt738BO+UoHRjlOhH6sgwxH2O5T7GvVx44nQXHD2pRnNki80BIFfr7NjnBSMvGTGJrvruDChNs0INAJrSsYx/9UrZ5Hqp3M2iUuTi2zyPVTuZtEpcnFtnkeqnczaJS5OLbPI9VO5m0S5zQguRtd7mClR61mCG41MRx2lSnL/wfYjOLGv7jAoT2Ceqb59Yq+3+hfVi4v6+2EEUVWX9ZsmBe8wuWW6IuFhgK5oepSMknl+jrMmry/H7gmf4bY8Qg8DZCVTi2zyPVTuZtEpcnFtnkeqnczaJS5OLbPI9VO5m0SlycW2eR6qdzNolNmP2X9NwYDQPXKg8OVs8syqKuBec5u/cKrS+bfYAA8z18Z8z816Y5NOV3LfGx3a+toJGbJhhyv0eZIqKd1EmsQ30DAQjvye2fw7boKs+nY+4eLoFyvwaOkIqO5q6iTzXgCnEo6oKaUcdajzi644wrfZxvf/fR9ET1QdcpcnFtnkeqnczaJS5OLbPI9VO5m0SlycW2eR6qdzNolLk4ts8j1U7mbfvS/ZLRY0zhJvdfE9EvvCVz8haW6vc6kBqbQQyhR5pAELBkR7F+RWTgeQ7a//+JkWb2f/X4b+EoREtLEAMCEKbk8m87JqD6EMb6KhiAZUIU3J5N52TUH0IY30VDEAyoQpuTybzsmoPoQxvoqGIBlQhTcnk3nZNQfQhjfRUMQDKhCjT1FzrSOgsTWlUtqK0m3P/swDzxXB64XSu6zAmiNCCYqQ7PMM6azyW5V4ptW3yf6ihcqlZv5VKzfyqVm/lUrN/KpWb+VSs38qlZv5VKzfyqVm/lUrN/KpWb+VSs38qlZv5VKzfyqVm/lUrN/KpWb+VSIJsbIFwvUhbp+xrjwtMdkeyqHnbfHJ+1ayInud8XnbZulHX5zGswowd8O6G4VvjVi9AaKVirQepL3SV9gCTFBH3/VrUMfH35JDTlYCthjLqIpn96yqT/6ez6Gwtl891rWQo7tdI8+XHVyHkguWGbqlbPI9VO5m0SlycW2eR6qdzNolLk4ts8j1U7mbRKXJxbZ5Hqp3M2jRsUU/UYnFiigs2h+cEi+9mvwl6rqrdmF6lhaMoyix3Wedmvo4kcYeJpWlaVpWfMw4+bWmTZNk2TZNk2TZNk2TZNk2TZNk2TZNk2TZNk2TZNk2TZNk2TZNk2TZNk2TZNk2TZNk2TZNk2TZNk2TZNk2TZNk2TZNk2TZNk2TZNk2TZNkidPhrApcBJkXpPOnt9Nxj6pc/6JCI4Y7lUASmg+PMOBda4YBpau6WtrTJZL9lq/HGxk+lncb86+LjgmgDXgXNu/h0d59M/R+zQnPTiknjh0KOeQ+I8Bycwow0w2695t9CiwtWYXIMyHwn6vqo1TrD+f48T5vxwqo8Ro+TPorCn6hnaCvZCNYB4hM2bJ2Ng+5B2as9tQmGM8XNNuGFG+U86usIf/cOqlgrrCy4ArQEE3ZbfiALRcVrfudyceGEevwAr2d6AnztH3tPY8/DOcPZr1nlBc2+0Fzb7QXNvtBc2+0Fzb7QXNvtBc2+0Fzb7QXNvtBc2+0EjQf0uJCAccGKw4Jhx2HYpQcBcvoRL1rm4+EyIF9MEvzBr/47jxe6ba0PvAed0RcPKTUR/oK1jj+yFO0fUF9KpgZmY+RoGqo3TiwSXL9y/wTwnzIciqLEMf/tBc2+0Fzb7QXNvtBc2+0Fzb7QXNvtBc2+0Fzb7QXNvtBc2+0Fzb7QXNvOWu8V6AJtYmGB0rohUUmnjieP//R05wToL3xQ810EyGyQ5sPtnQ0QyJVv1g+4/4fTnhlHQtHI4BonA20XPMUOS43/8I5H098xLjaKq7XWAbeEs8uNCcN9hTXc2BqlqkrpHvERwP74k5c/gnOatqLAvA78VX8Tuf/b1P6OdyHnEy6UytU81x9Fv+qnczaJS5OLbPI9VO5m0SlycW2eR6qdzNolLk4ts8j1U7mbRKXJxZ6DZfFX6wZxeymjUx/RTictE0+wzE2EzvO1SLBPXzY+7HsVVG19pgSRXhYXYfM8zzPJ7wvo1w640DHTwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LwvC8LvmZluDV3lGxTFp4J4r79h+8uUN2fkAmW35oFgzGS/SRdqs1sVhG3vofFdguEtnK9jolKvfwKPXYWPFTOULzkYUVRoQiEFiRqkPyCAylHcApEnCkWAnIzZG5bE1rZGbo+ThSLATkZsjctia1sjN0fJwpFgJyM2RuWxNa2Rm6Pk4UnpexvfLqdJX06CqAvCGOdkYicpynVQ4BPo2w3xQ2VSrcgYSW0AAP7/uJnHw8AJCD6lQKGMdqC7lvwa/Bux4htuL4NMHrOYaxHUhWqxWRDA6VBxQx56nIJDcnEAYPJ8zeCe7jHfIlhaOmhk1mJQpOC53KzCoYxedtEmusTnujGIhWnrIm3hsP89Jv4RCva1tIFz+B5bMmYsOQKXZarrBwwBj+SeuxTdy+aOUlXr+Xqv3b3B1D0OTlDlmaeKFcUz1gJF4Q6a6i3php9otGIIVMoHAlvLY6NHipweXi0Uua84V6tsgCEN6+b61jc9xpWC7TqEPy0GAg7qe+O1BqmWO3MwPt+ZJiPYUZaMaHREgDNIQJP29jpY++chbTld3bOZ5BinTWzhhtAztxfsYevlWiRjeim0aI+yjBvtbdnACg3i05EiO+CcfYilF6wojhp6DyaDWqlwDQyTLeMnXxqg2t8snLrY1PFvI+2EQ2IHyP7IiLeBdlf+LI2DB2lOUMjtZM04jR3IJZcCvni99DR7JqbKFwJxjnFCqv/REpBL7CP/vdFFn8uPTMfvBaNno2vvPp0w3y/x1oHVJm2Pvo/8vrKS4Dto95nM5PkupS8hI/fMMCF8ruPYXP/gh0R3iSjiiFGD5037az1ePahedUUaeOy4+Mr6c0BRkhTq3riwrao4fYB8tgb+E3qLFnC1dJea2EY1HR/0ccjfFI64GjXh39gJ/xqE2PIcWAKDmbpu6c+/D81FNTyi04v/qVAoYx26bunPvw/NRTU8otOL/6lQKGMdum7pz78PzUU1PKLTi/+pUChjHbpu6c+/D81FNTyi04v/qVAoYx26bunPvw/NRTU8otOL/6lQKGMdum7pz78PzUU1PKLTi/+pUChjHbpu6c+/D81FNTyi04v/qU8wOqtHBgwvoMvxjSaPT1wdY1qaXqOHM2Z+6VqpOWAyyYkpBMP6V/1uaP7/0j0lFzAMz55aliEDLeAizOLwZ6RKDU1SqobfsLBQ7K0uOaLPgv4h4QhpFGQJD9M5tav+0u47FqGzZ45c8orkrII68c05ZoWC0qzAdcxhvOZ0JOutbfsATDnnG+cC7Q61YbN2CO1DoPJ6/kABexq/ZWyeZtUJZXY5MutfMrm2l+kuw7VBdBioPDPKqpRLHPauNpDfk5pLPq1dpv0mYY+MfdGp7Ws51uyuiAxt1WTdEEoykX8VpOXroQRtbgXVN+G0tdkwwsjzFAeASr/AQ9k7OJDKraorltCQJsaraNfOFheYHG5bLqtRlb/sOoZ+3voo/mRLCfPJtP+vrONjL1jqNxxgKYbPt3ZzNd5xX1X4/s9nyF1feiahPWFWfU3ddr/svpkvPcFc38K8NvJjzZGb5Ypqn4tNIXmp1AOFjWMIZCU1CtV+5JYO5SXcoYIVDSbWRI2TMjGPQbYlckdVe+HqvXDTKeSIpcAg9T94YELBMlpyiXWjpM5GhRXQx+zkRn1YjZ7SZnreQLkTmfGNb7EF8eTx3W7gdnnL4WlwA2I/cPdIA5rdk0FQ6puOgrs2O5X1NyeDzZr5xUpxyx862V8rgvLszHVALugbVoD37bS3PSHwY2xZ7Krn2nAdXNhX08poya2PqxIth/hu0YCBaEfrK6QMik4BrA7Q6/X/NN8iutIZL6OoftVrAjrWR3l2ateAkIhmib4y94oOkzkoRhumxbzsIvyjztxvmISSMPyc6yE6nx0WghBZb1DbUQj6BKPmjbgP0Yp+OyZy/+ITXt6LUr3LcdLYUn8xuXH/VWOdGavZ1Khi9J88Wf98fi9ME6sQUBQhQvwENQEJB5TfqByLGwvscwvUd7glDLQ9gxcst3vl3Tj7pkdaTkiwIcMdNDAu+z1fpowYZxGl3xwALGD5RmoDw4j81fEGakYjSAbWMh2PZ98p2ZvCF1J9fob+2pL0ci4fNgMld+pAXytKJEGuSbsqSiL8qKf/ALyGDbq5kUNAwidLAk1CeiBFpWrehxQz8qItuu88qf1stsLpLQ5zJHxfbGObUF3dHN3V6HABySqLTvULN2xlNm6GTxSc6I6S0Y9noVhtCVBfFwzFBXEw0ObGBz9UxeyLRGIk8SpKujIiGJ8cY8TdfCCfk1nFmCPwIvGeruopcag9WkiCJuU1XuI0BQsvGA6CkdpjTcE2+V+06dXjQpmnNmJ2RmFCjFRGlAUllPmRinuj6Ulr4ww4UBILxsKYWmKH5xQyc6keJXXOuoHLun7MRaM+fxtCIWHHHZ2vMBnX3eqhPVkAW9F4wCXGwK1jzXk6dx9mBR5F1QYMY0c4rWAZ0pWtJ4dQcgTz+Xh0B1tR/au2vqfvb9W2pboKX9A30ymxqRO4jeRY1LtAh3kEY1EVsJk6Mdn9ygOlcu/YfJfZSAsO6N1qM8jxAUuxFEwF8b7FkCmqWoyUMHFEVefd3tYEqzJVSxbaOQerU9hwt2OsP97lYYDWWsGr7jti11R7F86t+lf2FnAHEeUUhuHl44dsyse6xEmejOtExGRqlp06k414dOWMnFt0zyiQXBAydV9oqLg2bTYkGkkgerRFAFOMDs5vfjrgah9pVut1z9YRTZCaIox5Mz+mLS56fozUaA41HSHbHPJx6PbrWxL1CQwzwjw6dWx7+JcmiyaNTLTKlNXEn19PQ6pBF9/+U8pmM+DUbAuSue/jYNnEPn1X7tasZf0cLF4HZy01MLT/pmqz1E1mUANt7cHGvU9vcpXjKMMfMmTVo9MOlSZm8wndksmHy+sFA5lv1AmfMofoxPqzQQf3W6XXJSoAyul1HgfPy1nVeclCXPRDzrWOkK9reU/kbqUG50SOv9HbzzuvwaVQ0O88/Lq1UMgZWOx4Z6HNY8weMV9rJE+f19ly0pAsqn1YgXVGqEoR3EHSvNC1E/9jI6rMC4fQf71Ic0Acg15onDaIpTifq3x5iHINqfGjUXiQG5eJGzVZ9W0AeZL6inlxn3KE97um8uc352hml/MS44EtCDWOVVWv8caXOyMefRTsNqBr94oZEZ1J6OB7Gnz+joBdIJ5efwvOu4qbhQQW34ju0wiCeiEOTHZM/CMkD/uMTuo/B2UGcniFQ1e0Bia+8FvgvidQYm0U6YsiCg/wDAFnF28oo8SkchVScJSfikhZnmAGBKKMlVwEhr4+/qSAaR+kcI6iVM1Hu6U4WJEcLjYIWG8tci2lsxM0RfA/vHGHhLCcnwnn8OEd2YM/FIqlX2ahWMDsyBoy7rOPCh5wPK/4CUnhZ4fbvD7JxbWbD/In3yZTjIOI09VM4PcxH5uwdNh6oUpeniUdlm7DbMwAqLnW1YR6I3qRAGgnCGDNo6a7Jee2OOKX7P4Dz6gn83gxN20EXLp7K8RjF/oNu1ybAaikfzyGP/NRaVeeC9XfDL+/gElMHHpUSscVEuFoDdg6BMD8KOAoEMoFw1MRXx1jcnCtbEzWmZZvUi4DbDB+1WWNXZnUd5Kam4PojVXyD6xsXOAdHG/78yHsXK8/t4glfhCIA0lzY9fvSubv64UU/eZvnV0IafR+4Ry7Io3AkB5gjiMfp1k3+0luySD4/UeQsAaErPevt9T1cDYSP5c3doODgh5Te0xIl/m1XedrQayKqVS01kx4yBPG082xbeaPk3GC2v0blajv7KV+gcI/HhFVOD2Q1ZVZTZ5zpipisrrktGTPjTS2ykjmEVZDusKxT1OtqmDXzg9seeZc/dfDxRBUhLyoe4CZKCaUtZs2bunhC0RSuC5CAxeo1VvF362AXpQgg0Zar7/QAtbGiU58CbgsEPKdyM7JoU5ldTrfAfc58CbgJCbmXkw++hiNtsK/BvpaDtmiYwmbEKh59owxQc9h42YdlDg2MQoyR4w0C092mFfyLyMAUUclVmMWN0+0TeKMUtQUgyhxVi6qguThXx0/7wZ33/SpBTzk13PNcuwYt+ZbUnMaa+ulef3hURCWZ/WxdnpxHber7IQVgAGk+kRacuXoKOTLiVFV78jrHCmJyrfSiaD8YjMi9q+j5LXYzb99x8jYSX0Dgds63aFgKolpkp/OSP1mu1Ld5zwhXnV5DxMjqBKFBVlvV48NxOL6F+T9x9ec04bMsaA5Nda3ZNhZoLCebsoL/KNkeGN216bneRBnWKHFLvvKFYDkvpS0Jxtqz2jmaSyWK0kML8GlUfEZUdzpsZ7OjRqHZtAS/mS4lYa+dd3psm+qmFvwcw9d2Cr+QpBV/IUgq/kKQVfyFIKv5CkFX8hSCr+QpBV/IUgq/kKQVfyFIKv5CkFX8avSf1/AQ2m7rE2+jecqUAdYsLXGiPIPVML8A73DJVQA0lU2QNBgmER5btskPKxh8M9JJM9Oc1RweIOTeF+e3ol859tj/ztWyqi8cbNTZL5Roigi/BoxnDlOf4kgGutghz52YTKSFAPlFtDXiPFwGQuY5n6IgIE91+DUgBM1MV0VtcUuSdh81+ax2HnsYWL5t5pSCHg0SrbMiQYypZ+JFdxcQDcw4aBNfL5hZiYulgn7FZxLOet8zxhM+teCqHcdmuztIGNFDYiO3mhjeGtgWw2LWqmQP97le4liNz2mcM85wN1aw8HHWHM14XW4bSJo+UWSZrCsj6lLh2gkha+nYYYQlWLyCOv6IXqgTnoJ7ECErL6GmKWHJEdA+WdZBVQKn6nwMcjvO4Ir0YsrX1J1uOsE+wKZygFwG95zFbDy66WukPxoRG7uJHDV2oTtBjLA2Rdr2EE/pKQ1ztbUUJ/qG8pe+woj3rmuETJGTe2PKI27DpTjOTjhJeQIr6nwlZdDHwyoiSTDOSDCED3M5zMxHH+fMLDh89z1JbTFGQSuXiyId80x2g+uEa16ci2idBmV4uZ8rBMdbdPltDZ+nbXXX/sHMuC393byzdpmMz4dhU6K7x+o8iQadvcKpVuVEpOJuX8Y00UCgHUyIxTM8nTnZ2aLzAWZI4NeR8kHy02HjLJ+Q0v7dWHjG1AbAdGTS3stYth38PpU/xGKxwpTFbq+MqYQkMz1Kv2wNtLHL0Dc+1YMxdBCa6ly+IQjVEuID19RmF+RK83r4Zwpii06Td42yWisNmzD928K4BrgS+F/RcrdAiqRe/dkKjZuejisdVyno8rhy081i0TAthbMyy60/jZ1y0IytLr2IXxMkQ1R6Ibc1S/tKsnEnirtVl3OJdN4XmB0OECzKqxsoownvyynoXgWg65LiODi4eR1XIFw9EPxj0O2Cz4sKc+78HdWERt4KqlgWQ2aIgexv2kcdpvz/mNDcpfZqpdWhW2rf9PDJoIOBYKJuJB0Tyy0bnl05vctfrcQXn2uJRZhugERdvjILES8yAFOw5SyKXctVzWgmbT8vKmrlZhhJqNIqv4Pr0s0RJH4xgjufFKwqnIvC4WJ1U77zt+/rIxqvJwFzOiXTIw3oQ6Z54nPxrxeLqtlvv/ZsGX//23UPeyh+FR5qWfxjdADOpbbRZ2bmEC8091RMFtJSm8piwq/0fU1xWh4z6WxaPhFvcYPM5Tw9MADW2VVowaTvxquCJWs6uaBVuQgCHohVOmmKY8Efm+WmoNL/3eqGQHllQwVlykLY9+bEni6pNxLasp9VxbPD5TVm26zAoQ2XM5XTftrEf+WyhT1euKyXH614T8QJAAD11Uev6JzBTcwpG1KmI0SMHkrmbPyJqTRu34OrOWPiZRrXqCMrLJYaT9sOYQoOCewnsgWpUtUJ/k78WFOtpoYHxsC8e89Sn/t7sh5tOQIgIvzphUXjRAWJv9vtSmYKCh1+P3M21/eDFIMt+rLSwMjqijicc7C6P34sKddOYszKXuZxhybHpGLHWEHRrYUFu2CMYV3WQinfAWzPGNvJTwZS6rjaCznVD3nsSg6vJNhrEk5qiHzwgOeQ/zK/LVN0s9lAzC4SUJGos6Zd3ibjVhiWfIyR0pHVp8N+WW8HUVe/gybnNx70NvURX2aqtS50epcQksX1lFSZ2eZrpI/GNrJLCnHrS0yyqOZOnX3bsEvQgZmavW2nqd0jgH00UrNYgpAgezAvotwiTztdlqiung7r34hrVSR+MbWPQjDZ5VRvhf0a9ZHa6j9FlBCIXsBsYNKvtujiu1tx2Xe5E7J6fPlPHVJ4zaUrbM3gSNg3aSu1h3ro97MV44F7mvycB8v22oXbkqiTP8zWGWvFsuiYDocSW/Lxat9a8njWD/PY4DysBmtxJVBWE0ovN7omEEnUw2e7GKsnoxjLo/8likqnz/1N0M3Az1Zffy/z9MXhJZHSWIEDNPxW0tBFrHb1DXoQWWSNmZphINbNHUd84L7drpKbQloemKe0KdhTO398H/CJ10h8dVWhF2nPTwzk8EN+DJ9DrPAgbJHsevXQBIk9/4V2YQG5S2uWQnS6xz1X/yiBQ06c37qhsEszQnpd/QeAHz4r0oNof/jW3ZEL1/vI1kxZkB6Wmc5nAYVcZluVX+XHtIOF7NWshxYArqR2vBNu1QnC04cvVSK0Dj/BZZy+Wedt+d9JjoxxD3UO/BLyV2JYT2U2T79sb9HE+pnVY8KeY/jftdkhkdYaEbII0awGEuS6lsPw8u51/nfoJDhGVeI2kVKN1IToQlEArhyLSot0LMnHU96LLBQPnTpb+dJFi2Nj2ODHDFXcg6QDi58fs0D6cyf8ad2OtxASiPh+54F3U0tN6Om5pmVyvC530R2fHySPCKOMEH0wDUeprFKTPagphrq7Y7XaWBJGFNGwkPMzQNFNvgL4T3j51xldOtork+9EciC8YtMseVIwYDcUUu8dEmQ86jxclPnCEdufkMm786nju3pazJYFu+Mv1jDIRo82VB2MkOzyon0caVJo7zYvK88kTGIag6MI/Z8SLAIIV2BjLzlnIEtVMCn/AoFgOdW2DNNgIi1xsfBhs7Zog2ds0QbO2aINnbNEGztmiDZ2zRBs7Zog2ds0QbO2aINnbNEGztmiDZ2zCWXiVCHVLFiDBbgYYrkkgWTruqAbbMXLwQYghTkoKbmoH/pRHDLry2pO9g3t0M++Tne69wD4R2J8lWmgmb3lTrQUGWGUJvsK5IqU7somRxTM8O2SRwxHPS/Fuo17TJ9LtGxph1UuLPLjuCjKK/vUqKPM2VAzgnN80rxYFcAT5P9tdZg1FY8Fkr3rbTTkiABWTXjzS7Iws0uJ2BeO6XZqIRlh4qTJBO6PbeYP6vakNNe7MOS9brzb2Py1nx/U1XOOt2gP3m0fDOTuvheNFxnFIWC+xUqc80cEOYpk4wC4UuTWYZtj4a4Mf4tlrBiHIw3wZJ9flx+mdg5IElmPGLp0wylznYy1vjhBhjra46Ksj/2e/qCQIHJNr/mQM1Wmg6142y6fJzrrKXYz+d/C641v+Hm0W0bwOuuOLbmtke/ozExcOTBhf/inRINCJ0nKD6Yveb8uHVvMs2m8TWpPk9bCnrO2UwWypIcbjYXdxF9yqfCr0t5WTdpELsTlOMNFHxAKP738BUAzqnRek+4u4zzl+tXNGBwWpJsErzEBa3CNX7xlj3P6J0w9xJfysFWZM2lE/Uiw5oBVSt0ZOwIj7PY6542QYMZzqKTIuSZ8p8/njv9kkTjIa6CQSMmA39/qt7cQn9aOqUlPhUEMMyqt0IAKp5OjOMAM3JkbEjcLNwnN3Ma7ynJqwoGHf/YgSoI8TV9j1/JXW+/7Y8d9odZGBnf+fGIOlg32ghxxqHZhWBwUw7mssCGApw7WPP8lW7bWRriQAshHtkTkNmD7zmocoBwD8qYpCzwtIcL3eIdV71M7WR9aCStzjxSvDzy6xSdFRnhSlcYWNAhPKz/yZHQpHFqkvYOHs7P8MzVrYT67puWFRmLF374A3Q1KB/jHzivYrK+txURJXXxGvdAtO5mMum8cdYKbsn9EitoZGuGzqi98rsdSfvP53qDXZMESX8eNzAA2OsVLetfB6zwOl2+desCzZ62gUzxkK2uWychlZbv9Fs1o3tqfTFMwDa74Xyimn+HyGL2VAWKX030FFK9HZjELBuVr+pAc2Wez2Np98GhiXcyBIWdWI8e+oHyu/725thUfIvw4UtAl59HZray1GfVul7sqn1tGLLqv/KLu/h6xFVWQybVYziD6nH6O8rBRU1jnICwqZJKOeG0m/pucyRfbgpOEmxNoYc2C/f7z9+eJ27PWLLR0fkOEwjig73rlSkQeI+NlnG1ouYAgVdJp4hC6vzwCu9WgGoUJMe/OH1Fj/zbSRmWUZKE+liNwtoAEE1x6xziaXD30iu3qa5oeCZXh9TU6JZr6L6aEh7NXrzF03tZWdo0wHgjZJ0IDN4PJZLtw/MumCtGYJqenwooFBTQj+4GZq+OZjunCmXwJteKZqtC49+RvZPW9GHX8Y0IkAvFAulFunpgZBVEfyFMlhlcBW7K0apU7lTX6P/RwYb15x89ZzRk6kD5jG2SmnzZBnrQcu5wg2VUOhAYx6Q1Wrw+Il9719S9yCbhFxfiLz6LeDcGp+J+lYUW6POU/wzZIACWnasP9kho7vThQxlJXWh46jBm5q/iaWYJxHKVpXI580bMn/WPxYHTVehEnDYi4y1jwgcJUk0uc+fiNmS3BT3aTUWAM7vplZvWV0sO3wrWFaeQ2TNKa0j6t5DdJF/lorxtkbAwQfSnPDCUAqHyhkAuj85D+xHqZaBF0gnLnNo2Ww3lG6Eblq64yt1hmbYKRPJ+6LPjRc2aU0Gy9QsKHB7ZI2kOsPO9jgowCeWo5YPoKXMldVihbHlFvD+bXvKkVRtDM3kWsN3YF6JTXUfozBnUoFm4Pyeq5mfjQ47U0M56ou9SXovfnTrvocfUI6io1DfqlmlhhX2C+WkGKAzKRnITFmlHr4b7lNOExWCS6mf156SwDKzRo0yNZDIThsPQpaTcTYIZvzPiYBKH//NHWx0pJBTB2FwpYQbVVettmDBbGPvf31DCB1aLnV1ga6cBWUGPnx64Z6opHXPqXCAfkmWWfJEWjyhJMX4z2rhxCKqERrKJaciUbfxH8Escm3DEmCIo/rhd85GZfYHSVNB+LWIqejaDSRhQZbhJviViev83K9BbxGUx8J54KigjkeessYHwzcNi0W/+riQvw26b/+Z8gxvW+FVivG2hwqIj+yNLWk5hySwKQfuqNFf+E+wSpCfnfi2MxknsddX+bqZ+T2gjGpYhzPukm8yOwRSCsMrqKxJB7kf5tpn3a71kkp3TuIwVmN1Xeu/HfTI2zysnpuWsSoxuP1LdbbhLjHuvUa5PkrMKYnM+2fghnczyvdw6DFHyT64gU+hdWsZiCS7hhwrBaj7tRXUQqIn4BGhQ/sVA19s3jcNwg9N6+mNc+XIgnp8nrFUPxR0vZQfNWxGIwsXduyoUZmoh/EdoI80wZusU40qNQgRSQx9sQUuO9aK1lsKrYGrrfjSGQCUzwZ9E9fekeDNl43qYOhw9z6sGL/Pf9kXeqtecCxDSXRIEsrvZ3WD0Y1lfwbavqMIphalNhbZaXBkxt9nV6L+KO9yC6mIRuyOVyiSZytarqMHkkoPS5vt5H3Vb57P7G4kXmaagKSiHMVkjsV9ek5/vrXbQxJ4zuwA6qMUTCUpSoqWN/AbOn+A2dP8Bs6f4DZ0/wGzp/gNnT/AbOn+A2dP8Bs6f4DZ0/wGzp/gNnT/AbOn+A2dP8Bs6f4DZ0/wGzp/gNnT/AbOn+A2dP8Bs6f4DZ0/wGzp/gNnT/AeuY5rllpf+CE7C9qCsnN8IsC0T5nKVuDJvva9jluso3oPLiMfmINm4YxaxzEuSRkFgKH8pHMx4ApjXhl+jAc3VpeoAD1ek8PbKw2U9BU3I//WKc990i9H4+Aph4s7tF2zgSlXNdZR7Bvn7jKcGcRB3U3RcA/CX/mMi2+3JCIbZ9oRs9VoQ/bGeRwTyaQfhabpojp67M2yGYet34/hXIr83VH0GlIoDBnv2MLEG8H1RN3C39znBJ5DeduE2TSDxT+9H9Ey1XPUfA+YeLembQfJf9nmMmPJmXL3yHwJbTGL61Mr54cFzmOZaMJs8VxXqQvzsRL4+G+2aVyhjAhfcFFCGYOHiuqHHajlgTMl9gksxtU9v0aJU99eT21yei8yb/sfPKRCt6nE5IpypM2E5+LNe9FFX3JffYJ/TpqS5upLmiNqwTxpLKryOA/bICd3r07EvbnSZh4uAhO3YF203W3DgcGqGBja0ZDTq9hymH8X83YUCbr6u/CKPfycvyb2iZVz1pgZ2E+/PA0bL9VqO6frlj8QsZG1xWNvZkV5SoL+qJx70EGdvO0FdzhC+fkl6+UZZp7nniibJhmim5A1KPn7lYyxRxIs1BVXiQhGsImshEIccA2yDjFNal3jTDYqvoSwFTxVQYYRmoaSr1dgJElwD02yOgqEf1tvK15m5qA4zGxA1aAEvRDoiYixklBeUTM3g1aDPGEK9p3cBc3lqOFVxJSEt127Lr5dEdgf7+iGknjf7ExgYng2u2+v1KaLVScTaMhYMlKWlHnuVyIA2kpQskGIh/2zLh+7eN4LNbCeMvMMCQSNWpCotvogTs6VzPwBiXxUVLtxokS8z+srlOXPRHjIuNvuXdTvjbeO7E10VGg69gw09CqFmSwnekn1df/3gKYty//u1WbTdUN5jk5byDXZK4sk/oudRt9+OtXFfyZXMeTlozg3jnCCWPTdYLzkGisJEBUlySjVaLbWLQriMkhZlIkbLNJIP1Fogr6A5XnzYnZE56so4/zbRNfGMhK8qkVhICiNl+muP5IXOpPMID6KiNebxl9SFdNzONW3Y7FhVoLaPm1lh2ts3GGZK1UflwQjz+8li5buBpJUojulx1ti/QixSXLEG1j+Q0UR1vzJXnYmcHOg7g1QwY/AsqRLNX0q6NH/Ik3q5GUUQ2OoU6mCkcrOc95lLW7YDxvmVgmk1seju4jHvEpUMxwD8hshksBrVmTZzi944b33E0tx3ENJTNvpm6l7RiOcEVM6bbgMnG48piKDQliYo2dVxbNZ0MQF/+F7NH8yFWSAn0jxNb8t311RZHmVZGCCnmkmtQgaADXm8wRCtqo/lSJ4P080xSBzao4AAwJVcbYkszPeNYmLZiM6ZraAc9NgPhajo52874T/LzHWetn8hD31FYvuH6b2+nKt6Q2eR3mrN9gTuIKDlVwvdVxpYAjQdmayyGJX+FH4BT76d3VfYDbBEvRiOppzBFfU//BX44V/vOROfVNeVMjkTHURdglNczK98zHSPcUX+MQPAshfdaF70m0vbpYFj6prQDDXBET3ikO3iXq7nmPtOVyzXX8+4zaaMGs1hY76oPjlWN24cIb/HNjFKtgxzJwdZWTbN0h7KjCTwJNCzJsC+B4x9bByqJbRTbawrLLKmYLpYK8lmS8LNR1P+YIdAyH699Ug5h1W1r6qllLLb9x8ztR8eBzrSeLHQISFVigAqLC2lA9hl3zNzfu+XNNqm6YDxPQrD7Vm/TUYBTKDSVjKd03EaBF3WC3LWRfNrvAYCrYFTaeWZnPQf81OfVIL9FF3Z1TuhrI1SfJujIS0UJtKImZrFpW+OUjh9y4Grto4qoy8pySjYiCK45Q97zf3pta88hegeqsPk/anWJHneEQZw/gAslhCuZpUoayIErnOXfoFNGN52RiNZrK21LHgeWkmm1njD4y7jSkfh0FRfXzPm/Usoa63sj99pteLYDryUvx9JGDBH9apf5/qDo2F6f6w+7HqCgBiKTsITH4HZYfjLgaDypNpmIw0b3eZnWbG2e9MK/VZOVtSVYtUliVtD86b9PqySTATOAmvsktlqRtvlen22g9uZ4Ghs/cp+ueaWXvwhr3cfeAWvNp9D8wpj5ieunJfpkXQfocVLRF9Z+3ppiCd3Zr+vyi57Rd77bUVcaRxv81IDppQ7mhHFNt0yH1ix0tb9Hf86slqyc+VFtDO/4YZh7UVvIxaHjvO0OKg2MelVmfdrDTr+ly9MRa03cMAeo1xvbkA0ks49CKMyPI94GW5KKOdmfijscrUUJa+H7ky/mxURcyymGUC8lAxITinuE9jnyK47JW8EKPtRltRhNY+U5lQUOnx+buKCNsn0r6qA5WNiY3Z3bfRobB7+XuSuSA5kJGC1bLeZkT/Zy6ZjeHHGraOhuQT68cGV0l3Y3tNNUUkWpoxC15qLKA8F6bUSkg2i6BHS0XZY3ej0FsfgoQNDQGaFCLBuG1EBGONpWx8yq/oly+83auHXudzsPMVn76v5DMlGSA6l/sJwZFmrxEAjWnZEjS/MlxtcHzsdcdZM3T5V31E2/w0Zq8fhU0WzOkl61gImXyO5cf7ftQMCphU3sJ673uvHlkPA5CqLX/LCSuJ00/H9KpFVCmiTv69wafvdesVQll07H2YKOJsQYNzYAJhRJKThPF4HDH+cxkAQplP+hbsber1myInJoU6N+BUoxktOEgYPfOT/0AMiZKLsLmzl9DdRA6XqXC8XeoXLOWZ5EiK6Yd/JNtw6v8iL961/NZfG6GR8LtFYSeLbpX5upg8etws/tC1Hxt86zYIq+p+UAzPQoTFIVRbWwFXMKDuJoAgfadwm7Ljd2MVODwtMer1lWf12nrzVQsYtvIaX73PHMB7i4D8BWoYlEEJ9l/pcahdLsoS9GjxF+dC1j6cO0UnsqQ2JC+eeAtQoYY/+gkO58l8kMC8wGKXLmATezeHVjkW5j162hjucqmatw0X2VUfDYMeM0LqPjfhdmmvkD43cq4t9beTrhH2TdjDv6IrIxrV8As3V69GN648qM7H1zuOPqjwDs2l2TRm1ya44ZtzBldWU4RAzFeWLVE38Z/uT/EoQrdR4yfPPBZsQiZI87bCEqjVJYysaffsFY+pNHLEFOKOyORPEl6Ml4QAdQK+qpGZPE360mdmJuW2o1PJLpvFLo0sn3oqtHO6qI24n+yrhcSyuYpZ8wAiIa18fgU8YMk3nygKqpa+fqwIqocB/4yYyimrxqhBLgGL+3HknLysqgONrghCY97AaHKwrtiCYXbaOTk68U4ah1wlsqbpQDes6c9evPqpL/p5AVOMAHUYfGfd4uTzGFKcvE0+stMiKWHyA1T9vCWcr2jkq7WPGN08EMUqQ6WntipGzOZqQXoD9qcF8WBQhGy0GFIjTPuZUvoQysOQ0pKhMUj3DvShKfiJhYE9GYGqcKhjE/+2zp2M6P9fsDG+YAd2kE++pWQ6CQ5WvUgp13bwW8dXfsNi83+o9kCafZbqEBselJu4O9WU44665TYEUT70gq5RR2LxMG+EZxEWZZIgRBU6TmzJg3nux87EUJ2Uze5gfngIHxbDWS+E1S8PGxG9UMHMcyPeeoMfvscZ//poz70liAp0WlAZeoB/E9HYL1sCg9+HP8QAZIjyXuAcI4wjjHO5w9U7rc7/JAP4NDMcSgMaEJnabfMzTsCUZQEuFpttrBscujPxtHmezqCC+2+aPZRcetuwkp5VtnwhHlWfrbs8c8kv0ZFBDDppX96Pxtxc8T3kmom+AWoAC1nAEt0rqcvHbbR/x56j84/GI0mZO9pLKtaX5G1L9xXbrYHACTGGKmicLUErBoiIzmuQ9ibcbDJxsRWqK/b75ImqFJfrwrSQYLVKaUHYZIQQZb7pFrhC6lAd4OdqkcJX1FJ34LjWCIdeie41NMNxJNzX7A9QfrnI/FcSiKpDiejHvLEqbN76Ogk6wbFkpT1b+L2tVlfJ4GZbuVXKdQ8LJGrHXvugTawmPAtKhrVjSIQQlmk64UVSr3VqKZCo0hLrTumCtSjhfLGKNqt0KzQznbQVLQN/eP34/VEoUlh5v10+x2tqTaBD7Fvo5DeBrtjXqhJT7V+Kl4Al8rhQj9DXWnXcfpl4KQw/irz3eFgRfcYYmyvMJpzrjE5uAVYh+N5SMCtCDIqlPcrwSCE5s3imnrVRxi+v03/U/ecwWOuubW2gcDWCSGK54EzrGKPrM8NXLr+3v50xnj2pIj3/JnPQAfgMsR5jQM1HU7sG4flxFs69p60K5Wq5fkK32hkYNCMiIPGg7PqKoJncx2OsTlcb0zutJU8bSdRwiEx4MkJyC7gFIiQBjBzMSJYFAIzgM2icU7A1b8/h1+Kfg+G0EBXY7SlD3Ll5vVwoLKdV5SpdaeOMqvnhS19v/qD9Nxi/klRmvUXAzoHDIEf7w2X+0pwN3BqWFw93V68ae9eKxGisTjUXi98hs3IlHjhF1CI6AT+dEob+btCOXSYR6Aa/gIbTd1ibfRvOVKAOsWFtv0GI9WlE26GAzaI8g9UwyL207A0XxkZQePc2HcY5tseVbvKxa7vFXsMjVJf23ve+QV9leQ0J5eaED8sHERKC3xBy1lPEcF+e3pglVQv+Rg1+AOM3IbLY6G/Z+PlTdYM5X4L3Hsa3ORJsFpHiYn6tKnrAoUz5v3aifkcX3Fn6PMqkl9k/bMHJF+/ll8se5qhh9rbh+Bu1+8OPshJamrJZBd7g/Yf+azzQhQiALIugikDRRvoilyTtMTwzS59xr9CsQ1NdSdbHK55aakEL6JBXhq1UMV8sJV7BDGfph7JZabYeHU/IyW97h6OMcDsB4Qk4HEKgFCL9MsmFbku7q3COasfA1ygoyjPWQUT1b/CnwH7Xcw+5Gp/dDsNWnEMUXQnFdRXmYKMdJ/Y0Rb+mQ27/lCOoP+X0CznZn8L5xumZEEQjX27jNpKLV8b6wtxuX5ErVCOt16+UyaJNDdeTswBjONp9ZWGYrMJvXN6OI8dDFa+hDX9XpLVunHtZRn/iWEo+Q+VlgAoz8Ztmsx+dQf/eCC/y6Jf0uVPAsfE6hB/Eu6H1gViaHpMh1uH4cZdC4D+VwiJ5o3bmocPlElBTKTOkr7khZYKSN46f3AeoE9inY6ONR54+OV2eer3UK9Xl1Ks5TcO2x8Crtn1fPCID0+IkomLqWiWC8rCoLHYKkQgFfWGaCIWJNZoLrDWeLfVbtSye1NoL8JLjTJX5gwReWuWpPy8GVbtst2CgBO2eaGBvGRXfAW8p/7VXcVAFfoFm5WRQJFnW+PL5JVIEXGed9VL8doB8kqNO57+oFaip0bPr6gOIWtWlTwWdWsl2UlpAhGGj/xnGE0FLrC32ro4VywyS4TkhKD9UtZTSnUUWb+sj8kMMe4UYeHByPP5tN9P8dA5PlGtaBjvAXvoA0ms0YO6oUm+tcqlGjCA9ojxqB2lpA5pSFdMpmjze1ykbZQSZ57T0hKlOr8yBSAZLdl0XR2Xly8rd+xOgi04CAX3A5s8gDA8bA7MkkNKHJh3yZaBf4UDcXfT8racoW3P5SXkqgIJYvs9gzQu5LeEyyyltw8Z5jrCVAv2ELiDaIbmm7gRFxddkSbtJLseJOkpvz+hP9/MSCDq+effPPdgKU3AlONemkRlFKAwh+kEkkvvkjQtMV7bf03s8RqMjkft/f+zJ0nHTRYIL1Yk4oj5XzDwc4eMd6kz3tWKPasdZtVzd4dD8JdL+OwBNveJlHYiMmWaLkkCDI+b30HmaG/bs0OQguqoBVkBDZWSZvxmFOqoujXeUSfsWaROzcAZmPkUQD1kbzHWNQbvp/SD5YfQZZAXAQjr/FCU82fyomZNfgKzFWTyD5prhWv9hFhb3NGDpokd0DwRi/WNSIVm+NqAbhrtAP9CsENiZcTBBhg5FsFJAXWTbJAAcbpD0SxUYcKMtqUgdBKxhqDzl2U7CUGQKI862Mcbw2UuCoV8qHlnLMn8YcWZxuJuCDpdIBbw6WDByKKTkKvRBZcrdQ+q4DvZr6IZUWajerk1fCbm6C1pzUtYl9xLg1xd/013z/hJoflXg3mY5KZN7IidV37smuYRNSxp2PTslgbsxF+OQiyLadzLwVpYcn6vgWHEjJQ6Qih2aq8YhJ3KZRaKsvKLJYUX4WPgEtqB5ZMd60+E3s3ki3D/JwgktM7PvIbevjj3L3HfLcpgkGPaYm19WtNIAkLdB3Xk1J8J6bb/UL9FoTTnvC/S924qeEBUy3fLSSKrDFK1CV4W29h+i2vwnSRFkJNRf0DpaDZpBHKswCOVZgEcqzAI5VmARyrMAjlWYBHKswCOVZgEcqzAI5VmARyrMAjlWYBHKswCOVZgEcqzAI5VmARyrMAjlWYBHKswCOVZgEcqzAI5VmARyrMAjlWYBHKswCOVZgEcqzAKJytVzXjDOXV6dg1DvshiFC9P06OHeD9AQ6sB60iVEKAwBC8UflT7s8fzllG8cyj5A3uHqs+BNS2uXb8T9ZQMYRbcAhyrWEkfbfvvHfolsGx9OxjfTJBRd4JGUYI5Le1F0Fpbog3bl0bWRSoqTuoyqGP5On8uH3MEjbLpas8QLKVk8fAFuosnxa2XkHOAAH9L/BRGnhVIadxn4MJ+WfTQcIvHzkGwNSlOGfeG781r24MdYPK729k0xiZ798pzdtzYR3WUHs9YJObM7iMsVvwjKvm/hYwgSSKR/EDsodtnE2vXJn2/IjNDIfO41GenhJr7iokoKz5OdkgWstAA/vY63I/lLD+hYq49903Koc/losRG8/wteigObW7ztcm03YogpudAmsa0bcNx4c1ao7QSQ9uYQbE9ANxFOVg71U9l/pM787lIKKK0CSFCwAaap7nV1wjPIGN/ifBMNJZih/JFlC2RgFTQQ+JH0BX5P1P99LRsNzd/1vX2CuY3cOX/ueyteMQXI7TkRydgqAL3LMVc+4r97PfxiJQPk8zR1W0guvWNRP7IzWGJlmJlmfdmD4k1RzvXg9qXh1+opmpCboBmbFrPwr93ZCBjPRU74MOC2PQRq5FAqrSBtBzHAWkPxDb3LkQiMAHnUzudA2rkqj0YbyCPksbcuNWN5MkTw5ziG+GAsWkeN3zIqI4zC1ToVaC80LH663TUgRpSHlgbLSNHwo0zWiDILazBUSDSG2OD8+qsmLU0TBgtRUkrzdtUtHt3l/PWDdneUkbiwemy+GbsEPUVQVaPcsYoZ0bwbaOAsFnXYbMGTlr6OSOjHrIUukN5WsaQR28QAMTx0X3nG2XhWmSsfmhgl8g+YZBHspT6PsmkZE+B4RKeuSj0o2nTI7fZEqPfATfyddBRAbtUKFYs8Mth+g594gxyFLqIKaNASDuvj71670402557KR1vfw9d/pa2YfdpR10KcmCnbDSkU0ZAvZTi8i05RTC/TQWmVQ7B9L77Ewt9/jdnrDvKSsvTwjF/rcG9b3WfGudcfCr2xPUoZnqN9Y+Y503IAX20ORhNCqb3CuPPPhlUgetrfoMlcrgTsGoYlY8Hnwe78xl4XYDZiH1pbtK0ZYeOy2SQdmG1trxZMb+6kMim3QmJpOpZTpTQ/9ujVko0OmYKa/xZWZvdyIN8WnDT7Jjp2X05dq/WKqUrMYwRIGlDXT/Mui+e0Lt6K3OHJbHgD3yEnLzBfx3FwwVtdOsW98bbocUxEfeQ+dDtYq+NL43VzDe8ZoPGhnJYyxcbzI+cMijUUd++GHXEF5nJ6liTeiW/yefjEIi6PcXf5glNhamZDUUVqqVHJTkwrH4xpalE7ElEB8xErGVMrOPcg4OtJzgUHxpYNt4BacQS2Ar0VTduUm4fk/mKx4ADp9UnakiP81zy7G7aUZbUf/huIDpopWWfxXUsvB33UJI8+Dkl9GIh9HPpbGiCdySSA8VJwaW/1/HaMTnU2gmA3sEtlNV0V75Q/PcbG/YnazUw1XGTZeNlTWXGBvC92Jj6PuMtHRN3/Qp+vXW1Q0wilXgd+QTHJDeUEtHXoG/tkEhdZp5xmf8jStLwcaN7SBq/lr7mOldxCFMdDtJo86CoTe1FPCPWKtFokmDn7uC+dAKWcAMmiXwmtR8YKX5cjWjdMo+Hf6rHEEMO5iLqNabMUEO4huFVBjMRXDMXeERPPkNtUrLDQrnjGB4UjfZNpXg4uKXplHLRAEk0/wW+FsR+DP95cDE1PtboIbNoJsXUeG+5uA2z9iBOHoDWVBXPMIhMoTCS5e4OUvwTg/oaeFYYF6eAhvnTm4AGjxYgzLDXH71tLy8QJ+hgexbuHpje7qH+HIxrgD82LxlVCcqVY38oWO9Dl82zQOXrnt5XuWfVoMbOeSMitIzQZ8d2EV0L0513La8ViKCKjix8wFa2x/dgvIXaXhGG4nC+LybUZEQEQOtOJqXkR9xW6Q85zhXUzQ6C5IQbepxdIzXRTIu1wG9Tk7DVv414fUWkqYnkauCkmwGPtycqeW+XUhueJBRw4pR3Jl1kFxmwJXmKA0FyNpuCRjQKmgO1GxSQPgNLS82p/fMc7yPb2VZK9PSsdcy/w1sTjwmhBUZ5+X1ukvl2XvuTn361H8Vg5dJV/nVirri/8sWl9GW6HSRmeUdQYAyskk6nA8ApV38lnXHbGM/7tO48za/E/+uCEUDzOyspY7nJmyjz0oGahMGosnEBVynz1hjkAXgGCMjOjWE+3HxiDfwOSYrhQIb2gZtTczv1hNPFiMFLEiIuK9LjL0+pgRK4fEdErXntiHkIrUarTkofkpP8mQHyuML8AlJb0uT/drMH2ZlJelNjc/bUP0iSyqLqULMTq2HPapB/Png3lXCi0pHmPGgKhXX+zt2Wk8Qus/UMNg58O87f4r/xp0hwq/NzMC2U40g037JPHOd2EnRZlzsqPDvEDG/VwfFqCyqXO+zATapNeCTAtB2V46vrAQ2QNGl6sei5n5pBn6lyZtKILtxG+dRXNDiu8N8J9fp2/qK9nSPOzO162d8H+PvpQ5eOgeplDo8SAIXrsdKfkn6wlm8OWaKAf4v/Zgy+C737oFVQu6hgy1R+x2vNPMczBZAZhwoMwpcNk3pIfx4jzU9yIr//4hjzbTXODmu+ZFNyrGr1//Ev3V8eDsxtCQtIcXIp/0pTdPESxAm3372EX0q72z7/wwu7AP+Za/RZBPBchRXXvR1wjkcAEo1I0LcStXf+TgQ/sUP8N7N5qCBRlbhRFkVGAfp4KU/QFQT83fIoSIplu/PzbiNPbmHZlMqOLEWv+BPFJcTCOm4uDGiu1sXuw6JRD2v2X5ZIkSsdDlp38/PFeWz1JT8NpNum+B078ZHypcq7zOlwU6ZFdHhTIIvx60FqFkgbbV5y6xYmybNqLc7MMpBElUzgKIWd9arJW6ratPi2iO3sCaIX44Rizs3yPm/RRd6Yj1hFHbmHSyCTQTw6wPEJCNricXyf9qCtC4HLjHlA3eVqGg+nkm8vppGtct46+q/6AuaeMZ/8KSaphTZu1NlYrWjCPB2dZlrwXVX1TmQ8XGzTq7REohIJqBr2zeSi3L8ZagFYf7QjPesK8cdTZgwqxYV9fOxsOCw0XsHo41u4iWWlrBzdbEk3iUDBO5073CpOx8AtWgMAzc9i2UfilzqCyV0hbibkpimlZB+/etKGXvEG7kWkw8UhyMHLfXGYYrC+SMbV56gwbHvFt+D6pujrqojmcYfl3cKN6ajZRKpxWj2Yj31+RvKFlHTUeU9OGLRssSBDmgmi2kd1qVwEKTHgYS3bTze1ESfcR5ckQnn9N5NT7uWcWexo18Mpt0HQLgCQvGE7Psj+NzlWwaOCSc4FFdBMMvAVZt1gI4xx4nXf8tm7M4LQnXo8C5EHfw38/h0kKsvReQrXBOd9FVcjLKZgZ7a19WhCK4otNBTU5OKIR/XIwHW0IlbFKW+/csN8+ep7wLfTdYddlMqsUZe7LxmJldPlKecVQX37aOdVsKQ/Tt3IQ4ct8QI+VqJpnsccUFjbqjEkoGDaccAmCYKDcQbdr/QeFG/JtH7tzPYsSHBDPOr5Gy3Qt0f6oJxwLCCw1K0bWefD2n9s0pt+p69tFg75wVjmsMaLkETpOcyNRRlnxquYsQZDO+D/mMfAM3EC9OyRGArcjJiXgXroYmVXlxvqwPToCxX13R+2Gt636YMfGwgne562PB4YKvs49r1RiGoC9pDvA7sQHmAVW3VSSxL4jxjMhJ2/GET5b6C/67IReKSvLxU1ZictjRumHpy8852Z3H2EtlKqHypatzGM26Z/lZQbUkG7O1lGLGBP13Iutj/NFF4YY1BZlwftAViUVDD6FtasVehcdTNOuUkx4MwED0OLfOuSOzxlyigWzTurL2/pspsGtaW0quyHtnfr6NbHLQvyiBQzO+1nd1Ydp+wsWFkam3u5QA+kw+LHnl7mMXFZWt0okYloCV0Wv0yvUvc2xwwT1EH+cY7QKX/gYZ39JhRjqKob96bGaFYHQVpcuGzPjF0c8YqnXwKVrrq/UYDsNQKFGonT0Umv0tjiWJk2KD62yKtX8UC/zGGF1OEOuETV1CPmZgbEjkSS7GbSeQNvB5Oa1PbJ0JR2WCCNoEI53XJrdPL/DKIR/W7iSCMRYzqAlmHjZfamu2Y9NVABMv5T6i4k4UDLuKu6mTys/J3M107ljvEwXPlMKOV3i5FXuGdJ33tzC7aPZDYc7iP07ltnCI5XMHnTrSEa4pVEdiskwj5gYK1urZbZUwXfxM1qcJ5Jm6IFyXACzseXSmNIf9Yn0k9Z8pPOhDeeDC/I0OZVddmx7qA+ZespI6hei2SYQubsKlfJlYGxktK1YdpVBFlK8ihAgB8X5s7CPBcHDcJQWnliYGKbv5jXOA9gxDFSS+W4KwQkigXm7xNqublo7a7pfTtlo+lMMS3DIhwWpAMkEKiIdQkGb/Q2gi+N1SPbVoy+lQjVBN73xBD5OGKoH6EgyhBH3W7LwAwkVSaUMxK0y1lkq9KmKkJ1VWXC+O1a1SdlWNKp4qqOVdDD9QGvoTIe8hf+dZ/jlQJrmj0SkTADmCgifEyrUhlgSnVMpzL7n6c7jDKoU9h1JPYA/kezaEZyNyQexUmhgBqA7gBvNFB+G7kmn0Pr1tphcsJwbtGOsLItIcRbW+s3G+Vxwkv5J74n1at9POw7Tc203PpAN5P0+/YI2LhBPMqfX7IzY+LXRIhmZILgMmZNg1gJbzlgADTibzBUXv1mUALSoCODkIthvPN1ur259/14YfRLQaUZQrR4u4dgB7nwq8hHCHYle/E4tGH+tW8+46F1UyZGpax3gH3kTFgt9u/CDGJQqpPiaSwUuQBEAVXSUoSkDmLCotvLqbTVUa8l8IZ+4V2j9QgpPDro/HjyelaS1rcxsx+o7MvssOn0NLZLIuDrbQ12efqNV1hTbFrd2Abo+J5z+kCGaZMvfL7QQGddEPMjYtLC2ni/21HpxhaQbiNqanewwXdEnc1T1FyCsLeKI8Izx0UJNZqJbP1ku6+oKJKBnznjGHHo2WA8e+Ze8utkhuG1Q4R3YRgJRia55iRAPc4UhTLWxKbctmv41KMc0qlvh7QOr7e1TPD+s8lsIevPGUUzS7L/kXvTXFLPKL7LGz2A278lPOSi3nou1GPAGnaR+vvM2WolAOvjBHI9XRvzyLym48KO7hbg4JBmUHQiwUgaeFE96AmbdmwPlasfJ4k+HL0xFx2HDItruRUytVIq+/I6trKDmcCJuSsrBEEyo1K9SdGKhiaxtl5/02Z+BU+D1RLRE0VI5WVM65dod7ZcaDM6DJ3aiCiORTwY+GvTgPpqbAw3Ak/Fv2kCs1l5ESlTjBbiGeDoOvjBG48LF+XFWdyVYc3BtkSvlHEAJY4TakdptuWPu5ktetJTeJT4eMAwurVSImBrLhxS02xJoG5oH1hpW0MPri6b1w8JQGztxAz6gmp8iK2fAqCSjDwpxTi5BWQujDlXOJHZeJg/d/DbwYcSFKtn3vfflm7UlDZnhpcvBb5UNwRZZbcnXwvA3WeIvaWXVCNnq0CD7pYDsB3vZx9CB/zzTgtdAALW8zglcie2wHnepf6pKPZaY9tUFtmtyXO6lKd7tPm5NR1x15a8s63/sgNAGirMQQ35Fd3gxsxRsAF2aviAWJ5lxK3I+wTYAyjz42LXtB27MUOlgUQ+MKldMfnv4xfdMrptCTe+QAn8tpXcEvqPqlFceeL1niA10oO+ZuqfvQ8pq93m8AKJFOgv1inlfQ+ky6F2t/gi9nUyDjaT1+PR1R2ehYgBec8Y9pJwDm9h6fudbtvvJop4Ff38B6NB/4QF2bej+ucRHDOjQGbk7usQ/EmYA0Elb/HB+srLD68W3jU6jxFkhpN2M2LRcdqqQAj1/eCb70/whh0+RSybE4chDrkQqr+rd+7cCRr1QZoev07y52rBySHfO2l9A6Dhdu832gbU8n6mFNRd1zBC/4y104IdYeHMwzDU2qEyXwtjr//8cZ6/rUso5S6UcGNhNhwMPgdgRjePrcWA/NvK+3VVLzN6XsnmomF1165Wgv6rFF1u4r9/4E3EyMnDhztQk/HF9p9W3DoYv1SBZegxPKi0gp812avxS6PE8KqLv6k+zlDbPW7ujysOwy/JqrnbWZf7NpRpRau7UqTwUxLpppSmw7ObACB9SxdJcwjAyDwcnfDHB1FGBDUjNCDIyhkAVGC03WsSMGZFFSlowndvn9JM/3GDfxnIGLQ/DetTpJGlrq/VgAeAD9Rl1LJQ5HG+O/tK6nVjSM4eSBCNJi/8goq07T7A+Gq2tPpy22ouLkfl5eYVrAHO3tPwAaP2cAAMgIaVHrt/MgJWSv1ofr1Ry5NpdBmeUPUxJG5gCcCaAeTiKmxqUFramW72f9kglvXNrRC6WZ378pBQ0P1QPZskaEXBJRYJSywPGI66ptYT1/m0Ts1LgCl+IttLl3ZdF3nlS9z8dkhf75ZSyGNCGHHSorsR/2YiaGkoy7x4SHozpyA/jMCvOVI5pb+mHnhorpb0XuXPkJt/7edvOdMuAvGP0f8iBI/5Q3Dm4o3a9OS+w23uXZxjOmG4h0d23X0rIJDG5sM9/kyYHo6UsH7x+T79TGsat+sK/hK78ASM5xOXlcpTojRLRZEl77BSvHpKAjHWayOEQ3KkOCZQ3U9lq0v5R3cUd7qrTW+sVFMzHjVKA6AVkvxBAcyZv2n39MZR6JoH45T5up4irNipFEiyIQJUE/auGvnNyw+scF277S90U8JgUctrWpiYwLR8capNZxb2fD2VNIFOSpXWn06Ud16UWhM4DWpNGdZhVotI1aHh9JNQSsr1SQnbLUi73Xu909CIjYrWnnIga7NJzeBAXLNXnM0sipBZf+9SoFCsUfedaHRsnDRVe0zCi5ocjBH7H8NO0kjzFeOGHz+JEdNckTUl+UZoRFk450tWuhzbZiPMYsHagpCpQ68LvgljH/DeeJO2iw6mtaM75rouLTpIkYDcoKk2IVhSThY5jzCW/HDccwsPHVMYV7FBPrzLTcR04cJRR+6CeXYt/8dVb7WHtSjUdS0pgrdtAWXAMwXe+bhXWhw74CXcDgaC/hPd9Vrp9/LU+/W2jaJauiMvbyBtORY5UIZwaCA3Z1LoMAUsJ9Xo8edlWj139BuXghRrx6Jn+LHCSvGmuwtYyTM/hrEX7Er8rwMPxPKLD7cMTe+PFoaKHFI19ZFbfWWCGbCkiWaHzE9SNPXczO/8XZXU/fTtdICtexRTmnhfOBXVm145hsbPSwiOYT0ziohKQeZDt5k9Eiqx+LkswrmxGpGr2KTWn4aY87lzsuyFDNNDGogJcouWrabPCsy5267n5eawBrNPRUtwmL3dACx9NiPapy24L0j6Pty9WuMakfN6zOSwbTBgf1ww+/5Hn1DhScjbG0an7f+vHc/C0Wt+Nl9WrRu+/mdwztLlD9vAwOVTEyGGeG0IP9ZSF0VOXTknPme0aQ1FE8vA4zouSW5ggfL6GljgYve7veNxikcfgkFJ0/M0ga5Ct8NpQ6wFxkAU/Ic4IEoy0WIRxRD6/PC7DIWR6J5nbvFX2M+tnfQNJbn+LSQoNbNGLowL6QdXiFsSnA2Y3P5/QCyr0w6mBHl8nXP1zZdbjbaBEGcJXvB2IsYYjLNU4SzAzFjJyXmi+qPEcrwRrQlvhtiycHo6+FDjGxPYJh5E3Cqq+8JAWVyDYyNa3ODVCoeTzW0vY6ySj6OzaQt6FDFUgMzOkMg7uaXAG8t+k3NIdPxdok6WjNKR4qa9cv/920LRBVwnRy0Wn9SnRaCGlxXmBqQ6/ZhkhEiPlmFTu458qzHWa3C765KHf3Gu8cSA8PjFI9YOX4y9y3WzSwmoA+NYawAQEImFXE4biBx1p+JDeaS9/y5VVNvC4VZCtkYdynk4wDx+9tTFB3UDAJqVZ8pkSKHhEfxGgA9ZC2jqCoaT4CEDFYvCZ8PZMCWSLzAWMzpVzjvogpC9ZoNqXYE7GDKdBR+bOSdO3hQoHXkcggdvstbP5SjB/lZTItoYqPNx9H7BXbPkv0rqQWedmN0EeovmQPdjkwnqeHny5zLb2NV0eD6G9AR1i0ilVuIvMsTqGsUHIyWh4nbeW5CEiqkua/latdgrv0R15WJ/bdLXVMnnYhe6M8RH2HwIeZp5JTyEiV7LwL6t67tJ5AJKKp0aeVnifbdBbuSu4Nl+WPCaM/DUMAvvc+ibhMoAD9HiYjr7gMYtpQWVUia6hI7Nw2fk6yR4r6tGMwrb/nVM6760C1RC35Br6WfFzWNOYOso+nB4Z9XmDYKpOu+BfykCSufjgW6JXSudgEkAkZUR6TDmlTnfav1BDhcsa8mXa1A2sIT6ok8NefgCHLQeZnV9nAyOrz1dpXZ1vARcZZgSPVDCSKrWTEfMU7FLOoxY9OGuyQITW1R4fz9zEFm5FiQXM8DIotvEkVULydd7zIZHGi3A+A4OBl4tHz4R/kGjcHBEvdJ2BlBj1DFcYr0fMvefQbQg8UMoqnNJCdc1Oznly6D4UaDKSd17qKweEWMQ32WqiHPywqMEVTFmAsoQiIi9bEwtcfXf0bXbhmxWMIzLs0pCClWPt5kWeibdu0R8P8mqBZ4ARKgybuzQ0xBF7OHNT8xPlADdumEVKX03uxP4EkfrB7cw4sGGFdx/OIYvyoTgX4DNSZxvbHgPF7jDFVtu1BxTFpgK30vU9unlpPlbZHl3MXiJJCQybMrKlGE95A01w+nQcCvCj1HOdlwxCM3mgM8bGb3UhKbEM5k5QFhfTDud0NOQgJxCabJKeQlwUyArbZImui9WOOFT38zywRxC7opNelWLPr1cP8DDVuJAYAQdS4qkLCt/lYRf+zzSOpMrlJyRH6uJ32rb1mkUJV4vbmPN7A4NBf8qVif9TmeaDr8YPByRzJpK8e/Yn/Jaj/uVzoshdIliNvPYQoztH+3im6ABgnJHLfrwFBsBmD5lRo38ovR4ycmpAZwJzbkxJTalULJgt5UAq6FXT+3l+yo3WM5d2+GQLi6+W/RGssGC/Jq4UW174qjsd9sNaiHtnQTS1HvR72EVtCQJiVUr2gZmUVXgIG4ghjJ6OnQZOpN+00KNwiNUfIoGOCviMTYFy4CIwfi+pQmETyyUfA3Gd1s3qPNapsbfxgzYgU5izE/pJ61jRB4EKO/tnOJxS+CCXRhDkT5/CKdqBDKIcv3gayf2/jPXor3QXElHTJMBDIXlebkerU/8FMO8FNwwDuNrTZ49VUyNxbyi6eC7LzLF2eKzTlo7gjzFgfWplfEbwyq6tBffsZtLAybFJ0tsjB0fymAGquoZiBw0CFYpbgDcMkw23oP3X7/9K2U8b8/maTlS4I9xbGNQ06q+UfXl6YJYH4TJzw8b4a8eW3hXEY9XwsLgJr9GnaT4HZXUEr8JCRuiluQLAAztlAJ1Er4C1/9DrvYGXAmFAETs2nmtizBVz/+kUlrp8fuapJTbQOrnELqyvVBCBCAxmSzL/YPo4qXlO18RpHJHWqTlpTBQooCPqzUcpN2ZP1cVudiI+4sNA3njVbTzOD6JN6jq7y1qVf+fvk+s95ttf7GUWhJ9yk7LkQCjEeU+M9tI9IWoK4n6PDrXUVg8+rgwP6sJRRoIn6XB5cx+n4uGtlI4cx16Euc5CGcmCqe04pUsEOHBpT/YurQLD5KDqEhNvcwL0HBhNY6i/chQYpKMaaEBJbLXRm26UrpqzfEDe9iLuemwBBMpOlXhyJzStQjqgtXHnp/quPvd+TyJxgUcL16VDfBNDxPCeKJZuJUTyLY61dph464HahGQhhVjncK8/Bq9Gi1GUvVVoGJ+6cUfkM5/uZhaS5fi7AqZkn/Dyr+CdqnfTRmnGpT3ez35g0MZ1xr8DR//xmzdWYLcBPIDQ59KpRsxQu9s90OHlkPwddFG5FhzkBUx0io7YCgxORq5ocxxXsWY3GnRfM4M7El27w9hs4SwiEqTzxCUVrhoVwAf0/w1s/bi2mJY9Fn93xV0J2MORKVkehF/5u9ohzwq67PxJH4soU6wAO7vRWN/cqCucPACYLeeWXqIlS4fJ0/6o+3KfkxOnQICaOYYwlAdQ0Jk4za/HfFH+D7rmYOIzsAuSFwwG+qVd8SAeyv7IBIrwCpP3+ala518TeCPgFAxUJqOXT3Mu02SUCUCC+lXcAJd4TNEvfIbi4JzJ9nn5PJuGjiQ+DnPcJz3Aw7w/7i+f1CHR3GIp7k2nIuAD8csfOWpnYS7XUEJDnVVvKgkxIqerDhchMmHjErafEm33mr0FJWpK+MtPm9BJg/o2D5ABjQREEzkN9+xRL6fvB28WXSzbzEQVJd0CuSwcvisHLoHdtcw1iGvQiODLvfyIJ+ME3N/hCSzUnI+cvyj5fy/l9ORCja8vMqU78JfqsFV+xp3g9yGnZaluGrHhF1YljyoXsQs8Axd0sOBX7U/qRrQQmlWeVAJ0oMpXjLoQlfK5JfoJB5F51tYYIiCohFKe6deM7i1MhXiNm6J3AOHqR9hdmfWV3Ne9zUDSR/B3JWuMc37y43nC1Oi194YO7W6ny9ttd9X9Xrkmml1fZg41gJ9846RbxO2Nww8o3idbaLrJ6XO1IZhhTE8f3SCOtRG+BWuaPZ7AO+Ka5vZ/OJWFYf0dZLZBaQLayeoPPmIIS4aJ5vlebC9IXrmjnWa8gJ5ae9a5ZF9NHOkjLfEbA/uDiZr08i23uE0g1V0z0ipQir3NfWsJygjvesP3MMGne66j+7w0oSj5rf8t2LrgmzUG4x2OfW3BexntQ8rfQwg+F5WbGHORTpXJR92uf1hz8Tmu6PF0/onrUt8LHkXLWi1CKqDN7pLWkdeAsyC6nx1+oLKqSH+VqfcWC4MKuaXKyfGuHCe6UpkkwuXhfr7+IXBrPUPmORHu0zpqdHzx2BSeBZc0AMOkSsoKPzDCD4wO+sZrdiRIDLQn/QfscCJ4kC2nTacHdAOT0ItagFccrBt3wKfL8txH5tpf2hslo/wsCONsjRKMwdLXmZkS1CSPFVVxb/NNV6Pl59Ze5mLJDKJpwOhvYc/hhFvECdoXXW5RGatj/q+cjoNS9K2Dof32+r8Fpzybtq6OJ6YoyxBqm0JRNjpeTWGV7dUxqduojeispGADlj9mkon1QEP1yl3xNElxH+M3TTfrlnNNSn21nB/zwLH+DRjDsomo9r15Wxq0G6FfDdLh5WqaRfm/s4u1iFZMvc8bZUrkDVJbrhmLyQkYBhDr+lcCR+Bfcjdvw5UQHj+ZUNBFIyuyLdPCYAZGZn2pDfLMl3l4WZ0Nu9wkQSwuaeUpJ7Szv4wWZFuZ1shAYLor9dpbz036m3u5tZm31xel4NRFENoIJ3ZHnGx2otgL4qy1atnmq9j6HsKuj7uvf29/tpbqNFKlugJJwlLeRoqebG9j+DEVTfaK9ya4PiNELMO73GnrsYsevVLWYbTLnX3nnNwj6x2TcHxCMRshLRc4MrRxuMy4vlxnnZaBI3w7xaiqYpFgk2cvo5uUCQFrxPR9KAjglM0hR1FEgBkn5U/A1yzKVriBTGN0dzrDnehvl9qlO+SfxIgoxVdoekgjhFMc6l7q7+HbBGnGsSaYhblaDobnysL81kFXCce0wbgZ7ueBTDtfy9SFsY164hfPWYoD/PSBTSIkNnUgvMDCgD/uVXvhS9SY9K76lJ8EbfN3VK7tGX1WzRIqOdRvXPhcRovo4Y7T7iT06Xs0LFPn/+ZYIgtqOGaTpcLAEKdwLG/8jkQ1gtdvURzjSR7P3+LA2JIZjW5S86u82swaPrictmd4NQhz8v8cItPAEEmNyYCBj/+e5EqjoCR3UBt366o8B8cQL4G8kV2vlRuxFicXzhvWPg5Vkr7SUq4f6KprloTaZKDGSF53gn3I4r0utQNigHDLnj/8KxfZ4GjK781aBxEV+YdzSxRWvA7gSX7uq6KZ58RxnLjdDNmJ7fnPHyqm1KXd6hp3AHw4/q8p27vnRlVJdz09oxiGRUmbGX7AK91U5X+Yrnwb8a8S6LTrM5vRBm+AQpful5zLQBiRzhlKrWMbMR3St2hgtPz0Byn0RbRH85A5Om5lGbMdXI32qxyCRWba4Ghj24WCDelcGiF1gu2lwgWVkHQP9XqQ6MYlAyPsaAlwa2VNyFbm2TT/YxcBWvZoz0HHSSQH6bVIqYzYcP/sTVke73mn4j+Tl/ov03T0HSUP71cBHkGYOMioQKfODbAAU4tp6Gc/TzVF6n0YtjZdDHEPbiKF/nsXrrzYnlpwwRrOqf8zLwp7eHoLLcf+3y/zfFEM5oknYimxsyX3G3GLVGi5szO5NtfYLVxEHJccd/QzPLL+IOyeTk2HfZR39e4xWu4gIuIZB00tgYmQwQeVsThWKunLMYmali1fqwCSjo9ux34ZebZY8GYHNRsVzJmy46cLhGWp61UKwdSY7YfpeO62jvXpPuNicWDjmrag4L4dUWVo9v9eOHkugdEKGMBZ8W+HvlP9WWhq4tWR1a8dgDvequMM9DIFBQ1Ok6inJ+BZ9k/dbT0q/g7019XO0E0UFo6VYtzoNhjU+3hNUh7vMnQjvx98z08trLn43yDEkte9p3WBzMkzbyYOG99io4lpYizM/ATeUCvW9TvlcaTQ5upARdAJU8BTa6uLnCMVzSyxxu3dXj5lPZTx4Icc/n4bNz1DUY0TSHGyVABuOsR20iL6d7zQP8r/pkU1lIx26r7JprzwxWoRysyCXPHawSQCPkGTOixXNdVcr8ItszN65NrLkeibTsM6imJ6SdTQrokHF4LbJtQ6BZHzRPFfh3vT7YHa9hZ8YcFmHBkDdnhRqPN8CxQYMcaTpsYYiYFoxMlaGqr8IjdCAVkgK9kEe7jox9jNZavgDJlqAWoNjol8nC8Nj5ZfLSKPMc3SBjuext2ouncE1M1GD33+z5vLbXxig7XEIQiJmxqmE+1E4cI8D1LGjo8SI5cvtq3W4sJCyomPSpPFpU9LjF7Nq4ZTTBJcYUNLQgzTjZ6RehbQatDqDHys+StV/NyJqSeRbAd68XLRB6Dpy9PW7qk2FZT04TK502v64vGb//l5+lD4YZkzdLP/lxypmmeRXQ9O/ghSkYTANIwzmHaqXa341HtOkF+MR1HgVY1Psjv8Vb0KyYJ66Ax6UgUiR4A/lgs2foKyjh4jPmDw9RenYrYozJFwSW1D2UKo5608b7TuQPNeSk7bQajNCVWs7SDoMrrN2UvxMu/B9crEARGAi7oNa2IKbrsRHpgi042AnhxD02mAeHZeuK1KbNrsvG5rDRNuxMU0Wb1fajuEIDO64XUu7Zwmxlu+aWVvD5kARdijdG6TwMLxkuZQ2WMEgPNNPpmPrQJ8haWGJbsqyveQfRWKiNZZ7p3do9eyYSoZrPy0oJNkVpJMFpWGzHv+gChXU2/ADV3im43q4q+hDteG/f5hC6ngjTHSq01sXCYma3QYiPaIVem4jDBmhSTph8DglGdbxylmdmLqYZ8HeWRumGMMPgb/xa9mrPGsJv1oV1liDaAxvxBHsOoMyeGxfGCzuhBreikxDWXHVf9J7Yzn22Pou7cWbKv42iQItftY46M2BDc+j+zJ6q7/1LTXTw/EVBelSWHaxrA6FvtyjThvR2AKzFhhFtc0+fS5LCqflWh7TOyODeNlHlur8AXHNlmk64h1TBJFhJiSPx33vU5AYCrvS4/5+IcgYxP4zF2UwLa1VCx/U/2U1M1gNvAXmcyUFNqzTZrzkiIPU+Xpd5elz1oT2kKaZMkWijCvfD6HS0SRgyI6dxzgdK3AxHrlDZR5x3qZsO6F4Tjs3xnmGUABhtB9YH9/9Q6souPyOJvC4BpRQmJ7n63yzgXthYqqBB5D9XfcdDLxIvYeTRHcuOMEa5FDKy3qbOpfAr+Zbichiu2aRZXF83Gc1hGxRlb7Xtm2q0+3tKNB7L+CAQra8SjzIzIZWa8dmXcVpq5HDCdLlxu2H/ZR1BouWZv+DUuk4t2K6jBhcZeQidtLoMnQHg1sNuRXjiVXRUVY8a6gZYjyDl8zFPk9iKOwjLdyUIw9LBdWMC1BmNMuHOs2mYUcmRptSZAPYgT+5uUc+lCLADJoWB27G+MIi25LRSIEmBqydmYfidK+CIY2ERSnjNfYPVJ2S28j2y/JDm5m3W3lVo+dAikH83pQPAEFUZX6d2YWrXlZ4kBXrGSCMYFt9yMFcPZPNXxttYn8kxi2cEiKUGpg61hQ0lXapBRQYGt+F7RKQpN8iaME+5VpN2mm44dzCWq1hKVN4QmXL/CQ/d6kjRkH4z1IHLiRhp2IgT3TNpSPu8hgFLrPY7IztQx1+yot6DKV4B0bAUw/fSpKp7SznQ/gwgVHdPUcIwP2zN4VS0ki/vY5HM3z29vy///IefzDs/1Oevtu2ZF4oO9DSayD9iFA2KC32Y34ZdYgRy99AkBvWAupHWj7omeHA8BqfpO+Ol8tc3i6rYetzXl7yZWiV/nLefOFYmaVOPNPt/17cDtMiDCUmquX57josoOxTfnqXt9s2Lkh1gDBkl9OWR30vKi+NzuPmYxEagLVw7vozFdyiv1twcj/GqZRPa5e+1oDvNjDthInqRXa5zLc0h75vQdWEN1+Lci00UQkQtotOG0FFs60IcquqqckinSwDKLL2jDbOQoQxUsCArFLoXZ+aVw3tsyqeqrigJDTt5M7UMdS8sUjMpmeSfIumGsBD9wrUODYWazQemlomZKL5EZrMSP7GAJwBGHyJBqi5iFLDrI1g0VVzjf1B889dxnGdgDSkSvc8g5gwOVqK7MrnZRo89ogt+TpBiZDy9xFur2HuJJE7v+QoDLsvCvdT0rra2UQOgyfc6hxDKtrV7MhH8SgkJ/ujMcuN61A/y09RqJxZWPCy7iG7189dzfwgOTksS/Fa9hWR5UoRDZ5VBchT7Iub0URCrNx1vE00p8YaP/3E+kL/SmeMqaekB0OU5U3S3UCH0Xr/lz2seq6L4bmEsQlieaWi2ITsoIdSOO/D3fU0iZ2UxOMjYsSkJAUWmpPbJsWxxk2THcrtMeyiJoBIIkfhb1jBbhwp0jqEcYC8Sj6J18AIbnb7AIkhxQvGcsVFiZ7xSWfIJ7Ipr4eYRL2XGCIHxvmw3IRgEZGiSTN8y2tEGdjVaiPTdp7LQ28n6rtjx9pFTMmYrBx9oualWotF/j8u/6uluI+oQjPMCU7AwFKpz1I+OxSZslX4049Y3FGyOANYodrIjPr8TIU3uvVHPlBszMyz7ewfnxn9sd9OkBSMtKKAyarqsJx6ag6N5f+c0Zid8pNsw9nVItSW5pAjN1Lzu08wD/lS3sboHJOsrnNrORUQS18bm1Xq4E4X+EMO5SoOMBIutZFQny8KEkoMdtlurqmJ/ZFtpXeQouL8Ki2rzaNw7OdI4nWX1iIG8hnDIW1KPWDg1/n4TCfRsyYESMewsXPBCXjNBtYy4kGMteW1E4eqtdMCI2mD2IKDY/ZHFArJ7qLREZ+/Mb5ymEvsMM5g0VkyCPRXa5cBeH01eP40j007EoJi9oJM7O+tU4bB1CjjkCsnMxE+BMjiTjh01MRA7Xaxten8zDupXDYT+QuL6KSZmKR2iiGjUZxveL6su/5JzIDoLDEA94YLjspLPjZ0dBjbrl4PiIRWd/kC+py9pfAW6K9+iYKSJrrpfJ1Y8/7b5zx8qI4DJHWNkpwwrBUg+YFUgBGfx5n2sqzBADvAZkZZfY0lWy6bSkiXcq+wAM+bln8HO77d8td4swp9z5oITzqUnuWZ+zY6zSxP1wHx+9OWlYTzxs/WJBCKHbGX+eNOvTJkIBSIWr+GoizUngJwY+HTLYmyNHMw0RZZCdpm9JLsaq6RsnRlT3+tgd13jVy9JtjQKeqB8+GmAokacUJ/fuj9lIzNaWED0rQWSrwzZMoN7ur1tepFmihW3ZQ4XcQMWlOB1lw1PXQtjhhlFvLQU5ushz+I3PotBYTI+oJplPenjljsWrXC9nEI5fB54uea89/UJkjt8TSHOxZN3xSiUpo6sf7y4OKVY0Ddzg6UjwL70ny2JXhIZ2H5Paly2m5EjXWCQW2qvGniHZIdRr2hG0N/bzXczf48feQH+kzOWsD+kIwjNta8KovakVFZexkxetVliHGYAHYRr4NUCi6cV/SQywLX6Ou9atRCBUyhAt6E+szCK5nOv52uZswY5iGCkvHQu43Cux+lHtdBidlk9y9ixxaYzJtTnprjwKN0g1XkMk/aI3VSTiQ5VXzW+q954d3B4bqBTK8A5i+FGjfwfFtLORLWbUE/nhKeFXEho4RmareiZOZk5eMi5HvQOFZyM1VRahD8QCwFSZ8Z8zfEJla1j+qjNdg8s3hZ7feHaUryThiphPkTfi4ejm8EiyBRilWg+9eVhNbda35Nr0ykWRRKuSzYEsCVuL8z/jtr4eIaQPIOwFuTeXWg+oa76sksQFb7DNorlaf+Uz4UwJA+E700JSBS3LvR10/8lUjk2idN6DDMCAis8O4nbEgHqNWLyALK2EH0d9CxBsWNPQyJ5r1O3OYkY/AOlYBhX2kCAPv46b1T0JtrC7ExEK3LoMChSXuuBzlKlsBqQZ4k88I8R2sFv26TaRJgC+5bnhg012PX1P1LpZEalOxEbaP96wZHtveLyFH/7dcTdlP7kF3QKC27WiOf4YgnHNnbvK83P4EhOKnNN/n0AVRH2+j8El3EClWRsPBdcPfT1zbnF79JZWWIAlvVnFWD5blxdIM5fCBnetow+6FJv8JQNkmd99ddbmgWP5C8JG4cHRi9d0mPsAh5dnqZeJnpbC1YCIfHRrrwHTPR6BPI5hsRXs6S2AKV2X1/pzUdI0/KEwn6oWED1rtvI7+CPAKzFoN7GuwOWXo87S1M5YqSXCNXGz6QRXHHWsw23y/3WEiw8nPROlFHgVaHtWhqYbSo1s7SKxAqR7AaKODoDxd0lr075H+uAbrjPUls/wpg6Pt5jIN7omiNQzgDDix38GDBSVlL1jHvZKhIKB6uGfHKM7Dtzz2Bl6trVc1fR7YCH3z4Eh+5iY40ojiHTor+gtUCSZkZiDD4QAOA94RAhTCZNAiVGWatdmdKLtIG+thM+tvS9PDjf17F9/kbUVTrG/E9Hrmwtt86jiM1ePLDFvCk3lHFH4jt1rOEWxcLdYt08VuI7hk2dZIK/hyEtZFP5PkW1IFCxmweQv2OTc7vt62J3mnYfOtUv/xrSHWGYtj+0GfkNRdmUpEBXYV2nRLmnWY1ZYmyCEjdWzsQ4uA70x5lTylosYKpsAch5Czn/Se5F9HquONO60P+R3/nZWM4ZkmnhfygzYzWuDqwZeksaqgXVcEGCundeC4M6vvUwl1tlSo/2hbPKx8TyZmnZAPUtRbzaoUBh8TSGjUWrprtqqfZ77GAr2OQ9qTv5yrFz2ydoIQ6yAOvsvF/ytVxfyfAX/CLxiITd3oadyw2D1tg8jr5Up2QX1xkjhTayCraa+Z35ZQcuNhymyuX0bskVRNm004p93YeHkGBn9Wg0pK2bzM6iCuJ4JW0HTO/XAv7VYB+USSm1ZgN8V6ZbBQYw/hZy/p4i+6hA8Cj6H35q6IDhbvKiAI5ImcNfsq4zcSIgWZaszu6+ItGIDs2qCYBHkHhKnj3uL8AiwyBMDgaJmeIb5Hvq++RcHD+T4j4cYNbrvqlmMP5ac0goJu4pd2Vj2A1SqPDzwgp3JlqQQjRfm8AeMVxW7LutYnlJYblIzBfAbXqfBE8zOHqwU5ofNhbpbkY7wlGoYHEyxvDwQk9F3+DpiiKmmgGfz/lfWZ851LWOGHVQ4tfPBRimVI2J77TDzcrNH6e4zCM/RVudD8FQBGnzPK2Xyl4f/0/tk0cO3IS0ft3dM1lYtfUEPFrbJ/cMIncg/szU1dnrguq4IMFejBPdxRNr718REwaTBO92CQkbj1PY7EiCTVlsfaA+efrYyzW0mv8sMsB9i0/gLtHJL9uJhVB7V8e5psMo9r0TldATGlXjIx25ESCxzNrMTygPTuxCCzAmiJExGTMCl7k3Dn/FR9Y7HVkU6xHpfTekziuPKjm8y5KXR3QSKWDY4PVaGDX63i92HLj+SHJz32NAXsYL2tFP3c/lsLbCe2ZNYFvCfhWvAw7fATB3p0Y6OMSPniJI2V/SDWQBTAqUrE25E5p8Ds2Glb0qS5Oojthx02bDNxvns2aYgppL8Kp60weiI3+q74HACEEqF0d6p8Qz8q0fdiTU0Qtz+Y+uSkwA6Y/BPF0CfQKvCN0BzxP74f82S1ZopSLviKL5K7WCp8ivXp2lBChKcvo4HltC9FAppuV4SFqk2vXQxpcUNvcjlT9pFP4sWEGKf6nc+jIcZWXcZ9JvVp/ynyZ+fJWWmWb+5YrUPYknCZav600zovrTcJxji75dUjFGQPU2pTA0ZA7fFkAq+HOyJaSs/uMn5trSfDoW+vIZdQXqfHd7RvbokE98ffCmqcpthH8vrBlho1rSocf0C3PCckySH8AHRMlCdOaYT5ieTbnVEjG/d3561u5fbkpL00dHZi6Fx9PbWniy80YC59phuq+7UHwGO2TJuo6ms5+VZemz+nMS5voXjSY3rmqn3U2Q5fxldFV37Dcf45ybgQSQG8IJIDeEEkBvCCSA3hBJAbwgkgN4QSQG8IJIDeEEkBvCCSA3hBJAbwglLFtIDuBPHCpoi2T5HjPpVkMe5743pB5kDpCoJbT91dljA8qCbCusg/xS4E+L28gaR/xl5lSFT8wBFC/GDjdlIR8G/NpgLnO5yqv+0p+mVEL0mCL0Ec3G/KK+MeABfbKbaSq5IJiAVFiE2BMOLdwDF+xn3CEZu5996z/MPp8Ecp5/Q/XFWJTIxeyoIbwyMGDpagRkLzcWN5VWwDbiAeoNhxCZfTc1E8LMnvtAo/ZadLRllJ6DDfIMS8ECAIET1A5uv4bCGvM3v4dtZ0Agn7WUoaQI3ClH6UrjgWT4DqqvIKSO4SXcYtQRHHhVSpUyl+kRgDXF26NMqn58TE9fQlesC0zFb/nFpuwCKFbLyPLz9UNnCNlN2JuxQWc2SPl2vahFjzmSt8ZxuAAnAoYnspk5EbQxCxuOyf3R2vh1RONSiB8UkFW7KNfTpydjbFq9GGOOI0HyoelsVeqgsdZ10O5ZyOmS02YO5yNnie+KBe1I3ygKQ2CovpijMJUEM2N4C2TCdUwmQBJTvRxrd8+q/CXxOfwL2iB/sDd9svJX7mXf6jSxVCn+jyDKjHvgTWblQl7NlJ8zIRXFqws8mAbdBxXsBTHMQRgGIenYwi70fXWutJVaXnOtxU17+CUOc2roLEG/NwwWn8yJXzhjP2LOuMoOMS/IJB54iHR1Gmjx91Uhp2/m825WgsB4TnvzkTIdAzOGivB+4LKc7SAV1sA9H6a1gKyrMCrWaT7YpqWBDHcyAsMjqruxSUHPQIeOCuAp3pY5fGeEk7KcycdRqyiRZiXyLwwbYJ5dBFPwf48OfcxBqTDxv3gIyPQjRLGP+xC3t4xkYtrToB6ZxlfmEOw2XmjOAyQy7vX7c4hynE3QLxDoGWQjQyn8Rpdj1prWjUxcB1mGGn3kK5H74fCKB2IEcogZGo5NO7BcA69+8HyKVi9JLuhZdH5vm+aqNu1Dgn91s21dRv3yRNt5ERkhhGbiXv8DQ52vK9tAJsYxFiQhHin4S1c+Ul/RoD4IVUIJCKsmhbmY/Dg/x7u5J9e0J2d7SiNq7VOEnPmhRwV+jAFeamlDa++SN93NnBxR5OSutPY19BXjX3PtOPZjyNetaW5eIUXOYY+D6SaEFGNGdqZqwFziWBQyU7M61xN4KLnVsTOHtzJEzd5R6emksBGKcxkQnvMh2a/6GXtWrCllepCnxZxK+Cqug5NUagmyOpWYazVAQus7MfjE5kSSpsfsLWVAsp5Nj8R1WMzVYFFOjCrDM4/myTGeRACxLWxLyANUGwnOWeWkDiXDAgv71QQXBNCyohutm2VOES8l/JS8uR4SVRybvMq6u2/tJZBxNOV6gf6b/gtM0VVOO+OXmuYa4YNcUX8ryLSP1x8VoNGxeRRJrxSkBZACPt3GtG63d63Eed+u+/Ih+zNnN7/jwjs41WUTUy/54VwFsxsFfGZeV0iskeiYX20nfBCfbo6uWmv2ZTg9t/4lvcE90Sj+OAk3lyKrKDnWnDyx3NNOxcrk9ir2tz7QLhWqDezo4SpNGgO9ESK0qeT+PySKawA2conPbo7wxaDD6pr4boB4rli0EJXdexNEaHl506VH1mQwxeGlSTQqchbbYx5iX4lTVN5rNTgPmjgFyOOvg1QuHguSqUDR+4hnNoB9O27kX6x/f73NzVD2g44IQO2xv/bqupK6KOGwALwZz4MWts9Opx0ZTfxap8mKID4Irn2JQBvEQ9IEG+RLczi1R5n1mhqrZdoI4/D3UH6x4MFbLSa2c6/Dl4aEk7UVrqcu7RL1IqamFnkVJxVKaeC4phdpQujbPzZLcdfH15NBj/ZVrgDUPUQWqZfzhXk8+ZKNLjIKUbAccj0bf2RBUrWjPnqd5ClUbBkpP9QYmVrv6fIv0H4tDFYCr232KigeGMlwpjb8zKD21s0UVH1Rn6gPjSPY6Fep7DF72K34PkbVQboMXvk9jelnQiCg5PdQz4sATuMbOKE7PYTZ2ewmzs9hNnZ7CbOz2E2dnsJs7PYTZ2ewmzs9hNnZ7CbOz2E2dnsJs7PYTZ2ewmzs9hNnZ7CbOz2E2dnsJs7PYTZ2ewmzs9hNnZ7CbOz2E2dnsGL5Gw4AAxRmcMdVV9lCI7Lemqi4iK6T+svdlYaNGibe0VU4wDTw5R5HRrR39oyE+MG0lpOkFyW2dtuGx1EIWxX4eRbr3phPtMStlL+kyp8i6xw+KU8Y2dsW7nV1xqHI5Lxyt5LuLYZ87HH9hvTIxeA+avyvvr5vSR+aBNUGrNr/7dXxGz2zRAlvyx/ktoEUoMrV5TRnks4oxe9LAMnnTm1etkskxth5DLRa+B0euArotjNEkhWAHrFBEqC1Yezb3RKndUCr4B0QXPv5y0Jo2z240LmnjpPGtz7RGlNHWPld44tW/q4/3aT1933VAwUR1raz5iNZKgiYBaEzD/1JmmUV2ejwzo95wHyCy1p/1qorGEUYO7dXP7t6zlHV8rjngs8b+AYM3+pht7DC8bWDWz/pMQOMiX8Pif9Ju+o6uXidHZR2hrha2mCxROUidf3vCl53Surqnn1vi6eR0jVJ8yRlBAuedbx4LZtlHm0kEHY1VZUF1vVZ4UJ7cDiLBJVG+INueF6d3lLq8heibVDH0yY5vGcOKsb3sZv+eouX143eTQ14RJAHkP4TK+rvTC2khjHfF8BcITqx4L5q3s+rHsWD1UEWCUaPvZDUsOnIB2QaJ8IPg3lj40Y954SA1Og9YRiZLksbysmkNpaZc3GydZHCttv4XPE3qEkF/Ikqw/gxd9rmpM0IEgyQlt4/jPQYuNYraBZ8Loerz1X5ZqQBmfwKEJdDyyXPhm6rCkX+eWanMH0j85PWFrFU7mT7/9IMqe9iK46FrwjshxxIUTS19BC8Hb/smZdzrd2svCfTvpC3qRkPOgf1fEHQgz9rd0AWXXu6ZM2H7dUro3yL00g01JoNIbJN8+laWJVDcMw5T0Xr3973WkTMGQcVLPffDvTH+7jOf5ltci7qp8XLyKDyl73DJ92nS7Ck88sn6RjahL2Z3j38kOGiR1+R5LS4QF5rf0p7CVUM59VfhebPMWjN8jLq8ZC8AU1poM1piHAFgaSPqrcgmyjrYSVMTp5HpQ2/eK2VG3mJYG3SwVi2cGxUDotgMNsogyMWbBB8m5aRoprH1ssI+vd99QnMSAQbfYdstANs69kp55YyWP13uaaofZb9d4d+g4+cVouRPM9N2P7cOxlPJ3KPqC6xRvWYrO+hObC2aYuRKn6syueAogBDL7LI2c8P7SnSYFoWiofwEskbE3PvnuFO9wazwJfan+oUR2rI5VcWghJb6KKcF/dn0DrbUt8RprjX+tuzE3QmPQD6QJ9obVApg1a42/fzzpmhzsiy+nuXeFVJXQqH3Zgp2KdRUHgi6iTE6ph6g0CnU/Uec1JHqMGfGOFXEVWawuIuP9MFS4M/+1WKXbNS4acEMSQMnVURW7QS6InG1OfWonFTFnSwLYLgwRcDtxn2uTzu0wJy+en5m5UX2rVNGwz9yFhloP5iv6J8pXIOaOKsvZYgbwhn7hWbe2jV0AEw00aab/rbhGBpGb2H2Ta0dyjCEQz1yDjNaZ6pMDBruJaFF2hb222N1pmT5VSkFV0KC063kB7eNNut0G3GwrvaVDEFGP2fCrALwuH7zAfbDlNCUWE3TGHmbZv0kpVaucqCgVe61M3Kc+a4q7YLvEjsWPyTf0YdAy/0wzqCss+WzPrXdJStcGgoEOjBY1Em+nWhG3ebnJdrq4qMuk/eOtEwbshKjG7D1CzN6GSCz7p5UPgcuy5ulyfiEp9qVjb6mKOSKlHBOqF6nvWJ6znt/nRaT329gc8h1O8bk6CjF+RwUHB6JnF5x0Lt6JkyaoC8c/PWsGuR2w5Zu3SRpfnNVE8uiPrANSu0vz4UitELSkdSBmxeNahE/9Dd71toJMZv9wYnHJEEmFfjaV1PY8gteiDzaQ/vTbhogbhV9qBu6L31OMvpvJ6y0KLA8V4fTdM3w2iKLeWCRV3wXKhOSHabzEIvKzYT+kYma2CAf7zk/2eF3Puh6Y/MnC72VBaNUQTKU1x8dALw0fuKgDK6dWJBlsDYjZHjUfLYOJXRAuJLQT2JnUjuUWVVYtkPCOHDlkKY8sUgbu0kgrk0u02Ioiywa7GbglJLDt4KGP/dhJK/Dlbn7x4/QtUV9+rITm383geyUs+qI6HN5XXck0gOOmBfd+wpNiwUJsVy5cR/97+cMNxGEE/u+8qCR4xtfGvqCDDH/wD+6l8YmBu0UqNeyLoAVcXldH+xMov4tpEhNENuXJfGcyGWopFwtKO6hfkDF6mY+CeBVPOrdq65sngGm2I6u5n8fpwZY5E1eFBAtf0JfVLHsllW8MIVJqcf8qAVov25P9zBxnx0+i+p1lZ08p+fMqI2jbFQEYSnhTVQK5dfXvdnKiV9bktPuHEeIuFEZIX4UPJ8TOJ2Ayi3nbfWGFLBl3wxRi5mtbrjwjo4dUKJG/ZswtoJ2rIXsxdWnWDVtOkdLdDJ1AsGDwmZaxukEbbD5WoiaV4cMt2AlEyf+J++73NUvrdYsN9qs7AIbdV5eXSotO4gcUxEJJsrGJZD+NAo7oPGoB0g7Xu3PBIhH67TnRcNu8Nr/HxiqIle7GGNwdxbGwymxjLVKOGNt5WUOuoxHW9GHUtBLKqSIHZ1t8wTjQ3XgEg//W4/JmReUyrT7zXE7nhEh44QflMrlBjFKgABJKLMf54MpXjsOoGfw5qJgJEn1tExmLKY9fBg2K136m4bp1B12QHlH4t8WuaWyl2ao5KdiFQcIhOt8IKu53fEgbT16m2JmNtimGSo0X7cVf44n60Y7AhxhLTW/26761i1+orZxI2DTUkbdL0YWQWpmnOJL6OwTyURwufPCqFnKtAyvTzj4Ka+rXSwwXxfV3LhjFTETkrQ+RU7ml69Dfteb9bxPqfyLcI3f81WrJqgfLfVy7y+oOcfBFctVOPmA1hV7o8n1A70w7443XifGd1Nsa1IyifwKahETYkVQ0uaW2LbcxTBtScfGK1otjx/jo7ffW9+NRdhWMJRExpuk18KUp8wMbhtkBMbLXNbuHcpbYfy+ciBz7mkl5fXU0w6FiRbaLASIkzYhMPdBFTicqdacpBKvHinaqAkIRjmHpZUfHJ7NK6EMY/I4JFu+JNKCELeRDkI5SWNuhWmIceLouj678FHIeEmyDhj0iMS9HYmQZ0B+Vh3i1K4OoDn7XiykTCxVAgWnFzkcEuacYUDv2zBSkUVuri9bF25nDzzVLCUEQJAbLQ8LGtNknYpyjDXGyNT1Km5vKzLlvdxKhQj9ZvDkcUoZctzCYnqTnRUXd8lvzti5LWPWr0M9I1zpLFh4t9ai2Xb6BmDlRsolf9XLEdfijtUcysFVS7NRm2fcm22OKVdsZg6IyUk0IiLVe6OT0h93PxJoY/LopPXm6rBJS87+OWGt26fCbRk4pE73F3CREqylKKgPrOFCsNScNs9vj+yyhQXCKgIyaeJ+N71r4qoVGVmzXyqRei4phUlnjKRXGiKK8nW0rCRQKfRnixHFA2BlAbFT0uwbgdsBaS1Hd5vWXZ5qGJs9EGrHbGmXbOM7chRJcxlB2h61PqJLAZvrppMb3mqn/GiVYu1WNKBf6lgqmZBeFCmpLeYEiXliB5qRCohS3THehsTTz2GKLbOyC6E6gcLx3OhKnsGb8XjwOGrMsFcncY6qF5AI7F63Q/EMOH04mMJRR5mgVANDCUDlQPRiE8Aj2QXKiDncVCAS+c2KnHlxhApvCMRj+Ubj5IS2O6R1LNE9axF0LGIRWbDIVkpAkXGgSayoxR4deT7AAp+L3FxjN/zeeAWG9s+WaWZfqb7GUnhRZzTU81NQ5iaLSc7wMnwCy4IGJHijViAaOiTrR4q5mIt5gsS6PKIaX4fmKP7JX25h7rhEm+jI2vdlQEYdtK9NJyGml7behkqP934O02pBvPU3wPc8x+gRNoPqJ4P2AKx3+aJGZgVzD9oFKTaWMLc7tvvqzIsimHNrryOMXiWjdhGqJr2eXfutzVfDJIb+hvICnyg717nFk34QOYPkKJ3SrnukAqpemDxlf3sIqPfwbtY8C+nKwwBrXJksWQQM5sDauv2D2jGz1giWS3D07UYIYex6EO3FnmM28XSsdmXTo9CUiUM3uuifT5XxxdkxPGRxYt5sHPXTiia0/M1lNoZK95lig1V0fIIOmP9Bfwi3vyeUYowL2Lvw7IdPAFPPUGb1h0B3gad1NC/eAoN4lV7VftX1khrI3y7xD9IRAKK38LDEpfgEAxT0a0MQO9wS0il/DvqFNcZ5Lh2jeZ5FXCH07W6uQIGKL9MZa7XD3BNqgESQqTQEU+MxQBu9tq24sYf+RZrygVrhWh1Sv6L5YDGS35KX0PvM528p/81ZqaAPodoH+Fu9uMzDd+knFY+gW7x6r4afrbASPkFOwKhhv/Uj2VHSpwPejevE2/HsDUTvB86H1w4aRdmZ3zvkLnYRdUPEif3iaBeIkyFTY4xSEHx/0OASvb55izhWAaidTjEbURA+sP9OF8p/MToeuGDSUu7tS5yH8ucrLXfwTFvTda3ua5saFZ+UGkKO8O4RSMK2/PmNkcWLrHiJHnGWlRf/yTr9JVaMi54Nc8CvdCCs0L4D2FGywbF9Oar8+ugudtA23dZ2QdoHSop4yyg0kk4t398qBSxDzjZ4SXefLRdF4N6HZagJzGns/Dp01BkNEhzWkOAdMuKeHb8gaINPsZ/+PpvrYurkR67dFAymUXzWQ19dt99OfytyEzwsxWJvZhtDJ6yG9WYEf9MCuOM+/YTvw5q00Tt9lVTtkbpeO1OZMVjbvhfbf0jeR95jxM+kswbKELoZVB/AoBe0N5zq/FQo1S2HLYwIeK/zDPNoVgubH97DB9TQX27ZjlmnRwlIhPnSTQX+nvQzeNHgt6gN5bS3DpqVtLl8+N+KwHAyCjdMzdDYCqJuZjPoYlM5n+QAI3qKm7tjZdIHiG9eymc5IV+gi5OXq5bf8WFIHPdHmZ1e0PItC6P58BWr2d/Jag2Gm5wDtTqAD4HvzwXOPvjHiUBCXKu6vQfdEglnCdq140qCM5pe01ltZRa6J4i+xsMBW55B0qAH77nNLrCOH3pRjUOPmb803ZlWIZ4PqqG95lgx3eFiBJ9/YEtzmE8FbPpCIs6jqYPFCVucBDqasEw15buJJWc5Thdv02j3YQbrGuZLW22EJnmiE8by9uEpBUB6nLeNSmgjf0VNpYihcWG3hu8hKKC4gMMU1FmauRO548QPGv2PfzUjQWjmgIuk9x99fl3VGaruutEmqDBKmNGy8hRgf/it/9LyiHOKx2hpOAFUVusYxhpeo4Ov7Ii9EcoOh54atRSmIeu20s9iEeecQNtocSwj9jAKaE3KOxSiQ/YS87Oz36b56wSLwjttg9zARO185MXQjWr8tTJfDx3lHVODQnJj/WJnLkdU+x6CBTCFYHHyEqDjKkdGghj9ETsi2eP6b0iA3V+Hc0bcXtRIC5Au9Q5ceu3zHax8FPJ81jgcsUfj9wXCgsVBdKcv8a9bz4PDHh6YQGdgiegI4U60/7qEyY2ezuFX2NTaAVRWlNygO3wPUX7ALgKh3PbqWrOthz8F05Th1P+8JbBc1ZMVfjQs3eusEnAE54/qOWT/vDaLkaR0oEkw5GARxxe1FKYNrKHxLD4YaPd8FAMWiZCZ5kkM+WDVcCeaHIERq17WyvsM8tdT6wyGfCmz4AaPuJUFWlEYx8YEHGFkS8O3LEeifR4ZjT2M5pLJV9J8WdJGZ3p3sY7iuLX1scetW+6NxySL0T6RyPTPqw8+Gi+cUwrIK4McEmLlQTWX//7+8JnPgWHZGyc45WCWCw256Ge+8H8HqXZ6NdEYUMBpza8PC+0MaRothofqkEAI5iP7e1OcAOvujkU1jmMzW4u7rP2XJJUkwUopiJ6T8KBDwE+kcj0z6sWpNGiEzcg/Kt3eUMRnX6ovubZP1ZPDUhmRoc0+6TjSdK27BV/IUgq/kKQVfyFIKv5CkFX8hSCr+QpBV/IUgq/kKQVfyFIKv5CkFX8hSCr+QpBV/IUgq/kKQVfyFIKv5CkFX8hSqPj8fHUjxVEAxD9mXLgRmRXHzG93przw4b5WsF5fSHHR5TLsTCWtHEBkG/SnoMHxEtObMjfcXmdI8FDFZrl0jAdwXwPwb+paI9FRocEEBbjXOPVJwm8pPvBsoJq6pg8itsCF54XExPNSE5WrDryvz/lxWDqmRzuQIfYcwtE/EH6Bgtq/xDkbO8MtRGe7AlYDprlphG5D3TxKFWrODOVEBgJg2rnAVibkByqPGCCtlNygHeN5HP0wWFuxpT+Y0AxjJQZnM/s2Vu+5KkGnWdefqHLjB8lSRWpFPOL1S0WfdS1UF1/BPMdD1CoXGcg7DVniXGDG7WXsPXebInn0Xcckahp6z/Qv2iSV4AxA/ca2u1bZ66t9fDWz+giYLWWZkzRqWpGsU2M8JFsrfz+zWWkL94ScwEvOvSUdL7xCMbjs8AKo/oJKMaOCswqiTC3SccqkqWw0TiDtsHIg3Aar1+UZ//RQWzX4XM65KO9f9hpoW5LQbl3i+mFNve1qfz0fiLXFQa5bV99YXVzpqUrMmaXx2HI5ghkpIMgc6oYtvHBI+4hIMkbRaS43Q5vS5WfgOrDntGJ+r/snSYoatRDA5dnO45VZSNX9mTAG8AAYsGuXakAORIgT+rwGYiyKWIvMsUVZ03RmdG5/s3lU6C3TR+JsdPCPsya0teiLl+fjQIoYdV0MTb6AVm3wPjIy0JXmphnX2Pgt8yIEv4MiATke9NfqTQCqNWXH5lZ3wdmhl/r7IJp8aw/8rtWtoAtREaK1QKMzkwyIZon7/PImpQ+YjaMs3MJwlgMy26FwyUQUamv6AmIygSwhBkgmjZGR5QRwAKaCQs43cVXL9KsxqFxj2JfIsZhfPgnsaGZTGPlxZtZyw0bNawBLMbR2dC7RmVKeYggojWcGFY6mnnJiT6wZdmpF6Tx6pQUZsneZCBuBKeJIbNszOsgjxtU7/PMVPj7hDqJoa1FjbzizubJrTJZ/jMpPTOO58tgeKxSYZScAblWAOaKpl29NvrvcuCZ7IcV/5Av2ZrZi5DxpFuK7r7la/OFl92XGJio0NnWtk8Xgtn3+Yx4YUT/nkw/3zgzrlAvBpZ092UQQ7HQ89bcE54UkRWlTfPrFF0CBhvTtzhcmG2VVbaqCvC+lh1gUq4rhJjx4FeG5lMl4QKq61yVwrM9V9ITAHqgjq8RgFA/Ca+F45hKAMwAmYfe4OGb+7RJNjmYz8wUwkIGwdrfdMSq6kH0rPh+wOu/BoHRmQ3JzowSFgqDDSg/91BCc0CVMSyjen4wYjqJl+7/t5eF1XnCwinIHDCQ4r/8T/JkFEVSCTTl09AJQC8tvsNlqO9ZiEec1R0/R4nSxy1rjMYEqMNtIvxT+SSXBOfYqOY84ZfIpuyqyAqlHYD88iqBw4eAXEGXdTkzmL3n2GAEUEDwC4gy7qcmcxe8+wwAiggeAXEGXdTkzmL3n2GAEUEDwC4gy7qcmcxe8+wwAiggeAXEGX8f1zDivLWECQFwyVsSUB54aHT8Rutf4J5KMfZxdbFtI3gUBrsFLN/Oi/Fn7k9xYjfaOTh6Z2vLnscmyqkykXRDSgIxQDNpbMtGqAQdRbDOFY/rDuxBw1HH+KMkjOpvyNYFSeoyTzMj9CaY21Kv9WALy6oxsI35Y/kvFZOwiOcIM9zKu/KClIwQeR5JOUE2SG7gPYrtKwilqXeg5G7nZvvnqF8eFgEDpPBhd6vvRya/9vTWpLdj0c/2a4HcClL4ckJqHZPAxcPdxtfKr57SBEWdaQeKFoHB53L0O5b9cK8SLYEqK4bOuGpoT2JLKDlDJv+cR42uEqg8CKsA3h2ioYgPeLelM39G19Jd75qPZ8V1st5uRAmvUOtNrw4xKJRFa5Aj/pDfJcSx4WWnhDGRNb7mvdWV8rzNaaK3cZiQrIW33rq9swcYo89PxJ22sZndXc93DO1HnFC4r029OaFEuyBOr40ROgQ9tS9bdZfLJ9a/uGCr9ZFzfMRRFeiSG/0wTcxkoirYPt5EExXCNk979UZAG0n/2Q7drafE0eZ2v/FaAzg3ugqlqUvtnH0P45OnepEPEpRSkr4tcSBDpYserSh5p0Pm4LYQY588SEsAjsM8+Y1Uc4WHmnMBDvk6nqV/rE/N2Eq1i13RL3KW0CnoPhNTCoFfRmIpgZGZK48UhVGQCdln+PQNbqLD9sTSgpazpnuj/IdMIk0KQr8UJhI9Kzy+6TDIzIS6P64uIpTXZlr9p9JGPWCatCY2bTo+kdp5yw2pIdCpDzU2vI+X4Jmapevs/4bjoozIRPscOhRsKJLVq7gOjMYU06CJrO8zSbUI7S3ra3qKXFAr5soFhBdxH9D9o3Yz/+Lu8wvSD4T/DYRKvOvSbnm2ZE2NZ2JRqaQyzfiXtr0YDtdL7l4fVu/wJ+THQUxe5NDtKccPygJwQJtN3PlzNOYk6/T4veyN0GXJtK/JajOnSvVqzW2WaXS1Abt+Ph83cX5nrMX41B4kSp2Li+ALlKOX5M9akJIM//mzj/kaInmG0EnYYRnbqPpRVeVRivFamWcWBJedFdC6vMwpGkO+9T1KuOUK8PgBTmjZWExH2mQXtUfWOZNqC/KOyGAlO9hGqxytlmobEtNhVp4BdVBWuP8eaKddceCp0rdZvA/1pOwzX8/FD1o++h2icl8AvkcIBGJCqMU0489k3D70JJuE6XXJ3Ejmet6i9Fh8iwZVa5bIJ0Df+uUn5Dxpv2QxEYwsJHK4q7yBgfLW7OLVJF3z7vtq2w2NvacPYGDPHSFpiaw6kh+LK3+vhUeKXE1nCTsilmCkI13yu7tduaFwlRC7y979hQFeMXdkgq4b1K4S4z5AlDWG6sYwoaggqg/wg/xnoXrKCNFsBS+JEhHqKh7W7HgycUoKWJNqP691ZBJH3OXCyQy0hnGYpy4R/W+5yjImfc8vYV0Uo/GMVpQsxxMMjGZf4tudhM7475/7rqMU9pJZdJXNrMLmDPDtNSCsd1R8R6nocMJeWRQLNzmGd0u/gAWlvBI2B3oCF99CeQNPnLvZLveEmVkybWPR+IMZMzkTi0N3KcHhlGk4s8tZtMaqTNGWrDzodViFftRATRBK85LFHfcrEZMN6iL+R+rJPiQI2oeOmLycWjRznBMzT2acCCrFWcTs4lehJmfiRDXSHKQycXvhPly+5FiM4J8Zieku2QaZ9heq7bel6Q7LMoe91TRaf6TIJZuFsh061IBSFBikJ+dkngWazLOgLcFSRYcKSI7Xgv3C6yLnwPHr1aqiUQxgu7ZADVIHqg5TKBhfi0vzQZl5pSbK0heTo+R92m0Oe60tg4W4HhO+hTCl5/Awq9nlccmCWgXrYoaktGNw2KVJPgotjsGZxoiWzKcu9lYDM0g7PGx9Sk1DCf/HGDa1EsQ+DI4cghkVazpPMrRl59x+hvyAQrk+g0NBd6TPFaZWEHImM3VvNTpGfZif/sDKr/h4C2D+ElUicRm2dvVPIrI9+unLHrK/yXaCdfP8X0K/MxvVPewdzjnAWG/mGFYAtT7Ym/uKH8+Pkxe/hUxDJGbzjZ5jZQkaorNvGh35AHoTp1x0Yb38jbfLmrPLTtreG0YKF9wavi0gAwk19fKDkMGFitzR+rWS3BZm8bbZW4evghrkz+3CogpY4gICQy0xhfQpAlh4jtFv6o0Ptf4yQhj0rXfbzS08FA8Yd3EK/VHewGA/FYw1CPxnVziNTP/BnpSvF1U3pGSyXw73zsb5KDjfrzXQIcxRgLZCAe8Ve7afKgNnOLu/JszvrCN17spf8c8j52QwbLWjfGFubzNHhz5RgKTJUOP+6tJa/XPK12X9QhL1OblIiqfWoU8ABjGdou3kcqd11fZL2rJZSyGzs7NxAA2gcKXXx5o4jG32Rvi6DiQ5hCsbTg26Ta8vyUixpPeokzjS0ikG699yZ+tInkFF+8z5tIXRqu16kNLP0aIJJkXlopPVhGBbXsQmcWZkEAPj/OV4CCgkwY23gsqpy4rPq6Pb4qMilRuSWs0QHG85GAfBgRc8nGFsluiHwzGIekI8bv1HaVp7ju7ByyVO7P0rpX4hCuec5fXiv+kAiaoXCFijSTZXd5aCR1hLRNxocVr6VrwOKsGZp0QIAk0YgweQ0oGjeDBZ0+n/GW5beHvyqP+3LAWfcgGfisWezRsz7npyb9s5D63flPSBTb0ESnyJ5Pv0nS1dNlOWV5E4gnAUzVTamcXGF4fKtxZQHMzGXylVBjP+OlIThuSVt6MbCdC2au5HsqrM54Uao9Ebtuk1U3jZGB8bjJq50aZn5+DuXzShaNNAF5yZx6aXwwqlWs/xmnOymJeJgDu0zXrLRyLhoINwc7RfdK/0hXJ16mWCIPLkOz1nZvh2GTVGxieJgcfjfI0ORTn9Cqbd/x+cqUtfeDagygMvUN7jJWvqu0qtRYhNIAxwmkkTGX9F5FdQNlFo5baUHjNKK/0A3TurET5AaQxTzNRWXnPFFF78P3F+CTd+RRruXDVAWubSrksPSU8Pry8epaCOLqpLIk94lt7cXX6KanTH+u0fqTKLGR89DGImxStj9/Nsfzwk5mkfAX/LYC5eQfCCZB1kBG/7oqeyBqjrsICFsB5cKLSWmrLDJbUGZgWCRZr29MJOB+HJ0qkS9J2t88Fw+99nsXVyTs5O21PNXr13o7nUskol2k/ircLL+VC2mlKfEqIxx3peQz/oDes/DpFwAPgKNvfXgoVlmWZeB4daTni0loPEz1Ni61Ua3LLIGHwWMrHnIHo2w0r94yLPb+ojBvzWFQlORC7YmQolohbTAK5egUX6YT+0mB2ex1f8tpURI1akNabRnhL6QLbISBnN2xvLKwIrjfAaJSmAq2BU2nijO04GgPRRym9bCKAf8BYA2IIg3KmoqZBHI63g0816VO6yEBHDT0RGNX2VxEbl5QxoiisyUhxOn35gTumRztfvSrPITrqEuHcY1HzNAJseLxMN1Yw41svD4K+4pMiMZitSbFLoKNQ0LwzU4KHbRi4JkJ+8qPRiOtk/wSNniwbhyi8GV9e2kbK6FcvwQEKqHe99nk1kXd1LzpTxiLw9mT5K9CYbvYvknEsqyOHXLDGHNS7/scHNwDO8iAeuVOTkz6QifGbxsccvkYvKyFkf9i0/KJc2hvtKTr6LXwXh3rh0UMd2JXJd5zCHUyLqKiKNGR3+lUuGSqL5mW5D2MlpVfG75GMv23KrFIJ4HoHPReLLYQwiYYS6WpdIBGy/oYLJFe/oomF3vokxvzDCI1TKoF7xqAEa6sAc7XIPWijn1B5yO9xBrtzg9D+ETPdFuNek7O9HyAtEsOlmZTz4snmS4lV07GuyTPHcVfxCbjM5pjEOvtRyR8pQxO5bPqqzXpWiUU79e77QIKXgjeHigCoQuaj95BhywSIp0sQGB9+o4xGTMyPBBiHAOkbV4Rv8heZSy+n+odebVY7D7YRRidxzVeSuULcarmJrZrMkXeS6j9llCZbaKjrJD3yVr29MZv54cB2q+KYTC7gLevQYZaw+pzO8uKyiYXmb2+uFg7jWmpp8DPOy2TE6XttP1/jYudG2Aj4FUqlTReL0qYOBiX1V5ttNd4aRPR7W5v4tEkMgUSoWmEAuXoBcHAXc0BOm0y5BlIu+OXGKADUZ0z6PNivjBCfJ2Y1oekH7uYj1b1lLgJzv4Vph7WId/WKuyjU5C2hjv4ZY1Hxcv0KBpwbf1JSl80jU9V5JY9wCRh7UhQHuYJJz/VbLaCxmJexi3eqlghMoJP3+XCROZeCLcvmw+caKtfH6LcM1y8LqTSUDAptM5hdbdUQ4oTCL+YGkHS3KcQx+7QXDL1HYCPCvf/z/ixyZmEod4imOX2XGa4GdxCPZZyHQCrQcy1FidWsVSSEWAqRm9bYfeKgrTz2nENlqBBSfyUZTMPaaJqXhEsn5q47Dh8uexlMJf+vIK7UfpQV988bRfJ+b2e15W6JgYErVX7WQsjol9dDsEZOHDRFcYtjQi4f+1bXgqeBExOsT2S15gWiCmwo1tUxKsDWIIIxLYkqbvaxCERs70La21BO74tex2ldihTUb/3RByLnokE7nSvrD55JQxQF3G+tJMvHOeCONcZkpO7DOfxDfOWJC1wTOu43b5aVvv/p24IKElT1DFcy/C2qmeocTg5t0Ojqdl1ad+Y3FtZUEQChg28IBUazhMjLN7uHKQdfVLrTXc54gtoqgS5+Bca/0u9E4IRz6tIUZyOAz6sYaP3NtrXvXkV2dC5wAxz2A3dI+xY0z9n6ji/eUh83z5rSrLq4uiuo4M7yrXF+YUAVNXqGiWG8nGe1+NMJiDVap4WywLJBi9eOPUJnsOM8Eu23BbY0dj8VSm6zUcsj7wqvf8I4fRFPmniw0QVCq+EzrTPzuEkOywNfsOo+KpNfD2TtYQGDqWyK89JHvLjthGKstCq9G4oo+inrQS1UcRu9nKplWx4imUO+zhiDthvx2jL8z1L0cz4WNg45mDay1R1Lisb5Oa6tqbqJdk05GTvkyzL6cgLJleYa3YOcym8oeKXuU/ER7pVcoJ2GKpjkGqpd20t4XxhKlZVPFZeShzYYNy+6nbMdkaoHhVY44a/p21PyqUdskFLErgPKmcM4VyM4kJuKruCuVC8NQIu9x8RMQDPqlUw8o23KLOyORvK6/7KTyNjyFNgLn56jBK+Yobd5DAU/ZlUM8/iLXD7mEnqzAXWtl80oqiLbwCZN8ZjVjeDra8Z3Ewa0O+CU+ldTHx8e960y5T5F05l3KIh3/17nqKP9jYGKlFZ7ZoFB6FSAnAtYy+nfB+qb0+1agcsdVNFEVPZPpD6rhsP4BEYsoRYdDA8ZkUSWc4oOImLgGdnAn6oEmIY5oQiblLBrITIEAFW6uX8SrNxVlZO3eSwJhkeSSIXOifU3Dg44xBRLz600ZSpOYo275gOndNlA6UEkvgdKCSXwOlBJL4HSgkl8DpQSS+B0oJJfA6UEkvgdKCSXwOlBJL4HSgkl8DpQSS+B0oJJfA6UEkvgdKCSXwOlBJL4HSgkl8DpQSS+B0oJJfA6UEkvgdKCSXwOlBJL4HSgkl8DpQSS+B0oJJfA6UEkvgdKCSXwOlBJL4HSgkl8DpQSS+B0oJJfA6UEkvgdKCSXwOlBJL4HSgkl8DXE7dFT4fWtFySU66U7RX61JKoH0ZgIym2gB0Mh5JD2iHO4u0dBYXg/YU6qIhOIehKMGMJ83irOdNZY3j/w+sMxNL538MMjD/2JeTUSFNv1bCsJxkFECuw67pOmB4R0UVo57YnVB0l2PazyE8ggDLDBPt8rxEwpDkuiMyXNsFaB52JNBYHQTNfOI6UHSgVtgQboR5aMjQk1Yhve36GJ7OVcIk0LyHtC4zHoDppooQIxjeWArXM+mUXHp2B+56/KrFrqWf+vnRmtCbCfYJrZYgxOxxXHRniW8B6jmZaytd2IUfW3EmrBJcjI0moYqIw50v7Pc8JSiNlvOxeUvl8daL+cBpUKohIl+YYB1jEaFSHb8RrsSjrx9gD3oTVUeUnmJSxA+bm972Gv96WH7x6PUvRhT9kYUi08H/MonN/ECxOnp2nMF7E8sMRkiTtpbAe1HkP+MFONWei1iup0Be1SphVkCTzfpJJCJ/mbj1GXfqo/HrpHpZ2ulFKteC6YpSbPRNKDEI7DCoLArZcPYJlRZe3ILChwgm8X3dFCvXvIV0rYEvfM79QF3XQJsSELH8EFgZzx/BBYGc8fwQWBnPH8EFgZzx/BBYGc8fwQWBnPH8EFgZzx/BBYGc8fwQWBnPH8EFgZzx/BBYGc8fwQWBnPH8EFgZzx/BBYGc8fwQWBnPH8EFgZzx/BBYGc8fwQWBnPH8EFgZzx/BBYGc8fwQWBnPH8EFgZzx/BBYGc8fwQWBnPH8EFgZzx/BBYGc8fwQWBnPH8EFgZzx/BBYGc8fwQWBnPH8EFgZzx/BBYGc8f0PClDZH5H5H5Bju895d9gCszdHPmiiyGol0GVKbkRMbVp+WlLq+LjAcj38VoKLwwDZApWyOivGabvBur9QBo23BZGIi8vxssrlKOuuTKVu4dogGFZnG105N3AI99Jj4Xinq1H3nXHjSjJObqS69k1PG2rxsfcPslFiNxua8NfNpYhWnbCjSkskb8dLt37ZZArifPJkkKMmsfNXI4YBY7woR9egCj/6EQW5tvHSvmYcd2yi6V2nQExMtCGqy0D2fRd54BZJV5U10faRFwtTTv2p0Sdl3AAWr2MAINpDoUi2arY+chj8UnPnyCP72rjQR5y8nZPBdVB+yQ4AAA)

i see nothing

## Assistant:

> 10/10/2026 15:40:52

> Explaining the blank cell and Kaggle session persistence risks.
>
> - Explaining the blank cell and Kaggle session persistence risks.
> - **Done**

That screenshot is normal, so nothing is broken. The "Fig." label is only a heading. The figure is the output of the code cell directly below it, and that cell hasn't been run yet.

- **What you can see:** the list of 9.72% missing values at the top is Fig. T1.4a. That is a figure. It is plain text in the notebook, not a chart or picture.
- **Why you see nothing under Fig. T1.7a:** the code cell right under that label (the `gap = ...` cell, below the visible edge of your screenshot) is new and hasn't been run. Cells I added start with no output.
- **The pink boxes:** this is Spark's progress bar. Kaggle shows it in pink because it comes through the error stream, but it isn't an error.

**What to do**
1. Click inside the code cell under "Fig. T1.7a" and press Shift+Enter.
2. Do the same for the other new cells: Fig. T1.6 (the size check, higher up), Fig. T1.7b (below the class balance), and then the `task1.json` cell and the last EP1 cell. You can also use Run → Run All.
3. The CSV size check in T1.6 can take a minute or two and uses a few GB of temporary disk space.

**Two things I can see in your screenshot**
- It says "No persistence". Kaggle deletes `/kaggle/working` files when the session ends, including `results/task1.json`. Download `task1.json` and the notebook before you close the session. The Spark progress bars and outputs are saved in the notebook only if you save it.
- You have a GPU T4 x2 turned on. Spark MLlib doesn't use it, so set the accelerator to None to save your quota.

Run those cells and send me what Fig. T1.6, T1.7a and T1.7b show. I'll check the report wording against them.

## User:

> 10/10/2026 15:41:38

so text box u are calling fig?

## Assistant:

> 10/10/2026 15:41:46

> Clarifying what counts as a figure in the output.
>
> - Clarifying what counts as a figure in the output.
> - **Done**

Yes, that's what I mean. In this notebook a "figure" is the printed output of a code cell, such as a text block or a small table. The "Fig. T1.4a" line above it is only a heading I added so you can point to the output. The evidence is the output below the label, not the label itself.

I used "Fig." because the answer sheet's rule says every claim must cite "a numbered figure or table from your own notebook". Your outputs are mostly printed tables and numbers, not charts, so "Fig. T1.x" is simply my way of numbering them. The label is my own convention, not something the module defined. I haven't seen the marking guidance on whether printed text counts, so I can't promise a marker treats it exactly like a chart.

You have two simple options:

1. **Keep it as it is.** The marker opens your notebook, finds "Fig. T1.2", and sees the output below it. The labels already match the Word text.
2. **Make them look more like figures.** Screenshot an important output (for example the tip leakage table, T1.2) and paste it into the Word file under the section that uses it. You could also draw a quick bar chart of the payment codes or cash share. This adds length to the Word file and isn't required.

If you'd rather not call text output a "figure", I can rename everything to "Output T1.x" in both the notebook and the Word sheet. Another option is to ask Dr Stamou whether printed outputs count. I'd do that along with your email about the 1 GiB size question.

## User:

> 10/10/2026 15:45:39

tableu dashbaord at end or for eac task?

## Assistant:

> 10/10/2026 15:45:45

> Mapping Tableau dashboard requirements to the project brief.
>
> - Mapping Tableau dashboard requirements to the project brief.
> - **Done**

Tableau comes **at the end, in Task 4 (Week 6)**, not one per task.

- **One workbook, four dashboards:** data quality and pipeline monitoring, model performance and feature importance, business insights, and scalability and cost. You publish it once on Tableau Public and put one link in the Word sheet.
- **The dashboards use results from every task.** For example, the data quality dashboard can use your Task 1 cleaning funnel and missing values, and the scalability dashboard can use Task 3 timings. So you keep the results from earlier tasks and use them in Week 6.
- **Task 4's notebook exports the data for Tableau.** The brief lists "data export for Tableau, preprocessing for visualisation" as its notebook requirement. You don't need to build any Tableau data in the Task 1 notebook.
- **Task 4 also needs three insights, each written as observation, evidence and decision, plus a short critical reflection.** The text is 150 words, and the contact sheet is one image showing all four dashboards.

Tableau Public workbooks are public by default. This is fine here, since the TLC data is open, but remember it applies to Tableau only. Your GitHub repo must stay private.

For now, nothing Tableau-related is needed for Task 1. The only thing worth doing is keeping `results/task1.json` safe (download it from Kaggle before the session ends), since Task 4 will pull from it.

## User:

> 10/10/2026 15:48:19

so now i am ooo away my frend is submitting now what exactly he needs to do and what to type hash tell clelalry step by step with ocmmands winsodws aiwll send him heis noob tell simple clear and whihc url?

## Assistant:

> 10/10/2026 15:49:09

> Mapping commit hashes to Word document evidence sections.
>
> - Mapping commit hashes to Word document evidence sections.
> - Update README with SID and catalogue number for the commit
> - Presenting file(s)...
> - **Done**

You can send this to your friend as it is. First, three things to know:

- **This is not the Turnitin submission.** It only puts Task 1 on GitHub, so you have commits and hashes. The Word file goes to Turnitin later, by 26 Oct at 6pm UK time, after Tasks 2 to 4 are done.
- **It must use your GitHub account.** The commits have to be under your name. Your friend should use your account only if you allow it, and should never put a password in a chat or a message. Git opens a browser sign-in itself.
- **The files must have been run first.** Every cell in the notebook must have been run and saved, otherwise the outputs won't be on GitHub.

---

## Steps for your friend (Windows)

**Step 1: Get the files from Kaggle**
1. Open Sridhar's notebook. Click Run, then Run All, and wait until it finishes (a few minutes).
2. Click File, then Download notebook. This gives you `Task1.ipynb`.
3. In the right-hand panel, open the Output tab. Go to `results`, find `task1.json`, click the three dots and choose Download.
4. Also download the `README.md` I attached to this message.

**Step 2: Install Git**
Download "Git for Windows" from https://git-scm.com/download/win and install it with the default options.

**Step 3: Find or create the repo**
- Open https://github.com/7006SCN2627SEPNOV and look for `7006SCN_SG_17165640` (or a name like it, with Sridhar's SID).
- **If it exists**, use that name below.
- **If it doesn't**, create it at https://github.com/organizations/7006SCN2627SEPNOV/repositories/new. Name it `7006SCN_SG_17165640` and set it to **Private**. Don't tick "Add a README".

**Step 4: Clone it**
Open PowerShell (press the Windows key, type `powershell`) and run these one at a time:

```
cd $HOME
git clone https://github.com/7006SCN2627SEPNOV/7006SCN_SG_17165640.git
cd 7006SCN_SG_17165640
git config user.name "Sridhar Gude"
git config user.email "THE-EMAIL-ON-SRIDHARS-GITHUB-ACCOUNT"
mkdir notebooks
mkdir results
```
A browser window will ask you to sign in to GitHub. Use Sridhar's account.

**Step 5: Put the files in place**
In File Explorer, open `C:\Users\<name>\7006SCN_SG_17165640` and put:
- `Task1.ipynb` into the `notebooks` folder.
- `task1.json` into the `results` folder.
- `README.md` in the main folder.

**Step 6: Commit and push**
Back in PowerShell, run these one by one:

```
git add notebooks/Task1.ipynb
git commit -m "[Task1] add Task1 notebook with load, cleaning and pipeline - 20,332,093 rows loaded in 7.4s"
git add results/task1.json
git commit -m "[Task1] save task1.json with pool ref, size and cluster config - 7-stage pipeline, 551 features"
git add README.md
git commit -m "[Task1] add README with structure and run steps - Task 1 marked done"
git branch -M main
git push -u origin main
```
Don't use `git add .` because it could add large files.

**Step 7: Get the hashes**
```
git log --oneline
```
Each line starts with 7 letters and numbers, like `a1b2c3d`. That is the hash. Copy the first 7 characters only. The oldest commit is at the bottom of the list.

**Step 8: Type the hashes into the Word sheet**
Open the filled Word file and replace each yellow `hash` with the 7 characters, with no brackets:
- Section 1.1, 1.3, EP1 and the Process Note: the hash of the **first** commit (the notebook).
- Section 1.2: the hash of the **second** commit (`task1.json`).

**Step 9: Fill in the repo details in the Word sheet**
- GitHub repository URL: `github.com/7006SCN2627SEPNOV/7006SCN_SG_17165640`
- Repository set to Private: **Yes**
- Task 1 Notebook (GitHub) link: https://github.com/7006SCN2627SEPNOV/7006SCN_SG_17165640/blob/main/notebooks/Task1.ipynb

**Step 10: Check it worked**
- Open the repo URL above while logged in. You should see a "Private" label next to the name.
- Open the notebook link and scroll. You should see the outputs and the "Fig. T1.x" labels.
- Open the repo link in a private (incognito) window. You should get a "404 / not found" page. That confirms it is private.

---

## Things to watch for
- **Weeks:** Task 1 needs at least one commit in Week 1 and one in Week 2. Making all three today only counts if today falls in the right weeks. Check the teaching calendar on Aula, and never change commit dates.
- **Repo name:** the brief gives two formats (`Username_SID` in one place and `7006SCN_<Initials>_<SID>` in another). The second one is the "required" one, and it's what I used. If the repo already exists with a different name, keep that name.
- **Kaggle:** it deletes files when the session ends, so do Step 1 before closing anything.
- **If `git push` is rejected,** copy the error message and send it to me.

> File: [/mnt/user-data/outputs/README.md](https://claude.ai/api/organizations/afcc61c1-790c-471f-97f8-f2613e3a76b5/conversations/3618d6dd-e0ac-45d3-9629-5b20892a234f/wiggle/download-file?path=%2Fmnt%2Fuser-data%2Foutputs%2FREADME.md)

## User:

> 10/16/2026 22:50:28

ok now recall everything end to end what we did so far and what we need to do?

## Assistant:

> 10/16/2026 22:50:49

> Weighing whether to save coursework details given identity mismatch.
>
> - Weighing whether to save coursework details given identity mismatch.
> - Updating memory
> - **Done**

Here is the full picture of Task 1 so far, and what is still left.

## What we did

**1. Understood the assignment**
- Module 7006SCN, a report on a big-data ML problem done in PySpark. It is due Monday 26 Oct 2026, 6pm UK time, which is 11:30pm India time.
- There are four tasks: Task 1 (Weeks 1-2), Task 2 (Weeks 3-4), Task 3 (Week 5) and Task 4 (Week 6, which includes Tableau).
- Marks are split into 40 for compliance (checked from your repo and JSON files) and 60 for academic judgement.

**2. Matched your dataset**
- Catalogue No. 33: NYC TLC Yellow Taxi Trip Records, Jan-Jun 2024.
- I framed the problem as binary classification: **cash vs card**.
- I explained the leakage risk: `tip_amount` and `total_amount` give away the answer, so they are removed.

**3. Built the Task 1 notebook**
- It covers the declaration, SparkSession, loading the six files, schema, row and column counts, cleaning, a train/test split, a 7-stage pipeline and the evidence pack.
- You ran it on Kaggle. Key results:
  - 20,332,093 rows and 19 columns.
  - 0.32 GiB as Parquet.
  - 17,577,524 rows kept.
  - Cash is 14.96% of kept trips.
  - 551 features.

**4. Improved it after reading your outputs**
- Found that the Parquet size is under the 1 GiB rule, so I added a CSV size check.
- Found that the missing values are all 9.72%, matching flex fare trips, so I added two gap-check cells.
- Added figure labels (Fig. T1.1 to T1.7 and EP1) above each output.
- Fixed the SID (17165640) and the pool reference ("No. 33").

**5. Filled the Word answer sheet (Task 1 only)**
- Sections 1.1, 1.2, 1.3, the EP1 caption, the process note, references, student details and the AI declaration row.
- The text is about 440 words.
- Yellow items still need filling.

**6. Wrote the GitHub steps for Windows,** so your friend can commit and push with the right messages.

## What is still left

**Week 1 / Task 1, in order**
1. Run the new notebook cells (T1.6, T1.7a, T1.7b, the JSON cell and the EP1 cell) and save the notebook with outputs.
2. Send me the T1.6 and T1.7 outputs. I'll check the report wording and fill the CSV size in.
3. Download `Task1.ipynb` and `task1.json` from Kaggle before the session ends.
4. Make the private repo (or find it) inside `7006SCN2627SEPNOV`, and commit and push using the Windows steps.
5. Copy the commit hashes into the Word sheet. Add the GitHub repo URL, "Private: Yes" and the notebook link.
6. Take the EP1 screenshot from the last cell and paste it into the Word sheet.
7. Email Dr Stamou about the 1 GiB size question.
8. Fill in the MS Forms checklist if you haven't.

**Week 2:** make at least one more Task 1 commit, and finish the AI declaration and Prompt Log entries for Task 1.

**Later:** Tasks 2, 3 and 4 (models, Spark UI and explainability, Tableau). They also need notebooks, JSON files, commits and Word sections. The final report goes to Turnitin by 26 Oct, and the total must stay within 1,320 words.

## Open risks to check

- **Commit weeks:** I don't know which teaching week it is. Task 1 needs commits in Weeks 1 and 2, and dates can't be changed.
- **Dataset size:** 0.32 GiB on disk against a 1 GiB rule.
- **Which Word sheet:** the generic one the brief names, or the Classification one I filled.
- **Repo name:** the brief gives two formats. I used `7006SCN_SG_17165640`.
- **Kaggle session:** files in `/kaggle/working` vanish when the session ends, so download them first.

If you want to continue, send me the new T1.6 and T1.7 outputs and I'll finalise the Task 1 wording.

## User:

> 10/16/2026 22:58:15

i finished week1 submssion now tell me what for week2 finish it end toe nd clelallry as asked proeprly same tone same style

## Assistant:

> 10/16/2026 22:59:17

> Planning how to share week two code without overwriting their files.
>
> - Planning how to share week two code without overwriting their files.
> - Write Week 2 notebook cells for Task 1 (not run) and syntax-check
> - Presenting file(s)...
> - **Done**

Here is the Week 2 plan for Task 1. The code is ready, but I can't run it, so a few numbers in the text have to come from your run.

## What Week 2 covers

The brief ties Week 2 to partitioning and sampling, dimensionality reduction, and EDA at scale. Week 1 only mentioned PCA, partitioning and drift in words. Week 2 backs those with real results from your data, which is what lifts the judgement mark. It also gives you the Week 2 commits the brief requires.

## Step 1: Add the new cells to your notebook

I wrote `Task1_week2_cells.py`. Open it in Notepad. Each "CELL" block becomes one new cell at the **end** of your Kaggle notebook, after the EP1 cell:

- **Cell 1 (Markdown):** the heading and figure labels.
- **Cell 2 (Code):** Fig. T1.8. It checks whether the training partitions are even, and builds a 5% stratified sample for tuning in Task 2.
- **Cell 3 (Code):** Fig. T1.9. A PCA check on the 14 numeric columns.
- **Cell 4 (Code):** Fig. T1.10. Cash share by month, a drift check.
- **Cell 5 (Code):** adds the Week 2 results to `results/task1.json`.

Run them in order in the same session, since they need the Week 1 variables. Use the same session as before. If it restarted, Run All first.

## Step 2: Send me the outputs

Please send me these, plus the two you still owe me from Week 1:

- **T1.8:** partition stats and the full vs sample profile.
- **T1.9:** how many components reach 95%.
- **T1.10:** the cash share by month.
- **T1.6** (CSV size) and **T1.7a/b** (the gap checks) from Week 1.

I'll confirm the wording and fill in the numbers.

## Step 3: Update Task 1.3 in the Word sheet

I'm not regenerating the Word file, so I don't overwrite anything you already pasted. Replace the "Why must the stages run in this order" answer with this, then fill the yellow numbers:

> Flags come before imputation, or the fill hides the gaps. Indexing precedes one-hot, and assembling precedes scaling. I fitted on the training split only, so test rows never shape the median or scaling. I rejected PCA: the 14 numeric columns need **[K]** components for 95% of the variance (Fig. T1.9), so little is saved. Cash share moves from **[LOW]**% to **[HIGH]**% across months (Fig. T1.10), so I will test drift in Task 3.

That raises Task 1 to about 465 words. Keep Tasks 2 to 4 tight to stay under 1,320 overall.

## Step 4: Commit and push (Week 2)

The commands are the same as before, from the repo folder in PowerShell:

```
git add notebooks/Task1.ipynb
git commit -m "[Task1] add stratified 5% sample and partition check - cash share [S]% vs [F]% full"
git add notebooks/Task1.ipynb results/task1.json
git commit -m "[Task1] add PCA check and cash share by month - [K] of 14 components for 95% variance"
git push
```
Replace the bracketed numbers with real values from your outputs. Then run `git log --oneline` and copy the new hash into Section 1.3 of the Word sheet, so the sheet points to the commit that produced the PCA and drift evidence.

## Step 5: Finish the Word sheet

1. The EP1 screenshot, taken after re-running the last cell.
2. All yellow `hash` fields filled for Task 1.
3. The CSV size in the Volume row (the yellow cell).
4. The GitHub repo URL, "Private: Yes", and the Task 1 notebook link.
5. The AI-Use Declaration: the number of prompts, the Prompt Log, and your signature.
6. The process note. Check it is still true, and edit it if something else went wrong this week.

## Step 6: Admin before Week 2 ends

- Fill in the MS Forms checklist if you haven't, and paste the signed screenshot into the Word sheet.
- Email Dr Stamou about the 1 GiB size question if you haven't yet.
- Open the repo in a private window. It should show "not found" (private), and the notebook link should open while you're logged in.

## What stays open

I haven't seen your T1.6 or T1.7 outputs yet, so the Veracity wording is still an assumption. The commit weeks, the dataset size rule, and which Word sheet to submit are also still unconfirmed.

Task 2 starts in Week 3, and the 5% sample you save today will make tuning faster. Don't start Task 2 until Task 1 is committed and checked.

> File: [/mnt/user-data/outputs/Task1_week2_cells.py](https://claude.ai/api/organizations/afcc61c1-790c-471f-97f8-f2613e3a76b5/conversations/3618d6dd-e0ac-45d3-9629-5b20892a234f/wiggle/download-file?path=%2Fmnt%2Fuser-data%2Foutputs%2FTask1_week2_cells.py)

## User:

> 10/16/2026 23:00:01

gety me all what i have to subm,it

## Assistant:

> 10/16/2026 23:00:11

> Listing all final submission items and their required locations.
>
> - Listing all final submission items and their required locations.
> - **Done**

Here is everything that has to be handed in for the whole assignment, and where each piece goes.

## Deadline

Monday **26 Oct 2026, 6pm UK time**, which is **11:30pm India time**. The extra 24 hours to 27 Oct is only for technical problems, and late work scores zero. Submit early.

## 1. On Turnitin (Aula): one Word file

One `.docx`, the answer sheet. The brief names `7006SCN2627SEPNOV_Report_AnswerSheet_Dr_KStamou_v1.docx`. I filled the Classification version, so check with Dr Stamou or on Aula which one to hand in. It must contain:

- **Student Details:**
  - Name and SID (17165640).
  - Pool reference (No. 33).
  - Dataset name and source.
  - GitHub repo URL.
  - "Private: Yes".
  - Tableau Public URL.
  - Total word count (**1,200 ±10%, so 1,320 at most**).
- **Signed checklist screenshot** from the MS Forms checklist.
- **AI-Use Declaration**, plus your signature.
- **Task 1:** sections 1.1, 1.2, 1.3, EP1 (the evidence image) and the process note.
- **Task 2:** sections 2.1, 2.2, 2.3, EP2 and the process note.
- **Task 3:** sections 3.1, 3.2, 3.3 and the process note.
- **Task 4:** sections 4.1 (contact sheet of the four dashboards), 4.2 and the process note.
- **Four notebook links**, one per task.
- **The Tableau Public link.**
- **A commit hash on every block,** 7 characters, from `git log --oneline`.
- **References.**
- **Prompt Log** (your AI prompts, in order).

## 2. On GitHub: one private repo

- **Location and name:** inside the module organisation `7006SCN2627SEPNOV`, named `7006SCN_SG_17165640` (or the existing repo's name).
- **Contents:**
  - `notebooks/Task1.ipynb`, `Task2.ipynb`, `Task3.ipynb` and `Task4.ipynb`, all with their outputs saved.
  - `results/task1.json` to `task4.json`.
  - `README.md`, kept up to date.
- **Commits:** at least **3 per task, 12 in total**.
  - Format: `[TaskN] verb object - reason or measured result`.
  - At least one commit per task must include a measured value.
  - Tasks 1 and 2 each need a commit in both of their weeks. Tasks 3 and 4 need all commits in their own week.
- **Visibility:** private until results are released.
- Don't commit the data or models folders.

## 3. On Tableau Public: one workbook

- Four dashboards: data quality and pipeline monitoring, model performance and feature importance, business insights, and scalability and cost.
- The link must work when opened by someone else.

## 4. On MS Forms: the checklist

The "7006SCN CW-Project_Checklist". The brief wants it by the end of Week 2. Paste the signed screenshot into the Word sheet.

## What happens if something is wrong

| Problem | Result |
|---|---|
| GitHub or Tableau link doesn't open | whole assessment marked **0** |
| Repo outside the module organisation | capped at **20%** (fail) |
| Repo public at the deadline | **minus 10 marks** |
| Wrong dataset | capped at **30-39%** (fail) |
| AI use not declared | academic conduct case |
| Report over 1,320 words | marker reads only up to the limit |

## Where you stand

- **Task 1:** notebook committed in Week 1, text drafted, Week 2 steps in progress.
- **Tasks 2 to 4:** not started.
- **Still open:** the 1 GiB size question, which Word sheet to hand in, the commit weeks, and sending me the T1.6, T1.7 and Week 2 outputs.

The Word file is the only thing you upload to Turnitin. The notebooks, JSON files and README stay on GitHub, and the marker reads them from the links in your Word file.

## User:

> 10/23/2026 12:42:28

ok now i am really in hurrry i missed week2 todya i will submit clellalry give me eveyrhting like last time simple endf tpo  end full dfetailed with commit steps tooo propelry

## Assistant:

> 10/23/2026 12:45:12

> Checking fairness gaps and budgeting remaining write-up word counts.
>
> - Checking fairness gaps and budgeting remaining write-up word counts.
> - Dump Task 2-4 structure of the answer sheet
> - **Done**

## User:

> 10/23/2026 17:39:13

Continue

## Assistant:

> 10/23/2026 17:41:07

> Evaluating model stability and computing SHAP feature importance.
>
> - Building out multiple task notebooks and accompanying documentation.
> - Write shared setup code for Tasks 2-4 and syntax-check
> - Build Task 2 notebook (not run) and syntax-check
> - Reinstall nbformat and build Task 2 notebook
> - Evaluating model stability and computing SHAP feature importance.
> - Build Task 3 notebook (not run) and syntax-check
> - Presenting file(s)...
> - **Done**

> File: [/mnt/user-data/outputs/notebooks/Task2.ipynb](https://claude.ai/api/organizations/afcc61c1-790c-471f-97f8-f2613e3a76b5/conversations/3618d6dd-e0ac-45d3-9629-5b20892a234f/wiggle/download-file?path=%2Fmnt%2Fuser-data%2Foutputs%2Fnotebooks%2FTask2.ipynb)

> File: [/mnt/user-data/outputs/notebooks/Task3.ipynb](https://claude.ai/api/organizations/afcc61c1-790c-471f-97f8-f2613e3a76b5/conversations/3618d6dd-e0ac-45d3-9629-5b20892a234f/wiggle/download-file?path=%2Fmnt%2Fuser-data%2Foutputs%2Fnotebooks%2FTask3.ipynb)

Powered by Claude Exporter (https://www.ai-chat-exporter.net)
