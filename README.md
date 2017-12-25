# Ruby-Quick-Reference-Guide
Ruby through code samples

## Table of Contents
* [Hello World](#hello-world)
* [Keywords](#keywords)
* [Comments](#comments)
* [Variables](#variables)
* [Constants](#constants)
* Basic Literals (TODO)
* Backslash Notations (TODO)
* Array (TODO)
* Hash (TODO)
* Ranges (TODO)
* [Class](#class)
* Operators (TODO)
* Conditional Structures (TODO)
* Loops (TODO)
* Methods (TODO)
* Blocks (TODO)
* Modules (TODO)
* Exceptions (TODO)



### Hello World
```ruby
puts 'Hello World!'
```
[back to top](#table-of-contents)



### Keywords
```ruby
__ENCODING__ #The script encoding of the current file
__LINE__     #The line number of this keyword in the current file
def          #Defines a method
defined?     #Returns a string describing its argument
do           #Starts a blockhis keyword in the current file
__FILE__     #The path to the current file
BEGIN        #Runs before any other code in the current file
END          #Runs after any other code in the current file
alias        #Creates an alias between two methods (and other things)
and          #Short-circuit Boolean and with lower precedence than &&
begin        #Starts an exception handling block
break        #Leaves a block early
case         #Starts a case expression
class        #Creates or opens a class
def          #Defines a method
defined?     #Returns a string describing its argument
do           #Starts a block
else         #The unhandled condition in case, if and unless expressions
elsif        #An alternate condition for an if expression
end          #The end of a syntax block.
ensure       #Starts a section of code that is always run when an exception is raised
false        #Boolean false
for          #A loop that is similar to using the each method
if           #Used for if and modifier if expressions
in           #Used to separate the iterable object and iterator variable in a for loop
module       #Creates or opens a module
next         #Skips the rest of the block
nil          #A false value usually indicating “no value” or “unknown”
not          #Inverts the following boolean expression. Has a lower precedence than !
or           #Boolean or with lower precedence than ||
redo         #Restarts execution in the current block
rescue       #Starts an exception section of code in a begin block
retry        #Retries an exception block
return       #Exits a method
self         #The object the current method is attached to
super        #Calls the current method in a superclass
then         #Indicates the end of conditional blocks in control structures
true         #Boolean true
undef        #Prevents a class or module from responding to a method call
unless       #Used for unless and modifier unless expressions
until        #Creates a loop that executes until the condition is true
when         #A condition in a case expression
while        #Creates a loop that executes while the condition is true
yield        #Starts execution of the block sent to the current method
```
[back to top](#table-of-contents)


### Comments
```ruby
#This is a single line comment

=begin
This is a multiline comment
This is a multiline comment
=end
```
[back to top](#table-of-contents)


### Variables
```ruby
_age = 21    #local variable
age = 21     #local variable
@age = 21    #instance variable
@@age = 21   #class variable
$age = 21    #global variable
```
[back to top](#table-of-contents)


### Constants
```ruby
AGE = 21     #constant
```
[back to top](#table-of-contents)


### Class
```ruby
class Customer
end
```
[back to top](#table-of-contents)
