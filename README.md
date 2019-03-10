# jspexamples

JSP stands for java server pages that is used to build the dynamic web page, in the end jsp also become the servlet.
basically it contains four tags that are used to construct the jsp program. 
those tags are 
1. Selective tags, denoted as <% %>, basically old plane java code goes between <% and %>. here the mean of the old java plane code is that
scrptlet tag can contain local variable declaration, looping statements, selective statements. Statements that are placed into the scriptlet
will be placed into the jspService() method.\n

2. Declaration tag, denoted as <%! %> inside this tag the variable declaration and the method declaration take place. Any variable that you
placed inside this tag will either become instance variable or class variable(static variable). in java ther is no terms of global variable
because global variable is used to declare above class and in java ther is no concept to declare variable outside of the class. statements
that are landed into this tags will take place inside the class but not inside the jspService() method.

3.Expression tag, denoted as <%= %>, any statement that will take place into the expression tags will become the argument of the method
pw.println(). one important thing is that in this tag no statement will ended through semicolon.

4.Directive tag, this tag denoted by <%@ %>, purpose of this tag is to give special instruction to their what container, basically this tag
is used to import packages into jsp files. for eg. <%@ import = "package1, package2, package3 ...etc "%>
