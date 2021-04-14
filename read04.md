# The Javascript

### HOW HTML, CSS, 
### & JAVASCRIPT FIT 
### TOGETHER.

- *Web developers usually talk 
about three languages that 
are used to create web pages: 
HTML, CSS, and JavaScript.* 

- *Where possible, aim to keep the 
three languages in separate files, 
with the HTML page linking to 
CSS and JavaScript files. *

- *Each language forms a separate 
layer with a different purpose. 
Each layer, from left to right. 
builds on the previous one. *


### PROGRESSIVE ENHANCEMENT

- *HTML+CSS+JAVASCRIPT 
The JavaScript is added last 
and enhances the usability of 
the page or the experience of 
interacting with the site. 
Keeping it separate means 
that the page still works if the 
user cannot load or run the 
JavaScript. You can also reuse 
the code on several pages 
(making the site faster to load 
and easier to maintain).*

### CREATING A BASIC JAVASCRIPT

**JavaScript is written in plain text, just like HTML and CSS, so you do not 
need any new tools to write a script.**

- *A JavaScript file is just a 
text file (like HTML and CSS 
files are) but it has a . j s file 
extension.*

- *To keep the files organized, in 
the same way that CSS files 
often live in a folder called 
styles or css, your JavaScript 
files can live in a folder called 
scripts,javascript,orjs. 
In this case.*

### LINKING TO A JAVASCRIPT FILE FROM AN HTML PAGE 

**When you want to use JavaScript with a web page, you use the HTML 
(script) element to tell the browser it is coming across a script. 
Its s re attribute tells people where the JavaScript file is stored.**

- *The HTML (script) element is 
used to load the JavaScript file 
into the page. It has an attribute 
called src, whose value is the 
path to the script you created.*

- *This tells the browser to find and 
load the script file (just like the 
src attribute on an (i mg) tag).*

### PLACING THE SCRIPT IN THE PAGE

**You may see JavaScript in the HTML between 
opening (script) and closing (/script) tags 
(but it is better to put scripts in their own files).**

- It is best to keep JavaScript code in its own JavaScript 
file. JavaScript files are text files (like HTML pages and 
CSS style sheets), but they have the . j s extension. 
- The HTML <script> element is used in HTML pages 
to tell the browser to load the JavaScript file (rather like 
the <link> element can be used to load a CSS file). 
- If you view the source code of the page in the browser, 
the JavaScript will not have changed the HTML, 
because the script works with the model of the web 
page that the browser has created. 

### STATEMENTS 

**A script is a series of instructions that a computer can follow one-by-one. 
Each individual instruction or step is known as a statement. 
Statements should end with a semicolon.**

*We will look at what the code on the right does 
shortly, but for the moment note that:* 
- Each of the lines of code in green is a statement. 
- The pink curly braces indicate the start and end 
of a code block. (Each code block could contain 
many more statements.) 
- The code in purple determines which code 
should run (as you will see on p149). 

**JAVASCRIPT IS CASE SENSITIVE** 
JavaScript is case sensitive so hourNow means 
something different to HourNow or HOURNOW.

**STATEMENTS ARE INSTRUCTIONS AND** 
**EACH ONE STARTS ON A NEW LINE** 
*A statement is an individual instruction that the 
computer should follow. Each one should start on a 
new line and end with a semicolon. This makes your 
code easier to read and follow.* 
*The semicolon also tells the JavaScript interpreter 
when a step is over, indicating that it should move 
to the next step.* 

**STATEMENTS CAN BE ORGANIZED** 
**INTO CODE BLOCKS** 
*Some statements are surrounded by curly braces; 
these are known as code blocks. The closing curly 
brace is not followed by a semicolon.* 
*Above, each code block contains one statement 
related to what the current time is. Code blocks 
will often be used to group together many more 
statements. This helps programmers organize their 
code and makes it more readable.* 

### COMMENTS

**You should write comments to explain what your code does. 
They help make your code easier to read and understand. 
This can help you and others who read your code.**

### Variables 

**A script will have to temporarily 
store the bits of information it 
needs to do its job. It can store this 
data in variables.** 

### DATA TYPES 

1. Numberic data type
2. String data type
3. Boolean data type

** Variables can be stored as numbers,strings and boolean** 

**RULES FOR NAMING** 
**VARIABLES**

1.*The name must begin with 
a letter, dollar sign ($),or an 
underscore (_). It must not start 
with a number.*
2.*The name can contain letters, 
numbers, dollar sign ($), or an 
underscore (_). Note that you 
must not use a dash(-) or a 
period (.) in a variable name.*
3.*You cannot use keywords or 
reserved words. Keywords 
are special words that tell the 
interpreter to do something. For 
example, var is a keyword used 
to declare a variable. Reserved 
words are ones that may be used 
in a future version of JavaScript. 
ONLINE EXTRA 
View a full list of keywords and 
reserved words in JavaScript. *
4.*All variables are case sensitive, 
so score and Score would be 
different variable names, but 
it is bad practice to create two 
variables that have the same 
name using different cases.*
5.*Use a name that describes the 
kind of information that the 
variable stores. For example, 
fi rstName might be used to 
store a person's first name, 
l astNarne for their last name, 
and age for their age. *
6.*If your variable name is made 
up of more than one word, use a 
capital letter for the first letter of 
every word after the first word. 
For example, f i rstName rather 
than fi rstnarne (this is referred 
to as camel case). You can also 
use an underscore between each 
word (you cannot use a dash). *
