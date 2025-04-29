# cpsc501-assignment-3--object-introspection-solved
**TO GET THIS SOLUTION VISIT:** [CPSC501 Assignment 3- Object Introspection Solved](https://www.ankitcodinghub.com/product/cpsc501-assignment-3-object-introspection-10-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116478&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CPSC501 Assignment 3- Object Introspection Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Assignment policy:

1. Cite all sources of code that you hand in that are not your original work. You can putthe citation into comments in your program. For example, if you find and use code found on a web site, include a comment that says, for example:

# the following code is from https://www.quackit.com/python/tutorial/python_ hello_world.cfm.

Use the complete URL so that the marker can check the source.

2. When you upload your project to GitLab, make sure your repository is set to private. Any repository set to public or internal is visible to other students in the class, and counts as academic misconduct.

4. Discuss and share ideas with other programmers as much as you like, but make surethat when you write your code that it is your own. A good rule of thumb is to wait 20 minutes after talking with somebody before writing your code. If you exchange code with another student, write code while discussing it with a fellow student, or copy code from another person’s console, then this code is not yours.

5. Collaborative coding is strictly prohibited. Your assignment submission must be strictlyyour code. Discussing anything beyond assignment requirements and ideas is a strictly forbidden form of collaboration. This includes sharing code, discussing code itself, or modelling code after another student’s algorithm. You can not use (even with citation) another student’s code.

Instructions:

The goal of this assignment is to create a reflective object inspector that does a complete introspection of an object at runtime. The inspector will be implemented in a Java class called Inspector, and will be invoked using the method:

public void inspect(Object obj, boolean recursive).

This method will perform introspection on the argument obj, printing what it finds to standard output. You should find and display the following information about the object:

1. The name of the declaring class

2. The name of the immediate superclass*

Always explore the superclass immediately and recursively, even if recursive is false

3. The name of each interface the class implements*

Always explore all interfaces immediately and recursively, even if recursive is false

4. The constructors the class declares. For each constructor, give the followinginformation:

Name

Modifiers

Parameter types

Exceptions thrown

5. The methods the class declares. For each method, give the following information:

Name

Modifiers

Parameter types

Return type

Exceptions thrown

6. The fields the class declares. For each field, give the following information:

Name

Type

Modifiers

Current value

– If the field is a primitive data type, simply print the value

– If the field is an object reference and recursive is set to false, then simply print out the reference value directly. This will consist of the name of the object’s class, plus the object’s identity hash code (e.g. java.lang.Object@7d4991ad)

– If the field is an object reference and recursive is set to true, then immediately recurse on the object

Arrays: Be sure you can also handle any array object you might encounter. This could be either the starting object or from a field. In addition to the regular name, type and modifiers, you must print out its component type, length, and the values of all entries. You can assume that array fields will be limited to one dimension.

Infinite recursion: It is possible to define objects that end up in infinite recursion if the recursive method argument is enabled. However, you do not need to design your code to detect or escape circular class references. The driver program for evaluating your assignment will not test objects with this circular reference behaviour.

Formatting: Please indent each class recursed into by one tab of depth, and indicate clearly whenever you enter a new class. It is also helpful to indicate which class you are listing the current fields, methods and constructors for with a header that indicates the current class. The appropriate header would then be displayed each time you enter or leave a recursion level. You can judge what looks best in terms of output formatting, but make sure it is easy for the TAs to read and grade.

Refactoring: At some point in the development of your assignment code, you need to perform two distinct refactorings. Any refactorings from the course list or from Fowler’s textbook are accepted. Write up these refactorings in a similar format to assignment 1 and include them in your report.

Other requirements:

You should have descriptive output. For example, you should not use toString() for Field/Method or Class to get information. You will need to use the reflective API methods discussed in class to pull out the required information and print more descriptive explanatory lines.

When printing modifiers, you must convert the returned integer information into descriptive text information such as public/private/final/static/transient/etc.

A Driver program is provided on D2L that creates objects to inspect and then invokes your inspect method on each. This driver will output eight different script*.txt files, each corresponding to a different object.

Remember to use version control and refactoring as discussed, as part of your coding process.

As in the previous assignments, you will be using GitLab to maintain version control and to share your final project with the TAs. Your assignment should be kept in a GitLab repository titled CPSC 501 A3. As you develop your code, make sure to use proper version control practices, making regular commits with descriptive messages.

Report: Create a written PDF report that describes your two refactorings in a similar format to assignment 1. Remember to include the name of the refactoring, reasons for making it, and before-and-after code excerpts. The justification can be brief – just a sentence or two is sufficient.

Submission instructions:

Rubric (100 pts total):

Version control: Used Git/GitLab properly, making multiple small commits with informative messages (5 pts)

Refactoring: Performed two refactorings to improve the code structure, which are clearly written up in the report. (5+5 pts)

Introspection: Program correctly displays the following information.

– Class: full name (2 pts)

– Superclass: full name (2 pts)

– Interfaces: full names (2 pts)

– Fields: name, modifiers, type (6 pts)

– Field data: value or reference or null (6 pts)

– Constructors: modifiers, parameter types, exceptions thrown (10 pts)

– Methods: name, modifiers, parameter types, return type, exceptions thrown (10 pts)

– Super recursion: inspects interfaces and parent classes (10 pts)

– Arrays: handles 1-dimensional arrays with required info (10 pts)

– Formatting: tabbing, spacing, clarity of description (6 pts)

– Recursion: handles recursive = true by performing introspection on all sub-objects (16 pts)

Logistics: Clear, working instructions on how to access GitLab project, submitted as a PDF report. Program can be run from the command line using the specified instruction (5 pts)

Bonus: Solution uses reflection to dynamically load classes as described (10 pts)

author: jcleahy@ucalgary.ca
