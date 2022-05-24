# Lab Report-2 Week-4
#
### Code Change 1
#### Changes to markdownParse:
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/change%20test2.png)
#### Failure inducing input file:
[tester2 LINK](https://github.com/brian-schodorf/markdown-parser/blob/main/tester2.md)
#### Command line output:
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/cmd%20test2.png)
#### Relationship between bug, symptom, and input
In this case the bug in our code was that Markdown Parse can not get the link if there were two leading open brackets. This bug lead to the symptom which was the error in the command line when we attemt to run the code. This is all reated to the input because the input causes the program to encounter the bug and trigger the symptom.


### Code Change 2
#
#### Changes to markdownParse:
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/change%20new.png)
#### Failure inducing input file:
[newTest LINK](https://github.com/brian-schodorf/markdown-parser/blob/main/newTest.md)
#### Command line output:
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/cmd%20new.png)
#### Relationship between bug, symptom, and input
In this case the bug in our code was that Markdown Parse can not get the link if there was a closed parenthesis before the actual url content. This bug lead to the symptom which was the error in the command line when we attemt to run the code. This is all reated to the input because the input causes the program to encounter the bug and trigger the symptom.



### Code Change 3
#
#### Changes to markdownParse:
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/change%20-%20file.png)
#### Failure inducing input file:
[test-file LINK](https://github.com/brian-schodorf/markdown-parser/blob/main/test-file.md)
#### Command line output:
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/cmd%20-file.png)
#### Relationship between bug, symptom, and input
In this case the bug in our code was that Markdown Parse can not get the link if the user forgot to use an open parenthesis to start the url. This bug lead to the symptom which was the error in the command line when we attemt to run the code. This is all reated to the input because the input causes the program to encounter the bug and trigger the symptom.



