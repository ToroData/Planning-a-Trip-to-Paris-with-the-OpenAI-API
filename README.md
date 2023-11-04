# Planning-a-Trip-to-Paris-with-the-OpenAI-API

<div align="center">
    <img src="https://thedatascientist.digital/img/logo.png" alt="Logo" width="25%">
</div>

## AI-Powered Paris Landmark Travel Guide

![Eiffel Tower](eiffel-tower.png)

## Project Overview

As a distinguished AI Developer, you've been selected by Peterman Reality Tours, an internationally acclaimed tourism company, to undertake an influential project. This project requires you to harness the potential of OpenAI's API, specifically using its state-of-the-art language model, GPT-3.5 Turbo, to create an AI-powered travel guide for the culturally rich city of Paris.

Your creation will become a virtual Parisian expert, delivering valuable insights into the city's iconic landmarks and hidden treasures. The AI will respond intelligently to a set of common questions, providing a more engaging and immersive travel planning experience for the clientele of Peterman Reality Tours.

The ultimate aspiration is a user-friendly, AI-driven travel guide that significantly enhances the exploration of Paris. This project will not only improve Peterman Reality Tours' customer service but also solidify their place at the forefront of AI-enhanced innovation in the global tourism industry. Users will be able to pre-define their questions and receive well-informed answers from the AI, making the travel planning process seamless and intuitive.

## Instructions

The AI team at Peterman Reality Tours, a global tourism company, has approached you to help them develop an AI-powered travel guide for their customers. The travel guide will focus primarily on intelligently answering specific queries regarding various landmarks in Paris. The AI team wants you to utilize OpenAI's GPT-3.5 model to build this AI tool.

They have proposed the following tasks:

1. Create a model variable to use OpenAI's 'gpt-3.5-turbo' model, to find answers to the following questions:
    - How far away is the Louvre from the Eiffel Tower (in miles) if you are driving?
    - Where is the Arc de Triomphe?
    - What are the must-see artworks at the Louvre Museum?

2. Limit the maximum number of tokens to 100 so that the model's responses are concise, and set temperature to 0.0.

3. Store the questions and the responses in a list called `conversation`. Each item in the list should be a dictionary with two keys: `role` and `content`. The `role` key should have one of three values: 'system', 'user', or 'assistant'. The role in the first dictionary of `conversation` should be 'system'. The `content` key should have a string value representing a dialogue related to the assigned role.

4. Print each generated response to the console as it is produced for users to read.

The above listed sample questions are what you will need to use to submit the project, but once you've passed the project, feel free to play around with these to change the model's behavior or design a completely different assistant!

## Getting Started

1. Clone this repository to your local machine.
2. Set up your Python environment and install the required packages.
3. Follow the provided instructions to build your AI-powered travel guide.
4. Customize the project as needed and explore different use cases.

## Dependencies

- Python 3.x
- OpenAI API
- pyttsx3 (for text-to-speech functionality)

## Acknowledgments

- Thanks to Peterman Reality Tours for their collaboration on this innovative project.
- OpenAI for providing the powerful GPT-3.5 Turbo model.
- The open-source community for valuable contributions to pyttsx3.
