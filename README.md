# Capabilities Update

Web service to update model layer of Capability Areas features of MII, including Technical Capabilities Areas (TCA) and Domain Capabilities Areas (DCA)

## Getting Started

Our team communicates via the Microsoft Office 365 Group, [EDGTeam](mphelan@fas.harvard.edu).

### Tools

This project is implemented using [SPARQL Web Pages](https://uispin.org/) (SWP). Our Ontology Editor is [TopBraid EDG](https://www.topquadrant.com/products/topbraid-enterprise-data-governance/). Our Integrated Development Environment is [TopBraid Composer](https://www.topquadrant.com/products/topbraid-composer/). We express our Resource Description Framework (RDF) graph using [Terse RDF Triple Language](https://www.w3.org/TeamSubmission/turtle/) [with extensions](https://composing-the-semantic-web.blogspot.com/2013/06/an-extended-turtle-format.html) (TTLX).

### Dependencies
The service relies upon the availability of additional company-interal web services.
The orgs services relies upon the [Enterprise Data Services](https://www.google.com) [human resources organizations endpoint](https://www.google.com).

### Deployment
#### Manual
##### Send the package to the development server
Under Project Explorer, context-click on your project
Choose Export...
Select an export wizard: General, Archive File
Choose Next button
Ensure that .project and the .ui.ttlx file are selected in the right-hand side pane
To archive file: <PATH_TO_LOCAL_ECLIPSE_WORKSPACE>\<YOUR_FILE_NAME>.zip
choose Finish button

Login to EDG server
Server Administration, Deployment and Export, Upload Project
Unless this is the first upload, you must select from the radio buttons among "Delete old project" and "Update old project"
