# ⏰ Task 1: OpenAI vs LangChain (2 minutes)

😵 Your Current Reality with OpenAI SDK:

client = OpenAI(api_key=key, base_url=url)
response = client.chat.completions.create(
    model="gpt-4",
    messages=[{"role": "user", "content": prompt}]
)
result = response.choices[0].message.content

10+ lines of boilerplate. Want to switch to Google? Rewrite everything! 😱
✨ The LangChain Way:

llm = ChatOpenAI(model="gpt-4")  # Or "gemini" or "grok"
response = llm.invoke(prompt)
result = response.content

3 lines. Switch models? Change ONE word. That's it! 🚀

🎯 Your Task: Experience the 70% code reduction yourself!

## 🆚 Task 1: Compare OpenAI SDK vs LangChain

📝 See the Dramatic Difference - 5 TODOs

📁 Select task_1_openai_vs_langchain.py from the explorer

📍 Go to line 17 (Press Ctrl+G or Cmd+G)
✏️ Raw OpenAI SDK (3 TODOs):

    Lines 18-21: Fill in API key and base URL
    Lines 24-29: Fill in model, role, and content
    Line 31: Fill in array index and field name

✏️ LangChain Approach (2 TODOs):

    Lines 45-49: Fill in model, API key, base URL
    Line 52: Fill in the question text

💡 Pro Tip: Use Ctrl+G (Windows/Linux) or Cmd+G (Mac) to jump to any line number!

🚀 Run Command
python /root/code/task_1_openai_vs_langchain.py

🎯 Why Run This Command?

After completing the TODOs, run the script to see:

    ✅ OpenAI SDK requires 10+ lines of boilerplate
    ✅ LangChain achieves the same with just 3 lines
    ✅ Both produce identical results
    ✅ 70% code reduction with LangChain!

Success: You'll see both approaches return the same response, proving LangChain's simplicity!