This is the Three Use Cases

# Use Case 1
Title: Determine License and Vulnerability Information

Primary Actor: Corporate Manager

Goal in Context: The corporate manager is able to determine license and vulnerability information from the provided project information

Stakeholders:
  Corporate Manager: To receive clear and relevant project information;
  Corporate Developer: To provide the relevant file/package level information;
  Project Owner: To clearly understand corporate manager decisions to free/red light a project

Pre-conditions:
  Relevant file/package information is in the SPDX database;
  Proper project information has been provided

Main Success Scenario: Corporate manager receives accurate license and vulnerability information for the requested project packages

Failed End Conditions: Corporate manager receives invalid license and vulnerability information for the requested project packages

Trigger: Corporate manager uploads and identifies project information to which license and vulnerability information is provided

# Use Case 2
Title: Develop, modify and manage the code based on organization needs

Primary Actor: Corporate Developer

Goal in Context: The corporate developer is able to develop code to meet organizational needs, modify the code as required and manage the code base through version control.

Stakeholders: 

Corporate Manager: To receive up to date code as per project requirements

Corporate Developer: To maintain the code as outlined in the project requirements

Project Owner: To coordinate the development efforts for the project requirements

Pre-conditions: 

Proper code has been received from the repository

Clear requirements have been provided for the project

Main Success Scenario: Corporate developer correctly develops the project requirements, modify the code without any issues, and maintain the proper version in the repository 

Failed End Conditions: Corporate developer cannot modify the code as required, and cannot resolve issues while developing the code

Trigger: Corporate developer receives the finalized project requirements

# Use Case 3
Title: Determine and set Open Source Software Policies

Primary Actor: Corporate Manager

Goal in Context: The corporate developer is able to determine the information flow to and from the organization and set software policies.

Stakeholders: 

Corporate Manager: To receive clear information to and from open source community

Corporate Developer: To provide relevant information to corporate manager

Project Owner: To accurately understand the policies set by the corporate manager

Pre-conditions: 

Accurate and relevant information has been provided to and from open source community

Updated package information has been provided by corporate developer

Main Success Scenario: Corporate manager correctly set up the software policies 

Failed End Conditions: Corporate manager cannot setup software policies

Trigger: Corporate manager receives current information from open source community and updated package information

