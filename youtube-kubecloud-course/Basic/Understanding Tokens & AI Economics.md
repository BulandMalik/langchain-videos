# Understanding Tokens & AI Economics

🧩 What Are Tokens?

Tokens are pieces of words that AI uses to process text:

    Simple words = 1 token ("cat", "run")
    Complex words = multiple tokens ("unbelievable" = ~3 tokens)
    Rough estimate: 1 token ≈ 4 characters
    Average: 1 token ≈ 0.75 words

📊 The Three Token Types

    prompt_tokens: Your question (what you send)
    completion_tokens: AI's answer (what you get back)
    total_tokens: Sum of both (what you pay for)

Find them in: response.usage
💸 Why Tokens = Money

AI companies charge by tokens consumed:

    Input tokens: $0.80 per million ($0.0008/1K)
    Output tokens: $3.20 per million ($0.0032/1K)
    Notice: Output costs 4x more than input!

💡 This is why keeping AI responses concise saves money!
🏢 Real Business Impact

Example: Customer Support Chatbot

1,000 queries/day × $0.001 per query = $1/day
→ Monthly: $30
→ Yearly: $365

vs. Human agent: $25/hour × 8 hours = $200/day!

🚀 What's Next? In Task 5, you'll calculate real costs for API calls and see how to optimize spending for your business use case!