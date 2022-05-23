# Lab Report 4

[markdown-parse Link](https://github.com/erhuang623/markdown-parser)

[Reviewed markdown-parse Link](https://github.com/alixintong/markdown-parser)

## Code snippet 1:

I believe code snippet 1 should produce these links:

![Image](codeSnippet1.png)


Test case:
![Image](snippet1Tests.png)


My failed test case:
![Image](fail1.png)

Reviewed case:
![Image](reviewFail1.png)


Code Changes: First I have an out of memory exception which can be fixed by changing my loop. I believe that it isn't possible to make a small change to pass this test due to my infinite loop as well as edge cases like backticks. I feel like it would be a big change to consider backticks, as well as multiple brackets in a link.


## Code snippet 2:
I think snippet 2 should produce this:
![Image](codeSnippet2.png)


Test case:
![Image](snippet2Tests.png)


My failed test case:
![Image](fail2.png)

Reviewed case:
![Image](reviewFail2.png)


Code Changes: Again, I have an out of memory error but besides that, I believe it may be possible to fix it with a small change because my code considers cases for multiple brackets. I believe nested brackets will prove a little more difficult but possible.

## Code snippet 3:
snippet 3 should produce these links:
![Image](codeSnippet3.png)


Test case:
![Image](snippet3Test.png)


My failed test case:
![Image](fail3.png)

Reviewed case:
It passed the test case.


Code Changes: With my other test cases, I believe there is an infinte loop that can be fixed in 10 lines or less. 