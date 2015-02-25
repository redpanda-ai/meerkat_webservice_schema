### RECENTLY COMPLETED
	1. 2/24
		A. Matt
			* Compare the lists make sure that Platform version of list can be compared to the Meerkat version
		B. Andy
			* Deploy Meerkat v1.0.0 to production VPC
			* Set up a distribution list or equivalent for labels
			* Obtain agreement on requiring "ledger_entry" in meerkat web service v1.0.0

### TASKS
	1. Andy
		__SOON__
		A. Due 2/25 - Launch a Meerkat daemon to handle CT testing data
		B. Due 2/25 - Ensure that Platform and QA can move on testing and integration Meerkat v1.0.0
		C. Due 2/27 - Update Meerkat daemon to handle column re-ordering
		D. Due 2/28 - Presently at 60 nodes
			1.  Performance tune the Elasticsearch cluster so that we get to under 50 nodes
		for a new hire.
		E. Due 2/28 -  Update the Meerkat daemon to deal with
			1.  multiple S3 input and output paths
			2.  report about delays via email / SNS
			3.  handle updated split files by analyzing timestamps
		F. Work with Richa
			1. Provide you with a complete schedule for transaction origin classifier
				a.  thoughtful plan
				b.  list tasks and dependencies
				c.  timeline with milestones

		__LATER__
		G. Due 3/7 - Work with Richa
			1. Provide you with a complete schedule for real-time Shadow Clustering Tool
				a.  thoughtful plan
				b.  list tasks and dependencies
				c.  timeline with milestones
		H. Due 3/7 - Speak to Sanjay's team about the prototype interface for the web service panels
			the realtime and batch enhancement for CT / Shadow CT and transaction origin
		I. Due 3/31 - Think of a way to process set of "deep clean" regular expressions.
			1.  Each bundle of regex expressions will serve as a merchant classifier
			2.  Nikhil is heading up a team of interns and data analysts to build it in Q1 and Q2.

	2.  Matt
		__SOON__
		A.  Get the labelers back on task
		B. Spread around findings from the labelers, the more the merrier.

### AGREEMENTS / DEADLINES
	A. 2/25 - Partially done, Does QA need a separate env? - Agree to get testing version of Meerkat
	B. 2/25 - Update the Meerkat daemon to give CT testing data.
	C. 2/27 - Complete Update for column placement in Meerkat gpanel_v2
	D. 2/28 - Release basic transaction origin prediction
	E. 2/28 - Reduce EC2 infrastructure for Meerkat to 50 nodes.
	F. 3/31 - Relesae shadow CT with end-to-end functionality

### NOTES
	A. Shaja and his data scientists would prefer checkbox to radio button on labeling tool.
	B. Tom has observed that our error rate is good but that they are not unifornly distributed within the panel if you look at "per-merchant" metrics

