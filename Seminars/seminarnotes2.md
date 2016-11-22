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

**Phase one **</br>

The first phase purpose was to prepare for the interviews and to formulate hypothesis from the experience of one of the author on the factor of over-scoping and its effects on the project as a whole. Thus, the author hypothesized five factors that causes over-scoping:
1.	Continuous requirements inflow via multiple channels.
2.	No overview of software resource availability.
3.	Low development team involvement in early phases.
4.	Requirement not agreed with the development team.
5.	Detailed requirements specification is produced upfront. </br>

**Phase two **</br>

The second phase of the study consisted of semi structured interviews of nine practitioners who are working in requirement engineering, software development and testing from a large market driven software development company that has started to shift to an agile way of working. The hypothesis provided framework but was not imposed on interviewee by making the discussion open ended. </br>

**Phase three** </br>

To validate the results from the interviews, a questionnaire was conducted of six additional practitioners from the same company. The participants were asked to state to which degree or disagree with the results, and to add any missed items. </br>

####**Results**</br>

The result of the interviews was collected and categorized in the form of answers to the research questions:

 **1. Causes of overs-coping** </br>
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
  1.	One continues scope and release plan flow
  2.	Cross functional development teams
  3.	Gradual and iterative requirements detailing
Additionally, three more practices were suggested by the questionnaire participant that will address over-scoping. </br>

