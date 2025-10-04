# 🧠 Automated Research Report Generation

**Project GitHub**: [sunnysavita10/automated-research-report-generation](https://github.com/sunnysavita10/automated-research-report-generation)

---

## ⚙️ UV Setup Commands

### ✅ Check UV Installation

```bash
uv --version
```

If `uv` is not installed:

```bash
pip install uv
```

---

### 🚀 Initialize Project

Option 1: Using `uv init` directly

```bash
uv init <project_name>
```

Then open the project in VS Code.

Option 2: Manual folder setup

1. Create a new folder.
2. Open it in VS Code.
3. Run:

```bash
uv init
```

---

### 🧪 Create Virtual Environment

Default environment:

```bash
uv venv
```

This creates a `.venv` folder by default.

Custom environment:

```bash
uv python list
uv venv <your-env-name> --python <your-python-version>
```
Activate the environment
- For macOS/Linux:

```bash
.venv\Scripts\activate.bat
```

Note: If it is a custom env then copy the path from that folder

---

### 📦 Install Dependencies

```bash
uv add -r requirements.txt
```

### work flow

![Alt text]workflow.png


---

