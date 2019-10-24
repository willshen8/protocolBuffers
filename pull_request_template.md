# Pull Request Template

## Description

Please include a summary of the change and which issue is fixed. Please also include relevant motivation and context. List any dependencies that are required for this change.

## Jira Link 

(Please copy and paste Jira link here)

## Abstract Link

Please copy and paste any relevant abstract link (if not available on Jira)

## Type of change

Tick the one that matches the change

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)

## How Has This Been Tested?

Please describe the tests that you ran to verify your changes. Provide instructions so we can reproduce. Please also list any relevant details for your test configuration

- [ ] Test A
- [ ] Test B

## Business Acceptance Criteria (if applicable)

Please copy and paste the business acceptance criteria from Jira if applicable.

## Test coverage report 

-[ ] I have run test and ensured that my test coverage is above the threshold 

## General Checklist:

- [ ] My code follows the coding standard and style of this project
- [ ] Common components modification is communicated to other devs
- [ ] I have performed a self-review of my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] My changes generate no new warnings/errors
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes
- [ ] I have added components into storybook (if applicable)
- [ ] I have made corresponding changes to the documentation (if applicable)
- [ ] I have examined SonarQube scanner results or ran locally

## Browser Testing Checklist

This PR has been tested in the following browsers:

- [ ] IE 11 on Windows 10
- [ ] Edge on Windows 10
- [ ] Chrome on Mac
- [ ] Safari on Mac
- [ ] Chrome on iOS
- [ ] default browser on iOS
- [ ] default browser on Android


## Accessibility Testing Checklist

This PR has been tested for accessibility by:

- [ ] Axe accessibility plugin on Chrome
- [ ] Jaws on Windows

## Primary Reviewer Checklist (Mandatory)
- [ ] Checkout the branch to be reviewed. 
- [ ] The new component/s are meeting the unit testing threshold
- [ ] Run the branch and report any eslint issues
- [ ] Run the Axe tool in your console and report any accessibility issue upfront

## Primary or secondary reviewer checklist
- [ ] Run the entire application and check for any console log
- [ ] Inside code check that there is no hard coding
- [ ] All the string are fetched from constants and dimensions from styles global
- [ ] Commented code is not left out 

## Good to have checklist
- [ ] Functional programming and ES6 Syntax
- [ ] There are no instances of multiple div nesting 
