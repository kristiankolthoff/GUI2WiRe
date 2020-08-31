## Overview

High-fidelity Graphical User Interface (GUI) prototyping is a well-established and suitable method for enabling fruitful discussions, clarification and refinement of requirements formulated by customers. GUI prototypes can help to reduce misunderstandings between customers and developers, which may occur due to the ambiguity comprised in informal Natural Language (NL). However, a disadvantage of employing high-fidelity GUI prototypes is their time-consuming and expensive development. Common GUI prototyping tools are based on combining individual GUI components or manually crafted templates. In this work, we present \textit{GUI2WiRe}, a tool that enables users to retrieve GUI prototypes from a semi-automatically created large-scale GUI repository for mobile applications matching user requirements specified in Natural Language (NLR). We extract multiple text segments from the GUI hierarchy data and employ various Information Retrieval (IR) models and Automatic Query Expansion (AQE) techniques to achieve ad-hoc GUI retrieval from NLR. Retrieved GUI prototypes mined from applications can be inserted in the graphical editor of \textit{GUI2WiRe} to rapidly create wireframes. GUI components are extracted automatically from the GUI screenshots and basic editing functionality is provided to the user. Finally, a preview of the application is created from the wireframe to allow interactive exploration of the current design. We evaluated the applied IR and AQE approaches for their effectiveness in terms of GUI retrieval relevance on a manually annotated collection of NLR and discuss our planned user studies.

![alt tag](https://raw.githubusercontent.com/kristiankolthoff/GUI2WiRe/master/gui2wire_tool_overview.png)



## Watch Tool Demonstration on Youtube

[![GUI2WiRe](https://raw.githubusercontent.com/kristiankolthoff/GUI2WiRe/master/gui2wire_youtube.png)](https://youtu.be/2nN-Xr2Hk7I)



### References

Kristian Kolthoff, Christian Bartelt, and Simone Paolo Ponzetto. 2020. GUI2WiRe: Rapid Wireframing with a Mined and Large-Scale GUI Repository using Natural Language Requirements. In 35th IEEE/ACM International Conference on Automated Software Engineering (ASE ’20), September 21–25, 2020, Virtual Event, Australia. ACM, New York, NY, USA, 5 pages.https://doi.org/10.1145/3324884.3415289
