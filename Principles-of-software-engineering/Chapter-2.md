                                                                    Architectural Thinking


THinking like an architect
1. Understand the difference between knowing artchitecture and knowing how to collaborate with development teams to make architecture work
2. Having a wide breadth of tech knowledge while still maintaining a level of technical depth, allowing u to see problems and solutions others cannot see
3. Understanding and analyzing tradeoffs between various solutions and technologies
4. Understanding importance of business drivers and how they translate to architectural concerns


Architecture: Style,Component structuring
Design: Source code,User interface,Class design
Architect and developers must be on the same virtual desk to make things work, Bi-directional communication is required
Architecture and design arent distinct, they both are a part of the circle of life in software world.

You can partition all your knowledge in 3 parts
1. Stuff you know               ->Stuff you must maintain
2. Stuff you know you dont know
3. Stuff you dont know you dont know
As an architect, you should know 5 solutions for a problem

THinking like an architect is all about analyzing tradeoffs in every solution,technical or analyzing those tradeoffss what is the best possible solution
    Architect is the stuff you can't google
    There is no right or wrong in architecture, only tradeoffs
You cant tell if REST or messaging is better, IT DEPENDS
It depends on deployment environment,business drivers,company culture,situation,problem

Queues VS Topics-Subscribe
Using queues requires significant change to the system when adding new bidding functionality,whereas topic approach no changes are needed at allin teh existing
infrastructure. 
PRogrammers knows benefits of everything and tradeoffs of nothing,architects need to understand both

Tradeoffs for Topics
Advantages: Architectural extensibility,Service decoupling
Disadvantages: Data access and data security concerns,no heterogenous contracts,
Analyzing both, architect has to decide which is more important


How to maintain the balance between technical depth and some technical breadth
1. Doing proof-of-work: 
    Whenever possible architect should write the best production code they can
        -> That code can become a reference or guiding example for others to follow
        -> He can practice writing quality coding,rather than learning bad practices

2. Tackle some of the technical depth stories
    These stories are usually low priority so its not the end of the world if the architect cannot complete it

3. Work on bugs

4. Leveraging automation by creating CLI tools and analyzers to help dev team with day to day tasks
    Ex: Fitness functions 

5. Code reviews