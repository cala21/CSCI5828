## Camilla Lambrocco
# Homework 1: No silver bullet

***

##Question 1
*Define the term essential difficulties as it is used by Brooks. Provide background and context with your answer and at least one example of an essential difficulty.*

In such an emerging technological culture we are exposed to several problems. One of these is that hardware can’t keep up with the incredible software requirements. Not only hardware seems to fail Moore’ law but also we observe software difficulties. Brooks identifies several obstacles to software development: essential difficulties and accidental difficulties.

Essential difficulties, as described by Brooks, are those difficulties inherent in the nature of the software.

The essence of a software entity is the collective of algorithms, data sets, functions and the relationships amongst the data items. These are inherently the building blocks of software development. Thus, essential problems deal with the primordial and conceptual structure of a software, indeed its essence. To develop a software it means to develop a vision which entangles the building blocks just mentioned. 

For example, the choice of creating a compiler in Java exposes the programmer to a detailed implementation which can be far more difficult then other implementations; the programmer has to adapt and deal with it because the problem (the specific requirements required by the Java) cannot be removed.

***

##Question 2
*Define the term accidental difficulties as it is used by Brooks. Provide background and context with your answer and at least one example of an accidental difficulty.*

Accidental difficulties are those difficulties related to the production of software; they are artificial barriers such as 

>“hardware constraints, lack of machine time and awkward programming languages”.

These are problems which experts create and thus can fix; they are usually related to the production of software. 
For example, if we struggle with a not intuitive language, like Fortran, to achieve a certain goal which could be achieved using OO and a higher level language, we would fix the problem and have a faster production of qualitative code by adopting python as our coding language. 

***

##Question 3
*List and briefly describe the four essential difficulties of developing software systems that Brooks identifies. Provide additional examples of each type of the four essential difficulties.*

Brooks identifies four subcategories of essential difficulties:
* complexity
* conformity
* changeability
* invisibility

**Complexity** derives from the different layers of structure of the software. This translates in a huge number of states. Moreover, there is no linear correspondence of complexity when a system increases but rather exponential. An example of this can be the bionic prosthetic system: a prosthetic limb has to be able to interact with nerves skin and has to malleable to depending on the specific body. The software that menages it has to be able to interact with a variety of hardware components which might not be from the same producer, thus introducing heterogeneity. 

**Conformity** is a kind of difficulty seen when the system is prone to changes. If a particular system changes the software needs to be scalable and dynamic enough to not have to be rebuilt. Although this difficulty is not essential because it is introduced by man kind and therefore it has an overarching design, the software must conform to the environment in which it exists, and this adds an essential difficulty of design.
For example, if at CU it is introduced a new school which allows students to not have a due date for when they can drop a class so they can always be refunded, our system has to now be compatible with this new feature and the old features (still applicable to the other schools - i.e. engineering, art and science etc…).

**Changeability** goes along with *conformity*; *changeability* is, indeed, the essential difficulty that deals with the fact that a software has to grow and change constantly. Visa USA has an incredible cybersecurity system; however, the field of cybersecurity is relatively new and unknown. Hackers finds continuously new ways to break into the systems, thus Visa needs to continuously update their softwares to protect the system form new creative attacks. 

**Invisibility** is the essential difficulty which delineates the inherit property of a software: the code is “invisible” and “intangible”. For example PrePaid (an internal Visa application) has a lot of abstraction and it is really difficult to have a complete view of the web api when you have to work on it. If refactoring is needed, this can represent a problem.

***

##Question 4
*Define what Brooks means by a silver bullet and reconstruct his argument as to why he believes there is no silver bullet for software engineering.*

In lecture we discussed the concept of silver bullet and we developed its definition: 
>a “silver bullet” is single technique or technology that by itself can deliver one order-of magnitude improvement to some aspect of software development. 

For Brooks there are not silver bullets in the sense that there is no actual 
*“cure against the software crisis”*. Indeed, for what concerns essential problems, Brooks argues that 
>“no single technique could produce an order of magnitude increase by itself.”

Moreover, in Brooks’ opinion, most techniques attack the accidents of software engineering which more or less count for 90% of the overall effort. In order to have a 10-times improvement we would have to reduce accidental problems to zero, thing that Brooks doesn’t believe to be possible because to reduce accidental problems we should introduce new tools which would introduce new problems.

***

##Question 5
In lecture, software engineering's relationship to computer science was described by analogy by discussing the differences between a chemist (chemistry) and a chemical engineer (chemical engineering). Define software engineering and its relationship to computer science; make use of the chemist vs. chemical engineer analogy when answering this question.

Software engineering is that field of engineering which mission is to implement a functional product. The product is based on a vision and it is implemented using techniques and algorithms developed in computer science. A chemist studies the peculiar features of a substance an derives its property. S/he develops a theory on how to use it so that the chemical engineer can apply the theory developed by the chemist and deliver a marketable product which entangles several theories and processes. Like the chemist, a computer scientist aims to study a characteristic problem to derive a theory on how to solve it or to improve the existing solution. Like a chemical engineer, a software engineer aims to produce an end product that can be distributed in the market (a pill in case of the chemical engineer, a software in case of the software engineer).

***

##Question 6
*In lecture, we discussed the importance of the following concepts to software engineers: abstractions, conversations, specification, translation, and iteration. Define each of these concepts as they are related to software engineering and discuss their importance.*

####Abstractions
Abstraction is a praxis that developers use to avoid repetitions of a certain structure. It is an important part of software engineering because it breaks the problem down into something that is easier to understand. Examples of abstractions are databases, APIs etc… .


####Conversations
Conversation is the verbal interaction that happens amongst a group of people. It is what we need to understand a problem, to solve it, to understand a part of code that another developer created, to write code and to make sure every part of the software we wrote is working properly.

####Specification
Specification is a detailed layout of the component described; it describes requirements (functional and non-functional), “*it includes design, code, test plan and life cycles*” (slides week 1.) It is important in software engineering because it provides the engineers with the needed knowledge to develop a successful product.

####Translation
In software engineering a developer is mainly a translator. The translation happens, indeed, continuously amongst specifications, abstractions and structures. Translation makes the product scalable, available and flexible.

####Iteration
Iteration is defined as the repetition of a certain task/action/procedure. Both in programming and in the development phase iteration constitutes the cell of the project. “The work of a software engineering is done iteratively” (slides week 1), the behavior of a program is mostly iterative. Iteration defines a methodology and thus a behavioral praxis. 