# Checklist - QA/QR Setup From Scratch

## Support
- [ ] Where is customer support done?
- [ ] Do clients like the customer support?
- [ ] Are there granular statistics about issues and customer satisfaction?
- [ ] How does customer feedback reach development team?

## Ideas Management
- [ ] Is there a system in place to collect ideas of team members?
- [ ] Are the ideas reviewed regularly?

## Product specifications
- [ ] Are they stored somewhere in written form and can be read/studied by team?
- [ ] Are they maintained properly and under version control? Maintained by whom specifically?

## Quality Control questions

### Budget
- [ ] How many paid QC hours are available per month?
- [ ] Is the budget stable?

### Releases
- [ ] What positive impact will have regular and reliable product releases have on clients?
- [ ] What is our release cycle? How often do we want to release?

### Risk analysis
- [ ] Create list. Aim: Failure of what functionalities will create the greatest damage and need to be therefore prioritized in testing?

### Testing Pyramid Implementation
- [ ] Create immediately some happy path UI test cases and schedule regular execution of these
- [ ] Check how many unit tests exist and what functionality they are covering
- [ ] Can API testing be implemented? If there are no APIs why not?
- [ ] Is contract testing needed?
- [ ] What is the plan for keeping the Testing Pyramid a pyramid?

### Static Testing
- [ ] Do QA/QR members review Product Specifications regularly so that possible ambiguities/contradictions/missing pieces can be caught very early?

### Black-box Testing aka Dynamic Testing
- [ ] Create test cases which cover areas with highest risk
- [ ] Check if test cases cover more than just the happy path

### Performance Testing
- [ ] Stress test app to find the limits when app collapses.
- [ ] Soak test app with high load for a week.
- [ ] What is the contingency plan for unusual stress?


### Automated UI testing
- [ ] Is it clear why “automating everything” is next to impossible?
- [ ] Has analysis been conducted to find out what areas of app can be tested and which not?
- [ ] Are there proof-of-concepts from this analysis phase?
- [ ] How many work hours per month are there available to maintain the tests?
- [ ] Does team understand why/how to keep track of needed maintenance efforts?

### Mind Set
- [ ] Does QC team understand that a company is an entity which must stay profitable?
- [ ] Is QC team able to provide management with clear and simple “Return-of-Investment” calculations for automated testing?

### Cultural Aspects
- [ ] Are we aiming for the one “SDET+DevOps+QA” super person, or rather the future “QA+SDET+DevOps” super team?
- [ ] Choice of programming language for automation: Why were programming languages invented in the first place?
