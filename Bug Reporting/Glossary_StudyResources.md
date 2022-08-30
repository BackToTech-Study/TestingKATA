## What is a bug report?

 A written summary/report that should explain how and where exactly the product is broken. It should contain all the required information to understand, reproduce, and fix the bug. 
 A good bug report:

	- contains only one bug

	- has a relevant TITLE

	- has the severity and priority defined

	- contains environment details and user steps that allow the developer to reproduce the bug on his side (Try to narrow the problem down, understand the issue it order to be explicit)

	- description - include more details than the title, like how frequently the bug appears if it is an intermittent error and the circumstances that seem to trigger it.

	- contains actual and expected results 

	- has any additional info that helps the developer easily understand and reproduce it (pictures, console error, videos)

### Bug Reporting Do’s

	- DO read your report when you’re done. Make sure it is clear, concise and easy to follow.

	- DO be as specific as possible and don’t leave room for ambiguity.

	- DO reproduce the bug a few times and try to eliminate any unnecessary steps.

	- If you have found a workaround or additional steps that make the bug behave differently, DO include that in your report.

	- DO check if the bug has already been submitted. If it has, add your details to the bug in a comment.

	- DO respond to developer requests for additional information.

### Bug Reporting Don’ts

    - DON’T include more than one bug in your report. Tracking the progress and dependencies of individual bugs becomes an issue when there are several bugs in the report.

    - DON’T be critical or blaming. Bugs are inevitable and not always easy to fix.

	- DON’T speculate on what’s causing the bug. This can send the developer on a wild goose chase, so stick to the facts.

	- DON’T post anything that is not a bug. Developers love to hear your feedback, but posting it in the wrong channel will only clutter their workflow and cause unnecessary delays.

### Screenshots / Videos

	- Pictures are worth a thousand words, and a screenshot/video is frequently the single most helpful piece of information to a developer trying to fix a bug. A good bug picture includes the URL, the bug highlighted, the console/network tab open.

	- A screenshot/video isn’t a substitute for words, but it can help developers narrow down the problem quicker.
	
### Bug Severity

Severity is how severe a bug is! The severity of a bug is derived based on the effect of that bug on the system. It indicates the level of threat that a bug can affect the system. Severity is divided into levels, such as-Severity:
Realizing the Severity of a bug is critical from risk assessment and management point of view.

	Blocker: The defect affects critical functionality or critical data. It does not have a workaround.  Is a type of a bug that blocks further testing

	Ex: Cannot login and test the application.

	Critical: The defect affects major functionality or major data. It has a workaround but is not obvious and is difficult. 

	Ex: Such bugs disable the app’s main functionality and are primarily fixed.
	(App crashes while performing an operation)

	Major: The defect represents a major loss of functionality. It has a workaround, but major parts of the functionality are missing.

	Ex: The product quantity can only be updated from the cart page.

	Minor: The defect affects minor functionality or non-critical data. It has an easy
	workaround.

	Ex: The text does not fit entirely in an input bar.

	Trivial/LOW: The defect does not affect functionality or data. It does not even need a workaround. It does not impact productivity or efficiency. It is merely an inconvenience. 

	EX: wrong button size
	
### Bug Priority
Priority is how quickly a bug should be fixed and eradicated from the website. Bug priority indicates the sense of urgency for dealing with a bug on our website.

	Low: The repair of the defect can be done once the more serious defect has been fixed

	Medium: During the normal course of the development activities defect should be resolved. It can wait until a new version is created

	High: The defect must be resolved as soon as possible as it affects the system severely and cannot be used until it is fixed
	
### Good to be aware of 

	- Bug Severity is determined by Quality Analyst, Test engineer; whereas, Bug Priority is determined by the Product Manager or by the triage team. 

	- For prioritizing the defect, it is imperative for a tester to choose the right severity to avoid confusion with the development team.

	- Understand the concept of priority and severity well

	- Always assign the severity level based on the issue type as this will affect its priority

	- Assigning a wrong severity to defect can have some drastic implication on the overall performance of the team. 
	
### Bug Severity VS Priority

	Bug Severity examines whether the impact of the bug is serious or not. 
	Bug Priority examines whether the bug should be resolved soon or can be delayed.

	Bug Severity is operated by functionality. 
	Bug Priority is operated by business value.

	Bug Severity, the level of severity is less likely to change. 
	Bug Priority may differ.

	Bug Severity is assessed from a technical perspective of the web-application workflow.
	Bug Priority is assessed from a user-experience perspective on web-application usage.
	
### Bug Rejections

When a bug is rejected, it is considered an invalid bug and hence rejected by the PO, Dev or team.

	Rejections reasons:

	Working as Designed: Expected behavior in the functionality or design of the product. 
	Duplicate: The bug was already reported by another tester or is a known issue.
	Out of Scope: The reported bug clearly falls into what is explicitly stated in the Out Of Scope testing area Did Other: The issue might have been rejected because it is not reproducible anymore.

When a rejected bug should be disputed?

	Always read and understand the rejection message carefully. You may dispute a rejected bug when:

		You are certain you are correct
		The bug can be reproduced, it is in the scope of the cycle/sprint 
		You searched and did not find a duplicated bug 

Best practices when disputing

		State your reasons for disputing clearly
		Always read and understand the rejection reason and decide whether it is appropriate to dispute or not
		Be professional when disputing a bug

Based on the situation and your evidence, your bug might be accepted or rejected again.
