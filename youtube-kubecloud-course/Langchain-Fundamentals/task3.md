# ⏰ Task 3: Template Magic (1 minute)

📚 What are Prompt Templates?

Definition: Reusable prompt blueprints with {placeholders} that get filled dynamically - like f-strings for AI prompts.

Think of them like Mad Libs for AI - same structure, different words each time!
😫 The Copy-Paste Nightmare:

// 100 files with slight variations:
"Explain quantum computing in simple terms"
"Explain machine learning in simple terms"
"Explain blockchain in simple terms"
// 😱 Change "simple terms" to "one sentence"? Edit 100 files!

✨ One Template to Rule Them All:

template = "Explain {topic} in {style}"
// Use it 1000 times with different values!
template.format(topic="AI", style="5 words")
template.format(topic="crypto", style="a haiku")

🎯 Real Impact: Uber reduced their prompt maintenance time by 85% using templates. One template update → thousands of prompts updated!

