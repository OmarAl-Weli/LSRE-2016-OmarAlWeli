#**Seminar Notes 1**

##**Questions and Answers**
*1. What is GAP analysis?* </br>

GAP analysis is the measure of postive and negative "gaps" between what the customer expect and what the customer recieve/product offers.[1]

*2. What is CVA analysis?* </br>

Customer Value Analysis is measuring the same variable as the GAP analysis but adding a competitor products to the process, and the analysed product is judged upon it's shortcomings in comparison to said competitor products.[1]

*3. What is IVA analysis?* </br>

Internal Value Analaysis is the measure weather a product is in line with a company's other products or strategies while resource limitation and the company other products in mind.[1]

*4. What tools are available for Continuous Integration?* </br>

Jenkins-ci, Codeship, Apache Continuum etc.
  * Experience:  </br>
  I used jenkins-ci before on a project. I created a maven project and used subversion as a code management tool, we used eclipse as an IDE and the code was written in java. Jenkins-ci would give daily builds and reports, and we felt that it hindered our work because we had to deal with on a regular bases and we felt it just added to our workload, most conflicts Jenkins falgged could easily be fixed using subversion alone code merging tool. We came to the conclusion that it did not work in our case because: 
  (1)the number of contributors was too few and we communicated face to face daily, therefore we could solve most code conflict without Jenkins.
  (2)Our inexperience with it as a tool and continous integration as a concept e.g. some contributors had not heard of continuous integration before we started the work. 
  
*5. What is technical product management?*</br>

*6. What is roadmapping? How can you do it in large scale?*</br>

Roadmapping is creating a strategy or a long term plan for a project, it provides an overview of the evolving market, competing products and technologies over time[2]. Additionially in software engineering, it provide a high level view of the products and links requirement engineering to the bussiness aspect. A typical roadmap involves the different stakeholders of the project, making decisions, which when followed, the roadmap outcome is reached[3]. For large scale roadmapping to be effective, it must solves large scale project issues[4]. 

##**Paper Summeries**

###**Paper 1**</br>

Gorschek, Tony, and Claes Wohlin. "Requirements abstraction model." Requirements Engineering 11.1 (2006): 79-101.</br>

####**Overview**</br>

In MDRE requirements arrives in various shapes and forms, and on different domains and levels. This paper develops a four level abstraction model to solve this problem. The model is tested and validated at a company and the results points to its usefulness. Finally, the model should be able to allow companies to compare requirements which would be usefull to different activities such as prioritization and packaging.

####**Problem**</br>

In incremental market driven products, product supplier need to deliver an optimal subset of requirements for each release. This practice require balancing between a number of variable such as what subset of requirements to release, what time should it be released and what is the cost of these requirements. Which depends on requirement elicitation, analysis and specification.
Additionialy, in MDRE it is more complicated since requirement does not come from one direction like bespoke, it comes from a lot of different internal and external sources such as customers, competitors, engineers, managers etc. Furthermore, the requirements comes in varying degrees of clarity or coherence, varying levels of abstraction, continuously, directly and indirectly. 
This problem is attributed to the phenomenon of moving from project centered development towareds product centred development.
Finally, the problem was identified in industry during a software process improvment venture where an atempt to adapt requirement engineering to more of continuous process.

####**Solution**</br>

Requierment Abstraction Model or RAM, was developed as a solution to the problem mentioned above and to give product managers a professional working model for planning and developing requirement engineering. Hence, RAM was developed for product centered requirements, supports continuous flow of requirements and requirement engineering effort, dealing with requirement of various levels of abstraction which it support comparison of these requirement, removing absraction from these requirement and adding details and vice versa. 
Finaly, the issues mentioned above were formulated into nine issues, and those nine issues were divided into three separate improvement packages, one of which, RAM was built to address and prepare for the other two. The issues in improvement issue package 1 are:
 1. Abstraction level, and content of requirements
 2. Roles and responsibilities
 3. Requirements upkeep during and post project

####**Results**</br>

Requirement Absraction Model or RAM, was statically and dynamically validated in industry, against an origanization who had the issues mentioned before.</br>
**Static Validation**</br>
Since the organization, requirement engineerings role were project focused and not product focused, like the roles in RAM, an identificaton proccess was held before starting the static validation process. After that, two static validation sessions in the form of unstructered interviews were held, each with a different division of roles.
From the first static validation session, the author identified a problem with the size of the model in terms of details i.e. the model required the requirements to be too detailed, according to the product managers, which could lead to it not being used. Thefore, a trade-off were suggested to make the model good enough and used instead of detailed and complete and unused.
In addition, the example driven nature of the model enhanced its usability, and the rules/structure of RAM were essential to making in RAM a systematic and repeatable process.
The second static validation session, provided evidence that RAM produced requirements were refined enough unambiguous and testable. To insure testability, a testability review document was propoesed for the dedicated requirement enigneering effort.</br>
**Dynamic Validation**</br>
There were some limitation to doing dynamic validation for RAM, since it is very difficult to do it a continuoues manner, that said there were some benifit to do a dynamic validation, which resulted in some leasons learned:
 1. After working up requirement i.e. de abstracting it, the number of requirements doubled.
 2. The worked up requirements were able to be campared to the product strategy.
 3. Improvement to the input requirements were needed to make sure the requirements were good enough in terms of testability and unambiguity.
 4. The overall impression of RAM was postive
 
###**Personal Impression and Experience**</br>
Overall, the paper was good and well structured. The Requirements Abstraction Model was described in details and the tutorial were excellent and easy to follow, although some part were redundant. The distinction between product focused and project focused software engineering provided a good motivation for create the Requirements Abstraction Model and one I did not and could not make without reading this paper.

###**Paper 2**</br>

Khurum & Gorschek “A method for early requirements triage and selection utilizing product strategies”

####**Overview**</br>

The paper presents a Method for Early requirements Triage and Selection or MERTS, which is a method for selecting requirements that is aligned with the company's strategy as early as possible. This strategy was created to solve a need from industry and is described in this thourghly in this paper and validated in industry.

####**Problem**</br>

In MDRE, there is continues flow of requirements which could overload the development team or organization. In addition, since MDRE is countinuous process, an emphasiss on selection requirement based on product strategies, bussiness goals and overal vision of the company. Moreover, in industry strategy formulation is often done ad-hoc which could lead to spending a lot of resource performing early triage of inappropriate requirements.

####**Solution**</br>

MERTS has two purposes, it guides creating product strategies that take technical and strategic views into accounts and using these strategies to perform requirements triage i.e. selecting the right requirements. To this end the operation of MERTS were divided into three parts:
 1. Early requirements triage, this part is divided into three steps to create a product strategy:
  1. Specify, this steps output an explicit understanding of goals and objectives that can be used to perfom requirement triage.
  2. Assign Weights, in this steps we assign weights to the answers of step one.
  3. Compare requirements, in this step the requirements are compared to factors and sub classification to figure out how these requirements contribute to said facors and sub classifications
 2. Requirement selection for release, this part is concerned with time aspect of the strategy and divided into two steps:
  1. Specify product technology roadmap, which means speficying what project achieves in terms of its evolution and technology trends.
  2. Estimate resources, which is assigning explicit financial and effor estimates to the roadmap.
 3. Strategy Rationale, in this part the reason behind the strategy is documented.

####**Results**</br>

To evalute MERTS two case studies were performed on the development teams of two anonymous telecom companies, in the form of interviews of the strategic and technical manager of each company. The result of the studies are:
1. MERTS is practical and applicable once understood
2. Since prequesites of MERTS was not considered in the overhead, MERTS was considered pragmatic and require effort investemnt.

###**Personal Impression and Experience**</br>
This paper relatively the same issue as the paper before it address, but they arrived to a quite different solution. Overall the paper describe the problem well and reasonably motivate the creaton of MERTS. I found the tutorial to be insufficient and there are some structural choices that I took issues with e.g. the validation is in two sections saparated by the description of solution.

###**Paper 3**</br>

Gorschek & Davis “Requirements Engineering. In search of dependent variables”</br>

####**Overview**</br>

This paper argues that assessing the quality of the product of a software requirement specification or SRS, that results from changing or modifying the requirement engineering process as an independent variable is flawed. This paper propose an alternative for this in the form of a framework of dependent variable which provide a full range of quality assessment for requirement engineering.

####**Problem**</br>

Organization have been trying to improve thier requirement engineering process by assessing the requirement process itself and the product of said requirement process. Based on literature that this paper presents, the result of these assessments are not necessarily proves of the process success. 
In addition, most software engineering improvement processes adress requirement engineering in terms of developing project and not a product, which this paper provide resources and litarture on. Which this paper argue that the success of the product cannot be determined by examining its development.
Finally, this paper attempts to find out what are the dependent variables in requirement engineering process.

####**Solution**</br>

There are a number of dependent variables, which are at five distinct levels:
 1. Requirement phase, this level include the following dependent variables:
  1. Requirement cost
  2. Requiremet quality
 2. Project, this level include the following dependent variables
  1. Project cost and time
  2. Project estimate
  3. Degree of requirement change
 3. Product, this level include the following dependent variables
  1. Requirement selection
  2. Degree of impact
 4. Company, this level include the following dependent variables
  1. Portfolio management
  2. Strategic alignment
  3. Degree of impact
 5. Society, this level include the following dependent variables
  1. Positive and negative externalities.
  
###**Personal Impression and Experience**</br>

The problem in this is well argued and well researched, and the motivation for the paper is there. The solution is well researched and well argued as well but the paper does not have validation case, it only propose measures for the dependent variables mentioned in the solution which are also well argued and researched.

###**Paper 4**</br>

R. Berntsson Svensson, T. Gorschek, B. Regnell, R. Torkar, A. Shahrokni, R. Feldt (2012) “Quality Requirements in Industrial Practice – an extended interview study at eleven companies”, IEEE Transactions on Software Engineering, vol.38(4), pp. 923-935 </br>

####**Overview**</br>

This paper studies quality requirements and it selection practices, by perforiming an interview study in the industry to find the right balance between functional requirements and quality requirement. 

####**Problem**</br>

Quality requirements are a crucial part of any software product and neglecting them lead to customer dissatisfaction, more expensive software products and increased time to market. However, quality requirement are oftenly missunderstood, poorly specified and stated in an informaly way. 
This problem is made worse in MDRE, since there more requirements, there are many sources of requirements, requirements comes at different absraction levels etc.

####**Discussion of Results and Solutions**</br>

This paper provide the results of empirical study that involves semi structured interviews of 22 practitioners from 11 companies, these companies serves different markets i.e. Bussiness to Bussiness or B2b and Bussiness to Customers or B2C. The result of these interview is presented by answering the four research questions:
 1. The first research question was concerned with finding which quality requirement is the most important according to the practitioners. Although, useability was chosen as the most important quality, although B2B and B2C prioritized different quality requirements.
 2. The second research question about what are the most common interdependencies between quaility requirements and functional requirements. They, also found that B2B and B2C prioritise different interdependencies.
 3. The third research question was concerned with cost estimation of quality requirements. The study finds that there are no distinction between quality and functional requirement estimation, althoug product managers estimated the cost to be slighly higher than a project leader. The study also finds that there are no difference between B2B and B2C in term of cost estimation of quality requirements in relation to the normal and best scenario.
 4. The fourth research question was involved with the dismissal rate of quality requirements and the reasons behind the dismissal, which they list as:
  1. Poor cost estimation
  2. Lack of resources
  3. Quality requirements have lower priority than functional requirements.
 The study finds that there no major difference between B2B and B2C companies in terms of why quality requirements are dismissed.
 
###**Personal Impression and Experience**</br>
The paper was very informative of how to conduct a qualitative research and of the companies handle quality requirements in general. This paper descibed every steps in details, therefore it made easy to understand and follow.

###**Paper 5**</br>

J. Karlsson, K. Ryan, “A cost-value approach for prioritizing requirements”, IEEE Software, 1997.</br>

####**Overview**</br>

Although requirement prioritisation is an important aspect of any successfull software engineering effort, requirment prioritisation and selection is mostly done informally and ad-hoc. Therefore in this paper, a requirements prioritisation tool is developed. The tool allows requirements engineers to rank requirements in two dimension: value to customers and cost of implementaion. Finally, the tool is applied successfully in two commercial telecom companies projects.

####**Tool 

###**References**

[1]Gorschek, Tony, and Alan M. Davis. "Requirements engineering: In search of the dependent variables." Information and Software Technology 50.1 (2008): 67-75.</br>

[2]Phaal, Robert, Clare JP Farrukh, and David R. Probert. "Technology roadmapping—a planning framework for evolution and revolution." Technological forecasting and social change 71.1 (2004): 5-26.</br>

[3]Lehtola, Laura, Marjo Kauppinen, and Sari Kujala. "Linking the business view to requirements engineering: long-term product planning by roadmapping." 13th IEEE International Conference on Requirements Engineering (RE'05). IEEE, 2005.</br>

[4]Dustdar, Schahram, et al. "A roadmap towards sustainable self-aware service systems." Proceedings of the 2010 ICSE Workshop on Software Engineering for Adaptive and Self-Managing Systems. ACM, 2010.
