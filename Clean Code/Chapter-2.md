                                            Meaningful Names




Use intention revealing names, it should tell you why it exists,what it does,how it is used
                                (If a name requires a comment, then the name does not reveal its intent)

Ex: cell[STATUS_VALUE]==FLAGGED <<<<< cell.isFlagged()

AVOID DISINFORMATION: DO not refer to a grouping of accounts as an accoundList unless its actually a List
- Beware of using names which very in very small ways   
    Ex: XYZControllerForEfficientHandlingOfStrings &&&& XYZControllerForEfficientStorageOfStrings
A very awful example of disinformation: lowercase L(l) and Uppercase o(O)   
int a = l;
if ( O == l )
a = O1;
else
l = 01;



Make meaningful distinctions: 
    Programmers make problems for themselves when they write code solely to satisfy a compiler or interpreter
    It is not sufﬁcient to add number series or noise words, even though the compiler is
    satisﬁed. If names must be different, then they should also mean something different.
    
    Noise words are redundant. The word variable should never appear in a variable
    name. The word table should never appear in a table name. How is NameString better than
    Name?

Use pronounceable names:
Use searchable names: 
    Single-letter names and numeric constants have a particular problem in that they are not
    easy to locate across a body of text.
    Longer names > Shorter names

Single letter names can ONLY be used as local variables inside short methods
length of a name should correspond to the size of its scope

Your classes and function should be small enough that you dont need them
Avoid using prefixes(m_ or f_), they are bad


Avoid Mental mapping:
    Readers shouldn't have to mentally translate your names into other names they already know
    

-------------------CLARITY IS KING-----------------------

CLASS NAMES:
    Classes and objects should have noun or noun phrase names like Customer, WikiPage,
    Account, and AddressParser. Avoid words like Manager, Processor, Data, or Info in the name
    of a class. A class name should not be a verb.

METHOD NAMES:
    Methods should haave verb or verb phrase names like postPayment,deletePage,saveProfile
    Acccessors,mutators and predicates should be named for their value and prefixed with get,set,post,is

DONT BE CUTE:
    Choose clarity over entertainment value
    whack()<kill()      SAY WHAT YOU MEAN,MEAN WHAT YOU SAY

PICK ONE WORD PER CONCEPT:

DONT PUN:
    Avoid using the same word for 2 purposes, its called a pun


ADD MEANINGFUL CONTEXT:

USE SOLUTION DOMAIN NAMES:
    USE CS terms,algo patterns,pattern names,math terms ans so on for naming
    Ex; AccountVisitor,JobQueue

