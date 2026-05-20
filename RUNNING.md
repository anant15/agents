# RUNNING.md

Quick start for this workspace (agents course repo)

1. Create and activate the Python virtual environment (repo provides .venv):
   - macOS/Linux: source .venv/bin/activate
   - Windows (Powershell): .\.venv\Scripts\Activate.ps1

2. Install Python requirements (if not already installed):
   pip install -r requirements.txt

3. Node setup for JS examples:
   - npm install

4. Environment variables:
   - Copy .env to .env.local or create a local .env with your API keys.
   - Required keys (examples):
     - OPENROUTER_API_KEY=your_openrouter_key
     - OPENAI_API_KEY=your_openai_key
     - Any provider-specific keys as noted in guides/ or setup/ files

5. Running examples:
   - See guides/ and specific folders for runnable demos. Many use `uv` and `crewai` tools described in the repo.

6. VS Code:
   - Recommended: select the workspace Python interpreter at `.venv/bin/python` (Command Palette: "Python: Select Interpreter").
   - The workspace settings include the recommended interpreter path.

7. Autocompletion & Agent setup:
   - To enable model-powered autocompletion and Agents, configure your model key in `.env` and follow the extension instructions (see .vscode/settings.json placeholders).

