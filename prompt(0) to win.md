**Prompt.ml**

[**prompt(0) to win ](http://prompt.ml/)**Writeup:**

In the first level we see that we have been given the following screen with a text editor and a blank field where we can input the payload to alter the html source.

![](Aspose.Words.f9a508d0-13ea-4748-b1c0-e75b01f5a13a.001.jpeg)

When we fiddle with the input area we see the html value also changes accordingly,

We have also been given a certain input parameter for the same which has to be added with the given payload.

**Payload : "><script>alert(1)</script>**

![](Aspose.Words.f9a508d0-13ea-4748-b1c0-e75b01f5a13a.002.jpeg)

As soon as the above payload is inputted the web page opens up a pop up as shown below. Now we will continue by replacing alert with prompt.

**Payload : "><script>prompt(1)</script>**

![](Aspose.Words.f9a508d0-13ea-4748-b1c0-e75b01f5a13a.003.jpeg)
