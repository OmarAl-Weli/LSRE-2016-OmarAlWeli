#**Seminar Notes 3**  </br>

##**Paper Summaries** </br>

###**Paper 1** </br>

Wnuk et al. “What Happened to Our Features? Visualization and Understanding of Scope Change Dynamics in a Large-Scale Industrial Setting” </br>

####**Overview** </br>

Deciding which features to implement in a software product line project is influenced by many factors e.g. changing markets, evolving technologies etc. Therefore, this paper presents the application of the Feature Survival Charts technique that visualize scoping change dynamics.

####**Problem** </br>

Product line projects receive a large number of requirements continuously, therefore, selecting which requirements to implements and which requirements to postpone for next release or next project, or scoping, is very important.

####**Solution** </br>

Feature Survival Charts or FSC was created to solve scoping changes for a company in the embedded system’s domain. Additionally, this paper proposes a set of scope tracking measurements which complements FSC to provide further understanding of scoping changes.

**Feature Survival Chart** </br>

The chart visualize scope changing through highlighting the changes in different colors on a chart. The chart contains each feature complete lifecycle plotted on the Y-axis of the chart while the X-axis represent the scope changing. 
The coloring scheme described by the authors is, green for features that are part of the scope, while red for feature that are not part of the scope and lastly, different shades of green for different requirements flow which a specific approach to the case company.
The features are also sorted according to how long they were in the scope to finally get a graph that illustrate several simultaneous scope changes. The feature that survive i.e. included early while lasting the entire scoping process, are placed at the top of the graph.
The graph also illustrates decisions that has been made to de-scope features and the impact of de-scoping features, which could provide valuable data on the effort that is spent on each feature. </br>

**Scope Tracking Measurements** </br>

The author of this paper devised five scope tracking measurements with the goal of characterizing and finding the reasons for volatility and velocity of the scoping process. These measurements are divided into two type:  </br>
 1.	*Time related scope tracking measurements:* these measurements defined as qualitative approach which offer additional information that complements the graph. There is only one measurement in the category: </br>
  1.	Number of positive and negative scope changes per tome stamp/baseline. </br>
 2.	*Feature relate measurements:* these measurements can be calculated based on the scope attribute values in the feature list document. There are four measurements in this category: </br>
  2.	Time to feature removal. 
  3.	Number of state changes per feature.
  4.	Time to birth.
  5.	Reason for scoping decision.
  
------------------------------------------------------------------
  
###**Paper 2** </br>

Wnuk & Gorschek “Obsolete Software Requirements” </br>

####**Overview** </br>

Continuous requirement’s change and customer’s need results in requirements obsolescence; thus this paper investigate the phenomenon of obsolete requirements through an empirical study. Furthermore, this paper defines obsolete requirements, study how they are handled in industry and their impact.

####**Problem** </br>

Due to rapid change in business environment and fierce completion, requirements that become obsolete before the project completion can have huge impact on software project.
Time to market pressure and deadlines can make early and predefined requirement obsolete immediately after their creation. Furthermore, in Market Driven Requirement Engineering or MDRE, the number of incoming requirements is large and the pace of change is high, therefore software companies have to identify obsolete requirements rapidly which can threaten effective requirement management. Additionally, obsolete requirement can lead to project delays or in some cases failure, and Identifying them is not enough, handling and removing them early is crucial.

####**Solution** </br>

The author of this paper conduct an empirical study of 219 participants, who answered a questionnaire that contained 15 open and close-ended questions of different formats. The questionnaire served to answer the research questions.

**Research questions and answers**  </br>

 1.	What is the definition of obsolete requirements? </br>
“An obsolete software requirement is a software requirement (implemented or not) that is no longer required for the current release or future releases and, for various reasons, has little or no business value for the potential customers or users of a software product.” [1] </br>

 2.	What is the impact of obsolete requirements? </br> 
The impact of obsolete requirements is serious or somehow serious according to 84.3% of the respondent of the questionnaire, furthermore the type of requirement engineering context had a minimal influence on the results. </br>

 3.	Does requirement type effect the probability of a requirement being obsolete? </br>
The answers of the questionnaire were categorized by the author and the category that received the category that had the most obsolete requirements, are incorrect/misunderstood requirements followed by inconsistent and ambiguous requirements. </br>

 4.	What methods are available to identify obsolete requirements? </br>
50% of the respondent pointed to manual methods, while 13.29% indicated that there is a predefined obsolete status for requirements, furthermore, 11.19% chose the category of “I never found them or I never thought of finding them”. Finally, only 10% indicated the existence of any sort of automation tools. </br>

 5.	When are obsolete requirements are identified and how are they handled in industry? </br>
60% of respondent assigned obsolete status to inappropriate or obsolete requirements, while 21.9% of the respondent suggested to put obsolete requirements in a separate requirements document. </br>

 6.	What context factors influence obsolete requirements? </br>
The first factor is project size i.e. the bigger the project the more it negatively impacted by obsolete requirements. </br>
The second factor is project type, with outsourced project being the most likely to be affected. </br>

 7.	Where in the requirement life cycle should obsolete requirements be handled? </br>
The result of the questionnaire, is that obsolete requirements should be handled in during the requirement analysis, requirement validation and requirement changes phases. </br>


##**References**

[1] Wnuk & Gorschek “Obsolete Software Requirements”

