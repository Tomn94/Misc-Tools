# Misc Tools
###### Useful coding tools

- **LaTeX** base document
- **git**
  - **pre-commit hook**, avoids committing Xcode placeholders: `<#Description#>`\
    Init templates: `git config --global init.templatedir '~/.git-templates'`\
    Create path: `mkdir -p ~/.git-templates/hooks/`\
    Put hook there, make it executable: `chmod a+x pre-commit`\
    Reset all repositories that need it: `git init`\
    *Use `git commit --no-verify` to bypass*
- **Xcode**
  - Put themes in: `~/Library/Developer/Xcode/UserData/FontAndColorThemes`
- **Visual Studio Code**
  - Put default settings in: `~/Library/Application Support/Code/User/settings.json`
- **Qt**
  - Put themes in: `~/.config/QtProject/qtcreator/styles`
- **Apple Script**
  - Find original script `.scpt` files from `.app` in `*.app/Contents/Resources/Scripts`
  - My scripts:
    - **App Valider** 🔓<br>
      Remove macOS Gatekeeper 1st launch verification from any given downloaded app/file
    - **Pick Color** 🖌<br>
      Persistent macOS Color picker tool window
    - **Music Tweet** 🎧<br>
      Export track info played in iTunes
    - **Android Emulator** 🤖<br>
      Launch Android Emulator with a smartphone configured in Android Studio
    - **Capture** 📷<br>
      Launch and configure QuickTime Player to record my iPhone screen & sound
    - **http** 📥<br>
      Download the file at a given URL
    - **LaTeX** 💀<br>
      Delete every useless LaTeX files after compilation
    - **Git Tag** 🏷<br>
      Create and push a new tag in the current repository
    - **No lyrics** 💬<br>
      Find tracks in iTunes which have no lyrics
    - **SoundCloud Artwork** 🖼<br>
      Copy the artwork from [SoundCloud](http://soundcloud.com) in the current Safari/Chrome tab to (Paste|Clip)board
    - **cd ⌨️**<br>
      Open a Terminal at the current Finder window
    - **ProSE SVN 📲 Checkout**<br>
      Checkout SVN
    - **ProSE SVN 🔄 Update**<br>
      Update SVN at current folder
    - **ProSE SVN ✍🏼 Diff**<br>
      Diff SVN at current folder
    - **ProSE SVN 📤 Commit**<br>
      Commit current folder, supports line breaks
