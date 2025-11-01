# 🔌 Task 2: MCP and LangGraph Integration

⚠️ PREREQUISITE: Task 1 Server Must Be Running

Before starting Task 2, ensure:

    ✅ Terminal 1: Task 1 MCP server is running (showing "Server ready!")
    ✅ Terminal 2: Open a NEW terminal for Task 2
    ❌ If Task 1 server is NOT running, this task will fail!

⚙️ Connect MCP to Your Agents

📁 Select task_2_mcp_langgraph.py from the explorer

✏️ Complete the TODOs:

    Line 79: Configure calculator server: "calculator"
    Line 93: Get tools from client: client.get_tools()
    Line 97: Create react agent: create_react_agent

💡 Key Learning: MCP client connects to running server, loads tools dynamically, binds to LangGraph agent

🚀 Run Command (Terminal 2)
`python3 /root/code/task_2_mcp_langgraph.py`