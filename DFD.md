This is the DFD file. We're going to use this file to display our Data Flow Diagram


This is the Data Flow Diagram for the class project




This is the DFD submission for 9/14/2016

![alt text](https://cloud.githubusercontent.com/assets/21319727/18532883/c397ada4-7aa4-11e6-8e7d-dfd6f42e39e3.PNG)



DFD dictionary

Developer - An entity that submits software packages to be searched for OSS components and used to populate the OSS component                     database.

Software Package - The software that a developer submits to be scanned for OSS licenses

Manage Software Package for License Scanning - A process which handles the software package scanning and sends the Software Package                                                     License Results to the database and the developer.

Scan for Licenses - The process that scans the submitted software for OSS licenses and returns the results to the Manage Software                         Package for License Scanning process.

Software Package License Results - The OSS component results of the Scan for Licenses process.

OSS Component Database - This is the database that stores the Software Package License Results for retrieval.

Manager - An external user who requests data from the OSS Component Database.

Data Manager Requested From OSS Component Database - This is the data that managers request from the OSS Component Database.

Request Data From Database - This is the process that handles the manager requests.

Data OSS Component Database Returned for Manager's Request - This is the data that the OSS Component Database returns to the Manager.
