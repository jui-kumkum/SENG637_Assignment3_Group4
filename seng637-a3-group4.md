**SENG 637 - Dependability and Reliability of Software Systems**

**Lab. Report #3 – Code Coverage, Adequacy Criteria and Test Case Correlation**

| Group \#:      |     |
| -------------- | --- |
| Student Names: |     |
|                |     |
|                |     |
|                |     |

(Note that some labs require individual reports while others require one report
for each group. Please see each lab document for details.)

# 1 Introduction

Text…

# 2 Manual data-flow coverage calculations for X and Y methods

Text…

# 3 A detailed description of the testing strategy for the new unit test

Text…

# 4 A high level description of five selected test cases you have designed using coverage information, and how they have increased code coverage

2. RangeTest.RangeExpandToinclude()
Before adding the test case RangeTest.expandToinclude(), the coverage calculated using EclEmma was:

| Counter | Coverage |
|----------|----------|
| Instructions/statement coverage   | 85.3%   |
| Methods/Condition   | 100%   |

As we don't have any branch in ExpandToinclude class, so we don't have branch percentage.
The minimum requirement of condition coverage was already met, however 90% statementnt coverage was not met.

When we analysed our test code coverage using EclEmma, we found that few test cases in ExpandToinclude were not covered so to improve the coverage we removed one test case and added null, 10 so that null range is also tested. Also changed lower boundary and upper boundary ranges.
With the addition of new test cases, 
| Counter | Coverage |
|----------|----------|
| Instructions/statement coverage   | 100%   |
| Methods/Condition   | 100%   |
	

# 5 A detailed report of the coverage achieved of each class and method (a screen shot from the code cover results in green and red color would suffice)
![Alt text](https://github.com/jui-kumkum/SENG637_Assignment3_Group4/blob/main/Images/ExpandToincludeBeforeCoverage.png)
![Alt text](https://github.com/jui-kumkum/SENG637_Assignment3_Group4/blob/main/Images/expandToincludeAfterCoverageCondition.png)
![Alt text]()

# 6 Pros and Cons of coverage tools used and Metrics you report

Text…

# 7 A comparison on the advantages and disadvantages of requirements-based test generation and coverage-based test generation.

Text…

# 8 A discussion on how the team work/effort was divided and managed

Text…

# 9 Any difficulties encountered, challenges overcome, and lessons learned from performing the lab

Text…

# 10 Comments/feedback on the lab itself

Text…
