#COMPLETED

#1.  Finish personal self-assessment
#2.  Upgrade Matt's self-assessment
#4.  Get the labeling demonstrated
#5.  Confirm that the delivery of the web service is good, as per Richa
#7.  Obtain documentation for how to deploy for Richa.
#8.  List of knowns and unknowns about Meerkat by monday morning to Chris.
#9.  List the layers of the technology stack for Chris by Monday morning

# Completed 2/10 1.  Get the extra column for GPANEL2 up and running so that we don’t fail to meet commitments on this newest version of the panel.
# Completed 2/10 3.  Get YSO rolling on giving ProPalms access for 3 more labelers in IAE so that we don’t fail to meet our 2/28 deadline for building a transaction origin classifier.
# Completed 2/10 1.  Need to provide access to Meerkat web service API to Saurubh and Richa.

# Completed 2/12 DONE:8.  Deepu needs s3 access
# Completed 2/13 0.  Andy - Nikhil needs to know by 3PM if you have time to help with SCData's permissions

#4.  Andy - DELAYED - Hard commit Monday at 9AM - Filling out YSO forms so that we can continue to use GitHub for source control because we need that tool as much as anything else in our technology stack.
#0. Completed 2/13  Matt - Web Service seems broken
#1. Manik - Partially done -  Platform engineering needs some tips, not new logs, schedule a meeting and offer suggestions.
#6. Failed 2/17 Tom - Following up on Zac Stewart’s candidacy to join the team, so that we have the bandwidth to actually finish things on time in 2015.  This is finishing up and we got Zac Stewart.

# Completed - Agreed to speak to brian conerning the labeling tool, to get them to open up.
#Restart the daemon
#Sanjay has a concern about

#Get moving ont the dumb integration.  1336
#Finished a dummy one tomorrow.

#Get Sanjay moving on
#!!! START writing down expectations and deadlines

		# Completed 1-18 A. GitHub assessment form, Brian made the request
		# Rejected 1-18 C. Work with Tom to figure out the status of the Job Description, before I make one for Debi and HR.

RECENTLY COMPLETED
	2/24
		Matt
			Compare the lists make sure that Platform's list, ensure no typos
		Andy
			Deploy Early integration with the platform, Plan to put bogus data into transaction origin type and subtype.
			Set up a distribution list or equivalent for labels, as they affect Richa, Saurubh, and Siva and their platform delivery.
			Obtain agreement to require "ledger_entry" in meerkat web service input_schema in production

TASKS
	Andy
		SOON
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

		LATER
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

	Matt
		SOON
			A.  Get the labelers back on task
		2. Spread around findings from the labelers, the more the merrier.

1.  Performance tuned the elasticsearch cluster, 29 
2.  IAE labeling seems to be progressing, but we have a few notes.
3.  Deployment window tonight for newest version of Meerkat which included transaction origin classifier.
4.  Up to bat, 

AGREEMENTS / DEADLINES
	B. 2/25 - Partially done, Does QA need a separate env? - Agree to get testing version of Meerkat
	C. 2/25 - Update the Meerkat daemon to give CT testing data.
	D. 2/27 - Complete Update for column placement in Meerkat gpanel_v2
	F. 2/28 - Release basic transaction origin prediction
	G. 2/28 - Reduce EC2 infrastructure for Meerkat to 50 nodes.
	H. 3/31 - Relesae shadow CT with end-to-end functionality

NOTES:
	1. Shaja and his data scientists would prefer checkbox to radio button on labeling tool.
	2. Tom has observed that our error rate is good but that they are not unifornly distributed within the panel if you look at "per-merchant" metrics
	3. Home Security - Drop-cam, camera with sensors and stream video to your phone. motion sensors zwave, virulite
	4. Ponder why we couldn't hit end of Feb and March.
	5. Anand recommends 'Imitation Game" on Netflix.

PLANS:
CT Shadow and Transaction Origin
	A week or two labeling, a day fiddling.
	We should have the multi-class classifier.
	Schedule an end-to-end test.
	So we'll have the CT replacement.

