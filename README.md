# AI Personas Hackathon 24 project - Using AI to improve technical documentation

This project transforms traditional user personas into interactive AI-driven entities that provide real-time feedback on technical documentation. By leveraging AI to simulate developers with varying skills and experiences, writers can engage in conversations with these personas to assess how well their content meets user needs. The Agents enable continuous testing and improvement of documentation, ensuring it is accessible and effective for a diverse range of developer audiences.

## Overview
As a writer, wouldn’t it be great if you could ask your customers to read your content and provide feedback as you work? This project makes that possible - with an AI twist.

Traditionally a tool called “personas” has been used to predict what your customers want. A persona is a fictional but realistic example of a typical user. Personas are used to promote empathy and help prioritize features or inform design decisions.

The persona has always been passive: a description that you keep in mind as you work.

However, thanks to AI, we can now turn personas into interactive artificial people that we can share our work with and get feedback in real time. We can even have conversations with them to find out what they’re interested in, and how well our content meets their needs.

### How does it work?

Langauge models can play roles with prompting: so let's experiment with using them to play the roles of developers with various skills and experiences, and use them to test our technical documentation. If they are a new developer, can they get started writing an application given existing docs? If they are experienced, can they implement a new feature with what we have published?

Our goal is to create agents that you can use to create personas to test your docs, and then find areas where you can improve the content, thus making things better for our external developer customers.
## Goals

Create a process for a Content Developer to feel confident they have tools to test their content against an AIP (AI persona) that represents their target audience.
The results of the test should highlight any areas in the docs that need improvement.

## Scenarios

1. A writer is working on topics for a new feature area. They use information from the feature owners to make a list of key scenarios and then create their docs.
Using the AIP (AI Persona) they confirm if, given the personas skillset and knowledge, they can achieve their goals with the new documentation.

2. A writer notices a lot of feedback centered around a certain area in the docs. Clearly something is not clear, or something is missing. They share the docs with the AIP, and query them to determine which areas need more work. They make changes to the content, and then re-test it with the AIP and check the number of feedback tickets to confirm their changes have been useful.


## Hackathon scope

1. Create a useful persona description template for content creators on the Learn team.
2. Create an agent to build a persona and related scenarios based off the template
3. Use templated version of the personas in an Evaluator agent with a given Learn article.
4. Create a series of example prompts to match specific tasks
5. Wrap it all up into a process that can be included in the Contributors' Guide

## Process flows
1. Decide which article you want use to create your AI developer persona.
2. Save your created persona file. [example personas link](https://github.com/ms-johnalex/h24_learn_content_personas/tree/main/personas)
3. Select a scenario from a list of the key scenarios you want your developer to be able to achieve.
4. Select the persona you are targeting with your content.
5. Use the Persona-Powered Doc Evaluator agent and submit your persona, choose a scenario, and the learn article to be evaluated.
6. Test your content with the agents and check the report for actionable feedback. 
7. You can also interact with the persona in a "chat" mode and get additional insights on your content.

## Agent prompts

- [Persona Creator prompt link](https://github.com/ms-johnalex/h24_learn_content_personas/blob/main/current/test-prompts/persona_creator_assistant_prompt_091924_142823.md)
- [Persona-Powered Doc Evaluator agent link](https://github.com/ms-johnalex/h24_learn_content_personas/blob/main/current/test-prompts/persona-powered_doceval_prompt_assistant_091924_130000.md)
## Tools and technologies used
- M365 Agent - Agent development and testing
- AI Foundry model playground - prompt development and testing

## Result
Two agents.
- Learn Persona agent: Assists users in creating detailed personas and scenarios based on Microsoft Learn articles, focusing on relevant goals and challenges, as well as basic and advanced scenarios that reflect realistic tasks. 
- Persona-powered Doc Evaluator agent: Use a persona to determine if a provided article will help the persona accomplish their goal, based on their background, expertise level, and the scenario presented. Creates an evaluation report with insights and recommendations also provides an nps score based on how well the article completes the given scenario.  

    


   
   
