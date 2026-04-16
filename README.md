# Chronos

Chronos is a Python package for fitting isochronal models to data.

**Disclaimer:** This package is still in development and should be used with care. Especially the Bayesian methods are prone to get stuck in local minima and all results should be thoroughly validated.


## Installation

### 1. Prerequisites

- Python 3.10 or higher
- [uv](https://docs.astral.sh/uv/getting-started/installation/) package manager

Install `uv` using one of the following methods:

**macOS / Linux (recommended):**

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

**Windows:**

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

**Homebrew (macOS):**

```bash
brew install uv
```

**pip:**

```bash
pip install uv
```

For more options, see the [uv installation docs](https://docs.astral.sh/uv/getting-started/installation/).


### 2. Clone the repository

```bash
git clone https://github.com/rottenstea/Chronos.git
cd Chronos
```

### 3. Create a virtual environment and install

```bash
uv venv
uv sync
```

This creates a `.venv` directory inside the project and installs Chronos along with all its dependencies.

### 4. Activate the virtual environment

**macOS / Linux:**

```bash
source .venv/bin/activate
```

**Windows:**

```bash
.venv\Scripts\activate
```

### 5. IDE Setup

#### VS Code

1. Open the `Chronos` folder in VS Code.
2. Install the **Python** extension if you haven't already.
3. Open the Command Palette (`Cmd+Shift+P` on macOS, `Ctrl+Shift+P` on Windows/Linux).
4. Select **Python: Select Interpreter**.
5. Choose the interpreter located at `./Chronos/.venv/bin/python`.

#### PyCharm

1. Open the `Chronos` folder as a project.
2. Go to **Settings** > **Project: Chronos** > **Python Interpreter**.
3. Click **Add Interpreter** > **Existing**.
4. Select the interpreter at `./Chronos/.venv/bin/python`.


## Getting Started

Check out the `Tutorials/` folder for example notebooks showing how to use Chronos.

