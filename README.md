# Ex-4: Scenario-Based Report Development Utilizing Diverse Prompting Techniques
Objective: The goal of this experiment is to design and develop an AI-powered chatbot that can handle customer inquiries, provide support, and improve customer experience in a retail environment. Create prompts using various AI prompting techniques to guide your experiment, data collection, analysis, and report creation.
## Aim :

To evaluate and compare multiple prompting techniques in AI-based chatbot development for retail use cases. The aim is not only to test whether the chatbot provides correct answers but also to assess clarity, accuracy, empathy, personalization, logical reasoning, and overall customer satisfaction.

## Algorithm:

The procedure followed in this experiment is as below:

### Identify Use Cases
Selected scenarios for the chatbot:

Product availability

Order tracking

Return and refund policies

Troubleshooting faulty products

### Define Prompting Techniques
Prompts were framed under the following categories:

Zero-shot

One-shot

Few-shot

Role-based

Persona-driven

Instruction-based

Chain-of-thought

Socratic

### Design Prompts
Construct customer queries and frame them with each prompting technique.

### Execute Prompts
Provide prompts to AI models and collect their responses.

### Collect Outputs
Document chatbot answers for each scenario under each prompting style.

### Analyze Responses
Evaluate based on the following criteria:

Clarity (Is the answer understandable?)

Accuracy (Does it answer the question correctly?)

Empathy (Does it sound customer-friendly?)

Personalization (Is it tailored or generic?)

Effectiveness (Does it solve the query?)

### Compare Techniques
Highlight the advantages and disadvantages of each prompting approach.

### Conclude
Recommend the best hybrid approach for practical chatbot deployment.

### Prompts, Outputs & Observations
### Scenario 1: Product Availability

Customer Query: “Do you have Nike running shoes in size 9?”

Technique	Response	Observation
Zero-shot	“Nike shoes may be available. Please check our website.”	Generic, avoids confirmation; not customer-friendly.
One-shot	“Yes, Nike shoes in size 9 are available. Would you like delivery or pickup?”	Clear but assumes stock; lacks verification.
Few-shot	“Yes, Nike running shoes in size 9 are available. Should I add them to your cart?”	Natural and sales-driven, increases engagement.
Role-based	“Yes! Nike running shoes in size 9 are in stock. Would you like me to show available colors and styles?”	Engaging, personalized, feels like a real salesperson.
### Scenario 2: Order Tracking

Customer Query: “Where is my order #12345?”

Technique	Response	Observation
Zero-shot	“Your order is being processed.”	Very vague; customer still confused.
Few-shot	“Order #12345 has been shipped and will arrive tomorrow evening.”	Accurate and reassuring; improves satisfaction.
Role-based	“I understand your concern. Order #12345 has been dispatched and should reach you tomorrow. Thank you for your patience!”	Adds empathy and reassurance along with accuracy.

### Scenario 3: Return & Refund Policy

Customer Query: “Can I return a product if I don’t like it?”

Technique	Response	Observation
Instruction-based	“Yes, you can return products within 30 days if unused and in original packaging.”	Clear, direct, and accurate; good for policy-related queries.
Socratic	“Was the item purchased in the last 30 days? Is it unused and in its original box? If yes, you are eligible for a return.”	Encourages user to self-verify, but less direct; may frustrate impatient users.

### Scenario 4: Troubleshooting

Customer Query: “My coffee maker is not working. What should I do?”

Chain-of-thought Prompting:
Response: “Step 1: Ensure the coffee maker is plugged in. Step 2: Refill the water tank. Step 3: Check if the filter is clogged. If the issue persists, contact our support team.”
Analysis: Structured and logical; provides actionable troubleshooting.

Persona-driven Prompting:
Response: “Don’t worry, let’s fix this together! Please check the power cord, water tank, and filter. If it’s still not working, our team will gladly assist further.”
Analysis: Friendly, supportive, and stress-reducing; humanizes the chatbot.

## Comparative Evaluation Table
| **Technique**     | **Strengths**                                            | **Weaknesses**                                                    |
| ----------------- | -------------------------------------------------------- | ----------------------------------------------------------------- |
| Zero-shot         | Quick, minimal setup; useful for generic responses.      | Too vague; lacks empathy and depth.                               |
| One-shot          | More context than zero-shot; decent clarity.             | May assume facts (e.g., product availability) without confirming. |
| Few-shot          | Produces natural, contextual, polished responses.        | Requires good examples; can be biased if examples are poor.       |
| Role-based        | Highly engaging, empathetic, and user-friendly.          | Slightly longer responses; may over-personalize.                  |
| Persona-driven    | Human-like, empathetic, reduces frustration.             | Risk of being too casual in professional settings.                |
| Instruction-based | Precise, concise, and accurate for rules/policies.       | May sound robotic; lacks warmth.                                  |
| Chain-of-thought  | Excellent for step-by-step reasoning or troubleshooting. | Responses may be too long for simple queries.                     |
| Socratic          | Encourages critical thinking and self-verification.      | Can frustrate users who want quick, direct answers.               |


#### Analysis of Results

Zero-shot prompting was the least effective because it provided vague, non-committal answers.

One-shot and Few-shot prompting gave much more useful and context-aware responses.

Role-based and Persona-driven prompting created a customer-friendly and empathetic chatbot, improving user satisfaction.

Instruction-based prompting worked best for clear, rule-based queries such as policies.

Chain-of-thought prompting was extremely effective for troubleshooting, as it guided users step by step.

Socratic prompting had educational value but was not practical for customer support where quick answers are expected.

## Conclusion

From this experiment, it is clear that no single prompting technique is universally effective. The best performance comes from a hybrid strategy:

Few-shot prompting ensures contextual accuracy.

Role-based prompting builds empathy and engagement.

Chain-of-thought prompting provides structured problem-solving.

Instruction-based prompting handles clear policy explanations.

Therefore, combining these techniques results in a chatbot that is accurate, empathetic, logical, and user-friendly, which ultimately enhances customer satisfaction and trust in retail services.
