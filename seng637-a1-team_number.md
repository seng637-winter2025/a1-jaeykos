>   **SENG 637 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group: Group Number      |
|-----------------|
| Student 1 Ayman Shahriar                |   
| Student 2 Harmandeep Teja              |   
| Student 3 Jae Kang               |   
| Student 4 Xin Wang                |   


**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction

This report covers Assignment 1 for SENG 637, which aims to introduce us to key software testing methodologies, including exploratory (non-scripted) testing, scripted testing, and regression testing. Another important goal was to gain hands-on experience using a defect tracking system and learning how to create clear and informative defect reports. To achieve this, we utilized a defect tracking tool to monitor and log defects identified during testing.  
  
The software under evaluation consisted of two iterations of a simulated ATM system—Version 1.0 and Version 1.1. Since access to the source code was not provided, we exclusively performed black-box testing.  
  
The assignment was a collaborative effort, requiring coordinated scheduling, remote meetings, and discussions via voice calls and text messages. Before working on this assignment, our team had theoretical knowledge of exploratory testing, manual scripted testing, and defect tracking but lacked practical experience in executing these techniques. This assignment provided an opportunity to bridge that gap and refine our understanding through direct application.  
  
As we progressed, we noticed a significant improvement in efficiency. When testing ATM Simulation Version 1.1, we completed the test cases in half the time compared to Version 1.0. The experience gained from the initial version helped streamline our process, making testing Version 1.1 much more efficient.  
  


# High-level description of the exploratory testing plan

Our testing strategy is based on carefully reviewing the requirements document in Appendix B and examining various features as we encounter them.  
  
For instance, if a requirement states that “A customer must be able to view the balance of any account associated with their card,” we will conduct tests to determine whether the system correctly displays account balances across different account types.  
  
Given the large number of functionalities described in the requirements, we will focus on testing a wide range of features rather than conducting an exhaustive analysis of each one. This approach allows us to cover as many aspects of the system as possible.  
  
The goal of this plan is to verify all critical system functions mentioned in the requirements. If we identify a potential issue, we will repeat the test to ensure the defect is real, reducing the chances of reporting incorrect errors.  
  


# Comparison of exploratory and manual functional testing

Exploratory testing allows testers to check the system in a flexible way, without following set test cases or strict rules. The tester chooses which parts to test and how to test them. This approach helped us quickly find the biggest and most obvious bugs, and we were able to test many different features in a short time. However, we did not go through the system in a structured way, so we might have missed smaller bugs. It was also difficult to track what we had already tested, and we didn’t test each function in detail.  
  
On the other hand, manual scripted testing follows a step-by-step process where the tester simply follows pre-written test cases. There is no need to think or make decisions since the goal is to compare expected results with actual results. This method is not creative, but it is very organized.  
  
A major benefit of scripted testing is that it helps keep track of what has been tested. This makes it useful for regression testing because we can easily repeat the same tests after system updates to check for new bugs. Unlike exploratory testing, which quickly finds obvious issues, scripted testing takes a more thorough and systematic approach, covering all the system’s functions. However, some bugs that were easy to find with exploratory testing were either harder to detect or completely missed with scripted testing.  
  
After using both methods, we realized that each has its advantages and disadvantages. Exploratory testing is good for quickly finding major bugs and understanding how the system works, while scripted testing ensures that all features are tested in an organized way. Both methods work well together, helping us find as many bugs as possible.  
  

# Notes and discussion of the peer reviews of defect reports

Before we divided ourselves into pairs, we set up the tracking system for bugs with required inputs, which allowed each pair to report bugs in a consistent manner. This allowed us to peer review each other’s reported bugs efficiently, as everyone in the group was familiar with the formatting.  
  

# How the pair testing was managed and team work/effort was divided 

## Exploratory Testing
Due to the remote nature of our meetings, we set up a dedicated server on an online platform to facilitate communication, share resources, and coordinate tasks. For pair testing, we divided ourselves into two teams: Jae and Xin (Pair 1) and Ayman and Harman (Pair 2). Each pair used separate voice channels to conduct their testing sessions.  
  
Our approach involved systematically going through Appendix B, which outlines the requirements for the ATM Simulation System. We carefully tested each specified requirement on ATM Simulation Version 1.0 to ensure functionality and identify any issues.  

## Manual Scripted Testing
During manual scripted testing, one person read through each test case, another shared their screen showing the ATM system, while the remaining two team members recorded any defects or issues they observed.  

## Backlog Entries
Once the meeting ended, each of us was tasked with adding 5 defects or bugs to the backlog.


# Difficulties encountered, challenges overcome, and lessons learned

The assignment document was overwhelming (due to its relatively large size) and difficult to follow at first. When we met as a group to work on this assignment, we weren’t sure where to start or what to do due to the large amount of info that was put into the document. However, after spending time to carefully go through the document, we managed to figure out what was expected of us in this assignment.  
  
We started this assignment early, and it benefitted us due to the large amount of time we required to finish this assignment. So a lesson learned is to always start working on the assignments as early as possible.  
  
Another challenge we encountered was figuring out how to work in pairs. Initially, due to our lack of experience in exploratory and manual scripted tests and unfamiliarity with the ATM application, we were unable to clearly define individual roles within each pair. To overcome this challenge, every member explored the ATM application and conducted a quick exploratory and manual scripted test, finding few bugs on their own.  
  
Once the methodology became clear to everyone, we decided that each pair should use one laptop for maneuvering the application and another for recording the bugs found. The individuals in pairs took turns maneuvering the application and taking notes on the bugs. The lesson learned here is that everyone should familiarize themselves with the tasks before delegating projects to individuals.  

  

# Comments/feedback on the lab and lab document itself

Initially we had trouble in figuring out how to setup and work on this assignment, so it would have been nice if there was some kind of tutorial that demonstrated what was expected of us in this assignment.  
  
While going through the test cases in the scripted testing phase, we were sometimes confused as there were no clear instructions on which cards to use or how much money should be inserted into the ATM. We feel that these details should be provided in the test cases rather than leaving us to figure them out without knowing what state the ATM simulation should be in. Additionally, some of the manual test case descriptions were rather too vague and could be interpreted in different ways, so it would be helpful to make them more specific.

