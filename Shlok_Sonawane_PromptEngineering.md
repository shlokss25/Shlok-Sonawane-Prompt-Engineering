# Prompt Engineering Portfolio

Name: Shlok Sonawane
Date: 02 June 2026
LLM Used: ChatGPT (GPT-5.5)


## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation

**Goal:** Explain neural networks to a 10-year-old child.

#### Version 1 Prompt

Explain neural networks.

#### Version 1 Output

Neural networks are a type of artificial intelligence inspired by the human brain. They consist of interconnected nodes called neurons that process information and learn patterns from data. Neural networks are used in image recognition, language processing, and many other AI applications.

#### Version 2 Prompt

Explain neural networks to a child using simple language and examples.

#### Version 2 Output

A neural network is a computer system that learns from examples, similar to how people learn. Imagine teaching a child to recognize cats by showing many pictures of cats. The computer looks at lots of examples and slowly learns what makes a cat different from other animals. After enough practice, it can recognize new cat pictures on its own.

#### Version 3 Prompt

You are an expert elementary school science teacher. Explain neural networks to a 10-year-old student who has never studied computers before. Use a simple real-life analogy, avoid technical jargon, and keep the explanation under 200 words.

#### Final Output

Imagine your brain is made up of millions of tiny helpers that work together to solve problems. A neural network works in a similar way inside a computer. Think of it like a team of students trying to identify different fruits. One student looks at the color, another looks at the shape, and another looks at the size. Together they decide whether the fruit is an apple, banana, or orange.

A neural network learns by looking at many examples. If it makes a mistake, it adjusts its thinking and tries again. After lots of practice, it becomes much better at recognizing patterns.

This is how computers can learn to recognize faces, understand speech, and even help answer questions.

#### Iteration Documentation

| Version | Prompt                                                                 | What Changed                                    | Why This Improved the Output                              |
| ------- | ---------------------------------------------------------------------- | ----------------------------------------------- | --------------------------------------------------------- |
| V1      | Explain neural networks.                                               | N/A                                             | N/A                                                       |
| V2      | Explain neural networks to a child using simple language and examples. | Added audience and simplicity requirement.      | Output became easier to understand.                       |
| V3      | Added teacher role, age, context, analogy requirement, word limit.     | Added role assignment and detailed constraints. | Produced a focused explanation tailored to a 10-year-old. |

---

### 1.1 Scenario B: Professional Email

**Goal:** Politely decline a job offer while maintaining interest in the company.

#### Version 1 Prompt

Write an email declining a job offer.

#### Version 1 Output

Dear Hiring Manager,

Thank you for the job offer. I have decided not to accept it at this time.

Best regards.

#### Version 2 Prompt

Write a polite email declining a job offer while thanking the company.

#### Version 2 Output

Dear Hiring Manager,

Thank you very much for offering me the position. I appreciate the time and effort invested in the recruitment process.

After careful consideration, I have decided not to accept the offer at this time. I am grateful for the opportunity and wish the company continued success.

Sincerely,
Shlok Sonawane

#### Version 3 Prompt

Write a professional email declining a job offer because I have accepted another opportunity. Express genuine appreciation, maintain a positive relationship, and mention that I would be interested in future opportunities with the company.

#### Final Output

Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you very much for offering me the position and for the time your team invested throughout the interview process.

After careful consideration, I have decided to accept another opportunity that aligns more closely with my current career goals. This was a difficult decision because I was genuinely impressed by your organization, team, and company culture.

I sincerely appreciate the opportunity to learn more about your company and would welcome the possibility of staying in touch. I hope our paths may cross again in the future, and I would be happy to consider opportunities with your organization later in my career.

Thank you again for your understanding and support.

Kind regards,

Shlok Sonawane

#### Iteration Documentation

| Version | Prompt                                                              | What Changed                           | Why This Improved the Output         |
| ------- | ------------------------------------------------------------------- | -------------------------------------- | ------------------------------------ |
| V1      | Write an email declining a job offer.                               | N/A                                    | N/A                                  |
| V2      | Added politeness and gratitude.                                     | Included appreciation.                 | Created a more professional tone.    |
| V3      | Added reason, future interest, and relationship-building objective. | Added context and communication goals. | Produced a realistic business email. |

---

### 1.1 Scenario C: Creative Content

**Goal:** Generate a marketing tagline for an eco-friendly water bottle brand.

#### Version 1 Prompt

Create a tagline for a water bottle brand.

#### Version 1 Output

Stay hydrated every day.

#### Version 2 Prompt

Create a catchy tagline for an eco-friendly water bottle brand.

#### Version 2 Output

Drink Smart. Live Green.

#### Version 3 Prompt

You are an award-winning sustainability-focused marketing copywriter. Create five memorable taglines for a new eco-friendly water bottle brand called EcoSip. The target audience is environmentally conscious young professionals. Emphasize sustainability, convenience, and positive environmental impact.

#### Final Output

1. EcoSip – Every Sip Makes a Difference.
2. Hydrate Responsibly. Live Sustainably.
3. Drink Clean. Leave Green.
4. Refresh Yourself, Not the Landfill.
5. EcoSip – Small Bottle, Big Impact.

#### Iteration Documentation

| Version | Prompt                                                             | What Changed                            | Why This Improved the Output                           |
| ------- | ------------------------------------------------------------------ | --------------------------------------- | ------------------------------------------------------ |
| V1      | Create a tagline for a water bottle brand.                         | N/A                                     | N/A                                                    |
| V2      | Added eco-friendly context.                                        | Introduced sustainability theme.        | Generated a more relevant slogan.                      |
| V3      | Added role, brand name, target audience, and marketing objectives. | Added detailed context and constraints. | Produced stronger and more targeted marketing content. |

---

### 1.2 Iteration Documentation Summary

The refinement process demonstrated that prompt quality directly influences output quality. Initial prompts produced generic responses because they lacked context, audience definition, and constraints. Adding specific instructions improved relevance and clarity. The final prompts generated significantly better outputs because they combined role assignment, audience awareness, and clear objectives.

### 1.3 Role and Context Analysis

Role assignment and context setting significantly improved the quality of responses. In Scenario A, assigning the model the role of an elementary school teacher encouraged the use of simple language and relatable analogies. In Scenario C, assigning the role of a professional marketing copywriter resulted in more persuasive and audience-focused taglines. Context provided information about the intended audience and goals, helping the model generate responses that were more relevant, accurate, and useful.
