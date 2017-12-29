# Ruby-Quick-Reference-Guide
Ruby through code samples

## Table of Contents
* [Hello World](#hello-world)
* [Keywords](#keywords)
* [Comments](#comments)
* [Variables](#variables)
* [Constants](#constants)
* [Integer Numbers](#integer-numbers)
* Floating Numbers (TODO)
* Strings (TODO)
* [Backslash Notations] (#backslash-notations)
* Literals (TODO)
* [Arrays](#arrays)
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
* I/O (TODO)



### Hello World
```ruby
puts 'Hello World!'
```
[back to top](#table-of-contents)



### Keywords
```ruby
__ENCODING__  # The script encoding of the current file
__END__       # Marks the end of the Ruby program; DATA can follow  
__FILE__      # The path to the current file
__LINE__      # The line number of this keyword in the current file

BEGIN         # Runs before any other code in the current file
END           # Runs after any other code in the current file
DATA          # An IO stream to read data embedded in the program following __END__

def           # Defines a method
defined?      # Returns a string describing its argument
do            # Starts a block
alias         # Creates an alias between two methods (and other things)
and           # Short-circuit Boolean and with lower precedence than &&
begin         # Starts an exception handling block
break         # Leaves a block early
case          # Starts a case expression
class         # Creates or opens a class
def           # Defines a method
defined?      # Returns a string describing its argument
do            # Starts a block
else          # The unhandled condition in case, if and unless expressions
elsif         # An alternate condition for an if expression
end           # The end of a syntax block.
ensure        # Starts a section of code that is always run when an exception is raised
false         # Boolean false
for           # A loop that is similar to using the each method
if            # Used for if and modifier if expressions
in            # Used to separate the iterable object and iterator variable in a for loop
module        # Creates or opens a module
next          # Skips the rest of the block
nil           # A false value usually indicating “no value” or “unknown”
not           # Inverts the following boolean expression. Has a lower precedence than !
or            # Boolean or with lower precedence than ||
redo          # Restarts execution in the current block
rescue        # Starts an exception section of code in a begin block
retry         # Retries an exception block
return        # Exits a method
self          # The object the current method is attached to
super         # Calls the current method in a superclass
then          # Indicates the end of conditional blocks in control structures
true          # Boolean true
undef         # Prevents a class or module from responding to a method call
unless        # Used for unless and modifier unless expressions
until         # Creates a loop that executes until the condition is true
when          # A condition in a case expression
while         # Creates a loop that executes while the condition is true
yield         # Starts execution of the block sent to the current method
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
_age = 21     # local variable
1age = 21     # INVALID variable name
age = 21      # local variable
@age = 21     # instance variable
@@age = 21    # class variable
$age = 21     # global variable
```
[back to top](#table-of-contents)


### Constants
```ruby
AGE = 21      # constant; by convention - constants can be modified and generate a warning
```
[back to top](#table-of-contents)


### Integer Numbers
```ruby
1234                 # Fixnum decimal
-1234                # Negative Fixnum
1_234                # Fixnum decimal (with underscore to improve readability)
0b1011               # binary
0xff                 # hexadecimal
0377                 # octal
12345678901234567890 # Bignum
```
[back to top](#table-of-contents)

### Backslash notations
```ruby
\n          # Newline (0x0a)
\r          # Carriage return (0x0d)
\f          # Formfeed (0x0c)
\b          # Backspace (0x08)
\a          # Bell (0x07)
\e          # Escape (0x1b)
\s          # Space (0x20)
\x          # Character x``
\nnn        # Octal (n = 0-7)
\xnn        # Hesadecimal (n = 0-9, a-f, A-F)
\cx, \C-x   # Control-x
\M-x        # Meta x 
\M-\C-x     # Meta-Control-x
\unnnn      # Unicode code point U+nnnn (Ruby 1.9+)


```
[back to top](#table-of-contents)

### Arrays
```ruby
array = []                  # Array; zero-based indexing
array = Array.new(5)        # Array with size 
array = Array.new(2, "abc") # ["abc", "abc"]
array = Array(0..9)         # [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
first_item = array.first    # Array first item
first_item = array[0]       # Array first item
last_item = array.last      # Array last item
last_item = array[array.size - 1]   # Array last_item
array.size                  # Array size
array.length                # Array size
array.count                 # Array size
array.at(5)                 # Element at index 5
array.push(42)              # Add 42 to end of array
array.pop                   # Remove last element from array
array.shift                 # Remove first element from array
array.unshift(15)           # Add 15 to beginning of array
array.methods.sort - Object.methods   # List all Array instance methods
```
[back to top](#table-of-contents)


### Class
```ruby
class Customer
end
```
[back to top](#table-of-contents)
