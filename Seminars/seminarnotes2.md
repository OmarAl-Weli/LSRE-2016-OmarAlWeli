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
 4.	Release Planning: prioritizing requirements, constructing and validating release requirements document and scope management.

