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



