### TASKS
	1. Meerkat Team, Andy
		__v1.0.0__ (due 2/28)
		A. Due 2/25 - Ensure that Platform and QA can move on testing and integration Meerkat v1.0.0
		B. Work with Richa
			1. Provide you with a complete schedule for transaction origin classifier
				a.  thoughtful plan
				b.  list tasks and dependencies
				c.  timeline with milestones

		__v1.1.0__ (due 3/31)
		C. Due 3/7 - Work with Richa
			1. Provide you with a complete schedule for real-time Shadow Clustering Tool
				a.  thoughtful plan
				b.  list tasks and dependencies
				c.  timeline with milestones
		D. Due 3/31 - Think of a way to process set of "deep clean" regular expressions.
			1.  Each bundle of regex expressions will serve as a merchant classifier
			2.  Nikhil is heading up a team of interns and data analysts to build it in Q1 and Q2.

### DEPENDENCIES
	__v1.0.0__ (due 2/28)
	1.  Platform Team, Saurabh
		A.  Initiate standard change management process
			i.  Change request for load balancer
			ii. Decide when/whether to terminate the pre-release front-end instances
	2.  Operations Team, Bibek
		A.  Be ready to support the Platform Team
			i.  Will the mechanism be change requests?  How do we streamline this?
	3.  Program Managment, Richa
		A. Schedule a meeting with to figure out what our QA test environment is for integration
			i.  Requires QA, Platform, and the Meerkat team.
			ii. Find out which VPC the test environment is in, either dev VPC or production VPC 
		B. Schedule a meeting to go over the transition from the pre-release version of Meerkat to v1.0.0
			i.  Requires Operations, Platform, QA, and the Meerkat team

### AGREEMENTS / DEADLINES
	__v1.0.0__
		A. 2/25 - Partially done, Does QA need a separate env? - Agree to get testing version of Meerkat
		B. 2/28 - Release basic transaction origin prediction
	__v1.1.0__
		C. 3/31 - Relesae shadow CT with end-to-end functionality, Meerkat v1.1.0

### RECENTLY COMPLETED
	1. 2/24
		A. Matt
			* Compare the lists of txn_type and txn_sub_type labels between Platform and Meerkat
			* Add semantic versioning for the v1.0.0 version of Meerkat
		B. Andy
			* Deploy Meerkat v1.0.0 to production VPC
			* Set up a distribution list or equivalent for labels
			* Obtain agreement on requiring "ledger_entry" in meerkat web service v1.0.0


