# Summary discussion on Population genomics, population structure and demography

# Papers discussed:

***Rougemont and Bernatchez 2018***. The demographic history of Atlantic salmon (Salmo salar) across its distribution range reconstructed from approximate Bayesian computations. Evolution: 72-6: 1261–1277.
***Moreno-Mayar et al. 2018***. Early human dispersals within the Americas. Science: 362, eaav2621.

We started the discussion by summarizing the article by Rougemont and Bernatchez. Authors re-analyzed previous global genetic data (> 2,000 samples) of the Atlantic salmon. To understand patterns of population structure and overall demographic history the authors used three main analytical tools: 1) admixture modeling, 2) geo-genetic assignments, 3) Common ancestor graphs and 4) approximate Bayesian computation modelling. Authors conclude that populations are well differentiated regionally (e. g. North American populations different than European ones) and some minor genetic differences exist among populations within regions. ABC suggested that the best model of demographic evolution is one that includes a signature of genetic divergence followed by a more recent time of gene flow among populations (i. e. isolation with secondary contact). The group discussed the variation in levels of differentiation among different kinds of SNPs. The data also revealed the intriguing case that most of the migration is happening from populations in North America that surprisingly have the lowest genetic variation, to populations in Europe with highest genetic variation. One explanation for this may be that the colonization of North American habitats occurred by the establishment of few founder individuals.

Some topics that involve discussion included:

PCA: A clear representation of the data without much assumptions or any modeling. Clear patterns of differentiation between North America and Europe along PC1, which also had the largest amounts of variation. It was also clear the lower levels of genetic variation in North American populations when compared to those sampled in Europe. PC3 was associated with genetic variation associated with the differentiation of the Iceland population.

Admixture graphs: The group thought it was a clear and straight forward representation of the genetic data. The graph depicted some clearly differentiated populations such as the “Baltic” or “Iceland” and some admixed ones such as “Barents-White” or “Spain”. The weird pattering of individuals does not the reflect their distribution in the field by and ad hoc organization based on their admixture coefficient.  

Common ancestor graphs: Also known as tress from TreeMix. Results recapitulated those from PCA and admixture plots. The migration bands (in red or yellow) show some level of admixture within and across continents, mostly from Europe to North America.

Geo-genetic maps: As PCAs provided a spatial distribution of genetic variation, but unlike PCAs, it inferred 2D position of populations. Similar to TreeMix, it provides migration bands across populations. In contrast to TreeMix results, most of the migration occurred from North America to Europe.  

The group have a discussion about ABC. The main idea behind this modeling approach is to: 1) Generate models to be tested (isolation without migration, isolation with migration, etc ..), 2) estimate parameters from the empirical data (e. g. Salmon data) to stablish priors for the parameters, 3) simulate genealogies under the proposed model, 4) estimate summary statistics (parameters) for the simulated data, 5) compare empirical with simulated data, 6) redo the process from 1 to 6 until you generate enough points (accepted points) to generate a distribution,  7) repeat the process with the next model and repeat the process until you have evaluated all the models. Compare fit of the empirical data to each of the models, rank the models and choose the one with the highest fit. https://www.annualreviews.org/doi/10.1146/annurev-ecolsys-110617-062431

Authors using ABC found a secondary contact the best demographic model. In brief, populations initially diverged in isolation for approximate one million year and then started mixing. Modeling suggest most of the mixing occurred from populations to European ones. The group found a bit problematic making sense of all > 150 models that contained all comparisons. It was also unclear whether the multiple comparison needs a correction technique.

Genic view of speciation: A model developed by Wu to illustrate the gradual progression of genomic differentiation during speciation. Initially populations only diverge a very few areas in the genome (often associated with adaptation to different habitats) and then divergence is built around those areas until divergence is rampant across the whole genome. https://onlinelibrary.wiley.com/doi/full/10.1046/j.1420-9101.2001.00335.x

Divergence hitchhiking: A process in which genetic divergence occurs across the genome due to strong divergent selection. Some parts of the “diverging” piece are not under selection nonetheless they hitchhike along with the selective SNP/locus.

Selective sweep: A location in the genome with a SNP/locus generally fix as a result of natural selection and the combined effect of reduced variation around that locus. Because such areas a low in genetic variation, they can be thought of as areas of small population size with higher effects of drift.

Background selection: Removal of non-deleterious alleles given their proximity to deleterious ones. It also reduces genetic variation.

The group then enter into a discussion of the Moreno-Maya et al. (2018) article. The group thought this was a hard to read article, yet the application of F-statistics was ingenious and allow for fine-detailed characterization of the migration patterns of humans in North America. F-statistics allows calculation of the magnitude of admixture among populations and those different levels of mixing can be summarized in qhGraphs. Here are slinks to get more familiar with F-statistics:
http://www.genetics.org/content/genetics/192/3/1065.full.pdf
https://github.com/DReichLab/AdmixTools/blob/master/README.3PopTest
https://gaworkshop.readthedocs.io/en/latest/contents/06_f3/f3.html
https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1005703













[prada@edu](mailto:prada@uri.edu)

[Slack](https://bio-594.slack.com/)

Level: Graduate, Upper undergraduate

Semester: Spring 2019

When and where do we meet:

    Tuesdays    9 - 10:30 AM CBLS 435

    Thursdays   9 - 10:30 AM CI 200




## Software License
All the contents of this course (e.g. all my notes) are under an [open-source license](https://en.wikipedia.org/wiki/Open_source) ([BSD](https://en.wikipedia.org/wiki/BSD_licenses)).


## Course Materials
Papers from the primary literature. All material will be provided via [GitHub](https://github.com/pradac/BIO594_2019). We will communicate info about the class through [Slack](https://bio-594.slack.com/).


## Course Description
The course provides an in depth discussion of the current research and possibilities to answer long-standing and new questions in evolution and ecology using genomic tools. The course will discuss articles and reviews with a genomic perspective related to: Population and Conservation Biology; Natural Selection and Adaptation, Functional Genomics; Trait Evolution; Epigenetics and Phenotypic Plasticity, Symbiosis, Hybridization; Community Ecology and Metabarcoding; and Speciation. The genomic revolution, fueled by the easy to sequence RNA and DNA has  opened the possibility of new research areas. We will examine how genomics tools that are emerging and changing rapidly are transforming biology.


## Learning Objective
The goal is to recognize the diverse possibilities that genomics allow to answer evolutionary and ecological questions. Together we will enrich our conceptual understanding of genomics and the types of analysis that can be performed with genome scale data. At the end of the course participants will be able to design experiments to answer their own questions and provide a detailed map of the methodological steps needed to carry out a robust study using genomic tools.


## General course organization
The first week of the course will consist on a review of the major aspects of genomics. We will then embark in a rich discussion of different disciplines of biology that use genomic tools. We will discuss at least two articles per meeting (some weeks three). Two participants will lead each discussion, and everyone has to be fully prepared to discuss articles in detail and submit [here](https://github.com/pradac/BIO594_2019/tree/master/750-1000-Summaries) a 750-1000-word summary of the topic for that week before the discussion starts. EVERYONE has to be prepared to be able to lead the discussion if I ask for it (even if you decide to not submit a summary for that week). EVERYONE has to read the papers in enough detail that are able to discuss information in SUPPLEMENTARY material. This is ESSENTIAL to truly grasp the info in papers. It is the responsibility of the leaders to maintain a fluid conversation and bring new aspects into the discussion. The leaders will have to prepare a ~1,000-2,000 word summary of the discussion and submit it within 48 hours after the discussion. I will lead the first discussion.

By the end of the class, and once students acquire some understanding of the possibilities to answer ecological and evolutionary questions with genomic tools, participants will write a research proposal that will be evaluated by their peers in review panels.  Reviewers and panelists will provide detailed criticisms to authors and authors will have one week to address criticism and resubmit their proposals. Upon resubmission, the authors have to write a one page letter highlighting the major issues found by reviewers and panelists and how they addressed the problems. Participants are evaluated both on the originality and effort to develop their own proposals as well as their detailed criticisms when acting as reviewers and or panelists.


### Discussion and Lecture Topics

Code    |Date	|Topic	|Name
----|----|----------------------------|--------------------------
Intro| Jan 24 (Thu)	|**Introduction** [Holenhole et al. 2018](https://github.com/pradac/BIO594_2019/blob/master/Papers/Holenhole_etal_2018.pdf)	|Carlos
No Class | Jan 29 (Tue)	|No class	|----
1	|Jan 31 (Thu)	|**Population genomics, population structure and demography** [Schraiber_Akey 2015](https://github.com/pradac/BIO594_2019/blob/master/Papers/1-PopulationGenomicsStructure/Schraiber_Akey_2015.pdf)	|Carlos
1a	|Feb 5 (Tue)	|DISCUSSION [Rougemont et al. 2018](https://github.com/pradac/BIO594_2019/blob/master/Papers/1-PopulationGenomicsStructure/Rougemont_etal_2018.pdf),  [Moreno-Mayar et al. 2018](https://github.com/pradac/BIO594_2019/blob/master/Papers/1-PopulationGenomicsStructure/Moreno-Mayar_etal_2018.pdf) & 	 [Suppl](https://github.com/pradac/BIO594_2019/blob/master/Papers/1-PopulationGenomicsStructure/Moreno-Mayar_etal_2018_SM.pdf) | Carlos
2	|Feb 7 (Thu)	|**Seascape/Landscape Genomics** [Fu_Akey 2013.pdf](https://github.com/pradac/BIO594_2019/blob/master/Papers/2-Landscape_Genomics/Fu_Akey_2013.pdf) & [Rellstab et al. 2015.pdf](https://github.com/pradac/BIO594_2019/blob/master/Papers/2-Landscape_Genomics/Rellstab_etal_2015.pdf)	|Amy
2a	|Feb 12 (Tue)	|DISCUSSION	[Brauer et al 2016.pdf](https://github.com/pradac/BIO594_2019/blob/master/Papers/2-Landscape_Genomics/Brauer_etal_2016.pdf), [Hancock et al. 2012.pdf](https://github.com/pradac/BIO594_2019/blob/master/Papers/2-Landscape_Genomics/Hancock_etal_2012.pdf) & [Suppl](https://github.com/pradac/BIO594_2019/blob/master/Papers/2-Landscape_Genomics/Hancock_etal_2012_SM.pdf) |Amy/Jennifer
3	|Feb 14 (Thu)	|**Correlation between Phenotype and Genotype** [Weigel_Nordborg_2015](https://github.com/pradac/BIO594_2019/blob/master/Papers/3-Correlations_between_phenotypes_Genotypes/Weigel_Nordborg_2015.pdf) & [Mallarino_Abzhanov_2012](https://github.com/pradac/BIO594_2019/blob/master/Papers/3-Correlations_between_phenotypes_Genotypes/Mallarino_Abzhanov_2012pdf)	|Maggie
3a	|Feb 19 (Tue)	|DISCUSSION	[Nadeau_etal_2016.pdf](https://github.com/pradac/BIO594_2019/blob/master/Papers/3-Correlations_between_phenotypes_Genotypes/Nadeau_etal_2016.pdf), [Barret_etal_2018.pdf](https://github.com/pradac/BIO594_2019/blob/master/Papers/3-Correlations_between_phenotypes_Genotypes/Barret_etal_2018.pdf), [Suppl](https://github.com/pradac/BIO594_2019/blob/master/Papers/3-Correlations_between_phenotypes_Genotypes/Barrett_SM.pdf) & [Bosse_etal_2016](https://github.com/pradac/BIO594_2019/blob/master/Papers/3-Correlations_between_phenotypes_Genotypes/Bosse_etal_2016.pdf)|Maggie/Matias
4	|Feb 21 (Thu)	|**Physiology and Gene Expression** [Ritchie_etal_2015](https://github.com/pradac/BIO594_2019/blob/master/Papers/4-Physiology-RNSseq/Ritchie_etal_2015) & [Conesa_etal_2016](https://github.com/pradac/BIO594_2019/blob/master/Papers/4-Physiology-RNSseq/Conesa_etal_2016.pdf)	|Cassie
4a	|Feb 26 (Tue)	|DISCUSSION	[Bernal_etal_2018](https://github.com/pradac/BIO594_2019/blob/master/Papers/4-Physiology-RNSseq/Bernal_etal_2018.pdf), [Lohman_etal_2018](https://github.com/pradac/BIO594_2019/blob/master/Papers/4-Physiology-RNSseq/Lohman_etal_2018.pdf) & [Walworth_2016](https://github.com/pradac/BIO594_2019/blob/master/Papers/4-Physiology-RNSseq/Walworth_2016.pdf)|Cassie/Amy
5	|Feb 28 (Thu)	|**Adaptive phenotypic plasticity and epigenetics**	[Bossdorf_et_al_2008](https://github.com/pradac/BIO594_2019/blob/master/Papers/5-Plasticity_epigenetics/Bossdorf_et_al_2008.pdf), [Richards_etal_2017](https://github.com/pradac/BIO594_2019/blob/master/Papers/5-Plasticity_epigenetics/Richards_etal_2017.pdf) & [Donelson_etal_2017](https://github.com/pradac/BIO594_2019/blob/master/Papers/5-Plasticity_epigenetics/Donelson_etal_2017.pdf)|Kevin
5a	|Mar 5 (Tue)	|DISCUSSION [Ghalambor2015](https://github.com/pradac/BIO594_2019/blob/master/Papers/5-Plasticity_epigenetics/Ghalambor2015.pdf), [Ryu_etal_2018](https://github.com/pradac/BIO594_2019/blob/master/Papers/5-Plasticity_epigenetics/Ryu_etal_2018.pdf) & [Lieu_etal_2018](https://github.com/pradac/BIO594_2019/blob/master/Papers/5-Plasticity_epigenetics/Lieu_etal_2018.pdf)	|Kevin/Elaine
6	|Mar 7 (Thu)	|**Developmental biology** [Davidson_2006](https://github.com/pradac/BIO594_2019/blob/master/Papers/6-Developmental_Biology/Davidson_2006.pdf) & [Mallarino_Abzhanov_2012](https://github.com/pradac/BIO594_2019/blob/master/Papers/6-Developmental_Biology/Mallarino_Abzhanov_2012.pdf)	|Jennifer
No Class | Mar 11- 14	|No class - Spring Break	|----
6a	|Mar 19 (Tue)	|DISCUSSION	[Israel_etal_2016](https://github.com/pradac/BIO594_2019/blob/master/Papers/6-Developmental_Biology/Israel_etal_2016.pdf) & [Manceu_etal_2011.pdf](https://github.com/pradac/BIO594_2019/blob/master/Papers/6-Developmental_Biology/Manceu_etal_2011.pdf)|Jennifer/Erin
7	|Mar 21 (Thu)	|**Symbiosis -The genomics of species interactions** [Gilbert_etal_2015](https://github.com/pradac/BIO594_2019/blob/master/Papers/7-Symbiosis/Gilbert_etal_2015.pdf)	|Ian
7a	|Mar 26 (Tue)	|DISCUSSION [Belcaid_etal_2018](https://github.com/pradac/BIO594_2019/blob/master/Papers/7-Symbiosis/Belcaid_etal_2018.pdf) & [Li_etal_2018](https://github.com/pradac/BIO594_2019/blob/master/Papers/7-Symbiosis/Li_etal_2018.pdf)	|Ian/Maggie
8	|March 28 (Thu)	|**Speciation and hybridization**	[Feder_etal_2013](https://github.com/pradac/BIO594_2019/blob/master/Papers/8-Hybridization_Speciation/Feder_etal_2013.pdf) & [Seehausen_etal_2014](https://github.com/pradac/BIO594_2019/blob/master/Papers/8-Hybridization_Speciation/Seehausen_etal_2014.pdf) |Matias
No Class | Apr 1- 7	|No class - Carlos in Mexico	|---
8a	|Apr 9 (Tue)	|DISCUSSION	[Edelman_et_al_2018](https://github.com/pradac/BIO594_2019/blob/master/Papers/8-Hybridization_Speciation/Edelman_et_al_2018.pdf) & [Kautt_etal_2017](https://github.com/pradac/BIO594_2019/blob/master/Papers/8-Hybridization_Speciation/Kautt_etal_2017.pdf)|Matias/Emma
9	|Apr 11 (Thu)	|**Climate change and conservation biology**	 [Hendricks_2018](Hendricks_2018.pdf) |Emma
9a	|Apr 16 (Tue)	|DISCUSSION and  proposals due  [Bay_et_al_2018](Bay_et_al_2018.pdf) & [Barret_etal_2018](Barret_etal_2018.pdf)	|Emma/Erin
10	|Apr 18 (Thu)	|**Community ecology eDNA and microbial genomics** [Deiner_et_al_2017](Deiner_et_al_2017.pdf) & [knight_etal_2018](knight_etal_2018.pdf)	|Elaine
No Class | April 23 (Tue)	|No class -Carlos in Buffalo- but proposal reviews are due	|----
10a	|Apr 25 (Thu)	|DISCUSSION	 [Boussarie_etal_2018](Boussarie_etal_2018.pdf) & [Sunagawa_etal_2015](Sunagawa_etal_2015.pdf)|Elaine/Cassie
Panel | Apr 30 (Tue)	|**Panel discussion -Summit summaries**	| Ian
Panel | May 2 (Thu)	|**Panel discussion -Summit summaries**	| Kevin
  11 | May 10 (Fri) | **Lat day to submit revised proposals** |


### Grading

In accordance with the URI grading policy, grades will be assigned using an A-F scale and the +/- system.

Item                                               | # of assignments  | % of grade
--------| -------------   | ----------------
[Class participation ](#class-participation)          | 20                   | 15%
[Per class summaries](#Per-class-summaries)                       | 5                    | 25% (5% each)
[Research proposal](#Research-proposal)                        | 1                | 40% (20%, 10%, 10%)
[Presentation ](#Research-proposal)                        | 1                | 20%
Total                                           |                     | 100%


### Grading Scale

Points        | Letter Grade Assigned
--------------|----------------------
900-1000       | A+
870-899        | A
830-869        | A-
800-829        | B+
770-799        | B
730-769        | B-
700-729        | C+
670-699        | C
630-669        | C-
600-629        | D+
550-599        | D-
< 550          | F


### Class participation
To earn this portion of the grade students must actively contribute to all class discussions. Essential to read articles in detail including supplementary info.

### Per class summaries
Before each week’s discussion, participants will have to submit a 750-1000-word summary (excluding references if you use them at all) of the topic being assigned for that day. Each participant has to submit at least five summaries (5% each). The participant chooses which topics to submit summaries for. It is expected that given feedback by the instructor students improve their written summaries overtime.

### Research proposal
This will involve writing a five-page proposal (excluding references) that seeks to answer an ecological or evolutionary question with genomic tools. The five pages are single space in Arial 11 and 1” margins. The proposal has to contain at least two aims/objectives a broader impact aspect and an intellectual merit. At least one of the objectives has to have a “genomic” approach. I advise you to have the first page as the project summary. You are welcome to use the structure that you wish to convince the readers why your research should be funded. The structure of the proposal is not important but convincing your peers that your proposal is the best is the aim. Writing the proposal itself accounts for 20%  and addressing the panel and reviewer’s comments accounts for 10%. Providing detailed criticism of the proposals when acting as reviewers or fully engaging in discussions during panels and writing panel summaries accounts for the other 10% of the grade. Here you can see examples of [proposals](https://www.ogrants.org). I have also included one 5-page example within the proposals' folder.

### Presentation
Each student will have a presentation on a subject. The aim of the presentation is to introduce the general subject that we will be discussing in the following class. The presentation must contain all the critical vocabulary and concepts needed to understand the papers that we will be discussing in the subsequent meeting. For each subject there is at least one review paper that contains the baseline info needed to develop the presentation. The review paper is MANDATORY for non-presenters too. Presenters should read also the upcoming discussion papers to make sure that they include all the necessary vocabulary in those papers in their presentations. The presentation is a key aspect of the discussion process because it will allow us to get a deeper understanding of the papers to be discussed. The presentation should be at least 30 min and no more than 60 minutes. Students are welcome to implement any kind of teaching technique to interact with all participants and transmit all the key concepts. Participants are welcome to bring all questions, especially basic questions so that the presenter or another person can answer them. The presenter has to schedule at least one appointment with me a week (seven days) before the presentation. You are welcome to meet with me more times if you need to. I encourage you to meet with me twice once to get a general idea of what you should include and then a second one with the presentation to improve it. Here are info about [presentations](http://gradschool.unc.edu/academics/resources/postertips.html#prez) and [this.](https://www.towson.edu/cla/departments/interdisciplinary/grad/hr/documents/guidelines_for_student_presentations_in_class.pdf)


### Surviving links to MarkDown and GitHub
As a Text Editor I have used [Text Wrangler](http://www.barebones.com/products/textwrangler/) and [Atom](https://atom.io)

To get familiar on how to comment and add info to the class please visit:
* [Github Guide](https://guides.github.com/activities/hello-world/) [See this too](https://swcarpentry.github.io/git-novice/)
* [Markdown Guide](https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

### Adding info to this class repository
First create an account in [GitHub](https://github.com). Once you have the account do the following:

`git config --global user.email "your-email@uri.edu"`
then
`git config --global user.name "Your Name"`

Make a folder called `repos`
`mkdir ~/repos`

Enter to that newly created folder: `cd repos`

Now, copy the class repository/folder: `git clone https://github.com/pradac/BIO594_2019`

You now have a directory called `BIO594_2019` and you can update it by `cd ~/repos/BIO594_2019` then `git pull`

You can propose changes to this repository by modifying or adding/deleting files locally and then pushing/uploading them to master project. See [this](https://help.github.com/articles/managing-files-using-the-command-line/)


### Do you need some help with your writing?
The Graduate Writing Center (Roosevelt 003) offers writing assistance to all URI grad students, in all disciplines. Trained tutors can assist you at any stage of the writing process, from brainstorming ideas to revising before submission. No matter your writing style or ability, GWC tutors can help you articulate your work more clearly. You can schedule a one-on-one appointment online at mywco.com/urigradwc, or visit the GWC’s website for more information. Visit early and visit often.

### Some other help
***Academic Skills and Strategies*** programs help students identify their individual planning and studying needs in this or any other course. They can teach you more effective ways of studying, planning, managing time and work, and how to deal with challenges like procrastination and motivation. Academic Skills Sessions are 30-minute, one-on-one appointments that students can schedule online by visiting the AEC on Starfish and making an appointment with Dr. David Hayes, the AEC’s academic skills development specialist. UCS160: Success in Higher Education is a one-credit course offered each semester to all undergraduates on learning how to learn and excel in college academics. For more information on these programs or for help making an appointment, visit [uri.edu/aec/academic-skills](uri.edu/aec/academic-skills) or contact Dr. Hayes directly at davidhayes@uri.edu  


### Academic Integrity
All students will be held to all rules and regulations concerning academic integrity according to URI’s [Student Handbook](http://web.uri.edu/studentconduct/student-handbook/). Cheating will not be tolerated and penalties may include a “zero” on an exam or assignment, which may result in failure (F) in the course. Any student who has knowledge of any violation of the rules and regulations in the Handbook is expected to bring that violation to the attention of the instructors. There will be no exceptions to this University policy. Honor your Education by adhering to all policies of Academic Integrity.  Please don’t test the system.

From the Provost:  *“Students are expected to be honest in all academic work. A student’s name on any written work, quiz or exam shall be regarded as assurance that the work is the result of the student’s own independent thought and study. Work should be stated in the student’s own words, properly attributed to its source. Students have an obligation to know how to quote, paraphrase, summarize, cite and reference the work of others with integrity. The following are examples of academic dishonesty.”*

Also from the provost:
*"
• Using material, directly or paraphrasing, from published sources (print or electronic) without appropriate citation
• Claiming disproportionate credit for work not done independently
• Unauthorized possession or access to exams
• Unauthorized communication during exams
• Unauthorized use of another’s work or preparing work for another student
• Taking an exam for another student
• Altering or attempting to alter grades
• The use of notes or electronic devices to gain an unauthorized advantage during exams
• Fabricating or falsifying facts, data or references
• Facilitating or aiding another’s academic dishonesty
• Submitting the same paper for more than one course without prior approval from the instructors."*

### Students with disabilities
Any student with a documented disability is welcome to contact Dr. Prada as early in the semester as possible so that we may arrange reasonable accommodations. As part of this process, please be in touch with Disability Services for Students Office at 330 Memorial Union, 401-874-2098 (http://www.uri.edu/disability/dss/)

### A note about course objectives and course evaluations
You will be asked to assess the following 12 learning objectives on the University course evaluations administered at the end of the semester. The objectives in bold are those that are most important in this course.

1. **Gaining factual knowledge (terminology, classifications, methods, trends)**
2. Learning fundamental principles, generalizations, or theories
3. **Learning to apply course material (to improve thinking, problem solving, and decisions)**
4. Developing specific skills, competencies, and points of view needed by professionals in the field most closely related to this course
5. **Acquiring skills in working with others as a member of a team**
6. Developing creative capacities (writing, inventing, designing, performing in art, music, drama, etc.)
7. Gaining broader understanding and appreciation of intellectual/cultural activity  
8. **Developing skills in expressing oneself orally or in writing**
9. Learning how to find and use resources for answering problems and solving problems
10. Developing a clearer understanding of, and commitment to, personal values
11. Learning how to analyze and critically evaluate ideas, arguments, and points of view
12. Acquiring an interest in learning more by asking questions and seeking answers
