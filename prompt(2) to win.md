**Prompt.ml**

[**prompt(2) to win ](http://prompt.ml/)**Writeup:**

In the first level we see that we have been given the following screen with a text editor and a blank field where we can input the payload to alter the html source.

![](Aspose.Words.cecb844c-9abd-481a-a4bb-9bb2b09a789e.001.jpeg)

When we input a very basic xss payload we see that the html source does not tend to reflect the ( bracket.

**Payload : <script>alert(1)</script>**

![](Aspose.Words.cecb844c-9abd-481a-a4bb-9bb2b09a789e.002.jpeg)

We will replace the ( with the html hex entity reference which is “ &#x28; ” , thereby altering the payload.

**Payload : <script>alert &#x28; 1)</script>**

Now for the following payload to run we will have to add the <svg>  tag

![](Aspose.Words.cecb844c-9abd-481a-a4bb-9bb2b09a789e.003.jpeg)

Now replacing prompt with alert.
