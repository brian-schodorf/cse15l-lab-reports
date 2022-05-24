## Lab Report 4 Week 8


### Links to Repos:
[My repo](https://github.com/brian-schodorf/markdown-parser)

[Repo reviewed in week 7](https://github.com/cbaeucsd/markdown-parser)

### Tests for Snippet 1, 2, and 3:
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/snippetTests.png)

### Output when ran on my version:
#### (my version was not successful)
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/newMyOut.png)

### Output when ran on the other group's version:
#### (tests passed)
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/otherSnippetOut.png)

### Snippet 1 question:
- Right now, my version of markdown parse only attempts look for the first instances of open parenthesis, closed parenthesis, open bracket, and closed bracket. I belevie that there is a small code change that will make my program work for snippet 1 because I could just remove any backticks from the url string then return the remaining characters. 

### Snippet 2 question:
- To make my program work for snippet 2, I would need to make large scale changes to account for repeating parenthesis and brackets. This code change would need to check the index of each bracket/parenthesis in the string to figure out where the actual url is, then read the characters. Implementing these changes would most likley invlove starting from scratch. 

### Snippet 3 question:
- Snippet 3 would need changes similar to those discuessed in snippet 2's question response to handle any repreating brackets and parenthesis. However, it would be fairly simple to trim any extra spaces or new lines from around the url.
