# Operating Systems: Starter Environment

We will be using GitHub Codespaces to ensure everyone has a standard Linux environment for system calls like `fork()`, `exec()`, and pthreads.

## 1. Launching Your Workspace

1. Click the green **Use this template** button at the top of this page to generate your own copy of this repository.
2. Navigate to your new repository, click the green **Code** button.
3. Switch to the **Codespaces** tab and click **Create codespace on main**.
4. Wait a few moments for the browser-based VS Code editor to load your Linux container.

## 2. Compiling Your Code

Once your editor is open, you will need to use the terminal to compile your C++ code. 

1. Open the integrated terminal by clicking **Terminal > New Terminal** in the top menu (or pressing `` Ctrl + ` ``).
2. To compile `main.cpp`, type the following command and press Enter:
   
```bash
g++ main.cpp -o os_program
```
