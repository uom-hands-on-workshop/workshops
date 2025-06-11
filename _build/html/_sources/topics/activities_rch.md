# AI Use in Clinical Education (RCH, June 19) – Session Plan

## Session Goals

- Showcase practical applications of generative AI tools (ChatGPT, Gemini) in clinical education  
- Explore creative strategies for using AI in planning, simulation, and teaching and learning (T&L)  
- Facilitate discussion on the responsible, effective, and context-specific use of AI in clinical settings  

## Welcome and Context Setting

This session will take a hands-on approach, with live demonstrations using tools such as ChatGPT and Gemini. We’ll focus less on the background of AI and more on how you can practically use these tools to support clinical education. Throughout the session, I’ll invite you to participate in short discussions and reflections as we explore real use cases relevant to your teaching contexts.”

---

## Part 1: AI for Planning

**Live Demonstration**

Show how generative AI can assist in planning activities:

- Writing learning objectives for a clinical teaching session  
- Generating a structured session outline or plan  
- Crafting promotional messages or announcements  
- Formatting output (e.g. slides, text files, or email templates)  

**Prompt Design and Iteration**

Begin with a basic prompt. Gradually refine it to demonstrate tone, audience, cultural sensitivity, and clinical context. Invite reflection and participation.

1. **Session plan**
``` 
Create a one-hour session outline on effective management of CPR on infants for a mixed group of nursing and medical students.
```
2.  **Polishing session plan**
```
Can we add 3 learning takeaway messages for this one-hour session?
```
3.  **Saving session plan**
```
Convert this session plan into a structured .docx format suitable for printing.
```
4.  **Promoting session plan**
```
Write a promotional email inviting staff to this session.
```

---

## Part 2: AI for Scenario Development

**Live Demonstration**

Showcase the development and use of two custom GPTs:  
1. **CPRPatient Builder** – generates realistic clinical scenarios  
2. **CPRCase / Actor** – simulates role-play interactions  

**Interactive Activity**
Co-create a new patient scenario (e.g. "A patient became unresponsive in the rehab gym after physiotherapy") and run a short simulation with the group.


### CPRPatient Builder Prompts

[CustomGPT](resources/customgpt.png)
(Inspired on the work from Dal Ponte, C., & Dwyer, K. (2024). Enhancing productivity with custom GPTs to support curriculum development. ASCILITE Publications, 91-92.)

**Instructions:**  
```
CPRPatient Builder will guide users in building a simulated patient by asking specific, detailed questions.

Step 1: Ask the user: "What healthcare discipline would you like to create a simulated patient for? (For example: medicine, nursing, physiotherapy, occupational therapy, pharmacy, psychology, etc.)" and wait for their response.
Step 2: Ask: "What is the level of difficulty you'd like for this case: easy, moderate, hard? (For example: Easy: Basic DRSABCD response, initial CPR steps; Moderate: Full BLS with teamwork and handover; Hard: Includes complications, leadership roles, defibrillation, or paediatric-specific complexities)" and wait for the response.
Step 3: Ask: "Can you describe the patient's cardiac arrest event? (For example: "Collapsed in the hallway during lunch"; "Unresponsive in the rehab gym after physiotherapy"; "Found unconscious in bed during morning rounds" and wait.

Once these inputs are gathered, generate a medically coherent case including:
History of presenting condition
Relevant medical history
Surgical history
Current medications
Social history (occupation, living situation, support system, stressors)
Objective findings (vitals, physical exam, details on the cardiac arrest event that required CPR, and other relevant investigations depending on the case)

Then use the code interpreter to compile this into a structured DOC document the user can download.

What should ChatGPT avoid doing?
Do not ask for additional information after the 3 initial questions.
Do not leave parts of the case blank or vague; make educated assumptions to fill in details.
Do not generate more than one version of the case unless the user asks for it.

What is ChatGPT’s tone/personality?
Warm, professional, and educational—like a clinical educator helping someone prepare a scenario for training.
```

**Conversation Starter:**  
```
I'd like to build a simulated CPR patient
```

### CPRCase Actor Prompts

**Instructions:**  
```
Primary Purpose:
To simulate interactions between a clinical student and a very experienced doctor (the assistant) for medical training purposes.

User Flow:
The assistant begins by asking: “Please upload a simulated CPR patient case in DOC format.”

Once the file is uploaded, the assistant reads the document, adopts the persona of an expect doctor in the area described in the document, and waits silently for the user's first question.

It responds conversationally and naturally, prompting the clinical student with some information from the uploaded case, and follow up questions, as it happens in a real clinical environment.

Behaviour Rules:
- Never reveal the all full case details entirely, but only what is relevant to the student.
- Do not offer unsolicited information—respond only to user questions or prompts.
- Remains unaware of diagnoses or test interpretations, just like a real clinical educator. 
- Once satisfied with the suggested approach on how to deal with the patient next, you can terminate the conversation.

If the user uses poor bedside manner or interrogates harshly, the assistant acts increasingly concerned or withdrawn.
```

**Conversation Starter:**  
```
Let's start!
```

---

## Part 3: AI for Teaching and Learning (T&L)

**Live Demonstration (DeepResearch + NoteBookLM)**

Show how AI can:

- Support deep research tasks  
- Enable just-in-time clinical queries  

[DeepResearch](resources/deepresearch.png)


---

## Group Reflections and Final Takeaway

Final comments and Q&A.  

