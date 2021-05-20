# service-testing
This repository has been set up to manage testing of services by data scientists.

For example if you have a new service that needs testing, or updates that you want to be checked before they go live etc.

### How to use

Open an issue in this repository. There is a test issue that already exists as an example.

A template will be generated which will guide you through what to fill out.

It looks like this:

```
Developer in charge: 
Requested reviewer(s): 
(Don't forget to tag and assign the reviewers to this issue!)

Service to be tested: 
Link to service:
Version to test (e.g. a tagged version/ most recent version):

Instructions to set up testing environment:

What type of review is needed? 
(example below or add your own/ add more detail as required)

- [ ] Component testing: Testing a component independently 
	Details:
	
- [ ] Smoke testing: Testing that the critical functionality of the service is working. Checking that no show stopper defects exist
	Details:

- [ ] End to End testing: Testing of a complete application environment in a situation that mimics real-world use e.g. would include interaction with database if needed
	Details:

- [ ] Ad-hoc testing: Try to find defects by trying random workflows/ functionality
	Details:

- [ ] Acceptance testing: Last phase of testing - testing that the end to end flow of the service is as required.
	Details:

Other actions required:

More information:

Tag this issue in an appropriate issue in the repository of the service being tested if possible (i.e. copy and paste the link to this issue)
```

It is useful to add the issue to the project board: https://github.com/cedadev/service-testing/projects/2 and move it into the appropriate column as each step is completed.

It is also important to tag and assign the issue to the person you want to test the service, and to copy and paste the link to the issue you create in an appropriate issue in the repository of the service to be tested.
