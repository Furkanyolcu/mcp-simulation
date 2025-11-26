## System Requirements
- Python **3.10+**
- Python MCP SDK **1.2.0+**

---

2. Create and configure the project
# Create a new directory for the project
uv init weather
cd weather

# Create and activate a virtual environment
uv venv
.venv\Scripts\activate

# Install required dependencies
uv add mcp[cli] httpx

# Create the server file
new-item weather.py
