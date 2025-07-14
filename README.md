# <img src="/favicons/favicon-96x96.png?raw=true" height="32px" alt=""/> Apple Podcast Transcript Viewer –Export Edition

This is a **customised fork** of the original [Apple Podcast Transcript Viewer](https://github.com/dado3212/apple-podcast-transcripts) by [@dado3212](https://github.com/dado3212).

It's a simple tool for viewing and downloading Apple Podcast transcripts directly from your Mac. No software required, just visit the website:
[zoomelk.github.io/apple-podcast-transcripts](https://zoomelk.github.io/apple-podcast-transcripts/)

<img width="3406" height="2294" alt="0  Apple Podcast Transcript Viewer" src="https://github.com/user-attachments/assets/9edd4a13-19ac-4d65-a735-bec1e0da2cac" />


## 💡 What This Is

The Apple Podcasts app on macOS stores episode transcripts locally, but doesn’t offer a way to export or bulk copy them. This tool allows you to easily extract them.

You can us it to:

* View transcripts in full, in a readable format
* Select episodes and download them as `.txt` files
* Batch-download transcripts in a ZIP file
* Optionally include metadata like title, author, date, and description

All processing happens locally in your browser. It does not upload or share any data externally. To confirm you can disable the internet after website is loaded.  

<br>

## ⚡ How to Use

1. **Make sure transcripts are saved on your Mac**
   
  * Open the Apple Podcasts app on your Mac
  * Go to an episode and click "Download" or choose “View Transcript” from the ⋯ menu

<img width="3046" height="1864" alt="1  Open Apple Podcasts" src="https://github.com/user-attachments/assets/1d82e104-3f1c-42cd-8ce6-e35515450922" />

---

2. **Open the tool**

  * Open `index.html` using a local server
  * OR visit: [zoomelk.github.io/apple-podcast-transcripts](https://zoomelk.github.io/apple-podcast-transcripts/)
  
<img width="3406" height="2294" alt="2  Open Tool in Browser" src="https://github.com/user-attachments/assets/9bd35799-6352-455a-9910-b1bd88d7cc2f" />

---

3. **Find your Apple Podcasts folder**

  * In Finder, go to the top menu bar and choose: `Go > Go to Folder…` (or press `Command + Shift + G`)
  * Paste this path and press Enter:

  ```**
  ~/Library/Group Containers/243LU875E5.groups.com.apple.podcasts
  ```
<br>
     
<img width="1614" height="1246" alt="3  Go to Folder" src="https://github.com/user-attachments/assets/37b471e7-e450-4ef0-aca7-2bc6b44631d5" />

---


4. **Drag and drop**

  * Drag the folder named `243LU875E5.groups.com.apple.podcasts` into the browser window with the tool open.

<img width="3406" height="2294" alt="4  Drag   Drop" src="https://github.com/user-attachments/assets/dea5be2a-94ad-4ee3-8ca6-98d6bd33b899" />

---

5. **Browse and download**

  * All available transcripts will appear.
  * Select episodes or download everything as a ZIP.

<img width="3406" height="2294" alt="5  Browse and Download" src="https://github.com/user-attachments/assets/dc8f1bf7-fa91-4b21-9316-a875e6b2b7a5" />

## 💻 Where Does This Come From?

The data is locally stored in `~/Library/Group Containers/243LU875E5.groups.com.apple.podcasts/Library/Cache/Assets/TTML`. The tool also pulls in the `.sqlite` folder to display additional information about the podcast to make it easier to find the one you're looking for. 

<br>

## 🛠 Key Changes

This fork adds:

* ✅ Multi-episode selection
* ✅ ZIP download of selected transcripts
* ✅ Option to include episode metadata
* ✅ Recursive folder search for bulk imports
* ✅ UI refinements

<br>

## 🧠 Credits

Based on the original project by [@dado3212](https://github.com/dado3212/apple-podcast-transcripts)

Shout out to @mattdanielmurphy and his [repo here](https://github.com/mattdanielmurphy/apple-podcast-transcript-extractor) 
