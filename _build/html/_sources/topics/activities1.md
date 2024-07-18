# Activity 1 

## Analyse ESS feedback, identify meaningful themes and provide suggestions for improvement

### Configuring Spark:

1. Login to [Spark](https://spark.unimelb.edu.au/)

2. Click on '+ New thread' (left side of the screen, under 'Secure Chat')

3. Click on 'Thread Configuration' (top right corner of new chat window)

4. Select 'OpenAI GPT 4 Turbo 128k (preview)' as your LLM

5. Set 'Temperature' to 0.5

6. Click on 'Apply' button (top right corner of the screen)

### ESS Example for Activity 1:

- [SWEN90007 Scenario](scenario.md)

  
## Problem Identification (human vs Spark)

**Objective**: Identify problems in students' comments.

**Steps**:
1. (human) Write your list of identified problems in students' comments.
2. (AI) Ask AI to identify problems in students' comments. [copy and paste comments or upload document]

(human) Input:   

```
Considering the Student Experience Survey results from SWEN90007 subject below, please help me identify and categorise the key issues mentioned by students in the survey.
 - More refined/less vague project requirements.
 - Less workload – this is too much for students studying full time.
 - Lecture slides can be challenging to read, especially the code part.
 - Project part 2 was too big for the time given and expectations were unclear.
 - Feedback needs to be provided sooner.
 - Marking rubric for reports depends on the tutor's personal feelings.
 - Marking rubrics were under-specified for parts 2, 3, and 4.
 - Performance coverage was good but needed more guidance.
 - Team members were not friendly.
 - Need more guidance on assignments in tutorials.
 - Would like more activities in the classroom.
```
  
Note that in this prompt, the comments from students were added as input to provide context to the LLM.


3. (human & AI) combine the list of identified problems in students' comments.

**Tips**:
- Ensure the comments can be clearly identified in your prompt.
- Compare the human-generated list with the AI-generated list to identify any additional insights or overlooked issues.

## Idea Generation (human and Spark)

**Objective**: Improve outcomes by adding actionable improvements and estimations to it.

**Steps**:
1. (human) Ask the LLM to update identified issues and categories to include actionable improvements and estimations to address them.

(human) Input:

```
Considering your identified key problems and categories in students' comments, please update your list with suggested actionable improvements. For each suggestion on how to minimise identified problems, please use t-shirt sizing for estimating the task required to address the issue and explain your estimation. Consider the context of the SWEN90007 subject (Software Design and Architecture) (document here attached), including project requirements, workload, lecture materials, feedback processes, and team dynamics.

Your generated list of identified issues and categories:
[INCLUDE LIST]
```

**Tips**:
- Ensure the designed prompt is clear and specific to elicit detailed responses.
- Refine the final prompt by combining the strengths of both human and AI-generated prompts.

## Selection of One Idea 

**Objective**: Select one idea to address a specific problem identified in students' comments.

**Steps**:
1. (human) Select one idea to be improved and developed with the support of AI

**Tips**:
- Choose an idea that is feasible to be addressed and impactful.
- Ensure the idea is clearly defined before seeking AI assistance.

## Content Development (demonstration: development of 1 idea only)

**Objective**: Develop a practical solution to the selected problem using AI support.

**Steps**:
1. (human) Ask the LLM for some help on how to help improve your chosen problem.

(human) Input:

```text
ChatGPT: Please expand the existing Part 2 rubric considering the exact same existing criteria as specified in the attached document [upload project specification]. Expand each criterion with EMRN four-level evaluation.
```

(human) Input:

```text
Spark: Please expand the existing Part 2 rubric (identified in the assessment breakdown page) considering the exact same existing criteria as specified in the table. Expand each criterion with EMRN four-level evaluation. Make sure marks distribution remain the same for the four criterion assessed in Part 2.
```

**Tips**:
- Review and refine AI suggestions to ensure they are practical and applicable.
- Implement the most effective suggestions and test them in a real lecture setting.

## Bonus Points

- Identify when the model hallucinates (creates inaccurate information).
- Identify limitations when using a one-shot prompt.
- Identify the biggest ‘wow moment’.
- Present your findings.
- Think-pair-share with your nearest colleagues.

