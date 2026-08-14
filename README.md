# Code_IDE

# Daddy AI — Online Coding IDE

A modern **AI-powered online coding platform** designed to write, run, debug, and improve programs directly from the browser. Daddy AI provides a clean IDE experience with code editing, execution, error detection, AI-assisted fixes, and project management.

## 🚀 Features

* 💻 **Online Code Editor**

  * Monaco-style professional code editor
  * Syntax highlighting
  * Line numbers
  * Code formatting
  * Error highlighting

* ▶️ **Code Execution**

  * Run programs directly from the IDE
  * Stop running programs
  * View execution output
  * Execution time and memory usage

* 🤖 **Fix with AI**

  * Automatically analyze compilation and runtime errors
  * Identify the cause of errors
  * Suggest corrected code
  * Apply AI-generated fixes
  * Explain errors in simple terms
  * Re-run the corrected program

* 🐞 **Debugging**

  * Runtime error detection
  * Compilation error detection
  * Error traceback display
  * Debug console
  * Input/STDIN support

* 🧪 **Test Cases**

  * Create and execute test cases
  * Validate program output
  * Identify failed test cases

* 📁 **Project Explorer**

  * Create and manage files
  * Project file explorer
  * File navigation
  * File history

* 📝 **Templates**

  * Ready-to-use programming templates
  * Quickly start coding without creating boilerplate code

* 🎨 **Modern IDE Interface**

  * Dark developer-focused interface
  * Responsive layout
  * Clean navigation
  * Professional coding experience

## 🛠️ Supported Programming Languages

The platform is designed to support multiple programming languages, including:

* Python
* Java
* C
* C++
* JavaScript
* TypeScript
* HTML
* CSS
* And more

## 🧠 AI Error Detection

Daddy AI can analyze errors such as:

```text
NameError
SyntaxError
TypeError
ValueError
IndexError
KeyError
AttributeError
ImportError
ModuleNotFoundError
ZeroDivisionError
```

### Example

Incorrect Python code:

```python
pprint(90)
```

AI detects:

```text
NameError: name 'pprint' is not defined
```

Possible AI fix:

```python
print(90)
```

Expected output:

```text
90
```

If `pprint` is intentionally required, AI can instead suggest:

```python
from pprint import pprint
```

## 🖥️ IDE Layout

The platform contains:

| Section       | Purpose                              |
| ------------- | ------------------------------------ |
| Explorer      | Manage project files                 |
| Code Editor   | Write and edit source code           |
| Run           | Compile and execute code             |
| Stop          | Stop program execution               |
| Format        | Format source code                   |
| Output        | Display program results              |
| Terminal      | Access terminal information          |
| Input (STDIN) | Provide runtime input                |
| Errors        | Display compilation/runtime errors   |
| Test Cases    | Run and validate test cases          |
| Debug Console | Debug program execution              |
| Fix with AI   | Automatically analyze and fix errors |

## 📊 Example Program

```python
import time

def calculate_stats(numbers):
    print("Processing numbers:", numbers)

    total = sum(numbers)
    count = len(numbers)
    average = total / count if count > 0 else 0

    return {
        "count": count,
        "sum": total,
        "average": average,
        "max": max(numbers) if numbers else None
    }

def main():
    print("=== Welcome to Daddy AI ===")

    user_data = [15, 42, 8, 99, 23, 67]

    start_time = time.time()
    results = calculate_stats(user_data)
    elapsed = time.time() - start_time

    print(f"Count: {results['count']}")
    print(f"Sum: {results['sum']}")
    print(f"Average: {results['average']:.2f}")
    print(f"Max Value: {results['max']}")
    print(f"Computation time: {elapsed:.4f}s")

if __name__ == "__main__":
    main()
```

## 🎯 Project Goal

The main goal of Daddy AI is to provide a **simple, fast, and intelligent coding environment** where users can:

**Write Code → Run → Detect Errors → Fix with AI → Debug → Test → Get Output**

## 🔮 Future Enhancements

* AI code completion
* AI code explanation
* Automatic code optimization
* Multi-file project support
* GitHub integration
* Cloud project storage
* Collaborative coding
* Breakpoint debugging
* AI-generated test cases
* Code quality scoring
* Code execution history
* More programming languages

## 📌 Project Status

**Development Version**

Daddy AI is actively being developed as an AI-powered browser-based coding and debugging platform.

---

### Built for Developers & Students

**Daddy AI** — *Write. Run. Debug. Fix with AI.*
