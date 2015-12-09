This is the Presentation & Presentation Slide Deck

# Slide 1
Introduction
-	Open source community is a group established to bring collaboration to resolve issues
-	Free to use and access
-	Provides free source code for software, support, documentation, and variety of expertise
-	Organizations have their own issues in achieving the goals and objectives
-	Information Technology (IT) is always emerging and possess challenges to the organization in reaching the goals
-	Organization cannot always expand and spend while trying to solve each problem
-	Open source is the way to go!

# Slide 2
Problem
-	Developers bring the outside code to the organization’s code base
-	While bringing the outside code, they also bring risks to the organization
-	The risks include licenses and vulnerabilities
-	If the code is modified to tailor the organization’s needs, it needs to be contributed back to the community by the organization
-	Need an efficient method of keeping track of communication between organization and the open source community

# Slide 3
Solution
-	A system as described in the Data Flow Diagram (DFD) model
-	Automate the processes of scanning licenses and vulnerabilities to and from the organization
-	Reduce the efforts for the developers and managers in maintaining the package information
-	Allow managers to properly determine and enforce policies
-	Provide a better way for developers to modify the package and update as necessary
-	This will provide the project manager to access risk associated with the software project
-	Let’s dive in to the deliverables!

# Slide 4
Use Cases
-	Developed three use cases based on the system
-	Corporate manager needs to be able to determine the license and vulnerability information
-	Depends on the  information in the Risk Info Database and project information
-	When corporate manager uploads project information, the scan determines the correct licenses and vulnerabilities
-	Developer should be able to develop, manage and modify the code based on organization needs
-	When the clear requirements are provided by the project manager to developer and the developer have the proper code from the repository
-	Developer needs to be able to maintain the code as outlined in the project requirements
-	Corporate manager needs to be able to determine the requirements to modify the package
-	The latest information about licenses and vulnerabilities needs to be received and reviewed by corporate manager
-	After comparing the current package information with the open source community, manager needs to be able to develop the requirements

# Slide 5
Software Manifest
-	Includes the document license information, and the name and the date of creation
-	Consists of detailed information about the package
-	This includes the package name, SHA1 information, CPE information from the CPE Request forwarded to NVD
-	Also includes all the licenses and vulnerabilities reported for the package
-	For MYSQL Server package, CPE is /a:mysql:mysql:3.23
-	Licenses include CPL, AGPL, Eclipse Public License, etc. including the version numbers for the licenses
-	Vulnerabilities include CVE-2012-3177, CVE-2012-3166, etc. which can be traced back in NVD for detailed information on the risks associated

# Slide 6
Software Policy
-	Includes the context of the policy if it is production source or test source or any other environment
-	Also includes the Licenses and vulnerabilities information
-	Licenses include Copy left and Permissive licenses
-	Copy left includes the modified versions of code
-	Permissive includes the redistribution conditions of the license
-	Vulnerabilities include scores for the risks associated with the package
-	For scores less than six could be yellow and greater is red, which allows to filter the vulnerabilities in the package information

#Slide 7
DFD Dictionary
- Corporate Developer - Plans and execution of a wide range of strategies to meet organizational objectives
- Corporate Manager - The process of leading administrating and directing a company
