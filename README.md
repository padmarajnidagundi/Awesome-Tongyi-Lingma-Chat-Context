## **🌟 Awesome Tongyi Lingma Chat Context Guide [2025 Edition]**

## 🧠 Tongyi Lingma Chat Contexts for Programmers

Boost your productivity by using context tags to give Lingma precise, relevant information. This guide lists common context types developers and test engineers can use to supercharge AI assistance inside IDEs like Alibaba Cloud Code or VS Code with Lingma extension.

**> ⚠️ Contexts are invoked using `#` tags in your prompt, just like Copilot Chat. Syntax may vary depending on Lingma updates.**

----------

**### 📌 Format**

plaintext

CopyEdit

`#context_tag → Description and use cases.` 

----------

**### 💻 Code-Based Contexts**

-   `#currentFile`  
    Includes the contents of the current file. Use when asking about bugs, refactors, or explanations.
    
-   `#selection`  
    Includes the currently selected code. Best for asking about a function, method, or code block.
    
-   `#workspace`  
    Includes relevant project structure, configs, or linked files. Useful for architecture-level questions.
    
-   `#testFile`  
    Automatically pulls in test files related to current code. Use to debug or improve tests.
    
-   `#gitDiff`  
    Adds staged Git diff for PR review help or code change explanations.
    

----------

**### 🧪 Runtime & Output Contexts**

-   `#terminalOutput`  
    Injects terminal logs or errors. Useful for debugging build, compile, or runtime issues.
    
-   `#debugSession`  
    Adds current debug session data (variables, stack, etc.) for real-time troubleshooting.
    

----------

**### 🔧 Config & Tooling Contexts**

-   `#packageJson` / `#pomXml` / `#buildGradle`  
    Includes dependency definitions. Ask about dependency issues or recommendations.
    
-   `#envFile`  
    Injects contents of `.env` or environment variable files.
    
-   `#tsConfig` / `#eslintConfig`  
    Useful for understanding TypeScript or lint-related errors.
    

----------

**### 📊 Data Contexts**

-   `#jsonData`  
    Includes selected or referenced JSON. Useful for API response questions.
    
-   `#yamlData`  
    Ideal for CI/CD files, Kubernetes specs, etc.
    

----------

**### 📚 Docs & Comments**

-   `#docComments`  
    Includes code documentation or JSDoc comments for context-based explanations.
    
-   `#readme`  
    Pulls project README.md content to give Lingma project-level awareness.
    

----------

**### 🔄 Example Prompt**

> “Why is this method failing? #selection #testFile #terminalOutput”

## 🚀 License

MIT License - feel free to use in your projects

## Contact

- Author: Padmaraj Nidagundi
- Email: padmaraj.nidagundi@gmail.com
- LinkedIn: https://www.linkedin.com/in/padmarajn/
- GitHub: https://github.com/padmarajnidagundi/Awesome-Tongyi-Lingma-Chat-Context/
