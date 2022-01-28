# Debugging Code

## First Problem
added a throws IOException to the function parseTestOne

![Image](picturesTwo/1.png)

This error was the reason for the change to the test.

![Image](picturesTwo/2.png)

The symptom that alerted me to the bug was that the tester file did not compile. The bug that was the cause of the problem was the lack of a throws IOException statement in the function header. The input did not seem to be the problem here, as there was no input that would allow our code to compile. 

## Second Problem

