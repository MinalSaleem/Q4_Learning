# ⚡️ FastAPI Starter with UV (Ultra Venv)

Set up a **FastAPI** project with **UV** – the blazing fast Python packaging tool!

---

### 🔧 Installing `uv`

Run the following in **PowerShell**:

```
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
```

### Verify Installation:

```
uv --version
```
OR
```
uv version
```



## 🚀 Setting Up a FastAPI Project with UV

### 📁 Step 1: Create a Project Directory and Switch to it:
```
uv init 02_Fastapi
cd 02_Fastapi
```

#### 🧪 Create & Activate Virtual Environment:
```
uv venv
.venv\Scripts\activate
```

#### 📦 Add Project Dependencies:

Install FastAPI and its standard extras:
```
uv add "fastapi[standard]"
```

Add development dependencies:
```
uv add --dev pytest pytest-asyncio
```


### ✨ Step 2: Create Your First API

Hello API: Create your first API
Write Code in main.py


#### ▶️ Run the Server:

Use the following command to start your development server
```
fastapi dev main.py
```

#### 🌐 Test Your APIs
Open in browser:

http://localhost:8000


