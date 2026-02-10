# How to Update Your Website

Whenever you make changes to your website (like editing `index.html`, `style.css`, or replacing your CV PDF), you need to send those changes to GitHub for them to appear online.

## Step-by-Step Guide

1.  **Make your changes**
    *   Edit your files in VS Code.
    *   Save your files (Command + S).

2.  **Open the Terminal**
    *   In VS Code, create a new terminal if one isn't open (Terminal > New Terminal).

3.  **Run these 3 commands:**
    Copy and paste these commands into the terminal one by one, pressing **Enter** after each line.

    ```bash
    git add .
    ```
    *(This stages all your changes)*

    ```bash
    git commit -m "Update website content"
    ```
    *(This saves your changes with a message. You can change "Update website content" to whatever describes your change)*

    ```bash
    git push
    ```
    *(This uploads your changes to GitHub)*

4.  **Wait a few minutes**
    *   GitHub Pages takes a minute or two to update. Refresh your website link to see the changes!
