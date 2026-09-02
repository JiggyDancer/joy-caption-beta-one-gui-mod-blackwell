Vram usage: 17.4 GB For BF16, 10 GB for FP8, 6 GB for 4-bit.

## Installation

Follow these steps to set up the JoyCaption GUI Mod on your system:

---

**1. Clone the Repository**
Open your terminal or command prompt and run:

```bash
git clone https://github.com/JiggyDancer/joy-caption-beta-one-gui-mod-blackwell
cd joy-caption-beta-one-gui-mod
```

**2. Create and Activate a Virtual Environment (Recommended)**

Create the virtual environment:

```bash
# For Python 3.12 (adjust if needed)
python -m venv venv
```

Activate the environment:

* **Windows (CMD or PowerShell):**

```bash
venv\Scripts\activate
```

* **macOS / Linux (Bash or Zsh):**

```bash
source venv/bin/activate
```

**3. Install Triton**
Triton can provide performance improvements. The wheel below is specifically for certain Python versions on Windows.

* **For Windows:**

```bash
pip install triton-windows
```

* **For Linux/macOS or other Python versions:**

```bash
pip install triton
```

**4. Install Core Dependencies**

```bash
pip install -r requirements.txt
```


5.  **Upgrade Transformers and Tokenizers (Recommended):**
```bash
pip install --upgrade transformers tokenizers
```

## Usage

1.  Activate the venv.
2.  `python Run_GUI.py` or `python Run_GUI_FP8.py` or `python Run_gui_4bit.py`


## Side note
Make sure to install Visual Studio with C++ Build Tools and Add Visual Studio Compiler Paths to System PATH if you have not done it already. 
