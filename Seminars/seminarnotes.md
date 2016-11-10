###**Seminar 1 notes** <br/> 

1. What is large scale requirements engineering?
 Large scale requirement engineering refer to requiremnts engineering for large and complex systems e.g large industrial projects and where managing a complete set of interdependencies is practically unfeasible, but feasible among small bundles of requirements. Although, in some case the requiremnts number is so large that managing complete set of interdependencies among small bundles of requirements become unfeasible in practice.
 
2. What are the challenges in large scale requirements engineering?
 1. **Large number of requirements:** The larger the number of requiremnts the more complicated and difficult it will be to analyze, specify and manage.
 2. **Communication between teams problems:** Since the project require a lot of resources, the number of developers or teams could have adverse effect on communication and collaberation espicially if those teams are distributed.
 3. **Long implementaion time:** The time it takes to develop these project in some cases are so long that technology could change and public interest could shift.
 4. **Management of customer expectation:** Since projects with large-scale requirements are usually so large and complex it will be difficult to manage the customer expectation and communication the project progress to them.
 5. **Limited communication and face time with the customer:** Since the number of requirements is so large, eliciting all the requirements from the customers direcly will require a lot of time and effort.
 
3. What is the order of magnitude of the number of requirements we are discussing?  <br/> 
 The sources vary on the number of requirements to be considered large scale, although it does not only depend on the number of requirements it also depends on thier complexity and size of features they describe additionially, the system being developed is also a factor.

###**Reference**
* Wnuk, Krzysztof. "Understanding and supporting large-scale requirements management." LU-CS-LIC 2010 (2010).
* Bergman, Mark, John Leslie King, and Kalle Lyytinen. "Large-scale requirements analysis revisited: the need for understanding the political ecology of requirements engineering." Requirements Engineering 7.3 (2002): 152-171.
* Wnuk, Krzysztof, Björn Regnell, and Claes Schrewelius. "Architecting and coordinating thousands of requirements–an industrial case study." International Working Conference on Requirements Engineering: Foundation for Software Quality. Springer Berlin Heidelberg, 2009.
* Konrad, Sascha, and Michael Gall. "Requirements engineering in the development of large-scale systems." 2008 16th IEEE International Requirements Engineering Conference. IEEE, 2008.
* Regnell, Björn, Richard Berntsson Svensson, and Krzysztof Wnuk. "Can we beat the complexity of very large-scale requirements engineering?." International Working Conference on Requirements Engineering: Foundation for Software Quality. Springer Berlin Heidelberg, 2008.


###**Paper Summaries**

##*Paper 1*

A release plan involves all the decisions related to the selection of features for each release to meet the important technical, risk, resource and budget constraint. Therefore, release planning is a very important and integral part of software projects and poor release planning could lead to unsatified customers, faliures to deliver on the project and poor bussiness value. 
<br/>
The objective of this paper is to describe the art and science of software release planning. According to aurhor, the art of release planning relies on the human element i.e his intuition and capabilities to make the best decisions between conflicting objectives and constraints, while the science of release planning refer the methodologies and systems that yeild best results for release planning.
<br/>
There are many challenges involved with release planning, but it mainly relate the cognitive and computational complexity of it.
To solve these challenges the paper offer two approaches:
* The first one relies on the human factor it is the art of release planning.
 To justify this approach the author describe release planning as ill-defined problem i.e its solution is not clear. Therefore, release planning in this approach is non-organized and usually done informaly and relies on primitive tools such as spreadsheets.
* The second one relies on more systematic and repeateable methodologies that is backed by meaningful data.
 To formalize release planning and make it scientific, and methodical, the author discusses a number of aspects that needs to be formalized while allowing most of the other parts to be carried out ad-hoc, these aspects are:
 1. Decision Variables: List of features planned for this release.
 2.	Dependencies between features: The dependencies between features can be of two types: the first type is coupling relation and the second type is precedence relation.
 3.	Resource Constraints.
 4.	Stakeholders
 5.	Prioritizing the features


<br/>
The authors further explain that the art and science of release planning while they both have challenges and justifications, they do not conradict but complement each other. To create synergy between them the author proposes a hybrid release planning framework, that is consisted of three phases:
 1. Modeling the detail of the problem: which has three frameworks and they are, planning objectives, resource allocation and stakeholder voting.
 2.	Exploration where an actual solution to the formal modeled problem is extracted.
 3.	Consolidation where the solutions are analyzed and modified (Scenario-playing and Re-Estimation).

<br/>

##*Paper 2*

#Overview
The paper is an evaluation of the QUPER model in practice, it focuses on how to handle cost dependencies in relation to quality. The paper illustrate the importance of having concrete guidlines with real practice, since it is not obvious to practitioners how to transfer cost depenedancy examples into the domain example. Finally, they suggest future research is needed to understand this issue.

#Problem 
Software development companies finds it challenging to set the right quality target in relation to future market demands. Several methods and approaches have been reported in the litterature, however, these technique use generic algorithms, which may not be worth while, if uncertainity in input data has occured.
Based on the knowledge of the authors of the paper, few studies have looked into startegic release planning of quality requirements. This paper is based on upon previous work that have been done by the author that introduced different aspects of the model as this paper provide detailed practical guidlines of how to apply the model in pracitice, how to incorperate cost dependencies between quality requirements and two new evaluations of the model with 24 professionals at a Rio case complany.

#Solution
The author provides detailed information about QUPER quidlines mode for elicitation for quality requirements, the detailed guidlines introduce a new step of how to identify cost dependencies. As this have a major impact on estimated cost for quality requirements.
This is done in seven steps:
 1. Identifying candidate QR and thier consequences. 
 2. Step Two. For each of the seleceted QR define scale and unit measurement to measure the level of quality.
 3. For each of the QR, identify reference level to calibrate the estimate and provide objective measures.
 4. For each quality requirements ellicit quality breakpoints for the market expectations.
 5. Estimate cost barriers for each market expectiation for each quality requirement
 6. Estimating, proposing, discussing and deciding candidate requirements for coming releases.
 7. Identifing cost dependencies.
 
#Evaluation
The evaluation was done in industry, with the goal of answering the research question: What are practitioners' views on the utilities of QUPER extended with guidelines including domain-specific examples?
 
##*Paper 3*

#Overview
The paper tackles the issues of balancing the quality of the requirements in market-driven product development and release planning. The paper evaluates a method that have been developed to address the issue of balancing with respect to other dimensions. The authors of the paper suggest the model provides insightful information about quality requirements in the context.

#Problem
With the increase popularity of market-driven product development and release in software industry, the product management role has emerged. Where the role has difficult and complex tasks that includes, applying different decision making that combine market and implementation considerations in release planning. As these decisions consists of different aspects such as what features should be in certain version, when it should be out or released, and at what cost. The lack of good release planning might lead to user rejection for the product and market loss. Thus, the planning of this process is essential to the product success.
Different models exist to help in the process. However, each of these models has its draw backs. Based on the authors research, very little research has looked into prioritization of quality requirements in release planning. The authors of the paper have developed a quality performance model (QUPER) and report its evaluation in Sony Ericsson.

#Solution 
The authors of the papers developed the QUPER model. Robust, ease of use and domain relevant were the main goals to guide the development of QUPER model. The development consisted of three steps:
•	Understanding the different requirements decisions, and the need for a cost-benefit model including quality aspects to support road mapping and scoping.
•	Based on the input of step one, the model definition was created. As it was defined of three views: benefit, cost, and roadmap views.
•	Using interviews as evaluation method of the model.

The QUPER model was tailored to Sony Ericsson. The evaluation of the model only considers the benefit view as that is the most important view of the model. The view was used as follow:
•	Identifying the relevant qualifiers and their consequences to define quality aspects.
•	Identifying reference levels based on actual products, to estimate current quality.
•	Identifying the current market expectations using the utility breakpoint against each qualifier.
•	Identifying and discussing the candidate targets of the coming releases.

#Evaluation
The goals of the research are to evaluate the QUPER model in industry, the ease of adopting the method in existing process, and what value the model bring to the release planning. To meet these goals of evaluation interviews have been conducted with representative subjects, followed by workshop, and another interview to assess.
•	Interview 1: Brainstorming and planning to design the study and the interview. Piloting three interviews with experts from Sony Ericsson. The authors provide information about the questions that carried out of the interview in the paper. The interview however, was semi-structured and individually. The interview sessions took between 20 – 40 minutes.  The analysis consisted of creating categories for interesting parts.
•	Workshops: How to use QUPER in practice was the goal of the workshops. The participants were collection of requirements engineers and managers. They were provided with reading materials before the workshop and were asked to prepare for it. The workshops took between 60 to 90. The goal was to make sure to know how to use QUPER in comping projects.
•	Interview 2: Semi-structured interview was used. Individually the QUPER model was discussed with the subjects who were the same subjects in the first interview. The interview took between 25 to 35 minutes. The data from the interview were coded and analyzed.

#Results
Three major challenges were identified in the results. A) The acceptance of provided quality level, B) Specification of the quality level, and C) Specifying performance quality that quantifiable, representative, and the conditions that should be fulfilled.
The results also indicated that the subjects liked the QUPER mode, especially the breakpoints utility. Which helps in understanding higher quality levels when they do not have practical impact on the benefit in particular context. Also it was indicated by the subjects that the model is not only applicable to performance requirements but also can be applied to all quality requirements. All subjects confirmed that CUPOER model was easy to understand and learn. All the subjects confirmed the estimations of performance requirements may be more accurate using the model. All subjects agreed the use of the model improved the decision making especially in release planning. Finally, one subject indicated that QUPER model is especially an important to use when making decisions about what time a product at certain level of quality should be released.
The challenges that have faced the team in using QUPER are believed will be resolved once the team have used the QUPER model for longer period of time. The evaluation indicated the QUPER model is feasible and relevant to the tested domain and it is applicable to different domains as well. Future research will also include additional evaluation of the model in more areas, subjects, and roles. As well as researching and evaluating other views of the model like the cost view. Finally, a future direction also includes evaluation of the market’s needs, how to use information about the current market to predict future quality levels.
