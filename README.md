# ![MedExplorer] (docs/Diagrams/icon_logo_medex_banner.png) MedExplorer

## Publicly-available URL to prototype
http://medexplorer.northropgrumman.com

## Description of the approach used to create the prototype
![Agile User Centered Approach](docs/Diagrams/Agile User Centered%20Approach.png)

Our Agile User-Centered approach ensures ongoing collaboration between development team, users, and stakeholders. To implement our [framework](docs/Software Development/Processes/Readme.md) we first identified the members of [our team and the roles](docs/MedExplorer Development Team.md) they would fulfil. We aligned our team with the RFQ requirements and leveraged our experience from our [Health Division] (http://www.northropgrumman.com/Capabilities/HealthIT/Pages/default.aspx). Our [multidisciplinary team](docs/Pictures/MedExplorer_Team.jpg) is comprised of experienced user experience (UX) designers, product manager (PM), software and test engineers, delivery manager, agile coach, and business owners. Our product, Medicine Explorer, is designed for the general public and clinicians who seek information on pharmaceutical (prescription and over the counter) performance so they can make better health decisions. The product supports [multiple device platforms](docs/Software Development/Screenshots/Platforms) and provides searchable information and trends on pharmaceuticals and related adverse effects. Our goal is to provide authoritative, trustworthy, and objective information to our users.

As a team we collaborated to review the RFQ details to ensure we understood the requirements and to set expectations. Part of the activities ([Sprint 0](docs/Pictures/Sprint0activities.jpg)) for the team was to review and analyze multiple data sets and API (Drugs, Devices, Foods) provided at [openFDA](http://open.FDA.gov). As part of the initial research we provided an analysis of the data to the Northrop Grumman Clinical Advisory Group for input as to which sets of information would be more useful by clinicians. We also met with a domain expert in the Health Care industry and representatives from the general public to understand what information would better meet people's needs. This was the groundwork for understanding the user and what information would be of value. Based on feedback, we decided to focus on the data sets associated with Drugs (Adverse Events, Labeling, and Enforcement Reports). As the lead decision maker the PM agreed to this decision and gave the permission to proceed. Our Product Manager played a key role in working with the team to define the level of quality and reviewing and accepting completed backlog items during sprint reviews.

Next the team used the feedback and learning in the initial research phase to develop our [product vision](docs/Vision Statement.md) and [personas](docs/User Centered Design/Personas). We created two personas, [Clinician] (docs/User Centered Design/Personas/Persona_Clinician.png) and [General Public](docs/User Centered Design/Personas/Persona_General_Public.png). Using the personas the Product Manager with the team revised our [product vision](docs/Vision Statement.md) and created a [product name](docs/Pictures/Product Name Brainstorming.jpg). The draft version of our vision helped communicate with users and domain experts the problem we are trying to solve. After a walkthrough of the vision with our stakeholders we were able to refine it with more clarity around who the product is for, what it provides, and its differentiating factors. To create a product name the team brainstormed a list of names that aligned with the vision. We spent time researching name options to ensure it was not already in use or in conflict with an existing product or company, and then using a voting technique, each [team member voted](docs/Pictures/DotVoting.jpg) on their top three favorites. This resulted in our product name, Medicine Explorer or [MedExplorer](http://MedExplorer.northropgrumman.com).

To better understand the needs of the users (Clinicians and General Public), we used proven [user-centered design](docs/User Centered Design/Readme.md) practices to conduct interviews, create user models, and develop style guides so designers and developers better understand the user needs operationally. We also created designs for [multiple devices](docs/Software Development/Screenshots/Platforms) for users to review. With user input the team generated an initial backlog of stories.

Our [Agile process](docs/Software Development/Processes#agile-user-centered-design) focused on an iterative development approach which included 2 sprints per day and [periodic standups](docs/Pictures/Morning Standup.jpg) to address concerns and impediments as we developed the [prototype](http://medexplorer.northropgrumman.com). Each sprint was comprised of planning, execution, and a review including a demonstration of working functionality and sharing of sprint results such a feedback from users as we continued to validate and improve designs and product features.

Sprint planning was a time for the team to focus on the goal(s) for the sprint. We identified [goals] (docs/Pictures/Sprint Goals.jpg) for each sprint (resulting in a set of goals for each day) and defined tasks for the highest priority stories that supported the sprint goal. Our stories and tasks were placed on our [scrum board] (docs/Pictures/Updated Task Board.jpg) in our [Scrum Room] (docs/Pictures/Scrum Room.jpg). As defects or requested improvements were identified by users and/or stakeholders these were placed on the scrum board as well for prioritization.

During sprint execution team members met with users to conduct [usability](docs/User Centered Design/Research Findings/Focus_Group.pdf) and [expectancy tests](docs/User Centered Design/Research Findings/Expectancy_Tests.pdf). A variety of [human-centered/user design techniques] (docs/User Centered Design/Readme.md) were employed including personas for our two primary user groups (Clinicians and General Public), conducting interviews, facilitating focus groups, conducting expectancy tests and gathering results, conducting generative research, and usability tests for regular feedback from our users. These were helpful techniques for the development team to better understanding the user needs and what they valued. The feedback from the test results and sprint reviews helped the team understand how intuitive the features are, whether layouts need to be modified, and how well the features meet user expectations. During sprint development we used an internal [GitHub Enterprise](docs/Software%20Development/Screenshots#github) server as our configuration management system.  

Our challenge was to identify the "minimum viable product" that we would provide for the first release. This caused us to focus on feature prioritization and move some stories into the [next release](docs/Diagrams/MedExplorer Product Roadmap.png).  We used [open-source technologies](License.md) throughout development and as part of our [DevOps](docs/Software Development/Processes/DevOps.md) practices. Practices included [unit testing](docs/Software%20Development/Processes/DevOps.md#unit-testing-and-automated-test), [continuous integration](docs/Software%20Development/Processes/DevOps.md#continuous-integration), [source code management](docs/Software%20Development/Processes/DevOps.md#source-code-management), and [continuous delivery](docs/Software%20Development/Processes/DevOps.md#continuous-deliverydeployment) and [conintuous monitoring](docs/Software%20Development/Processes/DevOps.md#continuous-monitoring). These practices are critical for product quality and sustainability. Continuous integration played an important role in our development process as we improved testing and continuously deployed code using GitHub after the first several sprints.  We used [Docker](docs/Software%20Development/Processes/DevOps.md#continuous-deliverydeployment) as our container system for our MedExplorer prototype.  Our MedExplorer used a number for modern, [open source](/License.md#open-source-third-party-software-licenses) technologies, including TwitterBootstrap, AngularJS, NodeJS, ExpressJS, Docker, MongoDB, Jenkins and Zabbix. As shown in our [technology stack diagram](docs/Diagrams/MedExplorer_TechnologyStack.png). The MedExplorer prototype and underlying platforms, components, and frameworks used on the project were [open source licensed](License.md) and free of charge.

We also included [install procedures](docs/Install Procedures) to support the deploy process. This enabled us to regularly test features as they were developed and build a more sustainable product. Regular demonstrations provided continuous progress and deployment of a working product to our users (internal and [IaaS provider/IBM Softlayer](docs/Software Development/Screenshots/softlayer.png)). Based on sprint review feedback from users and stakeholders, we regularly reprioritized our backlog with focus on the high value items. At the end of each sprint review the Product Manager would accept stories and place these stories in the [Completed Stories] (docs/Pictures/Completed Stories2.jpg) column. Each day we tracked the completed work and discussed our overall progress and any risks that needed to be addressed.
 Our detailed evidence is highlighted below.

***
####End of description
***
## Approach Criteria Evidence
[Link to Attachment E Approach Criteria Evidence Template Mod 5 spreadsheet](docs/Evidence/Attachment E Approach Criteria Evidence Template Mod 5.xlsx)

|#|criteria |evidence #1|
|---|---------|-----------|
|a|assigned one leader, gave that person authority and responsibility, and held that person accountable for the quality of the prototype submitted | We assigned our [Product Manager (Ray R.)](docs/MedExplorer%20Development%20Team.md) and gave him the authority, responsibility, and accountability for the MedExplorer prototype. <BR><BR>__Digital Playbook #6__ Assign one leader and hold that person accountable" |
|b|assembled a multidisciplinary and collaborative team including a minimum of 5 labor categories from the Development Pool labor categories to design and develop the prototype | Our [MedExplorer development team](docs/MedExplorer%20Development%20Team.md) used 10 of the labor categories to design and develop the prototype. <BR><BR>__Digital Playbook #7__ Bring in experienced teams |
|c|understand what people need, by including people in the prototype development and design process | Our User Experience [design team interviewed](docs/User Centered Design/Research Findings) and performed user tests with a number for General Public and Clinician users. The team also met with Northrop Grumman's Clinical Advisory Group as part of our Health Division. Users participated in periodic demonstrations for feedback. Created [scenarios](docs/User Centered Design/Scenarios) and [stories](docs/Software Development/User-Stories). The team gave periodic demonstrations to walk through scenarios and gather feedback. We captured feedback as user stories and added to the backlog for prioritization. <BR><BR>__Digital Playbook #1__ Understand what people need |
|d|used at least three "human-centered design" techniques or tools | Our [User Centered Design](docs/User Centered Design/Readme.md) approach used a number of techniques and tools, including interviews, focus groups, expectancy tests, generative research, and usability tests. <BR><BR>__Digital Playbook #3__ Make it simple and intuitive |
|e|created or used a design style guide and/or a pattern library | Our UX team created a [design style guide](docs/User Centered Design/Design Style Guide/Style_Guide_Master.pdf) to provide guidance for the web front end developers. Style guides were updated each sprint with development. <BR><BR>__Digital Playbook #3__ Make it simple and intuitive |
|f|performed usability tests with people | Our UX team performed a number of [usability tests](docs/User Centered Design/Research Findings/Focus Group2.pdf) with users and [provided feedback](docs/User%20Centered%20Design/Research%20Findings/Generative_Research.pdf) to the development staff. Once we had some initial features in place, usuability tests were run daily. <BR><BR>__Digital Playbook #4__ Build the service using agile and iterative practices |
|g|used an iterative approach, where feedback informed subsequent work or versions of the prototype | Using our [Agile framework](docs/Software Development/Processes/Readme.md), which is built upon Scrum, Extreme Programming, and [user-centered design](docs/User Centered Design/Readme.md) techniques, we were able to develop the product in an [iterative fashion](docs/Software Development/Iterative Development.md) while receiving regular, [timely feedback](docs/User%20Centered%20Design/Research%20Findings/Generative_Research.pdf) from users and stakeholders. We conducted an initial sprint 0 as we identifed the team and coordinated the infrastructure. Then we used sprint cycles of 5 hours each comprised of sprint planning, execution, and review (demo and retrospective). <BR><BR>__Digital Playbook #4__ Build the service using agile and iterative practices |
|h|created a prototype that works on multiple devices, and presents a responsive design | Our MedExplorer prototype was designed for [multiple platforms] (docs/Software Development/Platform Support.md) including PCs, laptops, tablets, and phones. <BR><BR>__Digital Playbook #2__ Address the whole experience, from start to finish <BR>__Digital Playbook #7__ Bring in experienced teams |
|i|used at least five modern and open-source technologies, regardless of architectural layer (frontend, backend, etc.) | Our MedExplorer used a number for modern, [open source](/License.md#open-source-third-party-software-licenses) technologies, including TwitterBootstrap, AngularJS, NodeJS, ExpressJS, Docker, MongoDB, Jenkins and Zabbix. As shown in our [technology stack diagram](docs/Diagrams/MedExplorer_TechnologyStack.png). <BR><BR>__Digital Playbook #8__ Choose a modern technology stack |
|j|deployed the prototype on an Infrastructure as a Service (IaaS) or Platform as a Service (PaaS) provider, and indicated which provider they used | Our [MedExplorer prototype](http://MedExplorer.northropgrumman.com) is deployed on a IaaS provider, we selected [IBM SoftLayer](docs/Software Development/Screenshots/softlayer.png) as our provider. <BR><BR>__Digital Playbook #9__ Deploy in a flexible hosting environment |
|k|wrote unit tests for their code | Our development wrote [unit tests](src/client/test) for their code and was part of the team's [definition of done](docs/Pictures/Definition of Done.jpg). The front-end unit testing is done using the Jasmine testing framework, which is run by the Karma test-runner. The back-end code is tested using the UnitJS testing framework and is run by mocha. These [unit tests were automated using Jenkins] (docs/Software%20Development/Processes/DevOps.md#unit-testing-and-automated-test) so that they run after every commit. <BR><BR>__Digital Playbook #10__ Automate testing and deployments |
|l|set up or used a continuous integration system to automate the running of tests and continuously deployed their code to their IaaS or PaaS provider | Our development team used [Jenkins](docs/Software%20Development/Screenshots#jenkins) for our [continuous integration](docs/Software%20Development/Processes/DevOps.md#continuous-integration) system to automate running of tests and to perform continuous deployment. <BR><BR>__Digital Playbook #10__ Automate testing and deployments |
|m|set up or used configuration management | We used an internal [GitHub Enterprise](docs/Software%20Development/Screenshots#github) server as our configuration management systems. <BR><BR>__Digital Playbook #4__ Build the service using agile and iterative practices |
|n|set up or used continuous monitoring | We setup and used [Zabbix](http://medexplorer.northropgrumman.com:9001/zabbix/dashboard.php) to perform continuous monitoring of our development/test environment and our production environment. <BR><BR>__Digital Playbook #12__ Use data to drive decisions |
|o|deploy their software in a container (i.e., utilized operating-system-level virtualization) | We used [Docker](docs/Software%20Development/Processes/DevOps.md#continuous-deliverydeployment) as our container system for our MedExplorer prototype. <BR><BR>__Digital Playbook #4__ Build the service using agile and iterative practices <BR>__Digital Playbook #9__ Deploy in a flexible hosting environment |
|p|provided sufficient documentation to install and run their prototype on another machine | We have provided [instructions](docs/Install%20Procedures) for installing MedExplorer in your own Docker container system. <BR><BR>__Digital Playbook #9__ Deploy in a flexible hosting environment |
|q|prototype and underlying platforms used to create and run the prototype are openly licensed and free of charge | The MedExplorer prototype and underlying platforms, components, and frameworks used on the project were [open source licensed](License.md) and free of charge. <BR><BR>__Digital Playbook #13__ Default to open |
