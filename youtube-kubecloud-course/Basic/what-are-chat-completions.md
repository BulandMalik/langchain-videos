# 💬 What are Chat Completions?

🗣️ It's a Conversation with AI

Chat Completions is OpenAI's conversational API. You send messages, AI responds - just like texting! The magic happens with `client.chat.completions.create()`

## 🧠 Choose Your AI Model

Different models = different AI brains. You MUST specify which one:

    gpt-4.1-mini: Fast, cheap, smart enough for most tasks (we'll use this!)
    gpt-4: Genius level, but slow and expensive
    gpt-3.5: Older, less capable

🎭 The Three Roles in Conversations

    "system": Instructions for how AI should behave (optional)
    "user": That's you asking questions
    "assistant": The AI's responses

📝 The Messages Format

Every API call needs these 2 parameters:

client.chat.completions.create(
    model="openai/gpt-4.1-mini",     # Which AI brain
    messages=[                        # The conversation
        {"role": "user", "content": "Your question here"}
    ]
)

Messages is an array because you can send conversation history!

🚀 What's Next? In Task 3, you'll use this exact format to make your first real API call and have your first conversation with AI!