## Setting up Ollama and Running a Small Llama3 Model

Here's how to download, install, and run Ollama with a small Llama3 model:

1.  **Download Ollama:**

    *   Go to the official Ollama website: [https://ollama.com/](https://ollama.com/)
    *   Download the appropriate version for your operating system (macOS, Linux, Windows (preview)).

2.  **Install Ollama:**

    *   **macOS:** Double-click the downloaded `.dmg` file and follow the on-screen instructions to drag the Ollama application to your Applications folder.
    *   **Linux:** Follow the instructions on the Ollama website for your specific distribution (usually involves using `curl` to download a script and then running it with `sudo`).
    *   **Windows:** Follow the instructions on the Ollama website.

3.  **Open Terminal:**

    *   Open your terminal application (e.g., Terminal on macOS, Command Prompt or PowerShell on Windows, your distribution's terminal on Linux).
    *  Start ollama 
        ```bash
        ollama serve
        ```

4.  **Pull and run a Model:**

    *   Once the model is downloaded, run it with the following command:

        ```bash
        ollama run llama3.2:1b
        ```

    *   Ollama will start the model and you can begin interacting with it in the terminal.



