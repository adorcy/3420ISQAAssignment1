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
    Relevant software information is in the OSS component database
    Proper project information has been provided 
###Main Success Scenario: 
    Manager receives accurate license and vulnerability
    information for the requested project packages
###Failed End Conditions: 
    Manager receives inaccurate or invalid license and
    vulnerability information for the requested project packages
###Trigger: 
    Manager identifies project information to which license and
    vulnerability information is provided


#Use Case 2

###Title:
    Add Software to the OSS Component Database
###Primary Actor:
    Developer
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


#Use Case 3 -- I don't think that you actually do this in your DFD. Not to say that it would be a bad use case, I just don't think that Developers can currently update exisitng information in the DB, based on your existing DFD. I think that a better case here would be that the Manager can update OSS policy. Or, the developer or manager and retrieve OSS Project License and Vulnerability Information. 

###Title:
    Manager can update OSS Policies
###Primary Actor:
    Manager
###Goal in Context:
    The Manager is able to update the company's OSS licenses and vulnerabilities 
    policies in the OSS Source policy documents database.
###Preconditions:
    The policy the manager wants to update must be in the database
    The manager must have changes to make to the policy
###Main Success Scenario:
    The Manager submits a change to a policy document already in the OSS Source 
    policy documents database and the changes are stored in the database.
###Failed End Conditions:
    The policy that is being changed is not in the database
    The Manager does not make any changes to the policy
###Trigger:
    The Manager submits a policy document with changed information to the OSS Source 
    policy documents database. Those changes are then stored on the database.

