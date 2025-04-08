## Common Limitations of GenAI

### Common Limitations of Generative AI (LLMs)
Generative AI tools are powerful, but they’re not magic. This page highlights some **known limitations** of large language models (LLMs) and offers **example prompts** so you can explore these weaknesses yourself.

---

## 1. Inaccurate Referencing and Citations

LLMs are not connected to real-time databases or reference managers. Even when they attempt to cite, the references often don’t exist or are mismatched.

**Try it yourself:**

> "Please provide 3 academic references (APA 7th) about the benefits of using GPT-4.5 model for writing in higher education, including DOIs."

> "Generate a list of peer-reviewed papers on climate justice in the Global South, with correct authors and publication years."

**Watch out for**: Made-up titles, incorrect DOIs, and mismatched authors.

---

## 2. Poor Performance with Complex Maths

## ➗ 2. Poor Performance with Complex Maths

LLMs can handle simple arithmetic and basic calculus, but they often **struggle with multi-step reasoning, symbolic manipulation, and logic-heavy maths problems**. They don’t “understand” maths — they’re predicting what looks like a correct answer, which means they can easily make subtle but critical errors.

**Try it yourself:**

> **Algebraic logic (multi-step)**  
> Solve for x:  
> 2(x + 3) = 3(x - 2) + x  
> *(Ask the model to show all steps)*

> **Recursive reasoning**  
> What is the 10th term of the sequence defined by:  
> a₁ = 1, a₂ = 2, and aₙ = aₙ₋₁ + aₙ₋₂ for n ≥ 3?

> **Symbolic manipulation**  
> Simplify the expression:  
> (2x² - 3x + 4)(x - 5) - (x² - x + 2)(3x + 1)

> **Multi-step logic puzzle**  
> A factory has two machines. Machine A produces 60% of the output and has a 2% defect rate. Machine B produces 40% of the output and has a 5% defect rate. If a randomly selected product is defective, what is the probability it came from Machine B?

**What to watch for**:
- Skipping steps or inventing steps that don’t follow logically  
- Confident but incorrect answers  
- Misuse of algebraic identities or calculus rules  
- Failing to remember previous variables or values in multi-part problems

**Facilitator Tip**: Copy the same prompt across multiple tools (e.g., ChatGPT, Claude, Gemini) and compare responses.

---

## 3. Struggles with Riddles, Logic, and Semantic Nuance

LLMs are great at pattern recognition but not reasoning. They can miss subtle semantic cues, fail to understand logic puzzles, or give answers that sound plausible but don’t hold up.

**Try it yourself:**

> "A man walks into a bar and orders a drink. He leaves without paying and the bartender is happy. Why?"

> "If two fathers and two sons sit down to eat three delicious vegan meals, and they all get one each, how is this possible?"


**Watch out for**: Over-confident explanations, missing logical connections, or surface-level answers.

---

## 4. Limited Knowledge (Cut-off and Hallucinations)

LLMs are trained on a static dataset. They **don’t know** anything that occurred after their last training cut-off (e.g. 2023 for GPT-4). They may also 'hallucinate'—i.e., make things up entirely.

**Try it yourself:**

> "Tell me what female won the 2025 Australian Open."

> "What are the latest COVID-19 vaccine updates from March 2025?"

> "What date is the next Australian federal election in 2025?"

**Watch out for**: Confidently false statements, fabricated news events, or vague hedging.

---

## What to try?

- **Compare tools** (e.g., Claude vs. ChatGPT) with the same prompt.
- Tweak the phrasing and **observe how small changes** impact accuracy.

