# DOM_Judge Auto Fetch Bot

Welcome to the DOM_Judge Auto Fetch Bot. This tool is designed to quickly fetch and sync data from an external GitHub repository into your local workspace.

## first push in your downloaded folder
```
git push -u origin main
```

## Setup Instructions

**1. Provide Your Repository URL**
Open `bot\my_repo_url.txt` and paste the link to your GitHub repository inside. You can use any of the following formats—the program will handle them all automatically:
- Browser URL: `https://github.com/Username/MyRepo`
- Browser URL with path: `https://github.com/Username/MyRepo/tree/main`
- Full Git URL: `https://github.com/Username/MyRepo.git`

*If you leave the file empty, don't worry—the program will prompt you to enter the URL manually within the console the first time you run it!*

> **Note:** This tool only clones the **`main` branch**. Please make sure your repository's default branch is named `main`.

**2. Running the Application**
Simply run the auto-fetch `.exe` file located in the same folder as this `readme.md` file. It will fetch and sync the **`main` branch** of your specified repository into the `data_on_github` folder automatically.

**3. Compiling the `.exe` Manually (Optional)**
If you are afraid to run the provided `.exe` directly for security reasons, you can absolutely compile the source code yourself!
- The source file is located at `bot\auto_fetch.cpp`.
- You can compile it using `g++`, `clang++`, or Visual Studio.
- **IMPORTANT**: After compiling it, **make sure to move the generated `.exe` to the same folder layer as this `readme.md` file** (the main `DOM_Judge-exe` folder). The executable relies on relative paths to run smoothly!
