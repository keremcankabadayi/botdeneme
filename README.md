# 2017-2018 Design Principles
# Project 1
### Project Definition
Solve a software development problem using one (or possibly more) of the design patterns that we cover in class. 
###  To-Do
- ~~**Statement of Work**: Write your problem definition in detail using 100-200 words.~~

- [x] Two different restaurant, Pizza Store and Kebab Store just contacted us about expanding their businesses. Firstly, they want to track their orders on the computer and they think it would be great if they saw items, preparation time and total bill. Besides these, they want to make some special meals beyond the regular menu. Customers or the owners want to mix some ingredients to make special tastes. In addition to these, the owners think their cooks should get some certificates to reduce preparing of foods and economy. City hall has some Vocational courses for their markets. In those courses, people can learn to be fast and to think how they can make easily sale like discount or something. Last but not least, they definitely code a program to extend easily. Because someday if they have to work other software engineers, expanding this program should be easy.
- ~~**Design Pattern(s)**: Select design pattern(s) that are useful in solving the problem you defined. Explain why and how you employ such design pattern(s) in your Project.~~
- [x] I'm planning to use Strategy Pattern and Decorator Pattern because using OO basics and those patterns can provide me to change objects behaviours at run time. The owners make some special orders without any trouble. Decorator pattern is going to be perfectly fit. I'm thinking I set employees default service times and price policies, using Strategy Pattern I can change at run time whenever i want. If one day new courses open, I or somebody can implement those courses without any changes. I'm gonna use two fundamental principles, Program to interfaces not implementations and Classes should be open for extension, closed for modifications. Then, hit the road!
    
 - ~~**UML**: Draw a detailed class diagram of your proposed solution using some UML Diagram Drawing Tool.~~
 - [x] [UML diagram can be seen here.](/UML-Diagram.pdf)
- ~~**Implementation**: : Implement your proposed solution based on the UML Class Diagram using the base Maven Project that you are supplied. The Maven Project produces a executable **.jar** file. 
Your project should not expect any input from user, and it should produce decent outputs when compiled by the following command:  `java -jar target\project1.jar`
You are allowed to change pom.xml to add or remove any dependency or plugin.~~
~~- You need to upload the **.pdf** file and necessary parts of your code. (Do not upload target folder and IDE-specific files)~~
- [x] All codes and commit details can be seen my github repo that you provided via Github Class.
Main.java output:
```
================================
This is Pizza Store, welcome!
This store: 
has normal service time.
has normal prices.
=============Let's make a pizza!===================
Ingredients: Fat Dough, Parmesan, Mozzarella
Total Cost: 6.5$
Total Preparation Time: 04 Minutes 23 Seconds 
=============Got a speed certificate!===================
This store now: 
is faster %10 than normal service time.
has normal prices.
==============New Pizza============
Ingredients: Fat Dough, Parmesan, Mozzarella
Total Cost: 6.5$
Total Preparation Time: 03 Minutes 57 Seconds 
================================
This store now: 
has normal service time.
is cheaper %20 than normal.
==============New Pizza============
Ingredients: Fat Dough, Parmesan, Mozzarella
Total Cost: 5.2$
Total Preparation Time: 04 Minutes 23 Seconds 
================================
This is Kebab Store, welcome!
This store: 
has normal service time.
has normal prices.
=============Let's make a Dürüm!===================
Ingredients: Double Bread, Mayo, Kebab Chili, Ayran, Beef
Total Cost: 15.8$
Total Preparation Time: 13 Minutes 24 Seconds 
=============Got a service-time and economy certificates!===================
This store now: 
is faster %10 than normal service time.
is cheaper %20 than normal.
==============New Pizza============
Ingredients: Double Bread, Mayo, Kebab Chili, Ayran, Beef
Total Cost: 14.22$
Total Preparation Time: 12 Minutes 44 Seconds 
```

###  To-Submit
Submit (1) Statement of Work, (2) Explanation on Utilized Design Patterns, and (3) UML Class Diagram as a **single _.pdf_** file and (4) Implementation codes (without the target folder and IDE-specific files) to your github classroom repository

### Important Dates
**Deadline:**  March 12, 2018.

### Notes
Please read this document very carefully. 
Submissions not complying with the **To-Do** list will be disqualified.
