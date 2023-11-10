The purpose of this document is to keep track of all technique questions concerning the lab assignment. If you encounter the following ones, you can find the answer by searching keywords. If your question is not listed here, please seek help from Zhihao in every Thursday afternoon lab (07.09.2023 to 19.11.2023).



### 1.0 Environment Setting

By default, we will use the computer in Lab PC-209. 

Here's a step-by-step guide on how to launch Anaconda and complete an assignment in a Jupyter Notebook (`.ipynb` file):

1. **Launch Anaconda Navigator:**

   - On Windows: Search for "Anaconda Navigator" in the Start menu and click on it.
   - On macOS: Open Launchpad, find "Anaconda Navigator," and click on it.

2. **Open Anaconda Navigator:** Once Anaconda Navigator is launched, you'll see a graphical interface with several options.

3. **Launch Jupyter Notebook:**

   - In the Home tab of Anaconda Navigator, find your environment (or the base environment if you didn't create a new one).
   - Click on the "Install" button in the Jupyter Notebook box if Jupyter Notebook is not installed for the selected environment. If it's already installed, you'll see a "Launch" button instead.

4. **Jupyter Notebook Interface:**

   - Your web browser should open, showing the Jupyter Notebook interface.
   - Navigate to the directory where you want to create your assignment notebook or open an existing notebook.

5. **Create or Open a Notebook:**

   - To create a new notebook, click the "New" button and select "Python 3" to create a Python notebook.
   - To open an existing notebook, click on the notebook's name in the file list.

6. **Complete Your Assignment:**

   - In the notebook, you'll see cells where you can write code or markdown text.
   - Use the "+" button in the toolbar to add new cells.
   - Write your code and text to complete the assignment.

7. **Run Cells:**

   - To run a code cell, select it and press Shift + Enter. The output will appear below the cell.

8. **Save and Export:**

   - Use the File menu to save your notebook.
   - You can also download your notebook by selecting "Download as" from the File menu and choosing the desired format (e.g., Notebook, PDF, etc.).

   

#### 1.0.1 How to set up a python environment on my own PC?

You can also do it on your own PC. There are several ways to install python environment, here is one of them, VS Code + Miniconda:

1. **Download Miniconda:** Go to the Miniconda download page: https://docs.conda.io/en/latest/miniconda.html

   Choose the installer based on your operating system (Windows, macOS, or Linux) and the appropriate architecture (32-bit or 64-bit).

2. **Run the Installer:**

   - **On Windows:** Double-click the downloaded `.exe` file and follow the installation prompts.
   - **On macOS and Linux:** Open a terminal window, navigate to the directory containing the downloaded installer, and execute the installer script using the terminal.

3. **Download VS Code** or other IDE you prefer: https://code.visualstudio.com/ **VS Code supports working with Jupyter Notebooks natively** (when you run it, it may ask you install some extensions, click yes).

4. **Open the project folder, and choose the python interpreter from Conda.** 



#### 1.0.2 How to use the remote server?

You can do your assignment on a remote server (you can get help from IT Drift to use [Computing Resources - Department of Geosciences (uio.no)](https://www.mn.uio.no/geo/english/services/it/help/servers/computing-resources.html)):

- remote desktop for Windows:[Remote Desktop from Windows - University of Oslo (uio.no)](https://www.uio.no/english/services/it/home-away/rdp/help/windows/)

- or using SSH: [Using VS Code to connect to servers using SSH - Department of Geosciences (uio.no)](https://www.mn.uio.no/geo/english/services/it/help/using-servers/vscode.html)

- or virtual desktop: [VDI install and use - University of Oslo (uio.no)](https://www.uio.no/english/services/it/computer/vdi/help/vdi-install-and-use.html#toc5)



#### 1.3 Using git to manage your assignments

We already have a template on GitHub. If your computer (or IDE) already has git, you can open the terminal:

```
$ cd <your-dir>
$ git clone https://github.com/liuh886/GEO4300_2023.git
```



### 1.1 Import Error

All import errors can be fixed by install dependencies. Here are some examples:



#### 1.1.1 **ImportError**: Missing optional dependency 'xlrd'. Install xlrd >= 1.0.0 for Excel support Use pip or conda to install xlrd.

To resolve this issue, you can follow these steps:

1. **Using Pip (Python Package Manager):** Open your command-line terminal and run the following command to install the 'xlrd' package:

   ```
   
   pip install xlrd
   ```

   This will download and install the 'xlrd' package and its dependencies.

2. **Using Conda (Anaconda Package Manager):** If you are using Anaconda or Miniconda, you can use the following command to install 'xlrd':

   ```
   
   conda install xlrd
   ```

   This will install the 'xlrd' package within your Conda environment.



### 1.2 Use Copilot in VS Code

GitHub Copilot can help you more productive and efficient in coding, which is free for student. Here is the official document [Quickstart for GitHub Copilot - GitHub Docs](https://docs.github.com/en/copilot/quickstart)



1. **Install GitHub Copilot Extension:**
   - Open VS Code.
   - Click on the Extensions icon in the Activity Bar on the side (or press `Ctrl+Shift+X`).
   - Search for "GitHub Copilot" in the Extensions marketplace.
   - Click the Install button next to the GitHub Copilot extension.
2. **Sign in to GitHub:**
   - If you haven't already signed in to GitHub within VS Code, you'll be prompted to do so when you first use the extension. Follow the prompts to sign in.
3. **Authorize GitHub Copilot:**
   - After signing in, you may need to authorize GitHub Copilot to access your GitHub repositories. Follow the instructions in VS Code to complete this authorization process. (Note: Authorization requires the latest version of VS Code)
   - If your account don't get **GitHub Education Benefits**, this step requires payments. You can verify you email by the link right: [Request a discount - GitHub Education](https://education.github.com/discount_requests/application)
4. **Write Code with Copilot.**
   
   - As you write code in your project, GitHub Copilot will provide suggestions and code completions to help you. It uses machine learning to generate suggestions based on your code and comments.
   - You can accept Copilot's suggestions by pressing `Tab` or selecting the suggestion with your mouse.
   
   

**What can Copilot do for you?** 

- Language learning. You don't need to remember or check the documents frequently.
- Reducing coding fatigue. It helps to reduce syntax errors, add comments, suggest code patterns that adhere to best practices.
- Productivity Boost. Copilot can generate code templates or entire functions based on description. You need to make sure you understand the generated code fully, otherwise you are cheating using AI.



### 1.3 Deliver your assignments to Canvas

It's better to upload .ipynb/.html files to the submission system both. 



#### 1.3.1 Exporting to html?

If you are using VS Code, you can click `...` to export html. You may need to install some plugins in your first time. 





