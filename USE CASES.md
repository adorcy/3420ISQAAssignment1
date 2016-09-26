#Use Case 1

###Title: 
    Determine License and Vulnerability Information
###Primary Actor: 
    Manager
###Goal in Context: 
    The manager is able to determine license and vulnerability
    information from provided project information
###Stakeholders:
    Manager: To receive clear and relevant project information
    Developer: To provide the relevant file/package level information
###Preconditions:
    Relevant file/package information is in the OSS component database
    Proper project information has been provided
###Main Success Scenario: 
    Manager receives accurate license and vulnerability
    information for the requested project packages
###Failed End Conditions: 
    Manager receives inaccurate or invalid license and
    vulnerability information for the requested project packages
###Trigger: 
    Manager uploads or identifies project information to which license and
    vulnerability information is provided


#Use Case 2

###Title:
    Add Software to the OSS Component Database
###Primary Actor:
    Corporate Developer
###Goal in Context:
    The developer is able to scan a new piece of software for 
    vulnerabilities and OSS licenses and then add that software to the 
    OSS Component database
###Preconditions:
    the developer must have a new software to add
    Security vulnerabilites must be listed in the NIST Vulnerability database.
###Main Success Scenario:
    Developer submits new software to scan for licenses and vulnerabilities
    and the results are added to the OSS Component database
###Failed End Conditions:
    The software has already been added to the OSS Component database.
    The software is not listed in the NIST Vulnerability database.
    The software has no OSS licenses
###Trigger:
    Developer submits a piece of software that is then tested for vulnerabilities 
    and OSS Licenses
