Insatlling UV:

powershell -c "irm https://astral.sh/uv/install.ps1 | iex"

Verify Installation:

uv --version

OR

uv version


Setting Up a FastAPI Project with UV:

Step 1: Create a Project Directory and Switch to it

uv init 02_Fastapi
cd 02_Fastapi


Create and Activate the Virtual Environment:

uv venv
.venv\Scripts\activate


Add Dependencies

uv add "fastapi[standard]"


To add a development dependency, use the --dev flag:

uv add --dev pytest pytest-asyncio


Step 2: Create your first API route.

Hello API: Create your first API
Write Code in main.py


Run Server:

fastapi dev main.py


Test APIs:
Open in browser

http://localhost:8000