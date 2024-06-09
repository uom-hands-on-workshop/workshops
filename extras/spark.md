# Spark

Spark is The University of Melbourne's AI Language Model and can be accessed [here](https://spark.unimelb.edu.au/). 

## Introduction

SparkAI is an advanced AI language model developed by the University of Melbourne to support various educational and administrative tasks within the university. This guide provides an overview of how users can adjust the LLM settings, including selecting the ChatGPT LLM and temperature for the secure chat thread.

## Adjusting LLM Settings

### Selecting the ChatGPT LLM

Users have the option to choose between two iterations of language models developed by OpenAI:

- **GPT-3.5 Turbo 16k**: A refined version of the GPT-3 model. While it offers enhancements over GPT-3, its understanding of complex or specialised topics may still be limited.
- **GPT-4**: The next evolution in OpenAI's language models. GPT-4 is designed to provide significantly improved understanding of both general and specialised topics, offering more accurate and contextually relevant responses.

### Understanding and Adjusting Temperature

The temperature setting in a language model controls the randomness of the output. It determines how creative or focused the responses will be. Temperature values range from 0 to 1, where:

- **0**: The model produces very focused and deterministic responses, prioritising accuracy over creativity.
- **0.5**: The model balances creativity and focus, producing responses that are varied yet still relevant.
- **1**: The model generates highly creative and varied responses, but at the cost of potential accuracy and focus.

#### Examples of Temperature Settings

- **Temperature 0**
  - **Prompt**: "Explain the significance of photosynthesis."
  - **Response**: "Photosynthesis is the process by which green plants and some other organisms use sunlight to synthesise foods with the help of chlorophyll, producing oxygen as a byproduct."

- **Temperature 0.5**
  - **Prompt**: "Explain the significance of photosynthesis."
  - **Response**: "Photosynthesis is a crucial process in which green plants and some other organisms convert sunlight into chemical energy, creating food in the form of glucose and releasing oxygen into the atmosphere. This process not only sustains the plant itself but also supports life on Earth by maintaining oxygen levels and serving as the base of the food chain."

- **Temperature 1**
  - **Prompt**: "Explain the significance of photosynthesis."
  - **Response**: "Imagine a world without the green touch of plants! Photosynthesis is this magical process where plants, basking in sunlight, whip up their food from carbon dioxide and water, and generously release oxygen. It's not just about plants feeding themselves; it's about life breathing freely, an unseen dance of energy and life, a foundational harmony in the symphony of nature."

## Data Sets in Spark

### What are Data Sets?

Data sets in Spark are curated pools of information that the AI model can reference when generating responses. When creating a project, users can choose between a global data set or a custom data set. 

- **Global Data Sets**: These are standardised data sets available to all users. They include a wide range of information and are designed to be broadly applicable to various contexts.
- **Custom Data Sets**: These are personalised data sets created by individual users. Only the creator has access to their custom data sets, ensuring privacy and relevance to specific projects. **Only you have access to the custom data sets that you create through your Spark profile.**

### Creating Custom Data Sets

Custom data sets offer a way to tailor the AI's knowledge base to fit your specific needs. To create a custom data set:

1. **Collect Data**: Gather the information that you want to include in your custom data set. This could be documents, research papers, internal reports, or any relevant data.
2. **Upload Data**: Use SparkAI's interface to upload your collected data into the platform.
3. **Configure Settings**: Adjust the settings to specify how the AI model should use the data. This might include tagging, categorising, or prioritising certain information.

By creating and using custom data sets, you ensure that the AI model in your project has access to the most relevant and accurate information, tailored specifically to your requirements.


## Summary

By understanding and adjusting the settings of SparkAI, users can tailor the AI's performance to suit their specific needs, whether it's for detailed, accurate responses or more creative and varied outputs. Choosing the right model (GPT-3.5 Turbo 16k or GPT-4) and setting the appropriate temperature can significantly enhance the effectiveness and relevance of the AI's responses in different contexts.

