# h24_learn_content_personas
Hackathon 24 project


## Overview
As a writer, wouldn’t it be great if you could ask your customers to read your content and provide feedback as you work? This project makes that possible - with an AI twist.

Traditionally a tool called “personas” has been used to predict what your customers want. A persona is a fictional but realistic example of a typical user. Personas are used to promote empathy and help prioritize features or inform design decisions.

The persona has always been passive: a description that you keep in mind as you work.

However, thanks to AI, we can now turn personas into interactive artificial people that we can share our work with and get feedback in real time. We can even have conversations with them to find out what they’re interested in, and how well our content meets their needs.

How does it work?

Langauge models can play roles with prompting: so let's experiment with using them to play the roles of developers with various skills and experiences, and use them to test our technical documentation. If they are a new developer, can they get started writing an application given existing docs? If they are experienced, can they implement a new feature with what we have published?

Our goal is to create a toolkit that you can use to test your docs, and then find areas where you can improve the content, thus making things better for our external developer customers.
## Goals

Create a process for a Content Developer to feel confident they have tools to test their content against an AIP (AI persona) that represents their target audience.
The results of the test should highlight any areas in the docs that need improvement.

## Scenarios

1. A writer is working on topics for a new feature area. They use information from the feature owners to make a list of key scenarios and then create their docs.
Using the AIP (AI Persona) they confirm if, given the personas skillset and knowledge, they can achieve their goals with the new documentation.

2. A writer notices a lot of feedback centered around a certain area in the docs. Clearly something is not clear, or something is missing. They share the docs with the AIP, and query them to determine which areas need more work. They make changes to the content, and then re-test it with the AIP and check the number of feedback tickets to confirm their changes have been useful.


## Hackathon 

1. Collect useful persona descriptions for content creators on the Learn team.
2. Create a templated version of the personas suitable for use in a Copilot Agent prompt.
3. Create a series of example prompts to match specific tasks
4. Wrap it all up into a process that can be included in the Contributors' Guide

## Example of the process

1. Decide which feature area you want to test with your AI developer persona.
2. Create a list of the key scenarios you want your developer to be able to achieve.

(ToDo: Provide guidance for writers on how to present these scenarios.)

3. Select the persona or personas you are targeting with your content.

4. Take the provided prompts, and fine tune them.
5. Test your content with the prompts and check the results for actionable feedback.

## Tools and technologies used
- M365 Agent - Agent development and testing
- AI Foundry model playground - prompt development and testing

# Result
Two agents.
- Learn Persona agent: Assists users in creating detailed personas and scenarios based on Microsoft Learn articles, focusing on relevant goals and challenges, as well as basic and advanced scenarios that reflect realistic tasks. 
- Persona-powered Doc Evaluator agent: Use a persona to determine if a provided article will help the persona accomplish their goal, based on their background, expertise level, and the scenario presented. Creates an evaluation report with insights and recommendations also provides an nps score based on how well the article completes the given scenario.  

    


   
   
