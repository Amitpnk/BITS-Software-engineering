# Object Oriented Analysis and Design 

## Modules 1 (Pre-recorded)

### What is Object Oriented Programming paradigms

![image](../img/OOAD/Module%201%20Paradigms.png)

Program - instructions to perform certain tasks it's called as program. eg: addition of 2 numbers
Programming -  whenever programmer developed this programs that particular activity is called as programming
Software - collection of programs
Procedural - Gives lot of importance to procedure. ie., Logic + Procedure (data or output)
Modular programming - Put logic in different modules (helps in reuse)
Object oriented programming - Gives first important to data and then to logic

![image](../img/OOAD/Module%201%20Paradigms%202.png)

Insted of programming computer to do calculation (mathematical functions), OO programming attempst to model interacting components to build a solution

### SDLC (Software Development Life Cycle)

* Analyze - understand problem (Domain experts like BA)
* Design - solution - intended system (Aware of domain and create blueprint like Architect)
* Implement - system is getting constructed (Coder)
* Test - correctness, performance, usability (Tester)
* Deployment - deploy system  (Release management team)
* Maintenance - fixes & enhancements (Supports)

### Waterfall model

![images](../img/OOAD/Module%201%20waterfall%20model.png)

All the stages are done one after the other from top to bottom. This means that all requirements are gathered first then it is all analyzed and then the design has started. Now it is difficult to add another requirement from the customer till the acceptance phase.

* Requirement and analysis - Analysis
* Acceptance - Deployment and mainteance

It is also called Vendor centric model

Advantages
1.  Simple in approach

Disadvantages
1. Sequential in design no space for concurrency
2. Poor resource utilisation
3. Not friendly changes

### Unified Process

* For simple systems, it might be feasible to sequentially define the whole problem, design the entire solution, build the * software, and then test the product.
* For complex and sophisticated systems, this linear approach is not realistic.
* The Unified Process (UP) is a process for building object-oriented systems.
* The goal of the UP is to enable the production of high quality software that meets users needs within predictable schedules and budgets

<br> <i>Note: </i> 

* for complex and sophisticated system we always require the smarter model like unified process
* UP is change friendly (whenever customer gives any change in the requirement, our SDLC model should be accommodate that * changes)
* the main thing that unified process model and force is UML

#### unified process is different than waterfall model
 
 * Development is organized into a series of short fixed-length mini-projects called iterations. 
 * The outcome of each iteration is a tested, integrated and executable system. 
 * An iteration represents a complete development cycle: it includes its own treatment of requirements, analysis, design, implementation and testing activities. 
 * UML is compulsory to use for Modeling

<br> <i>Note: </i> 

* Full/major project complete project it is divided into small chunks so these small chunks are called as mini projects
* All requirements, analysis, design, implementation and testing activities will be use in mini project
* This mini project will presented to customer 
* this complete project is divided into mini project like m1, m2, m3 etc and for m1 there may be multiple iterations like i1, i2, i3 etc so 

### Iteration Length and Timeboxing

* The UP recommends short iteration lengths to allow for rapid feedback and adaptation.
* Long iterations increase project risk.
* Iterations are fixed in length (timeboxed). If meeting deadline seems to be difficult, then remove tasks or requirements from the iteration and include them in a future iteration.
* The UP recommends that an iteration should be between two and six weeks in duration.

<br> <i>Note: </i> 

* Every mini project is time boxed (short duration), like 2 to 6 week to complete whole mini project and delivery to customer
* Periodic testing and design based on rapid feedback leads to better product
* Gives developers a better understanding of the customers requirements


### UP: An Iterative & Evolutionary Development

* The iterative lifecycle is based on the successive enlargement and refinement of a system though multiple iterations with * feedback and adaptation.
* The system grows incrementally over time, iteration by iteration.
* The system may not be eligible for production deployment until after many iterations.

* The output of an iteration is not an experimental prototype but a production subset of the final system.
* Each iteration tackles new requirements and incrementally extends the system.
* An iteration may occasionally revisit existing software and improve it.

![image](../img/OOAD/Module%201%20UP%20.png)

<br> <i>Note: </i> 
Rapid feedback - so opening up customer at early stage that is called
evolutionary - because your system gets evolved over the time so system grows incremental over the time 


### UP Embracing change 

* Stakeholders usually have changing requirements.
* Each iteration involves choosing a small subset of the requirements and quickly design, implement and testing them.
* This leads to rapid feedback, and an opportunity to modify or adapt understanding of the requirements or design.

<br> <i>Note: </i> 

* UP is change friendly
* Periodic testing and design based on rapid feedback leads to better product
* Gives developers a better understanding of the customers requirements

### UP Phases and Disciplines

A UP project organizes the work and iterations across four major phases:
* Inception -Define the scope of project (like preliminary analysis, feasibility study, estimation)
* Elaboration -Plan project, specify features, baseline architecture.
* Construction -Build the product
* Transition -Transition the product into end user community

![image](../img/OOAD/Module%201%20up%20discipline.png)

<br> <i>Note: </i> 
Inception - Giving proposal 
Elaboration - once get business, plan project and specify features (like detailed analysis, uml artifacts and HLD & LLD design)
Construction - Coding(implementation) and testing
Transition - Deployment, training, user manual

### What is Agilitiy 

OOAD_RL 1.3.1

3:15