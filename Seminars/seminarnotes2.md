#**Seminar Notes 2**

##**Questions and Answers** </br>

*1. Read up on the Boston Matrix* </br>

Boston Matrix or product portfolio matrix is a portfolio management tool that help businesses in identifying and prioritizing their product portfolios which aid in a business decision to allocate resources effectively.
The matrix classifies products in two dimension, market share and market growth. Market share is calculated in reference to competitors in the market, while market growth is the extent of an industry attractiveness.
Therefore, business products are classified into four different categories:
 1. Cash cows: High market share and slow market growth rate, generate a lot of cash and doesn’t require a lot of assets
 2. Dogs: low market share and slow market growth rate, break even
 3. Question marks: low market share and high market growth rate, generate a low amount of cash and require a lot of assets
 4. Stars: high market share and high market growth rate generate a lot cash and require a lot of assets. </br>
 
*2. How do you connect your requirements to your architecture?* </br>

Architecture is the fundamental structure of a software while requirements is the description of a software to be developed. Starting with one or the other introduces restraints to the system, therefore developing both concurrently addresses these drawbacks and many more [1]. </br>

*3. Can you connect all requirements directly? What do you do if you cannot?

Not all requirements can be connected to the architecture, because requirements come at different abstraction levels, have different amount of details and different clarity levels, therefore to connect requirements to architecture we need to remove abstractions from requirements and add details to make it viable to be connected to architecture [2, 1]. </br>
Although, some claim that architectural design decision and architecturally significant requirements are the same [2]. </br> 


###**References** </br>

[1] Nuseibeh, Bashar. "Weaving together requirements and architectures." Computer 34.3 (2001): 115-119. </br>

[2] De Boer, Remco C., and Hans Van Vliet. "On the similarity between requirements and architecture." Journal of Systems and Software 82.3 (2009): 544-550.</br>

##**Paper Summaries** </br>

###**Paper 1**   </br>

v.d. Weerd & Brinkkemper “Towards a reference framework for software product management”

####**Overview**</br>

Software product management as a discipline often gets neglected, therefore this paper conduct a systematic literature review of the field to provide a reference framework for software product management. To validate the reference framework a case study is conducted at a major software vendor. Finally, a workshop is proposed to support software product manager in software product companies. </br>

####**Problem**</br>

The software market has shifted from creating customized software to creating standard off-the shelf products. With that product management as a function has emerged although software companies have largely ignored software product management in the past, now software companies started studying it and paying attention to it.
Product management is an important and role in many companies, in addition to it being complex and difficult, since product manager have a lot of responsibilities and have to make many internal and external stakeholders happy. Software product management have even more challenges such as highly complex requirement organization, high release frequency, easy of update after release which prolong development cycle beyond release dates etc.
Finally, software product management as domain is need of a reference framework that integrate the area fragmented research and knowhow into a body of knowledge, and this paper aims to provide that.

####**Solution**</br>

To develop a reference framework for software product management, the complexities of the field is considered, part of these complexities are the interaction between stakeholders, and the product artifact hierarchy.
There are many internal and external stakeholders that product manager have to keep in mind, while internal stakeholder act according to the corporate strategy, external stakeholder cannot be influenced by product managers.
Software product management cover three issues: requirements, products and releases. These issues can into hierarchy, which is companies has products, products have releases and releases consists of requirements. This hierarchy divides software product management into four processes:
 1.	Portfolio Management: making decision about the products the company owns
 2.	Product Road-mapping: using scientific and technological resources to create long term plan for products.
 3.	Requirement Management: eliciting requirement from different sources, specifying, identifying and revising them, while keeping track of dependencies, core assets, product lines and release themes.
 4.	Release Planning: prioritizing requirements, constructing and validating release requirements document and scope management. </br>
 
###**Paper 4**   </br>

Wnuk et al. “Are You Biting Off More Than You Can Chew? A Case Study on Causes and Effects of Overscoping in Large-Scale Software Engineering”

####**Overview**</br>

In Market Driven Requirement Engineering or MDRE, scope management is very important as it is easy to over-scope, therefore this paper conduct a case study to understand over-scoping in market driver software engineering and how agile requirement engineering affect it.
Semi structured interview were carried based on hypothesis of which factors are involved in over-scoping, which resulted of detailed understanding and analysis of over-scoping and the possible impact of agile practices on this issue. </br>

####**Problem**</br>

Scoping or project scoping is a complex process of managing large number requirements which are continuously growing, while keeping track of market shift and changes and the impact of these requirements and changes on the code base of the product. Furthermore, in market driven software engineering, product managers have to factor competition and the unpredictability of the market. </br>
Software product manager also face the challenge of a product changing its scope during the development which can be attributed to over-scoping i.e. setting a scope that require higher resources than the company has. </br>
Agile development processes solve some the of issues that come with scoping however, these practices introduce new challenges such as satisfying all stakeholders and creating accurate plans for an entire project. </br>
####**Solution**</br>

To solve the problems mentioned in the previous section, the author of the paper conducted a case study with the goal of understanding the factor that are involved in over-scoping. To achieve this the authors formulated three research questions:
1.	What are the causes of over-scoping?
2.	What are the resulting effect of over-scoping? 
3.	How may agile process impact the causes and effects of over-scoping?

Furthermore, the case study was divided the into three phases:

**Phase one**</br>

The first phase purpose was to prepare for the interviews and to formulate hypothesis from the experience of one of the author on the factor of over-scoping and its effects on the project as a whole. Thus, the author hypothesized five factors that causes over-scoping:
1.	Continuous requirements inflow via multiple channels.
2.	No overview of software resource availability.
3.	Low development team involvement in early phases.
4.	Requirement not agreed with the development team.
5.	Detailed requirements specification is produced upfront. </br>

**Phase two *</br>

The second phase of the study consisted of semi structured interviews of nine practitioners who are working in requirement engineering, software development and testing from a large market driven software development company that has started to shift to an agile way of working. The hypothesis provided framework but was not imposed on interviewee by making the discussion open ended. </br>

**Phase three** </br>

To validate the results from the interviews, a questionnaire was conducted of six additional practitioners from the same company. The participants were asked to state to which degree or disagree with the results, and to add any missed items. </br>

####**Results**</br>

The result of the interviews was collected and categorized in the form of answers to the research questions:

 **1. Causes of over-scoping** </br>
All the interviewees in addition to agreeing or experiencing with the challenges of over-scoping, a majority of them agreed or experienced with the causes hypothesized in phase one of the case study. Furthermore, no interviewee disagreed to any of these causes, although causes four and five had less than agreed or experienced responses.
Finally, a six cause were derived from the first five interviews which is “unclear vision of overall goal” </br>

 **2. Effects of over-scoping** </br>
Six effects of over-scoping were derived from the interview:
  1.	Many requirements change after the project scope is set.
  2.	Quality issues.
  3.	Delays.
  4.	Customer expectations are not met.
  5.	Communication gaps.
  6.	Challenge to keep the software requirement specification updated. </br>

 **3.	How agile requirement engineering practices may impact over-scoping** </br>
  The study identifies that three of those agile practices that are being introduced might impact one or several of the causes of over-scoping. The practices are:
  1.	One continues scope and release plan flow.
  2.	Cross functional development teams.
  3.	Gradual and iterative requirements detailing.
Additionally, three more practices were suggested by the questionnaire participant that will address over-scoping. </br>

###**Paper 5**   </br>

Wnuk et al. “Factors Affecting Decision Outcome and Lead-time in Large-Scale Requirements Engineering”

####**Overview**</br>

This paper is a retrospective study at a large scale software manufacturer. To investigate the factors that affect decision lead-time. By analyzing 1439 change requests looking for statistically significant relationships between the decision making factors
The results of the retrospective study were also investigated more by surveying practitioners in industry to understand relationships among decisions. </br>

####**Research Goals**</br>

 1.	Validating the results of the decision log analysis in a survey
 2.	Extending the analysis of the results regarding factors that affect the decision lead-time and the relationship between the decision lead-time and the decision outcome.
 3.	Extending the analysis of related work.
 4.	Extending the interpretation of the results in the light of the related work.
 
The author of the paper run statistical tests on empirical data to either accept or reject hypotheses and draw conclusions based on the test results. The results of the statistical analysis were further validated in a survey and interpreted in relation to related studies. </br>

####**Method**</br>

Case study and survey methods were selected for conducting this study. </br>

**Case Study:**
The authors of this paper used the analysis of electronic databases of work performed technique (Lethbridge et al 2005) for data collection as it is a suitable technique for analyzing large amounts of data.
Furthermore, they were granted access to an extensive decision log of all products planned to be released in 2008 containing 1439 change requests. </br>
Five variables were created for each decision:
1.	Lead-Time.
2.	Number of Products Affected.
3.	Release Number.
4.	Type of Customer.
5.	Decision Outcome. </br>

**Survey:** </br>
A survey among 50 respondents from industry was conducted to validate the results from the case study as well as to strengthen the external validity of the study. </br>

**Case study analysis:** </br>
The choice of the right statistical test is dependent on three major factors, namely (Sheskin 2004):
1.	The level of measurement of the variables.
2.	The distribution of the data.
3.	The hypotheses that will be tested.
Five different decision characteristics were analyzed, which were all translated to quantitative, analyzable variables. </br>

**Survey analysis:** </br>
The case study revealed that in the calculated medians that are measured at least half of the samples have identified a negative relationship. When the median is positive, at least half of the samples in the study have identified a positive relationship. </br>

**Subjects:** </br>
The survey was answered by 50 respondents. 32% of the respondents came from the Netherlands, 14% from Sweden and 46% came from other countries, including US and UK. 
The majority of the respondents (68%) worked with companies, in which up to 100 persons were involved in the software engineering process. </br>

####**Results**</br>
The results of the study is categorized in the form of answers to the research questions and the hypothesis:
**1.	Which decision characteristics affect the decision lead-time?** </br>
When the number of products affected by a decision increases, the lead-time needed to take the decision increases as well. Since the correlation coefficient is rather low, the number of products may not be the only variable influencing the lead-time.
The results of the survey show a positive relationship between the decision lead-time and the number of products affected by the decision, the concordance between the results from the decision log analysis and the survey could be interpreted as an indication that more complex investigations take more time Effect of a certain release number on the decision lead-time. </br>

**2.	Which decision characteristics affect the decision outcome?** </br>
From the results the authors concluded that there is a high likelihood the two groups are derived from different populations or more precisely, the rejected decisions have a lower number of products they affect.
Also, a significant relationship was also discovered between the number of products affected by a decision and the decision lead-time. Furthermore, there is a relationship between the decision complexity, the decision outcome and time needed to take a decision in the case company.
Finally, the survey results disprove the statistical analysis of the decision log since 54.8% of the respondents answered that a high number of products affected by the decision increases the probability of rejection, and the majority of the survey respondents indicated that the importance of the customer that issues the request decreases the probability of rejection, in other words increases the probability of acceptance. </br>

**3.	Is the decision outcome related to the decision lead-time?**</br>
Based on these results, the average lead-time needed to reject a decision is statistically significantly longer than the lead-time needed to accept a decision.
Additionally, when looking at the survey results we see that 57.1% of the respondents indicated that the time to make the decision does not influence the decision outcome. </br>


