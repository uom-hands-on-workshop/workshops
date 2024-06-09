# Prompts

## Workshop 1: Introduction to Generative AI in T&L (Hands-on)

### Facilitator-led Activity [20 minutes]

**Objective**: Participants follow exact activities on their computers.

**Scenario**: Actioning feedback to enhance student experience in our subjects (real scenario – SWEN subject)

#### REAL SCENARIO: What would have improved your learning experience in this subject?

This report lists all comments entered by students.

```text
 - More refined/less vague project requirements 
 - Less workload – this is too much for student studying full time.
 - I think the lecture slides can be a bit challenging to read – especially the code part. I think the problem is that, when we try to put lots of code on one slide, then the text become rather small. Not sure what would be a better way though...
 - The project part 2 was far too big for the time given and I feel like some expectations for that part were not overly clear. I really enjoyed the subject otherwise 
 - Feedback needs to be provided sooner
 - Marking rubric for reports, extremely depends on tutor's personal feelings
 - Our team really felt the marking rubrics were under specified for parts 2, 3, and 4.
 - Even though the performance stuff was kind of tacked onto the end of the course, I'm really glad it was covered, as it wasn't something I had ever even considered when doing application development. In future, it would be nice to have a bit more guidance in this area.
 - Team members is not friendly 
 - Tutorials
 - I will appreciate if there could be more guidances on assignments in tutorials 
 - I would like more activities in classroom
```

Link to subject handbook: [https://handbook.unimelb.edu.au/2022/subjects/swen90007/assessment](https://handbook.unimelb.edu.au/2022/subjects/swen90007/assessment)

Project details and rubrics can be accessed [here](resources/SWEN90007Project2022_v1.pdf)

Tutorials: [https://cis-projects.github.io/swen90007_course_notes/introduction/introduction.html](https://cis-projects.github.io/swen90007_course_notes/introduction/introduction.html)

#### Activity Steps:

1. **Problem Identification (human vs SparkAI)**
- **Task**: Identify problems in students' comments.

   a. (human) Write your list of identified problems in students' comments.

   b. (AI) Ask AI to identify problems in students' comments.

   c. (human & AI) combine the list of identified problems in students' comments.

- **Prompt Example**:
(human) Input:   
```text
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

(LLM) Output:
```text
Based on the feedback provided by the students, the following key problems have been identified:

1. Project Requirements
   - Problem: The project requirements were perceived as vague and needed more refinement.
   - Comment: "More refined/less vague project requirements."

2. Workload
   - Problem: The workload was considered too heavy, especially for students studying full time.
   - Comment: "Less workload – this is too much for students studying full time."

3. Lecture Slides
   - Problem: Lecture slides, particularly those with code, were challenging to read due to small text.
   - Comment: "Lecture slides can be challenging to read, especially the code part."

4. Project Expectations
   - Problem: Part 2 of the project was too large for the time allotted, and expectations were unclear.
   - Comment: "Project part 2 was too big for the time given and expectations were unclear."

5. Timely Feedback
   - Problem: Feedback was not provided in a timely manner.
   - Comment: "Feedback needs to be provided sooner."

6. Marking Rubric Subjectivity
   - Problem: The marking rubric for reports was seen as dependent on the tutor's personal feelings.
   - Comment: "Marking rubric for reports depends on the tutor's personal feelings."

7. Under-specified Marking Rubrics
   - Problem: Marking rubrics for parts 2, 3, and 4 were under-specified.
   - Comment: "Marking rubrics were under-specified for parts 2, 3, and 4."

8. Performance Guidance
   - Problem: While performance topics were covered, more guidance was needed.
   - Comment: "Performance coverage was good but needed more guidance."

9. Team Dynamics
   - Problem: Issues with team members not being friendly.
   - Comment: "Team members were not friendly."

10. Guidance on Assignments
    - Problem: More guidance on assignments during tutorials was requested.
    - Comment: "Need more guidance on assignments in tutorials."

11. Classroom Activities
    - Problem: Desire for more activities in the classroom to enhance learning.
    - Comment: "Would like more activities in the classroom."
```

2. **Prompt Engineering to Improve Outcomes From Initial Prompt**
- **Task**: Improve outcomes by considering additional context.

   a. (human) Write an improved prompt to list identified problems in students' comments.

   b. (human) Ask the LLM for some help to improve design a prompt to list identified problems in students' comments.

   c. (human) Compare prompts, merge and polish your final prompt.

- **Advanced Prompt Example**:
(human) Input:
```text
Analyse the following student comments to identify key problems and suggest actionable improvements. Provide the analysis in a structured format with headings for each identified problem, including a detailed description, suggested improvements, examples, and references. Consider the context of the SWEN90007 subject (Software Design and Architecture) (document here attached), including project requirements, workload, lecture materials, feedback processes, and team dynamics.

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

Output Format:
- Problem #1: [Problem Title]
  - Description: [Detailed description of the problem]
  - Suggested Improvements:
    - Improvement 1: [Description]
    - Improvement 2: [Description]
  - Examples: [Provide examples that support the suggested improvements]
  - References: [Include any references or resources that support the analysis and improvements]

- Problem #2: [Problem Title]
  - Description: [Detailed description of the problem]
  - Suggested Improvements:
    - Improvement 1: [Description]
    - Improvement 2: [Description]
  - Examples: [Provide examples that support the suggested improvements]
  - References: [Include any references or resources that support the analysis and improvements]

... Continue this format for all identified problems.
```

(LLM) Output:
```text
Analysis of Student Comments for SWEN90007 Subject

Problem #1: Vague Project Requirements
- Description: Students felt that the project requirements were too vague, leading to confusion and a lack of direction.
- Suggested Improvements:
  - Improvement 1: Provide a detailed project requirements document with clear specifications, goals, and expectations.
  - Improvement 2: Include examples of what a successful project should look like to help students understand the requirements.
- Examples:
  - Example project briefs from previous years that were highly rated.
- References:
  - "Writing Effective Project Requirements" by Karl Wiegers and Joy Beatty.
  - SWEN90007 Project 2022_v1.pdf (detailed project description).

Problem #2: Excessive Workload
- Description: The workload for the course was considered too heavy, particularly for students studying full-time.
- Suggested Improvements:
  - Improvement 1: Break down the project into smaller, more manageable tasks with staggered deadlines.
  - Improvement 2: Provide optional resources and extensions for students who need more time.
- Examples:
  - Introducing weekly milestones to ensure steady progress.
- References:
  - "Managing Student Workload" by John Biggs and Catherine Tang.

Problem #3: Challenging Lecture Slides
- Description: Lecture slides, especially those containing code, were difficult to read due to small text and dense information.
- Suggested Improvements:
  - Improvement 1: Use larger fonts and highlight key sections of the code to improve readability.
  - Improvement 2: Provide downloadable, annotated code examples separate from the slides.
- Examples:
  - Annotated code snippets provided as supplementary material.
- References:
  - "Effective Use of Presentation Slides in the Classroom" by Garr Reynolds.

Problem #4: Large Project Part 2
- Description: Part 2 of the project was too extensive for the time given, and expectations were unclear.
- Suggested Improvements:
  - Improvement 1: Reduce the scope of Part 2 or provide additional time to complete it.
  - Improvement 2: Offer detailed guidelines and examples of what is expected.
- Examples:
  - A clear rubric outlining the criteria for each section of Part 2.
- References:
  - SWEN90007 Project 2022_v1.pdf (detailed project description).

Problem #5: Timely Feedback
- Description: Students expressed the need for more timely feedback on their work.
- Suggested Improvements:
  - Improvement 1: Implement a feedback schedule with specific deadlines for when students can expect their feedback.
  - Improvement 2: Use automated tools to provide instant feedback on certain aspects of their work.
- Examples:
  - Mid-project review sessions to provide interim feedback.
- References:
  - "Feedback in Higher and Professional Education" by David Boud and Elizabeth Molloy.

Problem #6: Subjective Marking Rubric
- Description: The marking rubric was perceived as being subjective and dependent on the tutor's personal feelings.
- Suggested Improvements:
  - Improvement 1: Develop a standardised rubric with clear, objective criteria.
  - Improvement 2: Ensure that all tutors are calibrated and trained to apply the rubric consistently.
- Examples:
  - Rubric calibration sessions before the start of the course.
- References:
  - "Developing and Using Rubrics for Assessment" by Jon Mueller.

Problem #7: Under-specified Marking Rubrics
- Description: Students felt that the marking rubrics for parts 2, 3, and 4 were under-specified.
- Suggested Improvements:
  - Improvement 1: Provide detailed rubrics for each part of the project, specifying the criteria and weight of each component.
  - Improvement 2: Include examples of graded work to illustrate the application of the rubric.
- Examples:
  - Sample graded projects with annotations explaining the scoring.
- References:
  - "Assessment Clear and Simple: A Practical Guide for Institutions, Departments, and General Education" by Barbara E. Walvoord.

Problem #8: Performance Guidance
- Description: While performance topics were covered, students needed more guidance in this area.
- Suggested Improvements:
  - Improvement 1: Integrate performance-related content throughout the course rather than just at the end.
  - Improvement 2: Provide additional resources and examples related to performance optimisation.
- Examples:
  - Case studies on performance tuning in software projects.
- References:
  - "Optimising Java: Practical Techniques for Improving JVM Application Performance" by Benjamin J. Evans.

Problem #9: Team Dynamics
- Description: Issues with team members not being friendly or collaborative.
- Suggested Improvements:
  - Improvement 1: Facilitate team-building activities at the beginning of the course to foster better collaboration.
  - Improvement 2: Implement peer evaluation mechanisms to address team dynamics issues.
- Examples:
  - Team charters and conflict resolution workshops.
- References:
  - "Team Building: Proven Strategies for Improving Team Performance" by W. G. Dyer.

Problem #10: Guidance on Assignments
- Description: Students requested more guidance on assignments during tutorials.
- Suggested Improvements:
  - Improvement 1: Allocate specific time during tutorials for assignment-related Q&A sessions.
  - Improvement 2: Provide detailed assignment guides and checklists.
- Examples:
  - Weekly assignment support sessions led by tutors.
- References:
  - "The Lecturer's Toolkit: A Practical Guide to Assessment, Learning and Teaching" by Phil Race.

Problem #11: Classroom Activities
- Description: Students wanted more activities in the classroom to enhance their learning experience.
- Suggested Improvements:
  - Improvement 1: Incorporate interactive activities and group work into lecture sessions.
  - Improvement 2: Use technology, such as clickers and online polls, to make lectures more engaging.
- Examples:
  - Real-time quizzes and interactive problem-solving sessions.
- References:
  - "Active Learning: Creating Excitement in the Classroom" by Charles C. Bonwell and James A. Eison.
```

3. **Selection of One Problem and Content Development**
- **Task**: Address issues related to rubrics and support teamwork.

   a. (human) Select one idea to be improved and developed with the support of AI

- **Selected Problem: Rubrics (#7)**:
   
- **Prompt Example**:
     
  a. (human) Ask the LLM for some help on what prompts could be used to help improving the rubrics for parts 2, 3 and 4 of SWEN90007 project description.

(human) Input:
```text
What prompt can I use to generate improved rubrics for parts 2, 3 and 4 that address Problem #7: Under-specified Marking Rubrics?
```

(LLM) Output:
```text
Develop detailed and specific marking rubrics for Parts 2, 3, and 4 of the SWEN90007 project (Software Design and Architecture). Each rubric should extend the description of the listed criteria, clearly outlining the criteria, the weight of each component, and providing a comprehensive description that enhances the assessment breakdown for students, ensuring clarity and consistency. Include descriptions for different levels of performance (e.g., excellent, good, satisfactory, needs improvement) and provide examples to illustrate each level. Consider the context and requirements of the SWEN90007 subject as outlined in the project description. Format the output in a structured manner.

Output Format:

- Part N: [Name of Part]
  - Criterion 1: [Criterion Name] ([Weight]%)
    - Excellent (90-100): [Detailed description of what constitutes excellent performance]
    - Good (75-89): [Detailed description of what constitutes good performance]
    - Satisfactory (50-74): [Detailed description of what constitutes satisfactory performance]
    - Needs Improvement (0-49): [Detailed description of what constitutes performance that needs improvement]

Project Parts:

1. Part 2: Design and Implementation
   - Criteria and Description:
     - Class Diagram: Evaluates the accuracy, detail, and comprehensiveness of the class diagram using correct UML notation. The diagram should include all necessary classes, relationships, and multiplicities.
     - Pattern Description: Assesses the clarity, completeness, and contextualization of the pattern descriptions, including relevant diagrams to illustrate their use.
     - Design Rationale: Evaluates the strength and clarity of the rationale for design choices, including supporting evidence and alignment with design principles.
     - Functionality and Pattern Implementation: Checks the correctness and completeness of the implementation, including how well patterns are applied and the overall functionality of the application.
   - Weight: Specify the percentage or points for each criterion.

2. Part 3: Concurrency and Deployment
   - Criteria and Description:
     - Class Diagram: Evaluates the accuracy, detail, and comprehensiveness of the class diagram using correct UML notation, with a focus on concurrency-related classes and relationships.
     - Concurrency Issues and Pattern Description: Assesses the identification and description of concurrency issues and the patterns used to address them, including diagrams and examples.
     - Design Rationale for Concurrency Patterns: Evaluates the rationale for the chosen concurrency patterns, including supporting evidence and explanations.
     - Testing Strategy and Outcomes: Assesses the thoroughness and clarity of the testing strategy for concurrency issues, as well as the documented outcomes.
     - Functionality and Pattern Implementation: Checks the correctness and completeness of the implementation, including concurrency handling and overall functionality.
   - Weight: Specify the percentage or points for each criterion.

3. Part 4: Performance Reflection
   - Criteria and Description:
     - Performance Discussion: Evaluates the depth and insightfulness of the discussion on system performance, including concrete examples and analysis.
     - Use of Design Patterns: Assesses the effective use of design patterns, including clear explanations and examples.
     - Impact on Performance: Evaluates the explanation of how design patterns impacted performance, including detailed analysis and examples.
   - Weight: Specify the percentage or points for each criterion.

Provide the rubrics in a clear and structured manner, ensuring they are easy to understand and apply.
```

(LLM) Output (as a result of the previous suggested prompt)
```text
Part 2: Design and Implementation
- Criteria and Description:
  - Class Diagram (20%): Evaluates the accuracy, detail, and comprehensiveness of the class diagram using correct UML notation. The diagram should include all necessary classes, relationships, and multiplicities.
    - Excellent (90-100): Accurate, detailed, and comprehensive class diagram using correct UML notation, including all necessary classes, relationships, and multiplicities.
    - Good (75-89): Mostly accurate class diagram with minor errors in UML notation or detail, including most necessary elements.
    - Satisfactory (50-74): Basic class diagram with several errors or omissions, missing some necessary elements.
    - Needs Improvement (0-49): Incomplete or incorrect class diagram with significant errors, missing many necessary elements.

  - Pattern Description (40%): Assesses the clarity, completeness, and contextualisation of the pattern descriptions, including relevant diagrams to illustrate their use.
    - Excellent (90-100): Clear, complete, and contextualised descriptions of patterns with relevant diagrams, demonstrating thorough understanding and application.
    - Good (75-89): Detailed descriptions with minor omissions or errors, demonstrating good understanding and application.
    - Satisfactory (50-74): Basic descriptions with some omissions or errors, demonstrating basic understanding and application.
    - Needs Improvement (0-49): Incomplete or incorrect descriptions with significant errors, demonstrating poor understanding and application.

  - Design Rationale (20%): Evaluates the strength and clarity of the rationale for design choices, including supporting evidence and alignment with design principles.
    - Excellent (90-100): Strong, well-argued rationale for design choices with supporting evidence and alignment with design principles.
    - Good (75-89): Adequate rationale with some supporting evidence and general alignment with design principles.
    - Satisfactory (50-74): Basic rationale with limited evidence and alignment with design principles.
    - Needs Improvement (0-49): Poor or no rationale with little to no supporting evidence or alignment with design principles.

  - Functionality and Pattern Implementation (20%): Checks the correctness and completeness of the implementation, including how well patterns are applied and the overall functionality of the application.
    - Excellent (90-100): Fully functional implementation with correctly applied patterns, demonstrating comprehensive understanding and skill.
    - Good (75-89): Mostly functional implementation with minor issues, demonstrating good understanding and skill.
    - Satisfactory (50-74): Basic implementation with several issues, demonstrating basic understanding and skill.
    - Needs Improvement (0-49): Non-functional or incorrect implementation, demonstrating poor understanding and skill.

Part 3: Concurrency and Deployment
- Criteria and Description:
  - Class Diagram (10%): Evaluates the accuracy, detail, and comprehensiveness of the class diagram using correct UML notation, with a focus on concurrency-related classes and relationships.
    - Excellent (90-100): Accurate, detailed, and comprehensive class diagram using correct UML notation, including all necessary concurrency-related classes and relationships.
    - Good (75-89): Mostly accurate class diagram with minor errors in UML notation or detail, including most necessary elements.
    - Satisfactory (50-74): Basic class diagram with several errors or omissions, missing some necessary elements.
    - Needs Improvement (0-49): Incomplete or incorrect class diagram with significant errors, missing many necessary elements.

  - Concurrency Issues and Pattern Description (30%): Assesses the identification and description of concurrency issues and the patterns used to address them, including diagrams and examples.
    - Excellent (90-100): Clear identification and detailed descriptions of all concurrency issues and patterns, including diagrams and examples.
    - Good (75-89): Mostly clear identification with minor omissions or errors, including most necessary elements.
    - Satisfactory (50-74): Basic identification with several omissions or errors, missing some necessary elements.
    - Needs Improvement (0-49): Poor or incorrect identification with significant errors, missing many necessary elements.

  - Design Rationale for Concurrency Patterns (20%): Evaluates the rationale for the chosen concurrency patterns, including supporting evidence and explanations.
    - Excellent (90-100): Strong, well-argued rationale for concurrency pattern choices with supporting evidence and alignment with design principles.
    - Good (75-89): Adequate rationale with some supporting evidence and general alignment with design principles.
    - Satisfactory (50-74): Basic rationale with limited evidence and alignment with design principles.
    - Needs Improvement (0-49): Poor or no rationale with little to no supporting evidence or alignment with design principles.

  - Testing Strategy and Outcomes (20%): Assesses the thoroughness and clarity of the testing strategy for concurrency issues, as well as the documented outcomes.
    - Excellent (90-100): Comprehensive testing strategy with clear and detailed outcomes, demonstrating thorough understanding and application.
    - Good (75-89): Adequate testing strategy with mostly clear outcomes, demonstrating good understanding and application.
    - Satisfactory (50-74): Basic testing strategy with several omissions, demonstrating basic understanding and application.
    - Needs Improvement (0-49): Poor or incomplete testing strategy, demonstrating poor understanding and application.

  - Functionality and Pattern Implementation (20%): Checks the correctness and completeness of the implementation, including concurrency handling and overall functionality.
    - Excellent (90-100): Fully functional implementation with correctly applied patterns, demonstrating comprehensive understanding and skill.
    - Good (75-89): Mostly functional implementation with minor issues, demonstrating good understanding and skill.
    - Satisfactory (50-74): Basic implementation with several issues, demonstrating basic understanding and skill.
    - Needs Improvement (0-49): Non-functional or incorrect implementation, demonstrating poor understanding and skill.

Part 4: Performance Reflection
- Criteria and Description:
  - Performance Discussion (50%): Evaluates the depth and insightfulness of the discussion on system performance, including concrete examples and analysis.
    - Excellent (90-100): Comprehensive and insightful discussion on system performance with detailed examples, demonstrating thorough understanding.
    - Good (75-89): Adequate discussion with some examples, demonstrating good understanding.
    - Satisfactory (50-74): Basic discussion with limited examples, demonstrating basic understanding.
    - Needs Improvement (0-49): Poor or incomplete discussion with few to no examples, demonstrating poor understanding.

  - Use of Design Patterns (30%): Assesses the effective use of design patterns, including clear explanations and examples.
    - Excellent (90-100): Effective use of design patterns with clear explanations and examples, demonstrating comprehensive understanding.
    - Good (75-89): Mostly effective use with minor omissions, demonstrating good understanding.
    - Satisfactory (50-74): Basic use with several omissions, demonstrating basic understanding.
    - Needs Improvement (0-49): Poor or ineffective use of design patterns, demonstrating poor understanding.

  - Impact on Performance (20%): Evaluates the explanation of how design patterns impacted performance, including detailed analysis and examples.
    - Excellent (90-100): Clear and detailed explanation of how design patterns impacted performance, demonstrating thorough understanding.
    - Good (75-89): Adequate explanation with some details, demonstrating good understanding.
    - Satisfactory (50-74): Basic explanation with limited details, demonstrating basic understanding.
    - Needs Improvement (0-49): Poor or no explanation of impact on performance, demonstrating poor understanding.
```

- **Supporting Teamwork**: Create an announcement or guidelines to support teamwork in SWEN90007, focusing on conflict resolution, collaboration strategies, and effective communication. Include examples and best practices.


#### Discussions about Misconceptions, Hallucinations, Ethics

- **Discussions (led by facilitators)**: Why are the suggested ideas good? Are there any research findings or best practices that support these ideas? Discuss any misconceptions or hallucinations that may arise during idea generation and how to address them.


### Hands-on Activities (T&L) [30 minutes]

**Objective**: Participants engage in T&L hands-on activities with facilitator support.
- **Task: Selection of Another SES Problem and Content Development** 

   a. (human) Select one new problem from the list below and interact with the LLM to find ways to address it. You should develop contents together with the LLM.

```text
Problem #1: Vague Project Description
Problem #2: Excessive Workload
Problem #3: Challenging Lecture Slides
Problem #5: Timely Feedback
Problem #6: Subjective Marking Rubric
Problem #8: Performance Guidance
Problem #9: Team Dynamics
Problem #10: Guidance on Assignments
Problem #11: Classroom Activities
```

- **Task: Design Some Classroom Activities**: 

   a. (human) Interact with the LLM to address issues related to problem #11. You should chat with the LLM to identify options on how to promote classroom activities, select and develop one.

### Hands-on Activities (Tips and Tricks) [30 minutes]

**Objective**: Participants engage in day-to-day hands-on activities with facilitator support (focus on productivity boost).

1. **Tasting Plate of Activities**
- **Whiteboards**: From handwritten to typed notes (digitalisation of contents)

```{figure} resources/whiteboard1.jpeg
---
name: whiteboard1
---
```

```{figure} resources/whiteboard2.jpeg
---
name: whiteboard2
---
```

Task: Can you digitalise the two images above and combine them in one text using a LLM?

- **Meeting Minutes**: Documenting notes efficiently
- **Writing**: Emails (one-to-one communication), announcements (one-to-many)
- **Discussion Board**: Analytics on threads
- **Research**: Summarising papers, supporting analysis, managing citations & references
- **Proof-reading**:

#### Wrap-up [5 minutes]

**Objective**: Summarise the workshop and discuss key takeaways.

