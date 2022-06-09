# Lab-Report-5 Week-10

#### [My MarkdownParse](https://github.com/brian-schodorf/markdown-parser/blob/main/MarkdownParse.java)
#### [Provided Lab 9 MarkdownParse](https://github.com/nidhidhamnani/markdown-parser)

#### How I found the tests with different results:
I just manually combed throught the test files to find a few that I knew would not work. At this stage in my MarkdownParser implementation I have a strong idea of what cases my code can and cannot pass.

## Test 194:
[Link to Test File](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/194.md)

#### Test 194 preview:
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/preview194.png)

#### Output should be: [my_(url)]

#### My output:
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/my194.png)

#### Given MarkdownParse Output:
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/other194.png)

For test 194 both my version and the given version of MarkDownParse did not get the correct output. For my version of MarkDownParse, the bug comes from the part of my algorithm that checks if the open parenthesis appears one index after the close bracket. Test 194 will cause an error because the url link does not start with the open parenthesis. This causes my MarkDownParse to return empty brackets [].The given version of markdown parse does not return because it begins reading at the index of the open parenthesis and thus, returns [url].
My bug:
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/myCodee.png)
Other bug:
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/otherCode.png)



## Test 12:
[Link to Test File](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/12.md)

#### Test 12 preview:
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/preview12.png)

#### Output should be: []

#### My output:
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/my12.png)

#### Given MarkdownParse Output:
![Image](https://github.com/brian-schodorf/cse15l-lab-reports/blob/main/other12.png)

