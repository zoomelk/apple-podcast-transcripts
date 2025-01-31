# Apple Podcast Transcript Viewer

This is a simple UI tool for viewing full transcripts in a way that you can actually copy them. No software needed, should work with any Mac with the Podcasts app just by visiting the website, https://alexbeals.com/projects/podcasts/. All you have to do is follow the instructions and drag-and-drop your podcasts folder.

This all works locally without uploading anything, which you can confirm by disabling the Internet after the website is loaded. 

<img width="1368" alt="Screenshot 2025-01-30 at 11 31 52 PM" src="https://github.com/user-attachments/assets/683f252d-4255-47d5-9e15-2c747ffefb68" />

Once you drag and drop your files you can browse all of the episodes with transcripts.

<img width="1368" alt="Screenshot 2025-01-30 at 11 31 47 PM" src="https://github.com/user-attachments/assets/a108a39a-2fbf-4971-a1ee-336d2ec45e9e" />

Clicking on any of them will pull up the full transcript, which you can copy and paste to whatever tool you want to handle the file in.

<img width="1368" alt="Screenshot 2025-01-30 at 11 31 40 PM" src="https://github.com/user-attachments/assets/96671490-2f88-4001-b5fa-6e43a4effaab" />

## Where Does This Come From?

The data is locally stored in `~/Library/Group Containers/243LU875E5.groups.com.apple.podcasts/Library/Cache/Assets/TTML`. The tool also pulls in the `.sqlite` folder to display additional information about the podcast to make it easier to find the one you're looking for. Shoutout to @mattdanielmurphy and his [repo here](https://github.com/mattdanielmurphy/apple-podcast-transcript-extractor) which I found when originally trying to do this for a podcast.
