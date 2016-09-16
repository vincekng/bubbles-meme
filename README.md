# AltspaceVR Engineering Project - Unity Testing

## Overview

This project involves adding a few different integration tests to a simple Unity game, and writing up a hypothetical testing strategy for the game as it develops into a larger product.

Our client at AltspaceVR is written in Unity and shares many architectural qualities with video games. 

The repo is a combination of
- A [Unity example game](https://www.assetstore.unity3d.com/en/#!/content/46209)
- The [Unity Test Tools](https://www.assetstore.unity3d.com/en/#!/content/13802)

To work on the project:
- Install [Unity](https://unity3d.com/unity/qa/patch-releases/5.3.4p1)
- Fork and clone the repo
- Open the project and the scene in the root folder called `AltspaceVR-Project-Unity-Testing`

## Goals

- To understand how you think about automated testing in a game engine
- To get a sense of your programming style
- To see how, if you joined AltspaceVR, you would be able to help us develop our larger testing strategy

# Part 1 - Integration Tests

Create three integration tests that work with the included Unity Test Tools Integration Test Runner. While Unity Test Tools does have a GUI Assertion Component, you will need to write C# behaviors to complete the assignment (either integrated with the Assertion Component, or standing on their own). 

Please build tests that verify the following aspects of the game

- A tank receives damage when hit by a shell
- The frame-rate of the game does not drop below 60 FPS for more than 100 milliseconds at a time
- Both tanks are constantly visible during 10 seconds of random movement input

# Part 2 - Testing Strategy

Consider that this tank game is going to be hypothetically built out into a competitive online PC video game. There will be a large number of different tanks and weapons, and the game will receive continuous updates to improve balance and add new features. The team will have 20 people on the project in various roles. 

Please write up a one page overview of what a cohesive testing strategy would look like that would allow for continuous deployment while minimizing downtime and bugs that negatively impact the experience for players. This should include recommendations from both a technical and a process perspective.

## Deliverable

In your repo, you should clobber this README file with your testing strategy. Any instructions or known issues should be documented in the README as well. If you use any code that was not included in the project or written by yourself, please note it here.

Email us a link to your Github repo to `projects@altvr.com`. Please include your contact information, and if you haven't submitted it to us already, your resume and cover letter. 

We hope you have fun working on the project, and we're excited to see what you come up with!
    
[The Altspace Team](http://altvr.com/team/)


