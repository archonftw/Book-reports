                                            Functions






The 1st rule is functions should be small.
the indent level of a function should not be greater than one or two.

FUNCTIONS SHOULD DO ONE THING ONLY. THEY SHOULD DO IT WELL, THEY SHOULD DO IT ONLY.
there should be only 1 level of abstraction per function

THE STEP DOWN RULE: 
    We want every funciton to be followed by those at the next level of abstraction so that we can read the program

SWITCH STATEMENTS:
    their nature is to be long, so we try to implement it in a lower level class and is never repeated

SINGLE RESPONSIBILITY PRINCIPLE(SRP):
    A class should have one responsibility and should focus on doing that well only

OPEN CLOSED PRINCIPLE(OCP):
    Classes,modules,functions should be open for extension but closed for modification

use descriptive names
long descriptive name >>> short enigmatic name
    It clarifies the design of the moduule in your mind
    Also be consistent in your names
    

Function Arguments
    Ideal number of arguments is 0(Niladic)
    1->monadic
    2->dyadic
    3->triadic
    4or more->polyadic

Argument Objects
    When number of arguments is like 2-3, try wrapping them in objects, it gets easier:
        Circle makeCircle(double x, double y, double radius);
        Circle makeCircle(Point center, double radius);

Functions should either do something or answer something
Doing both often leads to confusion
When you return an error code, you create a problem that the caller must deal with the errir immediately

on other hand, if u use exceptions instead of error codes, then the error processing code can be separated 
from the happy path code and can eb simplified


Try/catch blocks are ugly in their own right. They confuse the structure of the code and
mix error processing with normal processing. So it is better to extract the bodies of the try
and catch blocks out into functions of their own.

if the keyword
try exists in a function, it should be the very ﬁrst word in the function and that there
should be nothing after the catch/finally blocks.

DONT REPEAT YOURSELF
Dijkstra
said that every function, and every block within a function, should have one entry and one
exit. Following these rules means that there should only be one return statement in a func-
tion, no break or continue statements in a loop, and never, ever, any goto statements.

Every system is built from a domain-speciﬁc language designed by the programmers to
describe that system. Functions are the verbs of that language, and classes are the nouns.
This is not some throwback to the hideous old notion that the nouns and verbs in a require-
ments document are the ﬁrst guess of the classes and functions of a system. Rather, this is
a much older truth. The art of programming is, and has always been, the art of language
design.
Master programmers think of systems as stories to be told rather than programs to
be written. They use the facilities of their chosen programming language to construct a
much richer and more expressive language that can be used to tell that story. Part of that
domain-speciﬁc language is the hierarchy of functions that describe all the actions that
take place within that system. In an artful act of recursion those actions are written to
use the very domain-speciﬁc language they deﬁne to tell their own small part of the
story.