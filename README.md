🛡️ AutoGit Backup Tool

Automatically commits and pushes changes from your selected project folder to a GitHub repository at regular intervals — fully automatic, silent, and useful for developers.

✅ Features

Auto backup your selected folder to GitHub every X minutes

Git add, commit, and push — all automated

Fail-safe notifications on push failure

Configurable folder, repo URL, branch, and interval

Easy-to-use GUI (no terminal required)

🖥️ Installation

🔹 Step 1: Download

⬇️ Download Latest Release (Replace this with your GitHub release link)

Unzip the downloaded folder (e.g., AutoGitBackupTool.zip). Inside, you'll find:

AutoGitBackupTool/
├── AutoGitBackupTool.exe
├── config.json
├── logs/
└── README.md

🔹 Step 2: Run

Just double-click AutoGitBackupTool.exe. A user-friendly GUI will appear.

🔹 Step 3: Fill In Details

Project Folder Path: Browse and select your local project folder

GitHub Repo URL (HTTPS): Example – https://github.com/username/project.git

Branch: Usually main or master

Backup Interval: In minutes (e.g., 30)

Click Start Backup. You're done! 🔁 The tool will now auto-backup your work in the background.

📌 Important Note: Keep the Tool Running

Once you see the message "Backup started successfully!", do not close the application. You can safely minimize it — but closing it will stop the automatic backup process.

If you want backups to run continuously, make sure the tool stays open or set it to launch automatically at system startup (see below).

🛑 Important: Windows Defender / Antivirus Issue

Because this tool uses background automation, some systems may wrongly detect it as a threat (false positive). Here's how to fix it:

🔐 Step-by-step to Add Defender Exclusion

🛑 Do this before extracting the ZIP file:

Turn off Real-time Protection Temporarily

Press Windows + S → Search "Windows Security"

Go to: Virus & threat protection

Click: Manage settings

Turn off Real-time protection (temporarily)

Extract the ZIP File

Right-click on AutoGitBackupTool.zip → Extract All

Add Folder to Defender Exclusions

Scroll to Exclusions → Click Add or remove exclusions

Click + Add an exclusion → Choose Folder

Select the folder containing AutoGitBackupTool.exe

Turn Real-time Protection Back ON

Now that your tool folder is excluded, turn real-time protection back on safely.

✅ Windows Defender will no longer block or delete your tool.

⚙️ Optional: Auto-Start on PC Boot

Press Win + R → Type: shell:startup

Paste a shortcut of AutoGitBackupTool.exe here

Now the tool will start automatically every time you boot your PC.

💬 Support & Feedback

Created with ❤️ by Kunal Choudhary

If you face any issues, feel free to open an Issue or send feedback.

📜 License

This project is open-source under the MIT License.

