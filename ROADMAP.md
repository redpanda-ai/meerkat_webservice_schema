### TASKS
#### v1.0.0 *(scheduled for 2/28)*
1.  **Meerkat Team**, Andy
	* - [x] Due 2/25 - Ensure that Platform and QA can move on integrating and testing v1.0.0, respectively
	* - [x] Underway - Work with Program Managment
		* Assist with complete schedule for v1.0.0 release
			* - [x] thoughtful plan
			* - [x] list tasks
			* - [x] list dependencies
			* - [x] timeline with milestones

#### v1.1.0 *(scheduled for 3/31)*
1.  **Meerkat Team**, Andy
	* Begins 3/1 - Work with Program Management
		* - [ ] Assist with complete schedule for v1.1.0 release
			* - [ ] thoughtful plan
			* - [ ] list tasks
			* - [ ] list dependencies
			* - [ ] timeline with milestones
	* Due 3/31 - Think of a way to process set of ***deep clean*** regular expressions.
		* Each bundle of regex expressions will serve as a merchant classifier
		* Nikhil is heading up a team of interns and data analysts to build it in Q1 and Q2.

### DEPENDENCIES
#### v1.0.0
1.  **Platform Team**, Saurabh
	* - [ ] Initiate standard change management process
		* - [ ] Change request for load balancer
		* - [ ] Decide when/whether to terminate the pre-release front-end instances
2.  **Operations Team**, Bibek
	* - [ ] Be ready to support the Platform Team
	* - [ ] Determine whether we will always require change requests for this kind of deployment
	* - [ ] Suggest a way of streamlining the deployment
3.  **Program Managment**, Richa
	* - [x] Schedule a meeting with to figure out what our QA test environment is for integration
		* Required Attendees - QA, Platform, Meerkat.
		* - [x] Determine which VPC the test environment is in, either dev or production
	* - [ ] Schedule a meeting to go over the transition from the pre-release version of Meerkat to v1.0.0
		* Required Attendees - Operations, Platform, QA, and the Meerkat team
	* - [ ] Ask Platform Engineering to provide a document similar to this one for their work

### AGREEMENTS / DEADLINES
#### v1.0.0
* 2/28 - Release basic transaction origin prediction

#### v1.1.0
* 3/31 - Release shadow CT with end-to-end functionality, Meerkat v1.1.0

### RECENTLY COMPLETED
#### Matt
* 2/24
    * - [x] Compare the lists of ***txn_type*** and ***txn_sub_type*** labels between Platform and Meerkat
    * - [x] Add semantic versioning for the v1.0.0 version of Meerkat

#### Andy
* 2/25 
    * - [x] Ensured that QA had a valid testing environment for v1.0.0
* 2/24
    * - [x] Deploy Meerkat v1.0.0 to production VPC :+1:
    * - [x] Set up a [distribution list] (https://github.com/joeandrewkey/meerkat_webservice_schema/issues/21) or equivalent for labels
    * - [x] Obtain agreement on requiring ***ledger_entry*** in meerkat web service v1.0.0


