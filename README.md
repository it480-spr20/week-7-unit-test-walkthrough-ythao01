Assignment: Unit Test Walkthrough
=================================

In this lab we'll learn a unit-test framework, the one provided by Microsoft for their C# language in the Visual Studio IDE. C# is  similar to Java, so don't worry too much about the language differences. However, because we're using an interactive development environment instead of the command line, we get new ways of visualizing and executing unit tests. The price for this new capability is the extra effort and knowledge required to set things up. This lab walks you through the whole process.

Instructions
------------

 1. Read the "hints" section below. As new issues come up, I'll add them to the whiteboard.
 2. You'll need a working copy of Visual Studio. Visual Studio Community Edition works if you don't have Ultimate working yet. 
 3. Follow the walkthrough at <https://docs.microsoft.com/en-us/visualstudio/test/walkthrough-creating-and-running-unit-tests-for-managed-code?view=vs-2019>
 4. After you’ve completed the walkthrough, you should have a screen showing three green checkmarks in your IDE. Upload a screenshot of those three green checkmarks as proof that you've completed the assignment

Hints and common mistakes
-------------------------

- This lab is a fruitful source of "RTFM" moments. If it's not working, make sure you're not just ignoring something that it's told you to do. Remember, if I tell you to RTFM twice in a class, you lose attendance points.
- You get a free pass on "RTFM" for adding references to a project. This is one of the most insanely non-obvious parts of the Visual Studio IDE in my opinion, and they still haven't fixed it. Don't struggle on this one, just ask for help!
- When you create the project for unit tests, do File > Add > New Project, not File > Create > New Project. The first adds a project to the existing solution; the second throws away the existing solution and creates a new one.
- When you create the new unit test project, it includes a blank unit test. Delete or overwrite this. This won’t count as one of the three successful tests.
- When you add new constants “at class scope”, that means inside the initial class definition.
- You want to build a Visual C# => .NET Class Library, not a Universal Windows app or any other choice
- If the Test Explorer window doesn't appear, use Test -> Windows -> Test Explorer

As before, it’s encouraged to talk to each other and get help while doing lab work. The goal is to demonstrate that you’ve learned new skills and can apply them.
 
