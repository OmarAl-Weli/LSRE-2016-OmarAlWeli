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
  1. Specify
  2. Assign Weights
  3. Compare requirements
 2. Requirement selection for release, this part is concerned with time aspect of the strategy and divided into two steps:
  1. Specify product technology
  2. Estimate resources
 3. Strategy Rationale

####**Results**</br>

###**References**

[1]Gorschek, Tony, and Alan M. Davis. "Requirements engineering: In search of the dependent variables." Information and Software Technology 50.1 (2008): 67-75.</br>

[2]Phaal, Robert, Clare JP Farrukh, and David R. Probert. "Technology roadmapping—a planning framework for evolution and revolution." Technological forecasting and social change 71.1 (2004): 5-26.</br>

[3]Lehtola, Laura, Marjo Kauppinen, and Sari Kujala. "Linking the business view to requirements engineering: long-term product planning by roadmapping." 13th IEEE International Conference on Requirements Engineering (RE'05). IEEE, 2005.</br>

[4]Dustdar, Schahram, et al. "A roadmap towards sustainable self-aware service systems." Proceedings of the 2010 ICSE Workshop on Software Engineering for Adaptive and Self-Managing Systems. ACM, 2010.
