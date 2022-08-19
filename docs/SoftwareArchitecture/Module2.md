# Software Architecture 

## Modules 2

### Understanding Quality Attributes

This 3 things is required while taking requirement or capture 
1. Fucntionality
2. Sofware quality attributes
3. Design decisions

#### Functionality

Ability of the system to fulfill its responsibilities

#### Sofwware Quality Attributes 
* It is non functionality properties
* Orthogonal to functionality ()
* is a constraint that the system must satisfy while delivering its functionality 

<br> <i>Note: </i> 
Eg: television set - its functionality is to essentially display pictures, images, videos coming from different sources that's the functionality <br/>
but the quality attributes might be something very different - it might be the quality of resolution, quality of picture, ease of how good it is to integrate with other components, how good is a sound quality. <br/>
For sound recording system or a music player - then its basic functionality is to basically play some audio but it's quality attributes are again how good the is a sound quality how good is a music quality how easy it is to use similarly for software also there is a

<br> <i>Note: </i> 
Functionality is not about how many it can process is about processing a record and non-functional activities that it must be able to complete 5,000 record at least per second

#### Design Decisions
A constraint driven by external factors (use of a programming language, making everything service oriented)

<br> <i>Note: </i> 
In an organization, there could be a design decision that's already taken 
* that a programming language of choice should be something 
* or the platform should be something 
* or the infrastructure should be from a particular vendor
* or a network topology should be like this
* or every single reusable component should be service-oriented 
so these are all the design decisions that are already taken you cannot compromise you cannot even question those are all something that you must adhere to

#### Quality requiements to be consider or followed

* User interface should be easy to use Radio button or check box? Clear text? Screen layout? --- NOT architectural decisions
* User interface should allow redo/undo at any level of depth
--- Architectural decision
* The system should be modifiable with least impact 
    * Modular design is must --– Architectural
    * Coding technique should be simple –-- not architectural
* Need to process 300 requests/sec 
    * Interaction among components, data sharing issues --- architectural
    * Choice of algorithm to handle transactions --- non architectural

### Quality Attributes and Functionality


* Any product (software products included) is sold based on its functionality – which are its features
    * Mobile phone, MS-Office software
    * Providing the desired functionality is often quite challenging
        * Time to market
        * Cost and budget
        * Rollout Schedule

* Functionality DOES NOT determine the architecture. If functionality is the only thing you need 
    * It is perfectly fine to create a monolithic software blob!
    * You wouldn’t require modules, threads, distributed systems, etc.

Eg of Quality Attributes
* Availability
* Performance
* Security
* Usability
* Functionality
* Modifiability
* Portability
* Reusability
* Integrability
* Testability

The success of a product will ultimately rest on its Quality attributes
* "Too slow!"-- performance
* "Keeps crashing!" --- availability
* "So many security holes!" --- security
* "Reboot every time a feature is changed!" --- modifiability
* "Does not work with my home theater!" --- integrability

To address issues, this to be addressed in initial stages

* Needs to be achieved throughout the design, implementation and deployment
* Should be designed in and also evaluated at the architectural level
* Quality attributes are NON-orthogonal
    * One can have an effect (positive or negative) on another
    * Performance is troubled by nearly all other. All other demand more code where-as performance demands the least

* To achieve modify ability you may have to sacrifice performance
* all other attributes actually demand more code but performance actually demands the least amount of code so that it can run faster so there is always going to be a trade-off and that will be the role of the architect


### Defining and understanding system quality attributes

* Defining a quality attribute for a system
    * System should be modifiable --- vague, ambiguous

<br> <i>Note: </i> 
statement like system should be modifiable is quite vague and ambiguous it needs to be clear because unless it
is clear the architect cannot really design a system to address this and it
cannot even communicate this to the stakeholders so it should be so clear
that everybody should be able to understand it in an unambiguous manner so system should be modifiable is really
not a right requirement if someone gives a requirement like this as an architect you should reject this requirement and
you should say that the let's have more specific more clear and unambiguous


* How to associate a failure to a quality attribute
    * Is it an availability problem, performance problem or security or all of them?

<br> <i>Note: </i> 
when a system fail is it because of availability or is it because of performance or is it because security or
is it because of all 


* Everyone has his own vocabulary of quality
* ISO 9126 and ISO 25000 attempts to create a framework to define quality attributes

<br> <i>Note: </i> 
we understand unambiguously what an availability means what a performance means what a security means in this course

### Three Quality Classes

![image](../img/SoftwareArch/Module%202%20Quality%20classes.png)

<br> <i>Note: </i> 

* System quality - quality of the system that you are going to build like modifiability, availability, performance, security, testability, usability.
* Business quality is time to market, cost and benefit, project lifetime, schedules etc some of them do have an impact

In this course will concentrate on system quality only

### Quality Attribute scenario


![image](../img/SoftwareArch/Module%202%20Quality%20attribute.png)

* Who - is basically create scenario
* What - are the condition that system needs to be consider
* Where - is part some part of whole system is affected
* When - stimulus actually occurs, i.e., what was the state of the system when stimulus occurs 
* Which - what activity should be taken as result of sitmulus
* How -measurable response which can be tested for correctness of the quality attribute 

<br> <i>Note: </i> 

DOS attack can happen when the system is in running condition. It can impact maybe module X Y & Z of the entire system. The response is that the X Y & Z should be able to know counter and the measure could be that  response time of the overall system should not be impacted and even if it is impacted should not fall below certain threshold
cyber security can be key together as a requirement and then as an architect you can capture the requirement in this format and then you can use architectural tactics to address 

### Architectural Tactics

To achieve a quality one needs to take a design decision this called tactic
    * Collection of such tactics is architectural strategy
    * A pattern can be a collection of tactics

![image](../img/SoftwareArch/Module%202%20Tatics.png)

<br> <i>Note: </i> 

A tactic is a design decision that influences the achievement of a quality attribute response—tactics directly affect the system's response to some stimulus

