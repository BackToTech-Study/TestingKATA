## Change-related Testing

When changes are made to a system, either to correct a defect or because of new or changing functionality, testing should be done to confirm that the changes have corrected the defect or implemented the functionality correctly, and have not caused any unforeseen adverse consequences.


### Confirmation testing

After a defect is fixed, the software may be tested with all test cases that failed due to the defect, which should be re-executed on the new software version. The software may also be tested with new tests to cover changes needed to fix the defect. At the very least, the steps to reproduce the failure(s) caused by the defect must be re-executed on the new software version. The purpose of a confirmation test is to confirm whether the original defect has been successfully fixed.

### Regression testing
It is possible that a change made in one part of the code, whether a fix or another type of change, may accidentally affect the behavior of other parts of the code, whether within the same component, in other components of the same system, or even in other systems. Changes may include changes to the environment, such as a new version of an operating system or database management system. Such unintended side-effects are called regressions. Regression testing involves running tests to detect such unintended side-effects.


Confirmation testing and regression testing are performed at all test levels. Especially in iterative and incremental development lifecycles (e.g., Agile), new features, changes to existing features, and code refactoring result in frequent changes to the code, which also requires change-related testing. Due to the evolving nature of the system, confirmation and regression testing are very important. This is particularly relevant for Internet of Things systems where individual objects (e.g., devices) are frequently updated or replaced.

Regression test suites are run many times and generally evolve slowly, so regression testing is a strong candidate for automation. Automation of these tests should start early in the project.