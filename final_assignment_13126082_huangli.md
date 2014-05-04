How to ensure the quality of diandian app
=====
Huang Li (13126082)

-----
The SQA course is very useful to us, I have learned a lot from it. In this course we know software testing or quality assurance is an area of work which is often completely invisible to users. It is however a vital part of production process, essential in giving us the confidence we need when we make a new release of software. Taking the diandian(点点单词) as the target system, we can have an overview of how to ensure the quality of a software system.

## Test early and often
___
Quality should be built in throughout the development life cycle rather than tested in at the end of a project. After we start diandian(点点单词) project, We shall test what we do, whether it’s design, code, or documentation, early and often so that defects are found while the work is still fresh in people’s minds and before the defects can become too deeply embedded in the software.

## Minimise variation
___
Any customisation of the software introduces variation which needs to be tested and maintained for every version of the app. Lean manufacturing has taught us that by minimising variation and developing apps which work for people out of the box we can reduce costs and more thoroughly test what we make, increasing the value of what we do for our users. 

## Build in flexibility
___
Where there is a common need for the same customisation from lots of users we shall try to allow for this by building flexibility into the system. This limited and known variation can be accounted for when testing and does not add a huge cost overhead to our development process, while at the same time allowing our users to change the things they need to.

## Use great tools
___
Tools like Selenium, Jenkins and so on can enable us to run automated tests on our apps to ensure that any changes we make don’t break the existing features which our users rely on. We shall continually make use of these tools throughout our development cycle.

## Try out new ideas
___
We shall always eager to learn about anything which might help us increase the quality and value of what we produce. 

## Use the six functional tests to ensure software quality
	Six types of functional testing can be used to ensure the quality of the diandian(点点单词) app. Understand these testing types and make the most of them to fulfill the quality requirements of the project.

-	Ensure every line of code executes properly with Unit Testing.
	-	Function coverage: Each function/method executed by at least one test case.
	-	Statement coverage: Each line of code covered by at least one test case (need more test cases than above).
	-	Path coverage: Every possible path through code covered by at least one test case (need plenty of test cases).

-	Ensure every function produces its expected outcome with Functional Testing.
-	Ensure all functions combine to deliver the desired business result with System Testing. 
-	Ensure new changes did not adversely affect other parts of the system with Regression Testing. 
-	Ensure the system integrates with and does not adversely affect other enterprise systems with System Integration Testing. 
-	Ensure the user is satisfied with the system with Acceptance Testing.  	
	
