### TASKS
#### Meerkat Team, Andy
1.  v1.0.0 (due 2/28)
	* - [ ] Due 2/25 - Ensure that Platform and QA can move on testing and integration Meerkat v1.0.0
	* - [x] Underway - Work with Program Managment
		* Assist with complete schedule for v1.0.0 release
			* - [x] thoughtful plan
			* - [x] list tasks
			* - [x] list dependencies
			* - [x] timeline with milestones

2.  v1.1.0 (due 3/31)
	* Begins 3/1 - Work with Program Management
		* - [ ] Assist with complete schedule for v1.1.0 release
			* - [ ] thoughtful plan
			* - [ ] list tasks
			* - [ ] list dependencies
			* - [ ] timeline with milestones
	* Due 3/31 - Think of a way to process set of "deep clean" regular expressions.
		* Each bundle of regex expressions will serve as a merchant classifier
		* Nikhil is heading up a team of interns and data analysts to build it in Q1 and Q2.

### DEPENDENCIES
#### v1.0.0 (due 2/28)
1.  Platform Team, Saurabh
	* Initiate standard change management process
		* Change request for load balancer
		* Decide when/whether to terminate the pre-release front-end instances
2.  Operations Team, Bibek
	* Be ready to support the Platform Team
	* Will the mechanism be change requests?
	* How do we streamline this?
3.  Program Managment, Richa
	* Schedule a meeting with to figure out what our QA test environment is for integration
		* Requires QA, Platform, and the Meerkat team.
		* Find out which VPC the test environment is in, either dev VPC or production VPC 
	* Schedule a meeting to go over the transition from the pre-release version of Meerkat to v1.0.0
		* Requires Operations, Platform, QA, and the Meerkat team

### AGREEMENTS / DEADLINES
#### v1.0.0
* 2/25 - Partially done, Does QA need a separate env? - Agree to get testing version of Meerkat
* 2/28 - Release basic transaction origin prediction

#### v1.1.0
* 3/31 - Relesae shadow CT with end-to-end functionality, Meerkat v1.1.0

### RECENTLY COMPLETED
#### Matt
* Compare the lists of txn_type and txn_sub_type labels between Platform and Meerkat
* Add semantic versioning for the v1.0.0 version of Meerkat

#### Andy
* Deploy Meerkat v1.0.0 to production VPC
* Set up a distribution list or equivalent for labels
* Obtain agreement on requiring "ledger_entry" in meerkat web service v1.0.0

