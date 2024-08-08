# Open Source Code Assistant in Local: Ollama + Codellama + Continue
As developers, we are always looking for ways to improve our coding efficiency, accuracy, and scalability. That is why AI powered tools like GitHub Copilot and AWS Q are so exciting – they use large language models (LLMs) to provide real-time suggestions for coding. However, many organizations have concerns about the cost and licensing restrictions associated with using cloud-based coding assistants. In this blog, let's explore an open source and cost effective alternative that utilizes local LLMs. 

Let's dive in!

# What are Local LLMs?
Local LLMs are large language models that can be trained and run on a user's local machine, eliminating the need for cloud-based services. These models can be used for various AI-powered development tools, such as code completion, refactoring, and analysis.
   
# Ollama: An Open-Source LLM Solution
Ollama is an innovative platform that makes it possible to harness the power of LLMs on your local machine. This bridges the gap between AI technologies and user-friendly accessibility. 
With Ollama, we can:
 1. Run LLMs directly on our local machine reducing reliance on cloud services
 2. Develop innovative AI-powered tools that integrate seamlessly with the existing workflows.

# Continue
Continue is the leading open-source AI code assistant. You can connect any models and any context to build custom autocomplete and chat experiences inside VS Code and JetBrains
    
# Setting Up Your Local LLM Solution
This step will install the codellama large language model in your local machine. To set up a local LLM solution using Ollama, follow these steps:
# Mac:
1. Install Ollama: If you are using homebrew, open terminal and run 
```bash
brew install ollama
```
If you are not using homebrew, download and install Ollama from https://ollama.com/download/mac

2. Start the Ollama server in the background: run 
```bash
ollama serve
```
3. Download Meta's codellama model: run
```bash
ollama pull codellama
```

# Windows:
1. Visit https://ollama.com/download
2. Choose Windows
3. Download the latest version of Ollama windows installer.
4. Run the downloaded installer and follow the on-screen instructions to complete the installation process
5. Open command prompt and run 
```bash
ollama pull codellama
```
# Installing the IDE Extension
To install 'Continue', an open-source AI code assistant, follow these steps:
VSCode:
1. Run:
```bash
code --install-extension continue.continue
```
  Alternatively, you can click on the Extensions tab in VSCode and search for 'Continue'
      ![image](https://github.com/user-attachments/assets/9decbadc-41cf-4079-844f-55573d897dcb)
  
2. Select the Continue VSCode extension and install it in your VSCode
3. Once installed, click on the Add model button in your Continue extension
    ![image](https://github.com/user-attachments/assets/d02335c7-e35e-45f7-90b5-0eccf57c5c85)

4. Choose Ollama as the provider

    ![image](https://github.com/user-attachments/assets/9dab1895-9111-41df-b57c-523013ee9867)

5. Choose the model that you have installed (codellama in this case)
    ![image](https://github.com/user-attachments/assets/963a7d8a-f168-4ac4-8c82-f5ee0f93ad5d)

# IntelliJ:
1. Go to Plugins and search for ‘Continue’ in marketplace.
  ![image](https://github.com/user-attachments/assets/697bd9fa-515d-4ede-8b98-78853c3d6a7b)
2. Once installation is complete, you will be able to see the Continue icon in the right pane.
3. Click on the icon, then click on Local Models and click Continue.
   ![image](https://github.com/user-attachments/assets/8db3b276-0259-4b62-9929-9b902e748ee8)
4. Click on Add Model and choose Ollama
   ![image](https://github.com/user-attachments/assets/78416163-fdcb-454d-8ffd-d966dc4ddcfa)
5. Click on Auto Detect.
   ![image](https://github.com/user-attachments/assets/e01d0a23-2a40-4f02-9d49-3354f327dc11)
6. Choose codellama:latest
   ![image](https://github.com/user-attachments/assets/7b286c31-c9a6-4a27-8adb-7fcef9b5ef60)

Now, we are all set to use our locally installed LLM as a code assistant. We can ask questions, provide the context as a codebase or a particular file, auto code complete suggestions and many more.

# PROS
1. Cost: By using open-source software, organizations can avoid license costs for coding assistants and ensure that their codebase remains fully owned.
2. Offline development: Developer can access this code assistant even when there is no internet connectivity enabling developers to work with code assistants offline.

# CONS
1. The performance of the code assistant depends on the hardware capability of the local machines.
2. Needs some storage memory and RAM to install and run the LLMs locally.
   
# Conclusion
In our article, we illustrated the process of configuring a local open-source code assistant. Given the ongoing evolution of Gen AI, it will be intriguing to observe future models that specifically address local development requirements. If you have any inquiries or need additional guidance on setting up your local LLM solution, feel free to reach out!

# References:
https://www.continue.dev/

https://ollama.com/
