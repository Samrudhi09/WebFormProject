# WebFormProject
## **Title of the Project** : Creating a Web Form using JasonPowerDB

## **Description** :<br/>
Created a form that stores employee entries and can be visualized in tabular form

## **About JsonPowerDB**:<br />
JsonPowerDB is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. JsonPowerDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

## **Benefits of using JsonPowerDB :**<br/> 
Simplest way to retrieve data in a JSON format.<br/>
Schema-free, Simple to use, Nimble and In-Memory database.<br/>
It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.<br/>
It is low level (raw) form of data and is also human readable.<br/>
It helps developers in faster coding, in-turn reduces development cost.<br/>

## **Release Notes**
### v0.3.2.20190205.1721 beta
### 0.3.2 / 2019-02-05
Added: New implementation of Small Token for newly generated connection token.<br/>
Using Small-token, KVPDB request size will be reduced.<br/>
Fast Execution of KVPDB operation.<br/>
Added: JPDB Help in UI of User Dashboard, Now User can directly go to JPDB Help Docs for any API help.<br/>
Improved: User can now add the description of the connection-token, in which application user is using connection-token,
Easy To understand which connection-token is used where.<br/>
Improved: Limit Functionality in JsonPower SQL Query.<br/>
Improved: UI of Company User Management Webpage in Company Dashboard and User Tools Webpage in User Dashboard.<br/>
Changed: User SMTP settings Webpage moved to User Tools Webpage.<br/>
Fixed: Important bugs.<br/>
### v0.3.2.20181127 beta
### 0.3.2 / 2018-11-27
Added: New implementation of JsonPower SQL Query using HTTP REST API.<br/>
User can now query their data using JsonPower SQL Query which is,
Easy To understand.<br/>
Fast.<br/>
Added: Added support to generate a new connection-token.<br/>
To use it directly in any application to access JPDB IML, IRL, IDL, ISL and serverless api.<br/>
Increase security of data as user does not need to provide his user-id and password.<br/>
Added: Added support for creating new column in UPDATE command.<br/>
Added: Added support to get workspace name and workpspace ID of a given workspace in key-value DB.<br/>
Added: Added support to set or change the time limit for user-token.<br/>
Improved: Improved the performance of Backup, PUT and PUTALL command, Commit and Recovery.<br/>
Changed: UI of "User Tools" & "Company-Settings".<br/>
Fixed: Important bugs.<br/>
### v0.3.2.20181004 beta
### 0.3.2 / 2018-10-04
Added: New implementation of Key-Value data structures and supported HTTP REST API.<br/>
Multiple data structure in one Workspace.<br/>
Each Workspace will have one default data structure and multiple 'named' HashMap data structures.<br/>
All Workspace allows key-value pair data to be stored.<br/>
Expire of individual key-value pair can be configured through API.<br/>
Multiple Workspace can exist in Workspace_Pool.<br/>
Separate API for default data structure and HashMap data structures.<br/>
Added: Backup, Download, Upload, Restore and Delete JPDB backups.<br/>
Added: Commit and Recovery with User level controls only if organization / company admin allow.<br/>
Added: Added support for creating the structure of relation without inserting any data.<br/>
Added: Added favicon on all dashboard and in Help documentation.<br/>
Changed: API improved for serverless features.<br/>
Fixed: Important bugs.<br/>
### v0.3.2.20180615 beta
### 0.3.2 / 2018-06-15
Added: Help / Documentation site is created. Check http://login2explore.com/jpdb/
jpdb-common-reference.js: Helper jar Java developers to easy use of JPDB API from java.<br/>
CRUD examples added for JPDB user / developers.<br/>
API reference<br/>
NoSQL reference (2018-06-22)<br/>
NoSQL examples (2018-06-22)<br/>
Added: Added support for automatic indexing of new Columns in request.<br/>
Added: New command API added for 'IS_COLUMN_INDEXED' and 'IS_COLUMN_EXIST'.<br/>
Added: Limits data size per user in request and response for a specfied duration.<br/>
Added: Auto registration of new user in help / support email lists.<br/>
Added: JPDBUtils.jar: Helper jar Java developers to easy use of JPDB API from java.<br/>
Added: Added basic infrastructure for JPDB installations monitoring through JSSM server.<br/>
Fixed: Various Bug fixes and improvements.<br/>
### v0.3.2.20180507 beta
### 0.3.2 / 2018-05-07
Added: Security Layers for API access<br/>
Added: Serverless support for client’s session management<br/>
Added: Serverless support of SMTP Settings for user for sending emails<br/>
Added: Support for System properties like database access limits or restrictions, and status related controls, JPDB and JSSM host details<br/>
Added: Support for company to create and modify email template for sending emails<br/>
Added: Java utility class JPDBUtils.java to help developers to ease development<br/>
Added: Release version is now displayed on user and company dashboard<br/>
Changed: Display warning message on Company Dashboard, if SMTP is not set<br/>
Changed: UI of "Add Index" & 'Unindex Column"<br/>
Fixed: Heartbeat interval<br/>
Fixed: JSSM status admin removed in user management table of JPDB Company<br/>
Fixed: Same JPDB instance can now be both JPDB and JSSM<br/>
Fixed: After User licence limit exceed, a warning message displayed to user who is trying to register<br/>
Fixed: Ambiguity of intallation id resolved<br/>
Fixed: After adding 5 user, if SMTP of company is not set new user will not be able to login to JPDB user dashboard<br/>
### v0.2.7.20170919 alpha
### 0.2.7 / 2017-09-19
Added: Developer dashboard more easy to use, by which developer can insert, remove, update records easily<br/>
Added: NoSQL, using this feature developer can write their own query script in native (java) language and execute that script on JsonPowerDB server<br/>
Added: NoSQL is designed using QueryService interface which contains some ready to use high performance, easy to use query support methods<br/>
Added: NoSQL also has support for passing parameters to the QueryService interface’s execute methods<br/>
Added: User can add new index and remove existing index into/from JsonPowerDB<br/>
Fixed: Restricted indexing on Boolean columns<br/>
Fixed: Method which give accurate file size by deducting deleted record count<br/>
### v0.2.5.20170810 alpha
### 0.2.5 / 2017-08-10
Added: Any Json row if inserted by default it will store in JsonPowerDB<br/>
Added: User have facility to remove database<br/>
Added: User can add new index or column in JsonPowerDB<br/>
Added: User can remove single column in JsonPowerDB<br/><br/>
Fixed: If Column is not added(indexed) in PowerIndex then Error Message returned to the Client<br/>
### v0.2.5.20170718 alpha
### 0.2.5 / 20170718
DBaaS - A Database SAAS: Available as shared environment or as independent server on Internet / Intranet / Extranet / Cloud.<br/><br/><br/><br/>
A Single Instance - Million Indexes: Can support over a million indexed columns in a single instance spread across users and databases.<br/>
Querying Multiple Databases: Allows querying multiple databases which is as simple and fast as querying on single database.<br/><br/>
Serverless Architecture Support: Minimum learning curves, builds faster, cuts time to market, reduces the development cost.<br/>
NoSQL: Native Server Side NoSQL, suitable for high performance real-time data processing.<br/>
REST-API Webservice: Schema-free, Simple to use, Nimble and In-Memory database.<br/>
Developer - Dashboard: Helps developers in faster coding, in-turn reduces development cost.<br/>
PowerIndeX Energized: JsonPowerDB is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.<br/>
