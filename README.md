# Python Virtual Environment Setup

This project uses a Python virtual environment (`venv`) to manage dependencies and ensure a consistent development environment.

---

## Prerequisites

Make sure **Python 3** is installed on your system:

```bash
python --version
# or
python3 --version

Create the Virtual Environment

From the project root directory, run:

python -m venv venv


Activate the Virtual Environment
macOS / Linux
source venv/bin/activate

Windows (PowerShell)
venv\Scripts\Activate.ps1

Windows (Command Prompt)
venv\Scripts\activate

Install Dependencies

Install all required packages using:

pip install -r requirements.txt
