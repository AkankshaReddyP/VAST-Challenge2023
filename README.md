# VAST-Challenge2023

##### The global seafood industry, vital for sustenance and livelihoods, is under threat from illegal fishing. FishEye International aims to combat this by releasing datasets for Visual Analytics collaboration. The challenge involves identifying illegal fishing firms, utilizing a tool for decentralized node-based clustering, and implementing anomaly detection based on revenue-to-size ratios. The goal is to leverage collective intelligence for informed recommendations to address the complex problem of illegal, unreported, and unregulated fishing, ensuring the industry's sustainability and global food security.



###### A comprehensive data analysis process was undertaken using the MC1.json dataset, culminating in various visualization and detection methodologies. A PyQt framework facilitated the creation of a user interface allowing entity selection and control over the displayed nodes' quantity for the Force-Directed layout visualization. Patterns were identified through a Beeswarm plot developed using React, clustering entities into three categories: company, person, and political organizations, with hover-over functionalities revealing entity ID, country ID, and type. Anomaly detection focused on the proportionality between revenue and firm size, allowing identification of potential anomalies and connected firms. The PyQt-based interface enabled users to select graph size and revenue amount, while a React-powered tool facilitated the visualization of connected firms within a social network graph, potentially flagging associated firms as illegal if the central node was deemed illegal in prior steps. The integration of contextualizing data was a pivotal aspect across these analysis stages, ensuring a comprehensive understanding of the dataset.



To execute and visualize the results,perform the following steps

Installations Required: Node,React and Python

For TASK 1 output, run MC1.py file

For TASK 2 and sub-task of TASK 3,do the following steps

Step 1: In applications such as Visual Studio code Editor , go to dashboard folder in Vast Challenge 2023 folder.Make sure you are in the same folder in terminal.Use cd ../dashboard command.

Step 2: In the terminal, enter "npm start" command

This starts the server on localhost:3000 address

Above steps displays outputs of Task 2 and Subpart of task 3

For TASK 3 output, run MC3.py file

