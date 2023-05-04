Download Link: https://assignmentchef.com/product/solved-csc2001f-assignment-3-hash-tables
<br>
The goal of this assignment is to demonstrate an application that uses hash tables for repeated fast lookups within a fixed set of data elements.

You are required to develop a Java application that can be used to verify voter registration at a polling station using a low-powered mobile device (but with a decent amount of memory). The application should have a user interface (text or GUI) where ID numbers are entered continuously and each number is checked against a listing of valid voters. If there is a match, the person’s name must be displayed so this can be further verified by the voting station agent.

DatasetCreate your own dataset (of at least 50 entries, but preferably more) for this assignment.

You need a list of 13-numeral ID numbers and associated names. Do not assume 2 names per person – all we know about names is that any person has at least one name.

For example, the first few lines could look like:

9201211234567 Black Panther7111270987654 Wonder Woman6212081234567 Spiderman

Store your dataset in a file.

ApplicationYour application must have a user interface in either text or graphical form. The user interface must allow efficient and continuous entry of IDs so that people arriving at the voting station can be checked as quickly as possible.

Your application must use a hash table. Given that the voting station may not have Internet access, your application is running offline. In order to maximise speed of lookups, a hash table is to be used, with all data stored in memory. This means that the application will load the data into memory once and do repeated fast lookups within a data structure, which is an ideal application of a hash table.

You need to decide on the design of the hash table:

the hash function to be usedthe size of the hash table arraythe collision resolution mechanismYou must implement the hash table from scratch. You may not reuse code from anywhere, except for the implementation of linked lists or BSTs if you opt to use those:

ReportYour report must explain the following:

The design of your application, data structure and OOPThe interface of your applicationResults and discussion of tests that you conducted to determine the speed of your applicationWhat aspect of your submission constitutes creativityDev requirementsAs a software developer, you are required to make appropriate use of the following tools:

git, for source code management (but not required to submit a log)javadoc, for documentation generationmake, for automation of compilation and documentation generationSubmission requirementsSubmit a .tar.gz compressed archive containing:

Makefilesrc/all source codebin/all class filesdoc/javadoc outputreport.pdf