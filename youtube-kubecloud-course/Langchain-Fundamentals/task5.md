# ⏰ Task 5: The Magic | Operator (2 minutes)

📚 What is Chain Composition?

Definition: Connecting LangChain components with the | operator to create data pipelines - like Unix pipes for AI.

Each component does ONE thing perfectly. Chain them together to build complex AI workflows!
🧩 From Chaos to Elegance
😵 Without Chains:

prompt = template.format(...)
response = llm.invoke(prompt)
content = response.content
parsed = parser.parse(content)
// 4 steps, 4 variables 😫

✨ With Chains:

chain = prompt | llm | parser
result = chain.invoke(data)
// 2 lines. Done! 🎉

⛓️ The Power of |

Just like Unix pipes, data flows left to right:

prompt | llm | parser | database_save | email_notify

Each component does ONE thing well. Combine them infinitely!

🏆 Master Move: Amazon's recommendation engine uses 50+ chained components. Each team owns different parts, but they all connect with |