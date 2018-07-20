# Welcome to the Levridge Documentation Strategy
As a world-class business solution, [product name] will need to include excellent application documentation. This documentation will take several forms. This document will explain each form of documentation and how it will be created.


Types of Documentation
&nbsp;<ul><li><a href="#process-documentation">Process Documentation</a></li>&nbsp;
<li><a href="#user-reference-documentation">User Reference Documentation</a></li>&nbsp;
<li><a href="#technical-documentation">Technical Documentation</a></li>&nbsp;
<li><a href="#application-programming-interface-(api)-documentation">Application Programming Interface (API) Documentation</a></li>&nbsp;
<li><a href="#see-also">See Also</a></li></ul>

## Process Documentation

Process documentation explains how the software supports a specific business process and the necessary tasks the user performs to execute the business process. It also explains the various alternative paths for the process and provides links to the relevant User Reference Documentation for detailed instructions about using the software to perform the tasks.


Process Documentation Elements
&nbsp;<ul><li><a href="#process-overviews">Process Overviews</a></li>&nbsp;
&nbsp;<ul><li>SIPOCS</li>&nbsp;
<li>Narratives</li>&nbsp;
<li>Diagrams</li></ul>&nbsp;
<li><a href="#task-recordings-and-task-guides-(finance-%26-operations)">Task Recordings and Task Guides (Finance %26 Operations)</a></li>&nbsp;
<li><a href="#learning-path-guided-help-(customer-engagement)">Learning Path Guided Help (Customer Engagement)</a></li></ul>

#### Process Overviews

The process overview will define the process, provide a purpose or goal for the process and …


The overview will contain various artifacts to explain overall flow of the process and the context of the process including the process categories and process groups to which the process belongs. The process overview may utilize SIPOCS, Narratives or Process Diagrams to illustrate the process flow.



#### SIPOCS

SIPOC is a document that summarizes a process in table form. The name comes from the acronym for Supplies, Inputs, Process, Outputs and Consumers.



#### Narratives

Narratives are simply documents explianing a business process using narrative prose.



#### Diagrams

There are various diagrams that can be used to depict a business process. the most common are UML Activity diagram and Business Process Model Notation (BPMN).



#### Task Recordings and Task Guides (Finance %26 Operations)

Task recorder is a tool provided by Dynamics 365 Finance %26 Operations. You can use the tool to record actions that you take in the user interface (UI). When you use&nbsp;Task recorder, all of the&nbsp;events that you perform in the&nbsp;UI are captured, including adding values, changing settings, removing data. The steps that are recorded are collectively called a&nbsp;task recording.


From: <a href="https://docs.microsoft.com/en-us/dynamics365/unified-operations/dev-itpro/user-interface/task-recorder-training-docs">Create documentation or training using Task recordings</a>

A task guide is a controlled, guided, interactive experience through the steps of a business process. The user is instructed to complete each step by way of a pop-up prompt (or "bubble"), which will animate across the UI and point to the UI element that the user should interact with.
The text of the task recording can be imported into the Sandcastle document generation tool and included in the help.



#### Learning Path Guided Help (Customer Engagement)

Use Learning Path is an in-app Help experience that can be tailored to the Levridge environment and the specific usage and workflow of the Levridge software in Dynamics 365 Customer Engagement. Learning Path facilitates learning and adoption of Dynamics 365 Customer Engagement (online) and organizational processes, ensures that data is entered and interpreted consistently, and reduces errors.


From: <a href="https://docs.microsoft.com/en-us/dynamics365/customer-engagement/customize/create-guided-help-learning-path">Create your own guided help</a>



## User Reference Documentation

User Reference Documentation provides detailed explanations of each element in the software. Each form will be documented on a separate page and will contain an explanation of each user interface element including the valid input for a control, the result of the various values used in the control (i.e. what is the outcome of checking a box, or selecting a specific option from a dropdown).


In Dynamics 365 Customer Engagement we use <a href="https://technet.microsoft.com/library/dn832079.aspx">custom help</a>to provide the help URLs to Levridge forms. Customizable help and tooltips allow Levridge to provide contextual information to users filling in forms. We will replace the default Help with the custom Help at the entity level. This will make the content exposed through the help links more relevant to the user’s day-to-day activities. Per entity URLs will be used to override the out-of-the-box Help links on grids and forms for a specific customizable entity.



## Technical Documentation

This is documentation so Technical Documentation shows up.



## Application Programming Interface (API) Documentation

This is documentation so API Documentation shows up.



## See Also


#### Other Resources
<a href="10614215-4c2f-453d-b8f0-2d01d5e33cb3">Version History</a><br />