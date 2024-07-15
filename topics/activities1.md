# Activity 1 [facilitator-led]

## Analyse ESS feedback, identify meaningful themes and provide suggestions for improvement

### [pre-condition] Configuring Spark:

1. Login to [Spark](https://spark.unimelb.edu.au/)

2. Click on '+ New thread' (left side of the screen, under 'Secure Chat')

3. Click on 'Thread Configuration' (top right corner of new chat window)

4. Select 'OpenAI GPT 4 Turbo 128k (preview)' as your LLM

5. Set 'Temperature' to 0.5

6. Click on 'Apply' button (top right corner of the screen)

### [context] ESS Example for Activity 1:

- [SWEN90007 Scenario](scenario.md)

## [12-45mins] Activity 1 - Enhancing Students Experience (facilitator-led: participants follow along) 
  
### Problem Identification (human vs Spark)

**Objective**: Identify problems in students' comments.

**Steps**:
1. (human) Write your list of identified problems in students' comments.
2. (AI) Ask AI to identify problems in students' comments. [copy and paste comments or upload document]

(human) Input:   

```
 Identify the key problems mentioned in the following student comments:
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

### Idea Generation (human and Spark)

**Objective**: Improve outcomes by adding actionable improvements to it.

**Steps**:
1. (human) Ask the LLM to design a prompt to list actionable improvements to identified problems in students' comments.

(human) Input:

```
Considering identified key problems in students' comments, please update that list with suggested actionable improvements. Provide the analysis in a structured format with headings for each identified problem, including a detailed description, suggested improvements and examples. Consider the context of the SWEN90007 subject (Software Design and Architecture) (document here attached), including project requirements, workload, lecture materials, feedback processes, and team dynamics.

Student Comments:
1. More refined/less vague project requirements.
2. Less workload – this is too much for students studying full time.
3. Lecture slides can be challenging to read, especially the code part.
4. Project part 2 was too big for the time given and expectations were unclear.
5. Feedback needs to be provided sooner.
6. Marking rubric for reports depends on the tutor's personal feelings.
7. Marking rubrics were under-specified for parts 2, 3, and 4.
8. Performance coverage was good but needed more guidance.
9. Team members were not friendly.
10. Need more guidance on assignments in tutorials.
11. Would like more activities in the classroom.
```


2. (human) Compare prompts' results, merge and refine your final prompt.  

**Tips**:
- Ensure the designed prompt is clear and specific to elicit detailed responses.
- Refine the final prompt by combining the strengths of both human and AI-generated prompts.

### Selection of One Idea 

**Objective**: Select one idea to address a specific problem identified in students' comments.

**Steps**:
1. (human) Select one idea to be improved and developed with the support of AI

**Tips**:
- Choose an idea that is feasible to be addressed and impactful.
- Ensure the idea is clearly defined before seeking AI assistance.

### Content Development (demonstration: development of 1 idea only)

**Objective**: Develop a practical solution to the selected problem using AI support.

**Steps**:
1. (human) Ask the LLM for some help on what prompts could be used to help improve your chosen problem.

(human) Input:

```text
What prompt can I use to generate improved rubrics for parts 2, 3 and 4 that address the problem related to under-specified marking rubrics?
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

